# PLC-USB

![N|Solid](https://raw.githubusercontent.com/electgpl/PLCUSB/master/CAM00171.jpg)

Este es un PLC de openHard diseñado en base al microcontrolador PIC linea 16F compatible con 28pins PDIP, el mismo utiliza bootloader para la carga de su firmware basado en la nota AN1310.

  - Core PIC16 28-PDIP compatible
  - Bootloader UART AN1310 Microchip
  - USB Programming firmware
  - USB Serial Terminal/Debug
  - 4 Salidas contacto seco doble inversora 12Vdc 24Vdc 220Vac
  - 8 Entradas Digitales optoacopladas 0-10V 0-12V 0-24V 
  - 5 Entradas Analógicas 0-10V
  - Fuente de alimentación integrada

## Lenguajes Compatibles

  - C
  - C++
  - Basic
  - Ensamblador
  - Ladder
  - Niple
  - y mas...
  
## Diseño y Desarrollo

> Diseñado con EAGLE, en una sola capa para aumentar la facilidad
> de integración al alumno, el desarrollo del PCB en el hogar y mantener
> el menor costo posible.

### Instalación

Todos los archivos se encuentran disponibles en este repositorio, diagramas, pcb, bootloader (este requiere una primera carga con programador en el PIC).

### Pendientes

 - Migracion del hardware AVR Atmega Compatible.
 - Incorporación de Arduino IDE
 - Mejoras en inmunidad al ruido
 - Aumento de canales de entrada y salida
 - Aislación de canales analógicos
 - Enlaces 232, 485, 4-20mA

License
----

MIT


**Free Software, Hell Yeah!**

