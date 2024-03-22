# SistemaDeRiego_IOT

# Integrantes
- Alan de Jesús Avalos Negrete
- Josué Miguel Ortiz Meza

## Objetivo General

Desarrollar e implementar un sistema de riego automático basado en Internet de las Cosas (IoT), que optimice el consumo de agua en la agricultura mediante la integración de un tanque de agua con sensor de nivel, un sensor de humedad y temperatura del suelo, y una bomba de agua, con el fin de proporcionar un riego eficiente y controlado, mejorando así la productividad de los cultivos y promoviendo la sostenibilidad ambiental.

Crear un sistema de riego automatico, al detectar niveles altos de temperatura o niveles bajos de humedad

## Tabla de Software a utilizar

|Nombre|Versión|Descipción|
|-|-|-|
|Arduino IDE|2.3.2|Entorno de desarrollo para programar en C++ para subir el codigo a la ESP32|
|Node-Red|3.1.7|Herremienta para desarrolllar interfaces con codigo bajo|
|Mosquitto|2.0.18|Herramineto para comunicar con el protocolo MQTT|
|DHT sensor library|1.4.6|Libreria para usar el sensor de temperatura y humedad|

## Prototipo

![prototipo](https://github.com/JosueMiguelOM/SistemaDeRiego_IOT/assets/109251541/1aaea4aa-8721-4fcf-92d1-bdfcd9044cf7)

## Diagrama

En esta parte del diagrama podemos observar un circuito (ULN2003) para manejar el control del agua, este esta conectado a la ESP32 que a la vez estan a unos leds e indican el nivel del agua dependiendo de las 4 terminales que estan del lado B
![imagen](https://github.com/JosueMiguelOM/SistemaDeRiego_IOT/assets/109251541/e77fdc82-606f-4e8d-8030-982261029cf8)
Aqui se encuentra el relavador conectado a la ESP32 y a una terminal que seria nuestra bomba de agua, cuando llegue una señal a la placa el relevador se activara iniciando la bomba de agua
![imagen](https://github.com/JosueMiguelOM/SistemaDeRiego_IOT/assets/109251541/5544bbb5-226d-4a3a-9d4a-5d20a496a4c6)
Aqui se encuentra el sesnsor de temperatura y humedad DHT22 conectado a la ESP32 para manejar los niveles de agua
![imagen](https://github.com/JosueMiguelOM/SistemaDeRiego_IOT/assets/109251541/ef49459c-620a-4146-8afc-c32a8788801f)

Imagene general
![diagrama](https://github.com/JosueMiguelOM/SistemaDeRiego_IOT/assets/109251541/07bd8d5c-6b36-432c-90ac-569f110289e6)

