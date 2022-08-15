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
    <td>RFID-RC522</td>
    <td><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.14core.com%2Fwp-content%2Fuploads%2F2015%2F09%2FKit_Modulo_Rfid_Mfrc522_1356_Mhz.png&f=1&nofb=1" width="100" alt="RFID-RC522"/></td>
    <td>
      <ul>
        <li>Circuitos analógicos altamente integrados para demodular y decodificar las respuestas</li>
        <li>Controladores de salida con buffer para conectar una antena con el mínimo número de componentes externos</li>
        <li>Soporta ISO/IEC 14443 A/MIFARE y NTAG</li>
        <li>Distancia de funcionamiento típica en modo de lectura/escritura de hasta 50 mm en función del tamaño de la antena y de la sintonización</li>
        <li>Admite el cifrado MF1xxS20, MF1xxS70 y MF1xxS50 en modo de lectura/escritura</li>
        <li>Soporta la comunicación de mayor velocidad de transferencia ISO/IEC 14443 A hasta 848 kBd</li>
        <li>Soporta MFIN/MFOUT</li>
        <li>Fuente de alimentación interna adicional para el CI de la tarjeta inteligente conectado a través de MFIN/MFOUT</li>
        <li>Soporta interfaces de host
          <ul>
            <li>SPI hasta 10 Mbit/s</li>
            <li>Interfaz de bus I2C hasta 400 kBd en modo rápido, hasta 3400 kBd en modo de alta velocidad</li>
            <li> RS232 Serial UART up to 1228.8 kBd, with voltage levels dependant on pin voltage supply</li>
          </ul>
        </li>
        <li>El búfer FIFO gestiona el envío y la recepción de 64 bytes</li>
        <li>Modos de interrupción flexibles</li>
        <li> Alimentación de 2,5 V a 3,3 V</li>
        <li>Coprocesador CRC</li>
        <li>Modos de interrupción flexibles</li>
        <li>Oscilador interno para conexión a cristal de cuarzo de 27,12 MHz</li>
      </ul>
    </td>
    <td>1</td>
  </tr> 

</table>

#### Requerimientos

#####Funcionales
|No.  |Requerimiento Funcionales |
|---  |-------------  |
| 1   |El usuario pueda registrarse con un correo, contraseña, nombre, apellidos y número de teléfono.               |
| 2   |El usuario deberá poder ingresar con un correo y contraseña.|
| 3   |El usuario podrá agregar de uno a cinco pacientes que este bajo su cuidado.|
| 4   |El usuario podrá tener acceso a la información necesaria del paciente a su cuidado. |
| 5   |El usuario podrá editar la información del paciente que este a su cuidado.|
| 6   |El usuario podrá eliminar a algún paciente que este a su cuidado.|
| 7   |Cuando el portador de la pulsera pase por una entrada el arduino mandará una alerta al encargado avisando de la actividad del portador.|
| 8   |La administración de los usuarios estará monitoreada.|

#####No Funcionales
|No. |Requerimientos no Funcionales|
|---  |-------------  |
| 1   |El sistema debe estar disponible para los usuarios y solo estará fuera de servicio cuando sea necesario darle mantenimiento |
| 2   |El sistema debe ser capaz de soportar un crecimiento de usuarios.|
| 3   |El programa podrá realizar los procesos necesarios en el día y para ello debe estar ligado a una base de datos.|
| 4   |La aplicación debe ser fácil de usar para el usuario|
| 5   |La pulsera es comoda y ergonómica.|

#### Diagrama inicial
[![Diagrama.Inicial.jpg](https://i.postimg.cc/G202P93D/Diagrama-ianicial.png)](https://postimg.cc/wtVggqmx)


### Prototipo
#### Hardware
[![Integradora-II-bb.png](https://i.postimg.cc/90swW1F7/Integradora-II-bb.png)](https://postimg.cc/kRFgsQSJ)

#### Software
[![Web-Integradora.jpg](https://i.postimg.cc/054XLwBk/Login-de-Usuario.png)](https://postimg.cc/grvKhnpQ)
[![Web-Integradora-2.jpg](https://i.postimg.cc/3r61NH7Y/Registro-de-Uusuario.png)](https://postimg.cc/JtNZYvG2)
[![Web-Integradora-3.jpg](https://i.postimg.cc/bN9KtJv1/Administrador.png)](https://postimg.cc/jLCgVRPj)
[![Web-Integradora-5.jpg](https://i.postimg.cc/DZC98fP7/Registro-del-Paciente.png)](https://postimg.cc/62vjPXPP)
[![Web-Integradora-6.jpg](https://i.postimg.cc/26psW9PK/Formulario-del-Paciente.png)](https://postimg.cc/HJ2vDzWw)


<!-- Modelo y/o Estructura de Base de Datos -->
### Modelo y/o Estructura de Base de Dato
[![BasedeDatos.jpg](https://i.postimg.cc/vT5h31d6/Modelo-de-base-de-datos.png)](https://postimg.cc/K3vtY8jZ)


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
### Caso de Uso
Uso.
[![CU.jpg](https://i.postimg.cc/DzjG9Rkg/CU.jpg)](https://postimg.cc/yJRW9QNg)
## Guias
Guias.

## contribucion
Contribucion.

## Licencia
Licencia.

## Contacto
Contacto.

## Participantes
* [Maria Guadalupe Puente Gonzalez]()
* [César Daniel Casillas Céspedes]()

[contribuidores-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
