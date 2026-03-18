# Arduino_Mesa_Maldonado
Historia de Arduino Periféricos de Arduino y su uso Ficha técnica, pines de conexión Arquitectura, ventajas y funcionalidad.
# Investigación sobre Arduino

## Introducción

Arduino es una plataforma de hardware y software libre que permite desarrollar proyectos electrónicos de manera sencilla. Es ampliamente utilizada en educación, robótica, domótica e Internet de las Cosas (IoT).


## Historia de Arduino

Arduino fue creado en 2005 en el Instituto de Diseño Interactivo de Ivrea, en Italia. Sus fundadores fueron Massimo Banzi, David Cuartielles, Tom Igoe, Gianluca Martino y David Mellis.

El objetivo principal era poder facilitar el uso de microcontroladores para los estudiantes sin experiencia en electrónica o programación.

### Evolución:

* 2005: Lanzamiento oficial del primer Arduino
* 2008: Popularización global
* Actualidad: Su uso se ve en proyectos educativos, industriales y de innovación


## Periféricos de Arduino y su uso

El arduino puede conectarse con diferentes dispositivos llamados periféricos:

### Sensores (Entrada)

Permiten captar información del entorno:

* Sensor de temperatura
* Sensor de luz (LDR)
* Sensor de movimiento (PIR)
* Sensor ultrasónico

### Actuadores (Salida)

Son los que permiten ejecutar acciones:

* LEDs
* Motores
* Servomotores
* Relés

### Módulos de comunicación

Permiten conectar Arduino con otros dispositivos:

* Bluetooth (HC-05)
* WiFi (ESP8266)
* RFID
* Pantallas LCD


## Ficha técnica 

### Microcontrolador:

* ATmega328P

### Voltaje:

* Operación: 5V
* Entrada recomendada: 7V – 12V

### Pines:

* 14 pines digitales (6 PWM)
* 6 entradas analógicas

### Memoria:

* Flash: 32 KB
* SRAM: 2 KB
* EEPROM: 1 KB

### Frecuencia:

* 16 MHz


## Pines de conexión

### Pines digitales (0–13)

* Entrada y salida digital
* Algunos con PWM (~)

### Pines analógicos (A0–A5)

* Sirven para la lectura de señales analógicas

### Pines de alimentación

* 5V
* 3.3V
* GND
* Vin

### Pines especiales

* TX/RX → Comunicación serial
* PWM → Control de velocidad y brillo


## Arquitectura de Arduino

El arduino se basa en una arquitectura de microcontrolador la cual incluye:

* CPU (procesador)
* Memoria (Flash, SRAM, EEPROM)
* Entradas y salidas digitales y analógicas
* Interfaces de comunicación (UART, SPI, I2C)

El usuario programa el Arduino mediante el IDE usando lenguaje basado en C/C++.


## Ventajas de Arduino

* Fácil de usar para principiantes
* Hardware y software libre
* Gran comunidad de soporte
* Bajo costo
* Compatible con múltiples sensores y módulos


## Funcionalidad

Arduino permite:

* Automatizar procesos
* Leer sensores
* Controlar dispositivos
* Crear sistemas inteligentes
* Desarrollar proyectos IoT

### Ejemplo de uso:

* Encender un LED automáticamente con un sensor de luz
* Controlar un motor con Bluetooth
* Sistema de riego automático






