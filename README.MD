Crear la GVR Camera Rig y Preparando la escena para la interacción
Para la creación de la cámara se sigui los pasos dentro del PDF, y de ahí se tuvo que asegurar que todos los componentes dentro del GVRCameraRig estuvieran en la posición 0 0 0 para que encajen bien
 ![1](/READMEIMG/1.png?raw=true "Title")
Hacer que los objetos del juego sean interactivos (Coin, llave, Puertas y Letrero)
Pues para los primeros tres objetos se tuvo que simplemente añadir el script como lo indicaba el pdf en el caso del letrero ademas de añadir el script se tuvo que cambiar el Graphic Raycaster por el script GvrPointerGraphicRaycaster y listo.
 ![2](/READMEIMG/2.png?raw=true "Title")
Comportamiento del Coin
Además de crear el GameObject coinPoofPrefab; Se tuvo que crear otro GameObject mas para poder controlar la moneda desde ahí con la ayuda del script
 ![3](/READMEIMG/3.png?raw=true "Title")
Comportamiento de la Key
Pues es básicamente los mismo que la Coin pero esta vez se tuvo que hacer referencia a un objeto externo que es la door y llamar a uno de sus métodos
 ![4](/READMEIMG/4.png?raw=true "Title")
Comportamiento de la puerta.
En este caso la programación de este script estuvo mas complicada, se tuvo que establecer bien la posición inicial de las puertas para que luego estas no se desaparezcan, luego otro punto a recalcar es que se multiplico del Time.deltaTime por 8 para hacer que la apertura de la puerta sea mas veloz 
 ![5](/READMEIMG/5.png?raw=true "Title")
Programando el comportamiento del SignPost
Este estuvo muy simple solo se uso el SceneManagement y luego se referencio a la escena y que debería recargarse.
 ![6](/READMEIMG/6.png?raw=true "Title")
Crear la funcionalidad del juego
Este es el laberinto, contiene varios puntos, se muestra dentro del cuadro rojo la posición de la llave y dentro del cuadro azul la salida.
 ![7](/READMEIMG/7.png?raw=true "Title")




Objetos adicionales dentro del laberinto seria la presencia de un gran panel de vidrio frente a la puerta y la importación de un desiño realizado en SketchUp
 ![8](/READMEIMG/8.png?raw=true "Title")
 ![9](/READMEIMG/9.png?raw=true "Title")
