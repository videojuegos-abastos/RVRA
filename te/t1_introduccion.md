# Introducción

## Realidad Virtual y Realidad Aumentada

Aunque hoy en día ya mucha gente sabe qué es la Realidad Virtual, es importante definir algunos conceptos, más que nada porque cuando nos adentremos más en ésta, veremos que hay diferentes nomenclaturas para cosas muy parecidas como Realidad Mixta o Realidad Extendida.

Veamos primero la Realidad Virtual.

Definiremos **R**ealidad **V**irtual, en adelante **RV**, como una recreación tridimensional virtual inmersiva de un entorno que nos permite tener la sensación de encontramos realmente dentro de él.

Para generar dicha recreación, se necesita un software avanzado y diferentes componentes externos. Una de las claves de la RV es la interactividad con el entorno virtual. Una imagen de 360° en la que simplemente visualizamos algo, no lo consideraríamos RV ya que lo único que se puede hacer es mirar.

Si necesitemos un software avanzado para crear una de estas 'simples' experiencias como la de visualizar una imagen 360°, es obvio que si queremos ir más allá y permitir la interactividad entre el mundo virtual y nosotros, necesitaremos herramientas especializadas en 3d y muy optimizadas para ejecutar el código en tiempo real. Da la casualidad que los motores de videojuegos son la solución ideal a esta necesidad. Unity en concreto soprta diferentes plugins con los que podemos desarrollar para RV, lo utilizaremos también para esta asignatura.

<p align="center">
<img src="img/intro_vr.jpg" width="80%" />
</p>

Bien, ya sabemos qué es la RV, veamos ahora las diferencias entre esta y la **R**ealidad **A**umentada o **RA**.

La **Realidad Aumentada** es un recurso tecnológico que ofrece experiencias interactivas al usuario a partir de la **combinación entre la dimensión virtual y la física**, con la utilización de dispositivos digitales.

Es decir, que mientras que en la RV estamos sumergidos por completo en un mundo virtual, en la RA, mezclamos elementos virtuales con la realidad física.

<p align="center">
<img src="img/intro_ra.jpg" width="60%" />
</p>

La RA tiene muchos ámbitos de aplicación, desde los videojuegos hasta las empresas de logística. Veamos algunos ejemplos.

* Videojuegos, ([Pokémon GO](https://pokemongolive.com/es/))
* Moda, existen formas de 'probarnos' ropa, o complementos como gafas para ver cómo nos quedan.
* Logística, algunas empresas de logística y transporte han empezado ya a utilizar dispositivos con realidad aumentada sobre todo para ver cómo colocar y encajar las mercancías en sus almacenes, naves y medios de transportes. Volkswagen y Bosch son pioneras en esto.
* Publicidad, las empresas publicitarias ven un altísimo potencial en la RA para desarrollar nuevas actividades de promoción que “enganchen” a los consumidores. La empresa de publicidad Blippar por ejemplo, ya ha desarrollado una 'app' que permite escanear productos, folletos o anuncios con el móvil para iniciar experiencias interactivas en la pantalla.
* Sector inmobiliario, imagina amueblar un piso con una app primero para ver cómo queda y hacerlo después en la realidad. Esta es otra de las ideas para la RA.

Las ideas y posibilidades para la RA son casi infinitas, en este curso, veremos cómo desarrollar con esta tecnología para poder hacer nuestras pequeñas apps.



<p align="center">
<img src="img/intro_ra_pokemon.jpg" width="60%" />
</p>


## Realidad Mixta y Realidad Extendida

A parte de las más conocidas RV y RA, esxisten también otras dos de estas 'realidades'.

En **Realidad Mixta**, lo que hacemos, es también una mezcla entre entornos reales y virtuales pero no como en la RA.

La diferencia es que en la realidad mixta escaneamos o mapeamos de alguna forma un entorno real y lo virtualizamos, de forma que ahora podemo entrar en un entorno virtual que es exactamente igual que este entorno real.

Obviamente, a este entorno virtual, que es una imitación del real, podemos añadirle más elementos virtuales. Es como si escaneáramos nuestra propia habitación, nos pusiéramos las gafas y siguiésemos estando en nuestra habitación, pero ahora, además, hay un yeti en la cama.

<p align="center">
<img src="img/intro_rm.jpg" width="80%" />
</p>

Convertir los entornos reales en virtuales no es una tarea sencilla y hay varias formas de hacerlo. Dependiendo de los requisitos que tengamos nos vendrán mejor una u otras.

La forma más simple es directamente modelar el propio entorno, es decir, ir haciendo cada objeto y después montar una escena posicionando cada uno en su sitio. Si quisiérmaos por ejemplo crear un juego o una app que se desarrolla en un entorno muy concreto podríamos hacer esto. Tiene algunas ventajas, como que tenemos más nivel de control sobre la propia escena y que podemos dar diferentes propiedades a los objetos. Por ejemplo podemos hacer que una taza que hay encima de la mesa podamos cojerla pero que no podamos mover la propia mesa.

Existen técnicas más avanzadas que, por lo general, requieren dispositivos y software específico. ESCANNER OBJETOS; IA;


## Dispositivos


1. Introducción
• Realidad Virtual (RV) y Realidad Aumentada (RA)
• Realidad Mixta (RM) y Realidad Extendida (RX)
• Dispositivos
2. Actualidad de la RV
• RV y Videojuegos
• Problemas e Inconvenientes Generales
3. Proyectos y Justificación
• Orientación y Posicionamiento
• Opciones para el Desarrollo en Unity
• Instalación y Configuración del Entorno en Unity
4. Proyecto RV
• Diseño de Niveles
• Interfaz Gráfica
• Ejemplo y Testeo
• Desarrollo de Proyecto
5. Proyecto RA
• Creación de Espacios, Realidad y Virtual
• Dispositivos Específicos
• Combinación de mundo Real y Virtual
• Ejemplo y Testeo
• Desarrollo de Proyecto
6. Educación y Accesibilidad
• Aplicaciones Reales, Videojuegos para el Aprendizaje
• Accesibilidad