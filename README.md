# Estacion Meteorológica
Realización de una estación meteorológica para el instituto que mida magnitudes como temperatura, humedad, presión atmosférica o velocidad del viento, y que se conecte a internet y pueda publicar los datos. Fases: 
- Fase 1 (PMV). Construir una estación meteorológica con un sensor BME280 (que mide temperatura, humedad y presión) dentro de una cajita, y que envíe los datos a un Thingspeak.
- Fase 2. Solucionar problemas de energía del Node MCU ESP8266: modo sueño y placa solar.
- Fase 3. Mejorar el diseño de la caja, añadir más sensores (pluviómetro y anemómetro)

Para realizar el proyecto, hemos hecho la siguiente división de subsistemas:

<img src="división de subsistemas.png" width="600" align="center">



## Repositorio
El repositorio contiene:
- Esquemas de conexión
<img src="proyecto final_esquema.png" width="600" align="center">


- Esquemas de protoboard
<img src="proyecto final.png" width="600" align="center">


- [Código Arduino](https://github.com/pepeesp8266/EstacionMeteorologica/blob/master/EstacionMeteorologica.ino)



## Más información
- [Video del protecto](https://www.youtube.com/watch?v=KQAulrZM5ks)

- [Página web del proyecto](https://sites.google.com/iesvaleix.com/estacion-meteorologica-v-aleix/)



## LICENCIA
Este proyecto fue desarrollado durante el curso 2018/2019 en el IES Vicente Aleixandre de Sevilla en 1º de bachillerato de la asignatura TIND-TIC por Nuria Galve Contreras, Manolo García Martínez y Daniel Alexis Jurado Ortiz; con el apoyo de su profesor Jose Pujol. Se distribuye con licencia [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
