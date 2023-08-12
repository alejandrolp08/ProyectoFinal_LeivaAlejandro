Proyecto Final CoderHouse - Python
Comisión: 
Alumno: Alejandro Leiva Pimentel
Nombre del Proyecto
Tienda de figuras


El usuario admin (id: admin / passw: 1234)

Versión
1.0

Para poder ejecutar el proyecto seguir los siguientes pasos:

En terminal: 
> python3 -m venv .venv

Luego abrir neuvo terminal, tiene que aparecer (.venv), solo asi sabremos que estamos OK

Posicionarse en "project"
> cd project

Posteriormente ingresar los siguiente codigos para evitar errores:

`python manage.py makemigrations`
> Crea las migraciones, que son archivos Python encargados de la base de datos

`python manage.py migrate`
> Ejecuta las migraciones, para que se realicen los cambios en la base de datos

python manage.py runserver`
> Ejecuta el servidor

Luego seleccionar el link que aparecera en la terminal, EJM: "http://129.0.0.1:9000/"

Felicidades, ejecutaste el proyecto satisfactoriamente!


Descripción del Proyecto
Página Web destinada a la venta de figuras varias

A fin de navegar el usuario puede realizarlo libremente por la página web pero solo tendra visualizacion de la pagina de Inicio y About/sobre nosotros.
Otras opciones en la barra de navegacion estaran disponibles solo para usuarios registrados (como es la lista de productos en la pagina web y las categorias),


El usuario admin (id: admin / passw: 1234) es el unico que puede añadir, eliminar y/o editar los productos y categorias en la pagina web.
El usuario admin es el unico que tiene acceso especial e ilimitado tanto para editar, eliminar y visualizar productos y categorias
Admin tambien puede ingresar al panel de control (back end) y realizar ediciones internamente, se añadio la posibilidad de agregar un avatar a acada producto en la pagina web (para poder subir una imagen)

Para ingresar un nuevo usuario podra realizar el registro directamente en la web, ejm (id: alejandrolp / passw: 084231543a), un vendedor registrado puede realizar las guientes accciones:

Visualizar la lista de categorias en la pagina web
Visualizar la lista de productos en la pagina web

Ambas opciones no estan disponibles para personas no registradas

Tanto el usuario admin como cualquier vendedor tiene la opcion de cerrar sesión

Login en caso de haber cerrado sesión.


Tecnología Utilizada

Front-End
HTML
CSS
Bootstrap

Back-End
Python 3.11.3
Django 4.2.3


Video Demostración:

Por temas de trabajo no he podido dedicar un tiempo a realizar la grabacion y publicacion del video
demostracion del proyecto pero espero realizar en los siguientes dias
>>>>COPIAR LINK DE VIDEO DE YOUTUBE AQUI>>>
