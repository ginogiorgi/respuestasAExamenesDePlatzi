# Curso Profesional de Git y GitHub

## Los cambios a un archivo que están en “staging” están en:
    Un área temporal en memoria antes de llegar al repositorio.
## ¿Puedo crear ramas en GitHub que no tenga en mi repositorio local?
    Sí, tú decides si traer esas ramas a tu repositorio local.
## En un commit, los mensajes del commit son:
    Importantes y obligatorios.
## ¿La terminal ideal para usar Git en Windows es?
    Git Bash o una terminal derivada de Linux
## Con checkout puedo:
    Ver todos los archivos de mi proyecto como los dejé en otras ramas.
## ¿Puedes conectar tu repositorio local con más de un repositorio remoto?
    Verdadero
## Es mejor aprender a manejar Git con la terminal antes de hacerlo con herramientas visuales como Gitk porque:
    Debemos aprender Git con sus comandos de la terminal para resolver problemas o conflictos más avanzados. Gitk funciona bien, pero no nos permite realizar operaciones tan complejas.
## Un repositorio remoto y un repositorio local:
    Tienen ramas similares dependiendo de cuáles haya enviado entre uno y otro.
## El dueño de un repositorio al ver un pull request puede:
    Editarlo, aceptarlo, darle merge, comentarlo para pedir cambios.
## ¿Cuándo debería hacer un merge?
    Cuando quiero fusionar los cambios de una rama con otra.
## En un repositorio público en GitHub, ¿qué puede hacer los colaboradores?
    Hacer cambios al repositorio, hacer push/pull, crear ramas, etc.
## ¿Qué es un branch o una rama en Git?
    Un repositorio aparte del master donde puedes trabajar en paralelo.
## Si usas:
    git config --global alias.platzi "shortlog"
## Si usas: git config --global alias.platzi "shortlog" ¿Cómo invocar ese comando?
    git platzi
## ¿Con amend puedo?
    Corregir los mensajes de un commit que hice mal sin que quede en la historia del repositorio.
## ¿Cómo instalas Gitk?
    En Windows y Mac podemos instalarlo desde gitk.com/download. En Linux debemos buscarlo con el instalador de paquetes de nuestra distribución.
## Estás en la rama master y quieres mandar los últimos cambios que guardaste con git stash a la rama retomando-los-cambios (la rama no ha sido creada aún). ¿Cuál de las siguientes soluciones es incorrecta?
    git stash apply retomando-los-cambios
## Cuando hago un fork de un proyecto en GitHub, ¿lo que logro es?
    Copiar un repositorio público a mis repositorios en GitHub, con todas sus ramas e historia anterior.
## Git funciona para muchos tipos de archivo, ¿Qué tal funciona Git con archivos binarios?
    Los puede agregar y versionar pero es mejor usar Git con texto plano.
## ¿Cuál es la diferencia entre git rm y git reset HEAD?
    git rm saca los archivos del repositorio y (opcionalmente) del disco duro. git reset head saca los archivos de  Staging, pero no del disco duro.
## Cuando usas git stash, los cambios que “guardas” temporalmente se guardan en:
    Memoria temporal, volviendo al estado del último commit.
## ¿Qué crean los tags en Git?
    Versiones descargables y puntos únicos en una rama de un repositorio.
## Si en el .gitignore agrego esto: images/*.js. ¿Cuál de los siguientes archivos sería ignorado?
    images/jquery.js
## ¿Para qué sirve git grep?
    Para encontrar las veces que hemos usado una palabra en los archivos del repositorio.
## ¿GitHub es?
    Un sistema online de manejo de repositorios de Git.
## ¿Cuándo deberías usar cherry-pick?
    Cuando quiero los cambios de un commit pasado sin dañar la historia de la rama.
## ¿Las llaves públicas son?
    Fáciles de compartir y sus mensajes imposibles de descifrar.
## ¿Para qué sirve GitHub Pages?
    Es un servicio de GitHub que nos permite publicar nuestros repositorios en internet (por ejemplo, nombre.   github.io o nombre.github.io/proyecto).
## ¿Cómo llaman GitHub y GitLab a los "merges" (propuestas de cambios desde otra rama o repositorio)?
    GitHub los llama Pull Request y GitLab Merge Request.
## El Jefe Freddy despidió a Anita y no piensa volver a contratarla. ¿Qué debe hacer Anita para seguir  haciendo contribuciones a los proyectos públicos de Platzi?
    Crear un Fork del proyecto y enviar Pull Request al proyecto original.
## ¿Qué guarda Git?
    Los cambios de los archivos de un proyecto. 
## Para transmitir cambios seguros entre tu repositorio local y GitHub, ¿qué se recomienda?
    Usar una llave SSH.
## ¿El HEAD en una rama es?
    El apuntador al estado actual del repositorio basado en la rama en la que estoy trabajando.
## Se crean dos archivos cuando creas una llave pública y privada para SSH, ¿cuál es la extensión de la llave privada?
    Ninguna extensión
## ¿Qué puedes hacer con gitk?
    Ver en una interfaz visual las ramas y el log de tu repositorio.  
## Un pull request es:
    Un cambio sugerido a un repositorio que el dueño del repositorio puede autorizar y hacer merge a la rama que elija.
## Si ya hiciste el desafío de “Hazme un pull request,” ¿dentro de cuál etiqueta tenías que agregar el cambio?
    <divid="post">  
## Por defecto, GitHub usa la rama main como la rama principal. ¿Podemos cambiar la rama principal?
    Verdadero 
## Para que dos personas trabajen en paralelo sobre el mismo archivo se recomienda:
    Una rama independiente por cada persona y sus cambios que luego con verificación se hace merge a master.
## Cuando hay un conflicto entre archivos lo mejor es:
    Analizar los conflictos tal como los reportó Git y elegir los cambios finales, luego commit.