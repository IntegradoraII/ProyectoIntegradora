# Proyecto Alerta
[![Contribuidores][contribuidores-shield]][contributors-url]

## contenido
<details>
  <summary>Tabla contenidos</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca Del Proyecto</a>
      <ul>
        <li><a href="#construido-con">Construido Con</a></li>
      </ul>
    </li>
    <li>
      <a href="#iniciando">Iniciando</a>
      <ul>
        <li><a href="#requisitos">Prerrequisitos</a></li>
        <li><a href="#instalacion">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#uso">Uso</a></li>
    <li><a href="#guias">Guias</a></li>
    <li><a href="#contribucion">Contribución</a></li>
    <li><a href="#licencia">licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
## Acerca del proyecto

### Nombre del proyecto
**Alerta**

### Justificación del proyecto

> La cantidad de personas con la necesidad de un mayor cuidado y atención va aumentando conforme pasa el tiempo por lo que esto puede presentar un problema para esas personas que viven lejos de ellos.

> Según la página del INEGI  en el año del 2020 en el estado de Guanajuato al rededor de 684,529 personas son mayores de 60 años por lo que esto implica un mayor esfuerzo y atención por parte de sus familiares para cuidarlos y si bien algunos de ellos son auto suficientes esto no es en todos los casos esto debido a que entre mayor es una persona esta llega a tener mayores complicaciones respecto a su salud mental siendo algunos de las causas más comunes de gente mayor desaparecidada causa de padecimientos mentales como lo son el alzheimer, esquizofrenia y o depresión provocando que estos abandonen sus hogares de manera conciente o inconciente siendo este ultimo caso el más alarmante y la razón por la que muchos de los cuidadores de estas personas no se puedan separar de ellos.

> Con este proyecto buscamos facilitar el cuidado y monitoreo de personas las cuales no posean las facultades para hacerse valer por si solos, proveyendo una solución util y economica para sus cuidadores.
> 
### Objetivo del proyecto: 

> Facilitar el cuidado de personas mayores o con capacidades diferentes de manera remota.

### Descripción general del proyecto

> Este proyecto consiste generar un prototipo que busca facilitar el cuidado de personas mayores o personas con capacidades diferentes mediante el uso de sensores y microcontroladores los cuales estaran monitoreando y almacenando información en una base de datos a la cual tendrá acceso tambien una aplicación con la cual sus cuidadores serán avisados cuando esta persona salga de una determinada area permitiendo tomar acciones rapidas en caso de que habandonará el hogar.


