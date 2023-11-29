# Banderín Hecho a Mano - Etapa 1

Para realizar el proyecto, identificamos las siguientes tareas a realizar. Vamos a trabajar usando git + github, realizando cada tarea en una rama que salga directamente desde dev, donde luego integraremos los cambios.

**La rama main queda reservada para deployar**

#### nota: 
    Quedaron muy bien resueltos los diseños! Algunas propiedades que les van a ayudar con el tema de las partes superpuestas unas a otras son: 
        position: relative | absolute
        z-index: nmber 


## Antes de empezar

- Definir paleta de colores
    - incluirla en la rama *dev* usando customProperties sobre el pseudelemento :root.
    **Intentaremos no usar colores que no llamemos a tráves de estas variables, para mantener un estilo consistente**.
        Esto lo hacemos antes que nada, para ya salir con las ramas para las distintas tareas con eso hecho.
- Igualmente, definir la altura a usar para breakpoint de las mediaqueries y recordar desarrollar usando el método **mobile-first**.

## Primera etapa
 Apuntamos a desarrollar el sitio de manera correcta, aprendiendo a colaborar en un repositorio de git. Cuando tengamos una primera versión completa, haremos el primer deploy de prueba y pasaremos a hacer las mejoras necesarias en la **segunda etapa**

### Navbar/Header
En principio, *no incluir barra de búsqueda ni logos de perfil y carrito*
La navbar debería seguirnos y estar siempre en la parte superior de la página. Al scrollear X cantidad de píxeles, debería pasar a ser una versión más pequeña (por ejemplo, el logo desaparecería, quedaría solo la barra naranja del  fondo incluyendo ahora una versión más pequeña del logo).
En dispositivos móviles, la navbar debería ofrecer un botón para mostrar/ocultar las opciones. También debería ser siempre visible.

### Hero
La sección Hero es lo primero que vemos al entrar a un sitio institucional. Está muy bien resuelta en los diseños tanto en desktop como responsive.


### Productos

Para ambas secciones, una galería de cards que se recorra hacia los lados con un click/deslizando el dedo sobre la pantalla.

#### Por Categoría

Para esta sección, redirigir a una página donde se vean en galería (sin scroll horizontal) todos los productos de esa categoría, donde cada uno se puede abrir en un modal, que muestre en grande la foto y todo el fondo oscurecido.

#### Productos Favoritos

para esta sección, cada producto que que sea clickeado abrirá un modal como el que se describe arriba, sin salir de la página principal. El botón ver más llevará a una página con todos los productos de todas las categorías.

### Quiénes somos

Respetar el diseño planteado. Si van a mostrar fotos de las distintas dueñas, que la etiqueta con el nombre no sea parte de la imagen, sino un elemnto HTML que manipulen con JS.

[Compartir mapas y direcciones](https://support.google.com/maps/answer/144361?hl=en&co=GENIE.Platform%3DDesktop#:~:text=Share%20a%20map%20or%20location&text=Go%20to%20the%20directions%2C%20map,image%20you%20want%20to%20share.&text=Select%20Share%20or%20embed%20map,next%20to%20%22Short%20URL.%22)
<br />
[Librería de animaciones CSS, algo como la animación de nombre 'pulse' ](https://support.google.com/maps/answer/144361?hl=en&co=GENIE.Platform%3DDesktop#:~:text=Share%20a%20map%20or%20location&text=Go%20to%20the%20directions%2C%20map,image%20you%20want%20to%20share.&text=Select%20Share%20or%20embed%20map,next%20to%20%22Short%20URL.%22)


### Vení a conocernos

Agregar una animación leve a la imagen central de la sección, y que al hacer click te abra google maps con la dirección del local. 


[Compartir mapa o dirección](https://support.google.com/maps/answer/144361?hl=en&co=GENIE.Platform%3DDesktop#:~:text=Share%20a%20map%20or%20location&text=Go%20to%20the%20directions%2C%20map,image%20you%20want%20to%20share.&text=Select%20Share%20or%20embed%20map,next%20to%20%22Short%20URL.%22)
<br />
[Librería de animaciones (ejemplo 'pulse')](https://animate.style/)

### Espacio cultural

Incluye el formulario. Buscar como plantearlo, ya que no es un formulario para "enterarse de novedades". Podría ser para hacer consultas o inscribirse como artesano para colaborar con el local.

### Footer

Incluir íconos a las redes sociales.

[Sitio para buscar SVGs](https://www.svgrepo.com/vectors/facebook/)
[Proveedor de íconos](https://fontawesome.com/)



## ¿Qué sigue?

- encontrar problemas y realizar mejoras
- investigar y aplicar SEO
- testear en distintos dispositivos/ambientes
