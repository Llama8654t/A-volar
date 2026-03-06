# A-volar
## Objetivos del projecto
En este projecto nuestro objetivo es programar un dron **_DJI TELLO_**<sub>B2B</sub> para que vuele alrededor de unas columnas en nuestro instituto, Para programar este dron vamos a usar la aplicación **_Droneblocks_**<sub>B2E</sub>, que es una aplicación de programación para drones que usa bloques para programar de forma simple.
## Dron **_DJI TELLO_**<sub>B2B</sub>
El dron DJI tello cuenta con 
  * Hélices 
  * Motores
  * Indicadores de estado de la aeronave
  * Botón de encendido
  * Antenas
  * Sistema de posicionamiento visual
  * Batería de vuelo
  * Puerto micro usb
  * Protectores para las hélices
  * Placa base

y su conexión es a través de wifi.

Un dron **_DJI TELLO_**<sub>B2B</sub>
![descarga](https://github.com/user-attachments/assets/93637f90-9a5b-49fe-b681-4f2db656d79e)

## Normativa europea de vuelo
Para poder volar el dron es obiamente necesario saber la normativa europea de vuelo asi que he incluido las partes más importantes y hay algunas formas de separar las normas y reglas.

### Reglas generales
Para poder volar un dron debes:
+ De día y en condiciones meteorológicas de vuelo visual
+ No puedes volar de noche salvo autorización de la AESA
+ Manteniendo la distancia adecuada a obstáculos
+ A menos de 120 metros de altura sobre el terreno
+ Dando prioridad a otras categorías de aeronaves
+ Siempre fuera del espacio aéreo controlado
+ Lejos de aeropuertos o aeródromos
+ Sin poner en riesgo la seguridad de personas o bienes materiales
+ Siempre con la aeronave dentro del alcance visual del piloto
+ Sin grabar imágenes sin permiso de las personas filmadas

Luego no puedes volar el dron donde quieras debes hacer caso a estas normas:
+ Lejos de zonas urbanas<sup>*</sup>
+ Fuera de reuniones en exteriores, playas o campos de fútbol
+ Fuera del espacio aéreo controlado
+ A más de 8 kilómetros de cualquier aeropuerto o aeródromo
+ A más de ocho kilómetros de ejes de pistas de aeropuertos
+ Sin poner en riesgo la seguridad de las personas
+ Dentro del alcance visual
+ Hasta a 120 metros de altura sobre el terreno
+ Puedes volar en clubes de vuelo o en zonas no controladas

<sub>*Puedes volar en zonas urbanas pero debes de hacer caso al estas normas:
+ El peso máximo al despegue del dron no debe sobrepasar los 10 kg (con la nueva normativa no debe superar los 250 gramos)
+ La operación se debe de realizar dentro del alcance visual del piloto (VLOS).
+ La zona para volar deberá de estar acordonada por la autoridad competente, o en su defecto, debemos mantener una distancia horizontal mínima de 50 metros con edificios u otro tipo de estructuras y mantener una distancia de 50 metros con las personas del entorno.
+ El equipo deberá de tener instalado un sistema de limitación de energía del impacto, tipo paracaídas, airbag, etc.
+ Contar con la autorización por parte de AESA a través de la realización de un estudio de seguridad aeronáutica.*
</sub>

### Reglas segun el peso
* Drones de menos de 250 gramos pueden ser pilotados en la mayoría de las ocasiones siempre que no sobrevueles eventos o personas ni molestes a nadie.
* Drones de entre 250 gramos y 25 kilos No necesitan matriculación ni certificado pero deben de seguir ciertas normas y tener permisos específicos si quieres usarlos en eventos.
* Drones de más de 25 kilos necesitan el certifcado de AESA para ser pilotados.
Además de todo esto necesitas ciertos permisos y certificados para usarlos de forma profesional, pero...

### ¿Como afecta la nueva normativa europea?
La nueva normativa europe requiere las exigencias de AESA que consisten en tener un seguro de responsabilidad civil, tener las competencias mínimas y respetar las zonas de vuelo que puedes ver en el mapa de ENAIRE [aquí](https://drones.enaire.es/?authuser=1).
Y una nueva clasificación que afecta a las personas sin licencia que no esten registradas en la red de AESA las características de esta clase son:
+ Masa máxima al despegue de menos de 250 gramos.
+ Velocidad máxima en un vuelo horizontal de 19 metros por segundo.
+ Altura sobre el terreno de un máximo 120 metros.

Y deben de cumplir con estas normas:
+ No se puede volar en espacios naturales protegidos, Reservas de Biosfera o zonas de conservación de fauna.
+ No se puede volar a un radio de 8 Km de aeródromos, aeropuertos, espacios aéreos controlados ni edificios prohibidos.
+ Los que incluyen cámara han de respetar la Ley de Protección de datos y el derecho al honor e intimidad de las personas.
+ El dron debe estar siempre controlado por ti y a tu vista.
+ Lo volarás en condiciones meteorológicas aptas.
+ Por la noche, no debe superar los 50 metros de altura.

## ¿Cómo te debes conectar al dron para poder controlarlo?

Para conectarse al dron lo que debes de hacer es conectarse a una wifi llamada tello-XXXXXX como dice aquí abajo en el extracto de manual que he insertado siendo las "X" la matrícula del dron.
<img width="692" height="121" alt="Captura" src="https://github.com/user-attachments/assets/f1fef758-92b4-46ba-93a2-c36bc609da95" />

## Manual básico de programación con **_Droneblocks_**<sub>B2E</sub>

Programar con **_Droneblocks_**<sub>B2E</sub> es muy parecido a otros softwares de programación con bloques como _Scratch_ o _Crumble_ para empezar deberías usar el bloque de despeje que va a hacer que tu dron despegue desde ahí puedes usar otros bloques como avanzar cierto número de pulgadas o centimetros, girar la cantidad elegida de grados en la dirección que tu quieras o usar bloques conocidos como un bucle, una espera o una condicional sin olvidarse de programar que aterrize con el bloque de aterrizaje

Un bloque de despegue
<img width="153" height="64" alt="Captura de pantalla 2026-03-06 210229" src="https://github.com/user-attachments/assets/91fe5e6e-f78d-4a0d-badf-ace0a7088b31" />

Un bloque de volar hacia delante 20 pulgadas
<img width="345" height="71" alt="Captura de pantalla 2026-03-06 210249" src="https://github.com/user-attachments/assets/0ffdbfa7-9cde-4781-8667-5d332d7ab7e5" />

Un bloque de girar 90 grados a la izquierda
<img width="381" height="77" alt="Captura de pantalla 2026-03-06 210257" src="https://github.com/user-attachments/assets/ed1974f8-1a04-4355-bcbc-46d538905499" />

Un bloque de aterrizaje
<img width="96" height="53" alt="Captura de pantalla 2026-03-06 210616" src="https://github.com/user-attachments/assets/66bf2847-591c-4fe5-a49b-986bf68106fa" />

Programa completo con bucle
<img width="525" height="408" alt="Captura de pantalla 2026-03-06 210727" src="https://github.com/user-attachments/assets/11a5d3e7-81c8-4f96-bd3e-710696518d83" />