### Material de uso:
<table> 
  <tr>
    <th>Componente</th>
    <th>Imagen</th>
    <th>Descripción</th>
    <th>Cantidad</th>
  </tr>
  <tr>
    <td>Raspberry Pi 4</td>
    <td>
    <img src="https://user-images.githubusercontent.com/36056832/165995675-da53df0d-9c67-46af-94e3-22f30ad2aa4d.png" alt="Raspberry Pi 4" width="100"/>
    </td>
     <td>
       <ul>
         <li>Raspberry Pi 4 Modelo 4 8GB RAM Original Uk.
         <li>Memoria microSD 32GB Clase 10 A1 con adaptador.
         <li>Adpatador microHDMI a HDMI
         <li>Cable HDMI
         <li>Carcasa con soporte para ventilador.
         <li>Ventilador 5VDC con tornillos y tuercas.
         <li>Fuente 5V 3A USB-C con Switch On/Off.
         <li>Kit de disipadores de calor cobre y aluminio con cinta térmica adherible.
         <li>Puerto de cámara CSI para conectar una cámara Raspberry Pi
         <li>Puerto de pantalla DSI para conectar una pantalla táctil Raspberry Pi
         <li>Puerto Micro SD para cargar su sistema operativo y almacenar datos
         <li>Fuente de alimentación Micro USB conmutada actualizada hasta 2.5A
       </ul>
    </td>
    <td>1</td>
  </tr> 
  <tr>
    <td>ESP32</td>
    <td>
    <img src="https://d229kd5ey79jzj.cloudfront.net/1013/images/1013_1_H.png"  alt="ESP32 Cam" width="100"/>
    </td>
    <td>
      <ul>
        <li>Voltaje: 5 V
        <li>Microprocesador Xtensa Dual-Core 32-bit LX6 con 600 DMIPS
        <li>Wi-Fi (802.11 b/g/n) HT40
        <li>Bluetooth 4.2 y BLE
        <li>Frecuencia de operación (valor típico) 160 MHz
        <li>SRAM 448kb
        <li>Flash 520kb
        <li>GPIO 34
        <li>PWM 16
        <li>SPI 4
      </ul>
     </td>
    <td>1</td>
  </tr> 
  <tr>
    <td>Display LCD 16x2</td>
    <td><img src="https://user-images.githubusercontent.com/8560750/166756741-813b8a4a-d952-4e20-aa89-b7699ffeb30d.jpg" alt="Lcd Display" width="100"/></td>
    <td>
      <ul>
        <li>Voltaje: 5 V</li>
        <li>Un pin de selección de registro (RS) que controla en qué parte de la memoria de la pantalla LCD está escribiendo datos. </li>
        <li>Un pin de lectura/escritura (R/W) que selecciona el modo de lectura o el modo de escritura</li>
        <li>Un pin Habilitar que permite escribir en los registros</li>
        <li>8 pines de datos (D0 -D7) . Los estados de estos pines (alto o bajo) son los bits que estás escribiendo en un registro cuando escribes, o los valores que estás leyendo cuando lees,</li>
      </ul>
    </td>
    <td>1</td>
  </tr> 
  <tr>
    <td>RFID-RC522</td>
    <td><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.14core.com%2Fwp-content%2Fuploads%2F2015%2F09%2FKit_Modulo_Rfid_Mfrc522_1356_Mhz.png&f=1&nofb=1" width="100" alt="RFID-RC522"/></td>
    <td>
      <ul>
      </ul>
    </td>
    <td>1</td>
  </tr> 

</table>

#### Requerimientos
|No.  |Requerimiento  |
|---  |-------------  |
| 1   |El sistema deberá permitir dar la bienvenida al cliente o visitante a través de lectura de rostro, si la persona es un cliente mediante un Display y/o un repetidor de Voz dará la bienvenida. A su vez, el empleado recibirá una notificación a su dispositivo móvil para su atención.               |
| 2   |Mediante lectura de código QR a través de dispositivo móvil la persona podrá observar la descripción del producto. |
| 3   |Mediante realidad aumentada a través de dispositivo móvil el cliente o turista podrá interactuar con las características y uso del producto.|
| 4   |La persona podrá solicitar la atención del empleado a través de su dispositivo móvil ya sea para muestra del producto o venta del mismo.|
| 5   |La persona podrá responder la encuesta de salida si fue agradable el servicio al cliente, etc.|
| 6   |El gerente o dueño del negocio podrá ver estadísticas como: Número de visitantes que llegaron al establecimiento. Número de visitantes que realizaron compra. Encuesta de satisfacción de salida.  |

#### Diagrama inicial
![image](https://user-images.githubusercontent.com/8560750/166749650-89fba768-4bbc-45c4-93d3-df9e5d08ad4c.png)


### Prototipo
#### Hardware
[![Integradora-II-bb.png](https://i.postimg.cc/90swW1F7/Integradora-II-bb.png)](https://postimg.cc/kRFgsQSJ)

#### Software
[![Web-Integradora.jpg](https://i.postimg.cc/1zMggy3P/Web-Integradora.jpg)](https://postimg.cc/7CGPd8zQ)
[![Web-Integradora-2.jpg](https://i.postimg.cc/k4zW47TG/Web-Integradora-2.jpg)](https://postimg.cc/Kk71phSh)
<!-- Construido con -->


<!-- Construido con -->
### Construido con
Construido con.

<!-- Iniciando -->
## Iniciando
Iniciando.

<!-- Requisitos -->
### Requisitos
Requisitos.

<!-- Instalación -->
### Instalacion
Instalación.

<!-- Uso -->
### Uso
Uso.

## Guias
Guias.

## contribucion
Contribucion.

## Licencia
Licencia.

## Contacto
Contacto.

## Participantes
* [Guadalupe Puentes]()
* [César Daniel Casillas Céspedes]()

[contribuidores-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
