# Configuración del proyecto de RA para Unity.

Una vez tengamos descargado el [XR-Interaction-Toolkit-Examples](https://github.com/Unity-Technologies/XR-Interaction-Toolkit-Examples), abriremos el proyecto [AR](https://github.com/Unity-Technologies/XR-Interaction-Toolkit-Examples/tree/master/AR).

En este proyecto vienen dos escenas de ejemplo que son con las que empezaremos a hacer las pruebas. El problema viene cuando al intentar generar la build para probar la aplicación nos da errores. En este documento vamos a ver qué parámetros de configuración tenemos que cambiar para que no suceda esto.

Lo primero que necesitaremos es obviamente tener el módulo para exportar a Android instalado. Desde el Unity HUB podemos ir a Installs > Versión de Unity con la que estamos trabajando > Add modules > Android Build Support (Android SDK & NDK Tools y Open JDK).

Una vez tengamos esto, ahora si en nuestro proyecto podemos cambiar el build target a Android y probar a hacer una build. Seguramente nos de algún error. Para evitarlos, nos aseguraremos de que se cumplen los siguientes requisitos en las 'Build Settings' (BS) o 'Player Settings' (PS).

* PS > Other Settings > Color Space*: Linear

* PS > Other Settings > Rendering > Graphics APIs: nos aseguraremos de que no esté Vulkan.

* PS > Other Settings > Identification > Minimum API Level: Mayor que 24.
* PS > Other Settings > Configuration > Scripting Backend: IL2CPP.
* PS > Other Settings > Target Architecture > ARM64.

* PS > Publishing Settings > Custom Gradle Properties Template: True.
Al marcar el checkbox nos aparecerá una ruta donde está el fichero de Gradle Properties, en este fichero, que lo podremos abrir como un archivo de texto normal, comentaremos la línea `android.enableR8=**MINIFY_WITH_R_EIGHT**` con un `#`.

* BS > Developement Build: True (Recomendado)