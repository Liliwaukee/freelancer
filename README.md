# Freelancer

* **Track:** _Common Core_
* **Curso:** _Creando un sitio web interactivo con JavaScript_
* **Unidad:** _1: Maquetado web con HTML & CSS_

***

Este reto consiste en replicar la página https://blackrockdigital.github.io/startbootstrap-freelancer/.
Lo más importante en el reto es la maquetación.


## Construcción del sitio web

* La maquetación se dividió en 6 secciones con etiquetas semánticas:

   **Nav
   **Main
   **Section (3)   
   **Footer

Para el sitio necesitamos la tipografía Montserrat y los íconos de FontAwersome, ambos se van a enlazar dentro de la etiqueta "head". La tipografía la obtenemos de Google Fonts y en la página de FontAwersome descargamos el zip.

## Nav
- Nav esta dividido en 2 "divs". Uno para el título "START BOOTSTRAP" y el otro para el menú. Tiene la propiedad de "position:fixed" para que se mantenga fijo aunque se haga scroll.
- Cada div ocupa el 50% del ancho de pantalla y tienen la propiedad "float=left" para que se ponga uno de lado de otro.
- La parte del menú se construyó con "ul", se agregó un link "a" para cada "li" y así nos lleve a esa parte de la página.

## Main
- En main esta contenido una imagen, un título (subrayado) y un párrafo. El subrayado es una estrella con líneas laterales.
- Para el título se creo una clase que se va a reusar en los demás  títulos de secciones, las propiedades que se usan son "font-size, font-weight, y padding" para modificar tamaño, peso y el espacio alrededor del título.
- La estrella se agregó con FontAwersome "i" y las lineas son "hr" con propiedades en css que modifican su "width" y el borde inferior.

## Section Portfolio
-Está compuesta de un título y 6 imagenes.
- Las imagenes se agruparon dentro de un "div" y se les dio un ancho de 27% para que sólo quepan 3 imágenes por fila.

## Section About
- El título de la sección se usa con la clase que ya se creo.
- Para las columnas se creó un "div" con 2 divs anidadados, cada una contiene un párrafo.
- El botón tiene anidado un link "a" y un icono "i".


## Section Contact
- Tiene un título y un formulario. El título tiene la clase section-title (creada desde el principio) y el formulario esta creado en un div anidado.
- El formulario tiene 5 etiquetas "label", 5 "input" y un "button". Las etiquetas "label" son para poner el nombre del dato que se espera recibir del usuario y los "input" para ingresar el texto.


## Footer
- Esta dividido en 3 columnas creadas con divs, tienen la propiedad "display= inline-block" y "float= left" para que se coloque horizontalmente una a lado de otra.
- Todos los textos se colocaron en etiquetas "p".
- Los iconos de redes sociales se ordenaron por medio de "ul" con un link "a", en la propiedad "a" se le dio una clase para poder crear el círculo que envuelve el ícono.
- El copyright esta dentro de una etiqueta "p" y tiene la propiedad "clear:both" para que el float de los divs no le afecte.
