# Proyectos RA

## XR Interaction Toolkit

Como sabemos, vamos a utilizar los componentes que nos proporciona el `XR Interaction Toolkit`, como es normal, no sabremos qué hacen o cómo se usan los componentes, para ello debemos consultar la [Documentación](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@0.9/manual/index.html).

A parte de la documentación, hay ejemplos que utilizan el toolkit desarrollados para que podamos copiar los componentes y objetos, estos los hemos usado en clase y los podemos encontrar en el repositorio de Github [XR-Interaction-Toolkit-Examples](https://github.com/Unity-Technologies/XR-Interaction-Toolkit-Examples).

Aunque hemos explicado lo más básico sobre algunos de estos componentes en clase y tenemos la documentación y ejemplos, es extremadamente recomendable ver vídeos explicativos ya que se hace mucho más ameno que leer y por lo general vamos a acabar entendiendo mejor las cosas. [Vídeo introducción a XR Interaction Toolkit](https://www.youtube.com/watch?v=H6d-hagFFNc) (AR).

> A parte del vídeo adjunto existen mucho más, cuantos más vemamos y más claras tengamos las cosas mejor. No olvidemos eso sí que solo viendo vídeos no vamos a saber hacer las cosas, será necesario ponerlas en práctica.

## Tutoriales

[Configuración y requisitos básicos](https://youtu.be/H6d-hagFFNc?t=136).

> Para la configuración, la mayoría de los vídeos no nos van a valer debido a que las versiones pueden ser diferentes o pueden tener algun tiempo. Preferiblemente seguiremos el [Documneto de configuración](https://github.com/videojuegos-abastos/RVRA/blob/main/te/configuracion_ra.md).
> En cuanto a los requisitos básicos, aunque ya los tenemos con el XR-Interaction-Toolkit configurados, no está de más ver esa parte ya que nos haremos una mejor idea de para qué sirven cada uno y cómo están relacionados entre sí.
> En el vídeo, en la parte en la que crea los objetos y componentes básicos se olvida del `AR Session`, podemos verlo en el [minuto 11](https://youtu.be/H6d-hagFFNc?t=660).


[Selección, Translación, Escalado y Rotación](https://www.youtube.com/watch?v=AGAjUt5Oy6o)

[Anotaciones](https://www.youtube.com/watch?v=hi-zVWJOfxY)

## Proyecto 0: Configuración

Seguiremos el documento de [Configuración RA](https://github.com/videojuegos-abastos/RVRA/blob/main/te/configuracion_ra.md)


## Proyecto 1: Aplicación Muebles

El objetivo de este proyecto es desarrollar una aplicación de Realidad Aumentada para dispositivos Android en la que podamos escojer un mueble y posicionarlo en la habitación.

### Requisitos:

* Podremos mover, escalar y rotar el mueble.

* Al mirar hacia el mueble, aparecerá su nombre.

* Podremos crear más de un mueble distinto.

* Habrá un boton que al pulsarlo nos indicará hacia dónde mirar para ver el mueble.

* Utilizaremos los eventos que nos proporciona la librería para conseguir algun efecto interesane. (Cambio de color, partículas, cambio de mueble, etc.)
