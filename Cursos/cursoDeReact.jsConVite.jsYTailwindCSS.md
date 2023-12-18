# Curso de React.js con Vite.js y TailwindCSS

## ¿Qué componente de react-router-dom nos permite saber si está activo o no para cambiarle los estilos dependiendo de este estado ?
    NavLink
## La prop children sirve para crear componentes genéricos como Layout en nuestro proyecto ya que el contenido puede ser intercambiable.
    Verdadero
## ¿Qué clases de TailwindCSS nos permite que un elemento tenga posición absoluta y que tenga top: 0 y rigth: 0 ?
    absolute top-0 right-0
## ¿Qué Hook se utiliza para hacer el llamado a una API ?
    useEffect
## ¿Qué nos permite pasar datos a los diferentes componentes sin tener que hacer tanto uso de props ?
    context
## En ¿Qué nos indica el número 0 dentro de useState ?
    ``` 
    const [count, setCount] = useState(0)
    ```
    El valor inicial del contador.
## Si tenemos para abrir y cerrar un menú, ¿qué usaríamos para MODIFICAR el valor de false a true ?
    ``` 
    const [isProductDetailOpen, setIsProductDetailOpen] = useState(false)
    ```
    setIsProductDetailOpen(true)
## Si queremos crear una función generica (como la de totalPrice), lo ideal sería añadirle un comentario que contenga:
    Descripción de lo que hace la función, los parámetros que recibe y lo que retorna.
## ¿Qué le haría falta a: context.items?.map(item => ) ?
    Una key para cada Card
## Qué retorna la siguiente función:
    ``` 
    const handleDelete = (id) => context.cartProducts.filter(product => product.id != id)
    ```
    Todos los productos del carrito que tengan un id diferente al id enviado en el parámetro de la función.