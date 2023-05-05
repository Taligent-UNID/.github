# Instructivo para el Equipo

En este instructivo se detalla como es el proceso de gestión de tareas, como también el uso de herramientas para un mejor seguimiento y control del proyecto.

Como primera instancia es necesario el conocimiento del uso de las siguientes herramientas:

- [Git](https://git-scm.com/)
    Instalar git, y pueden ver un video introductorio para entender su funcionamiento: 
    https://www.youtube.com/watch?v=DinilgacaWs
- [VSCODE](https://code.visualstudio.com/)
    VSCODE Instalar Vscode para tener una mejor edición de texto. También debes instalar las siguientes extensiones.

    Muestro un ejemplo de como instalar una extension.
    ![alt text for screen readers](/profile/assets/install-pp-tools.gif "Extensions")

    Instalar la Extension Github.

Una vez instalado todas las herramientas el team puede realizar un logueo con la extensión GitHub. Donde dispone de los issues asignados a él.

Cada desarrollado, analista de datos o arquitecto debe realizar las entregas entre tipos de documentos:


- •	Documentación o Instructivos (Markdown o md)
    [Documentacion al respecto](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- Código
    Depende del tipo de lenguaje que se lleve a cabo en el proyecto, ejemplos:
    -   Python
    -   JavaScript
    -   Terraform
    -   Bash

Cada Issue o Tarea va solicitar un entregable en estos tipos de documentos.

Un issue lleva un proceso Kanban, donde se va realizando un seguimiento y acciones.

![alt text for screen readers](/profile/assets/status.png "Status de un Issue")

__Backlog__

Acá se listan todas los issues a la espera de su asignación, prioridad y tamaño.

__Ready__

En este proceso cada issue es asignado a su responsable, con prioridad y tamaño.

__In Progress__

En este punto el team va dando curso o ejecutando la tarea en el tiempo. Acá se puede realizar la serie de commits o cambios en los entregables que se pide el issue. Un issue puede tener uno o más commits.

__In Review__

Al finalizar todos los commits, puede solicitar una incorporación de rama o Pull Request, a la espera que un revisor realice la aceptación del issue terminado, en caso contrario se puede pasar a una discusión o una devolución del pull request, determinado que el issue no está terminado.

__Done__

Al dar aceptación al pull request el issue se daba como finalizado.

## Ejemplo de un Issue.

Podes visualizar nuestros issues en el repositorio correspondiente del proyecto debemos tener la extension de Github instalada.

![alt text for screen readers](/profile/assets/github.png "Status de un Issue")

Para este ejemplo si utilizar este mismo repositorio .GITHUB, el cual se establecio un ISSUE [#1](https://github.com/Taligent-UNID/.github/issues/1)

![alt text for screen readers](/profile/assets/ready.png "Status de un Issue")

Cuando queremos empezar a trabajar en el Issue damos clic en la flecha y cambiara su estado.

![alt text for screen readers](/profile/assets/in-progress.png "Status de un Issue")

Tambien en la esquina inferior izquierda nos indica que estabamos trabajando sobre la Issue.

![alt text for screen readers](/profile/assets/activity.png "Status de un Issue")

Al realizar un cambio un archivo Markdown por ejemplo, nos indicara en source control que se realizaron modificaciones.

![alt text for screen readers](/profile/assets/changes.png "Status de un Issue")

Podemos ver estas modificaciones en detalle.

![alt text for screen readers](/profile/assets/commit.png "Status de un Issue")

A la izquierda el archivo sin modificar y a la derecha sus modificaciones. Esto es un cambio o un commit.
Ahora lo tenemos que subir a nuestro repositorio remoto.

[Fixed 1](https://github.com/Taligent-UNID/.github/commit/25a3b15849957c9b45f8585b0628c5953e3c6cde)

Como tambien se detalla en el Issue

[Fixed #1](https://github.com/Taligent-UNID/.github/issues/1)

Si queremos podemos para de trabajar en este issue y trabajar en otro, solo con dar stop.

![alt text for screen readers](/profile/assets/stop.png "Status de un Issue")

(*)Para poder parar de trabajar en un issue si o si no debe haber cambios por commitear.

Es una buena practica realizar commits en cada momento o de forma organizada, ya que en todo momento se puede regresar atras y borrar el ultimo cambio. Si solo se hiciera un solo commit, se borraria todo.

Al finalizar todos los commmits se puede realizar una solicitud de Pull Request esto indica que esta listo para ser revisado y darle done a la issue.

