# InovaMath

## Integrantes
- Osmar Israel Villegas Martinez 
- Jose Armando Gutierrez Rodriguez
- Victor Andres Garay Montes

## Objetivo general
Diseñar y desarrollar un sistema de IoT (Internet de las cosas) que permita monitorear y controlar el ambiente de una habitación con el fin de mejorar la calidad de sueño del usuario, monitoreando y en el caso de ser necesario mejorando las condiciones del ambiente para garantizar un sueño de calidad.

### Objetivos específicos
Implementar un sistema de análisis del ambiente que monitorice condiciones como luz, ruido, temperatura y ritmo cardiaco en una habitación, en base a los resultados el sistema puede mejorar la calidad del ambiente y activar automáticamente mecanismos como un ventilador o música cuando las condiciones puedan llegar a perjudicar la calidad del sueño.

## Tabla de Software utilizado
| Id | Software | Version | Tipo |
|----|----------|---------|------|
| 1 |  sqlite  | 3.46.0 | SQL |
| 2 | Thonny  | 4.1.4 |  IDE |
| 3 | Node-Red | 3.2.9 | MQTT |
| 4 | Firebase | 13.8.0 | NoSQL |
| 5 | Square line studio | 1.4.1 | IDE |

## Tabla con el hardware utilizado (El costo de cada componente es al dia de 2 de junio del 2024)
| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
|1|Sensor de frecuencia cardiaca|Sensor de ritmo cardiaco para medir la calidad de sueño. |![image](Imagenes/Ritmo_cardiaco.jpeg)|1|$47,03 MXN|
|2|Sensor de temperatura|Sensor para medir la temperatura del ambiente. |![image](/Imagenes/Modulo_DHT11.jpeg)|1|$17,04 MXN|
|3|Fotoresistencia|Sensor capaz de medir la oscuridad del ambiente.|![image](./Imagenes/Fotoresistor.jpeg)|2|$13,97 MXN|
|4|Sensor de ruido|Sensor para medir el ruido del ambiente.|![image](./Imagenes/INMP441.jpg)|1|$23,69 MXN|
|5|DFPlayer-Mini Módulo/bocina y tarjeta sd|Modulo DFPlayer permite la reproducción de audios grabados en una memoria sd.|![image](./Imagenes/DFPlayer.jpeg)|1|$26,46 MXN|
|6|ESP32|ESP32 es la denominación de una familia de chips SoC de bajo coste y consumo de energía, con tecnología Wi-Fi y Bluetooth de modo dual integrada.|![image](./imagenes/Esp32.jpg)|2|$250.00 MXN|
|7|Ultrasonido|Modulo de ultrasonido especializado para humidificar.|![image](./Imagenes/Mini_Humidificador.jpg)|1|$11,42|
|8|PantallaTFT|Pantalla TFT con esp32 programable.|![image](./Imagenes/Esp32.jpg)|1|$653.78|
|9|Pantalla (Weareble)|Mini Modulo Reproductor Mp3 Dfplayer Ranura Micro Sd Arduino|![image](./Imagenes/Esp32_E-Watch.jpeg)|1|$356,64|
|10|Ventilador| Ventilador de bajo consumo. |![image](./Imagenes/Ventilador.jpeg)|1|$16,87|

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








