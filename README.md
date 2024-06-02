# InovaMath

## Integrantes
-Osmar Israel Villegas Martinez 
-Mario Alberto Rangel Marquez
-Martin Gabriel Godinez Morales

## Objetivo general
Diseñar y desarrollar un sistema de IoT (Internet de las cosas) que permita monitorear y controlar el ambiente de una planta en una maceta utilizando sensores y actuadores, con el objetivo de maximizar su crecimiento y desarrollo al proporcionarle las condiciones ambientales óptimas, y presentar la información en una pantalla para su fácil acceso y visualización

### Objetivos específicos
Implementar un sistema de control de riego utilizando un sensor de humedad en el suelo y una bomba de agua, que permita mantener el nivel de humedad del suelo en un rango óptimo para el crecimiento de la planta, y que se active automáticamente cuando el nivel de humedad caiga por debajo del umbral deseado.

## Tabla de Software utilizado
| Id | Software | Version | Tipo |
|----|----------|---------|------|
| 1  |   MySQL  |   8.0   | SGBD |
| 2  |ArduinoIDE|  2.0.3  |  IDE |
| 3  |  Grafana |  9.4.7  |Dashboard|
| 3  | Node-REd |  12.0.1  |Dashboard|

## Tabla con el hardware utilizado
| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
|1|Bomba|Mini bomba de agua sumergible. Excelente para proyectos en los que se necesite de poco voltaje, de 2,5v a 6v DC, puede bombear caudales de hasta 80-120L/H a una altura de 40-110cm, dependiendo del voltaje de alimentación usado, a mayor volteja mayor caudal y altura de bombeo.|![image](https://user-images.githubusercontent.com/48172198/234118727-50742d44-f3c1-496b-bfb6-5e9c5e15dbd2.png)|1|$55.00 MXN|
|2|Fotorresitor|Una LDR es una resistencia que varía su valor en función de la luz que incide sobre ella. Así de fácil. También se llama fotocélula o resistencia LDR. Cuando hay luz sobre la LDR, su resistencia disminuye. Cuanto menos luz tenga la LDR mayor será su resistencia.|![image](https://user-images.githubusercontent.com/48172198/234118593-4d5ef68f-480e-4a53-8d18-4b59bc9e762b.png)|1|$3.00 MXN|
|3|Proto Board|Una proto board es un tipo de tablero de circuito impreso utilizado para construir y probar prototipos de circuitos electrónicos. La proto board tiene una superficie con hileras de clavijas que se pueden soldar fácilmente a componentes electrónicos para crear un circuito temporal. Este tipo de tablero es ideal para desarrolladores de hardware y profesionales de la electrónica que desean experimentar con diferentes configuraciones de circuitos antes de producir un diseño final. Con una proto board, es posible realizar cambios y modificaciones rápidamente, lo que ahorra tiempo y reduce el costo de errores en el desarrollo de productos electrónicos.|![image](https://user-images.githubusercontent.com/41849043/215903654-777973ff-9668-4cec-bc4d-0ec231e15cf8.png)|2|$167.76 MXN|
|4|Raspberry Pi|La Raspberry Pi es un ordenador de bajo costo y bajo consumo diseñado para el aprendizaje de informática y el desarrollo de proyectos electrónicos. Es una placa pequeña y compacta que se puede conectar a una pantalla, un teclado y un ratón para funcionar como un ordenador completo. La Raspberry Pi es una plataforma versátil y poderosa que se puede utilizar para una amplia gama de proyectos, desde el desarrollo de juegos hasta la automatización del hogar y la robótica.|![image](https://user-images.githubusercontent.com/41849043/215904260-e01da17b-a6ec-47e9-bda2-b8a267f1c31c.png)|1|$700 MXN|
|5|Sensor de Humedad|Un sensor de humedad para Arduino es un dispositivo que se utiliza para medir la humedad del suelo y proporcionar una señal eléctrica proporcional a la cantidad de humedad presente en el suelo. Estos sensores constan de dos partes principales: el circuito de detección y la placa de control.|![image](https://cdn.shopify.com/s/files/1/0083/1858/2874/files/sensor-de-humedad-en-suelo-yl-69_2048x2048.jpg?v=1595010811)|1|$93.00 MXN|
|6|ESP32|ESP32 es la denominación de una familia de chips SoC de bajo coste y consumo de energía, con tecnología Wi-Fi y Bluetooth de modo dual integrada.|![image](https://m.media-amazon.com/images/I/61eyPE6adjL._SX466_.jpg)|2|$250.00 MXN|
|7|Led RGB|LED RGB significa LED rojo, azul y verde. Los productos LED RGB combinan estos tres colores para producir más de 16 millones de tonos de luz.|![image](https://user-images.githubusercontent.com/41849043/232653796-da96d277-e313-47c5-b7e6-556e41decacd.png)|1|$1.00|
|8|Sensor de gas|Este es un sensor muy sencillo de usar, ideal para medir concentraciones de gas natural en el aire. Puede detectar concentraciones desde 300 hasta 10000 ppm.|![image](https://user-images.githubusercontent.com/48172198/234708080-fb59c3ed-d30c-482e-8a76-057949332586.png)|1|$63.00|
|9|Modulo MP3|Mini Modulo Reproductor Mp3 Dfplayer Ranura Micro Sd Arduino|![image](https://user-images.githubusercontent.com/48172198/234710251-6df62f9b-ceb9-4341-845f-874cc2ec9a85.png)|1|$59.00|

## Epicas del proyecto (Minimo debe de haber una épica por integrante de equipo)
-Monitoreo de las condiciones ambientales de la planta: esta épica se enfoca en el monitoreo de las condiciones ambientales de la planta, como la humedad del suelo, la temperatura y la cantidad de luz que recibe. El objetivo es medir estos factores y presentarlos de manera visual en una pantalla para que los usuarios puedan tener una idea clara del estado de la planta.

-Control de riego automático: esta épica se enfoca en el control automático del riego de la planta utilizando un sensor de humedad en el suelo y una bomba de agua. El objetivo es mantener el nivel de humedad del suelo en un rango óptimo para el crecimiento de la planta, y que se active automáticamente cuando el nivel de humedad caiga por debajo del umbral deseado.

-Integración con una plataforma IoT: esta épica se enfoca en la integración del proyecto con una plataforma IoT para la recopilación y análisis de datos en tiempo real. El objetivo es enviar los datos medidos por los sensores a una plataforma en la nube y permitir la visualización y análisis de los mismos desde cualquier lugar del mundo. Además, esto podría permitir la configuración remota de los parámetros del sistema.

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
|  1  | Como usuario, quiero poder ver los datos de humedad del suelo de mi planta en tiempo real, para poder determinar si necesita ser regada. Para ello, deseo que la pantalla muestre un gráfico con la evolución de la humedad del suelo en las últimas horas, así como un indicador de nivel de humedad actual. Además, deseo recibir una alerta visual o sonora cuando el nivel de humedad caiga por debajo de un umbral específico, indicando que la planta necesita ser regada.                   |           |            |               |             |
|  2  | Como usuario, quiero poder configurar el riego automático de mi planta, para que se active automáticamente cuando el nivel de humedad caiga por debajo del umbral deseado. Para ello, deseo poder especificar el umbral deseado para el nivel de humedad, así como la duración y frecuencia del riego. Además, deseo tener la opción de desactivar el riego automático si lo deseo.                  |           |            |               |             |
|  3  | Como usuario, quiero poder acceder a los datos de monitoreo de mi planta desde cualquier lugar del mundo, para poder verificar su estado y hacer ajustes si es necesario. Para ello, deseo que el proyecto esté integrado con una plataforma IoT en la nube, que me permita visualizar los datos de humedad, temperatura y luz de mi planta en tiempo real, desde cualquier dispositivo con conexión a internet. Además, deseo tener la opción de recibir notificaciones cuando el nivel de humedad caiga por debajo del umbral deseado, para poder tomar medidas inmediatas si es necesario.                 |           |            |               |             |
|  4  |Como usuario, quiero poder ajustar los valores de referencia para el control automático de riego, para poder personalizar el sistema a las necesidades específicas de mi planta. Para ello, deseo tener acceso a una interfaz de usuario que me permita cambiar los valores de umbral de humedad y la duración y frecuencia del riego automático. Además, deseo poder guardar múltiples configuraciones personalizadas para diferentes tipos de plantas y suelos.|||||

## Prototipo en dibujo
Coloca la fotografia de tu prototipo dibujado a lapiz
![WhatsApp Image 2023-04-24 at 4 34 01 PM](https://user-images.githubusercontent.com/48172198/234130922-47634047-e751-4dbc-bcff-5c4b5a530080.jpeg)

## Codigo

  [MIPROYECTO_1.zip](https://github.com/GabrielGM16/InovaMath/files/11337473/MIPROYECTO_1.zip)

## Fritzing

<picture>
  <img alt="Imagen Fritzing 1" src="./Fritzing/IMG_1.PNG">
</picture>

<picture>
  <img alt="Imagen Fritzing 2" src="./Fritzing/IMG_2.PNG">
</picture>

json


https://github.com/GabrielGM16/InovaMath/blob/main/flows.json

garfana

![WhatsApp Image 2023-04-26 at 8 27 37 PM](https://user-images.githubusercontent.com/48172198/234745292-05452899-e679-411e-b98b-e3cd1712b205.jpeg)

![WhatsApp Image 2023-04-26 at 8 27 40 PM](https://user-images.githubusercontent.com/48172198/234745310-4e88d0d1-0884-414e-81a5-ec602567f18d.jpeg)



## Librerias Utilizadas
-SoftwareSerial

-DFRobotDFPlayerMini

-Wire

-LiquidCrystal_I2C

-WiFi

-PubSubClient

[LCD03.zip](https://github.com/GabrielGM16/InovaMath/files/11337519/LCD03.zip)


## Video demostracion

https://vm.tiktok.com/ZMY35E1VB/

## Evidencias fotograficas
![IMG_20230424_163821](https://user-images.githubusercontent.com/48172198/234709203-864ae5cc-25b3-4cba-a822-992062646fc5.jpg)


![IMG_20230424_163714](https://user-images.githubusercontent.com/48172198/234709222-0ba2172b-abd0-4201-a1fb-4eac9e9ad035.jpg)



![IMG_20230424_163753](https://user-images.githubusercontent.com/48172198/234709236-b5a27ff8-6fcd-4829-b49c-e05192dcb604.jpg)


<img width="224" alt="image" src="https://user-images.githubusercontent.com/48172198/234709323-9bf92e4b-09e9-41db-a317-838d5f58832d.png">


<img width="236" alt="image" src="https://user-images.githubusercontent.com/48172198/234709392-c9aed3ab-bd5c-440c-8cc1-39c33aa78929.png">








