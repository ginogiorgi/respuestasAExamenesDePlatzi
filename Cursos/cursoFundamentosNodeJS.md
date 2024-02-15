# Curso de Fundamentos de Node.js

## ¿Cuál es el motor de JavaScript sobre el que corre Node?
    V8
## Cuando un evento llega al Event Loop, ¿dónde lo manda Node?
    Al thread pool
## ¿Cómo accedemos a una variable de entorno llamada NOMBRE?
    process.env.NOMBRE
## ¿Qué pasa si salta un error no capturado en el hilo principal?
    El proceso se detiene
## ¿Cual es la herramienta más adecuada para ejecutar nuestros procesos de Node en producción?
    PM2
## ¿Cómo se le llama a la función que se ejecuta cuando termina otra función asíncrona?
    Callback
## ¿Cuál es la mejor forma de evitar un Callback Hell?
    ESTAN MAL: [Modularizar el código][No anidar callbacks]
## ¿Cuántos parámetros puede recibir el then de una promesa?
```js
promise
    .then()
    .catch()
```
    ESTAN MAL: [Dos: Success y Error][Todos los que quieras]
## ¿Se puede usar la palabra reservada "await" en cualquier sitio?
    No, solo en funciones declaradas con async
## ¿Cuál de los siguientes módulos NO está en los módulos globales?
    crypto
## ¿Cómo indentamos un nivel los logs de consola?
    console.group
## Por defecto, ¿cómo detectamos que un fichero se ha escrito con fs.writeFile?
    Con el callback
## Cuando se lanzan excepciones, ¿cómo las capturamos?
    Con try / catch
## ¿Se pueden ejecutar comandos del sistema desde NodeJS? ¿Cómo?
    Si, con procesos hijo
## ¿En qué lenguajes se pueden desarrollar módulos nativos para NodeJS?
    JavaScript y C++
## ¿En qué puerto se puede iniciar un servidor HTTP en Node?
    En cualquiera
## ¿Podemos acceder a la memoria disponible y total del sistema operativo desde NodeJS?
    Si, con el módulo OS
## ¿Podemos controlar cuando se cierra el proceso de Node, y ejecutar código antes de que muera?
    Si, con el módulo Process
## ¿Dónde se listan las dependencias de nuestro proyecto?
    En el package.json
## Cuando creamos un módulo, ¿podemos exportar mas de una entidad?
    Si, tantas como queramos
## ¿Qué módulo nos permite trabajar con imágenes desde NodeJS?
    Sharp
## ¿Cuál es la principal ventaja de trabajar en memoria frente a la lectura y escritura en disco?
    La velocidad es mayor
## ¿Qué es un Buffer?
    Un conjunto de datos crudos
## ¿Puede un stream transformar datos?
    Si, usando un stream de transformación
## ¿Cómo sabemos lo que tarda un trozo de código en ejecutarse?
    Usando console.time
## ¿Podemos parar el código en un punto determinado mientras se ejecuta?
    Si, con el debugger
## En un callback, ¿cuál debería ser el primer parámetro?
    El error
## ¿Podemos usar NodeJS para acceder al DOM de un sitio externo y extraer información de él?
    Si, con puppeteer
## ¿Qué herramienta nos permite crear tareas en NodeJS para automatizar procesos?
    Gulp
## ¿Se puede usar NodeJS para crear aplicaciones de escritorio?
    Si, con Electron