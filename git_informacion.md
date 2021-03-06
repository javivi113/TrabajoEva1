# Informacion sobre GIT

> Estos son los comandos necesario para el uso de GIT:

1. **git** init : Para iniciar el seguimientde nuestros documentos.
1. **git** status *-s* : nos muestra el estado de nuestros archivos; si han sido modificados,ect.
1. **git** add < directorio/archivo> : Para añadir un archivo o directorio a GIT.
1. **git** commit *-m* "identificador" : Guarda versiones de nuestro trabajos.
1. **git** branch : esatblece como master el directorio.
1. **git** remote add origin "Link de nuestro repositorio de github" : crea el repositorio remoto.
1. **git** push : para subir nuestros archivos a GITHUB.
1. **git** clone : tranforma el repositorio de GitHub en un directorio de nuestro ordenador.
1. **git** pull < Link de GitHub> : descarga en repositorio en tu ordenador.

> Añadiendo mas comandos
1. **git** reset *--hard/soft/mixed* : se utiliza para volver a un commit anterior y asi recuperar datos.
1. **git** checkout < *nombre de la rama* > : para cambiar la rama.
1. **git** merge < *nombre de la rama* > . fusiona las ramas como va encontrado huecos.
1. **git** rebase < *nombre de la rama* > : fusiona dos ramas manteniendo un orden cronologico.
1. **git** branch < *nombre de la rama* > : crea una rama.
1. **git** checkout -b < *nombre de la rama* > : crea y te cambia a la rama que has creado.
1. **git** fetch : Verifica cambios en el repositorio online con el local.
1. **git** rm < *archivo* > : elimina el archivo del directorio.

<br>
<br>
<br>

>> PREGUNTAS

- ¿Que es **git**?
    - 
    - **Te ayuda a rastrear y registrar los cambios efectuados en uno o en varios archivos. Es muy utilizado por programadores y en trabajos en los que participan una o mas personas.**
- ¿Cuál es la diferencia entre un "repositorio simple" y un "directorio de trabajo"?
    -
    - **Un repositorio simple, como su nombre lo indica, no cuenta con ningún archivo de trabajo que se use en Git. No existen subdirectorios ni control de versiones, solo una plantilla simple.**
    <br>

    - **Por otro lado, un directorio de trabajo contiene todos los archivos anteriores , subdirectorios, etc.**
    <br>

- ¿Cuál es la diferencia entre una "bifurcación" y una "rama"?
    -
    - **Bifurcaion:**  *La bifurcacion es una copia de un repositorio que está completamente separado del original*
    <br>

    - **Rama:** *La rama es algo que se usa para cambiar ciertas partes de un programa,  para luego fusionar los cambios con el núcleo.*
- Has creado una confirmación y la has enviado, ahora es pública. Sin embargo, has notado que todavía hay cosas que deben cambiarse. ¿Puedes hacerlo en la etapa de confirmación? y si es así, ¿Cómo?
    -
    - **Si, lo que tienes que utilizar es un comando llamado 'revert'.**
    > git revert [--[no-]edit] [-n] [-m parent-number] [-s] [-S[< keyid>]] < commit>…​<br>
    git revert (--continue | --skip | --abort | --quit)
-   ¿Qué es "cherry-picking"?
    -
    - **Es cuando tienes un rama git y aplicas las caracteristicas a otra rama**
- ¿Qué es un "stash"?
    -
    - **El stash actúa como una unidad de almacenamiento, guarda tu proyecto y todas sus características, esto te permite regresar luego de un tiempo y continuar trabajando desde donde lo dejaste.**
-  ¿Cómo resuelves "conflictos " en Git?
    -
    - **Los conflitos se resuelven utilizando comandos como 'git add' y 'git commit', despues de haber modificado y descartando los cambios requeridos.**
- ¿Cuál es el lenguaje utilizado en Git?
    -
    - **El leguaje utilizado en git es 'c'**
- ¿Qué es una "solicitud de extracción"?
    -
    -  **Una solicitud de extracción es cuando tomas un repositorio y luego creas tu propia rama. Para realizar cambios y luego fusionarla con la principal.**
-  ¿Cuál es la manera más eficiente de encontrar una mala confirmación?
    -
    - Con el comando 'git bisect' es la manera mas eficiente de harcerlo aunque tambien se podria hacer.

> Anexo a preguntas interesantes de Stackoverflow

1. https://es.stackoverflow.com/questions/90/c%c3%b3mo-puedo-deshacer-el-%c3%baltimo-commit-en-git
1. https://es.stackoverflow.com/questions/170/c%c3%b3mo-cambiar-el-mensaje-de-un-commit
1. https://es.stackoverflow.com/questions/1458/regresar-un-repositorio-a-un-commit-especifico
1. https://es.stackoverflow.com/questions/121/c%c3%b3mo-revertir-un-commit-si-ya-sub%c3%ad-los-cambios-al-origen
1. https://es.stackoverflow.com/questions/90567/git-push-falla-porque-otro-desarrollador-subi%c3%b3-cambios
1. https://es.stackoverflow.com/questions/197462/para-qu%c3%a9-se-usan-los-tags-en-git
1. https://es.stackoverflow.com/questions/83624/cu%c3%a1l-es-la-diferencia-entre-git-rebase-y-git-merge
    - https://medium.com/@MiguelCasas/diferencia-entre-git-rebase-y-git-merge-workshop-de-git-8622dedde2d7
    - http://panicoenlaxbox.blogspot.com/2017/09/merge-vs-rebase.html 
    - https://www.youtube.com/watch?v=quwMkNL4MJg
1. https://es.stackoverflow.com/questions/1148/c%c3%b3mo-ver-qu%c3%a9-archivos-son-diferentes-entre-2-ramas-con-git
1. https://es.stackoverflow.com/questions/15317/git-me-pide-contrase%c3%b1a-cada-vez-que-env%c3%ado-a-github 
1. https://es.stackoverflow.com/questions/1740/eliminar-una-rama-git-tanto-el-local-como-en-remoto
1. https://es.stackoverflow.com/questions/158303/c%c3%b3mo-averiguar-la-procedencia-de-una-rama-determinada