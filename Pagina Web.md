# *Git*
#### ¿Que es *Git*?

*Git*, es un software de control de versiones diseñado por Linus Torvalds. Fue creado pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente, es decir Git nos proporciona las herramientas para desarrollar un trabajo en equipo de manera inteligente y rápida y por trabajo nos referimos a algún software o página que implique código el cual necesitemos hacerlo con un grupo de personas. Algunas de las características más importantes de *Git* son:
* Rapidez en la gestión de ramas, debido a que Git nos dice que un cambio será fusionado mucho más frecuentemente de lo que se escribe originalmente.
* Gestión distribuida; Los cambios se importan como ramas adicionales y pueden ser fusionados de la misma manera como se hace en la rama local.
* Gestión eficiente de proyectos grandes.
* Realmacenamiento periódico en paquetes.
### Comandos Básicos 
* **Iniciar un repositorio vacío en unas carpeta específica.**
  * ``` git init ```
* **Añadir un archivo especifico.**
  * ``` git add “nombre_de_archivo” ```
* **Añadir todos los archivos del directorio**
  * ``` git add . ```
* **Confirmar los cambios realizados. El “mensaje” generalmente se usa para asociar al commit una breve descripción de los cambios realizados.**
  * ``` git commit –am “mensaje” ```
* **Revertir el commit identificado por "hash_commit"**
  * ``` git revert “hash_commit" ```
* **Subir la rama(branch) “nombre_rama” al servidor remoto.**
  * ``` git push origin “nombre rama” ```
* **Mostrar el estado actual de la rama(branch), como los cambios que hay sin hacer commit.**
  * ``` git status ```
