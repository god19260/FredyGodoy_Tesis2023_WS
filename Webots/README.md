La carpeta "Webots" incluye subcarpetas que contienen archivos del entorno simulado, modelos 3D que representan el vehículo de tracción diferencial Pololu 3Pi+, así como los controladores de dicho vehículo con los algoritmos desarrollados en este trabajo. Además, contiene el controlador del entorno simulado.

Para utilizar este trabajo es necesario descargar toda la carpeta de Webots. Para este trabajo se utilizó Webots R2023a y los controladores se desarrollarón con Python 3.11.1.

* [controllers](Webots/controllers): Esta carpeta contiene 2 controladores diferentes. La primer carpeta, Contralador_VD, contiene los archivos con los algoritmo para el funcionamiento del vehículo diferencial.
y la segundo carpeta, Supervisor_Mundo, contiene el controlador del entorno simulado en Webots. El controlador del entorno tiene 2 modos de funcionamiento. El primero es para obtener la información de la posición y orientación de los obstaculos definidos tanto en Webots como en este controlador. El segundo modo es
para colocar las paredes en posiciones previamente definidas.
* [worlds](Webots/worlds): Esta carpeta contiene el entorno de simulación.
* [Modelos_3D/pololu](Webots/Modelos_3D/Pololu): Esta carpeta contiene la representación 3D del vehículo con tracción diferencial Pololu3pi+, los cuales se utilizaron en Webots para realizan un proto y así poder tener una plataforma en la cual poner a prueba los algoritmos desarrollados.
  
<p align="center">
  <img src="Anexos/Pololu3pi+/Portada.png" width="50%">
</p>
