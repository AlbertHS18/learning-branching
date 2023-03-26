## Resumen de los comandos usados en el juego.

### Commit.

Este sea quizás el comando más utilizado de Git. Una vez que se llega a cierto punto en el 
desarrollo, queremos guardar nuestros cambios (quizás después de una tarea o asunto específico).  

### Branch.

Con este comando se pueden crear ramas en git, una 
rama esencialmente dice "Quiero incluir el trabajo de este commit y todos su ancestros".

### Checkout.

Este es también uno de los comandos más utilizados en Git. Para trabajar en una rama, primero tienes que 
cambiarte a ella. Usaremos git checkout principalmente para cambiarte de una rama a otra. También lo podemos 
usar para chequear archivos y commits.

### Cherry-pick.

Es un potente comando que permite que las confirmaciones arbitrarias de Git se elijan por referencia y se añadan
al actual HEAD de trabajo. La ejecución de cherry-pick es el acto de elegir una confirmación de una rama y aplicarla
a otra. git cherry-pick puede ser útil para deshacer cambios.

### Reset.

Git reset es un comando potente que sirve para deshacer los cambios locales en el estado de un repositorio de Git. Git
reset actúa en "los tres árboles de Git". Estos árboles son el historial de confirmaciones ( HEAD ), el índice del 
entorno de ensayo y el directorio de trabajo.

### Revert.

Utilizando este comando es una manera segura para deshacer nuestras commits y debe
ser utilizado cuidadosamente para evitar borrados no deseados.

### Rebase.
Este comando consiste en cambiar la base de tu rama de una confirmación a otra haciendo que 
parezca que has creado la rama desde una confirmación diferente. Internamente, Git lo hace 
creando nuevas confirmaciones y aplicándolas a la base especificada.

### Rebase -i.
Es cuando git rebase acepta un argumento - i , que significa "interactivo". Sin ningún argumento, 
el comando se ejecuta en el modo estándar. En ambos casos, vamos a presuponer que hemos creado una rama de 
función aparte. Y este nos permite poder elegir el orden y cuales commir queremos incluir a la operacion con una ventana
emergente.

### Merge.

Hacer merge en Git crea un commit especial que tiene dos padres diferentes. Eso 
significa que el merge creado tiene todo el trabajo junto de sus dos padres anteriores.

### Especificadores.

En lugar de especificar cuántas generaciones hacia atrás ir (como ~), el modificador de ^ especifica por 
cuál de las referencias padres seguir en un commit de merge. Recuerda que un commit de merge tiene múltiples 
padres, por lo que el camino a seguir es ambiguo.

Git normalmente sigue el "primer" padre de un commit de merge, pero especificando un número junto con ^ cambia 
este comportamiento predefinido.

### Git clone.

Git clone se usa principalmente para apuntar a un repositorio existente y hacer un clon o una copia de ese repositorio en un nuevo directorio, en otra ubicación . El repositorio original se puede ubicar en el sistema de archivos local o en protocolos admitidos a los que se puede acceder desde una máquina remota.

### Git Fetch.

Git fetch es un comando principal que se usa para descargar contenido de un repositorio remoto . git fetch se usa junto con git remote, git branch, git checkout y git reset para actualizar un repositorio local al estado de un remoto. El comando git fetch es una pieza fundamental de los flujos de trabajo colaborativos de git.

### Git Pull.

Git pull se emplea para extraer y descargar contenido desde un repositorio remoto y actualizar al instante el repositorio local para reflejar ese contenido. La fusión de cambios remotos de nivel superior en tu repositorio local es una tarea habitual de los flujos de trabajo de colaboración basados en Git.

### Git Push.

El comando git push se usa para cargar contenido del repositorio local a un repositorio remoto . Empujar es cómo transfiere confirmaciones de su repositorio local a un repositorio remoto. Es la contraparte de git fetch , pero mientras que la obtención de importaciones se compromete a las sucursales locales, la exportación se compromete a sucursales remotas.

### Git Pull origin.

Obtiene confirmaciones de la rama maestra del control remoto de origen (en la rama local de origen/maestro), y luego fusiona origen/maestro en la rama que actualmente has desprotegido . `git pull` solo funciona si la rama que ha verificado está rastreando una rama ascendente.


## Capturas de niveles realizados.


### -  Principal levels.



[![Principal-levels.jpg](https://i.postimg.cc/yYQZ9MBK/Principal-levels.jpg)](https://postimg.cc/4mcyRFm2)


### - Remote levels.



[![Remote-levels.jpg](https://i.postimg.cc/XvV6bzGZ/Remote-levels.jpg)](https://postimg.cc/cv5b7TcZ)


