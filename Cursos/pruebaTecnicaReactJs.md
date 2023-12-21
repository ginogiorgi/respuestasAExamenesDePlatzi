# Curso Profesional de Git y GitHub

## ¿Por qué hacemos `JSON.stringify({})` en `localStorage.setItem('account', JSON.stringify({}))`?
    Para que en localStorage no tengamos algo como: account = [object, Object], sino como: account = {}.
## Podemos renderizar unos elementos del Navbar u otros dependiendo de si el usuario está loggeado o no gracias a:
    Conditional Rendering
## Para capturar la información de un formulario, debemos:
    Añadir el atributo ref en el elemento de HTML, usar el hook useRef y crear una instancia de FormData.
## Si un usuario quiere ir a la vista Home, pero no tiene cuenta, ¿qué usaríamos en useRoutes para no permitirle el acceso a Home, pero que lo redirija a la página de SignIn?
  path: ‘/’,
  element: hasUserAnAccount ? <Home/>: <Navigate replace="" to="{’/sign-in’}"/>
## ¿Qué clases de TailwindCSS nos permiten centrar un elemento verticalmente con Flexbox?
    flex y items-center