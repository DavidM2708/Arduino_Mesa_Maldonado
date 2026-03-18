# Arduino_Mesa_Maldonado


David Esteban Mesa Gonzalez
Daniel Alejandro Maldonado Silva

DOCENTE:
Diego Alejandro Barragan Vargas


## 1. HISTORIA:
Historia de Arduino Periféricos de Arduino y su uso Ficha técnica, pines de conexión Arquitectura, ventajas y funcionalidad.
El Arduino es una **placa electrónica programable** que nació en 2005 en el Interaction Design Institute Ivrea, en Italia, como una solución práctica para facilitar el uso de la electrónica a estudiantes y diseñadores sin experiencia avanzada. Fue creada por un equipo liderado por Massimo Banzi y David Cuartielles, quienes buscaban reemplazar los sistemas tradicionales de microcontroladores que eran costosos, complejos y poco accesibles. El componente físico de Arduino consiste principalmente en una **placa de circuito impreso (PCB)** que integra un **microcontrolador**, generalmente de la empresa Atmel, junto con pines de entrada y salida que permiten conectar sensores, motores, luces y otros dispositivos electrónicos. La primera placa fue sencilla y estaba pensada para comunicación serial, pero con el tiempo evolucionó hasta modelos más completos como el Arduino Uno, que se convirtió en el estándar por su equilibrio entre facilidad de uso y capacidad. Físicamente, estas placas incluyen puertos USB para programación y alimentación, reguladores de voltaje, cristales osciladores que controlan la velocidad del sistema, y una serie de pines digitales y analógicos que permiten interactuar con el entorno. Gracias a su diseño abierto, cualquier persona puede fabricar, modificar o mejorar el hardware, lo que impulsó su expansión global y permitió que Arduino se convirtiera en una herramienta fundamental en áreas como la robótica, la automatización y el Internet de las cosas. En esencia, el Arduino como componente físico representa la democratización de la electrónica, al transformar un circuito complejo en una plataforma accesible, versátil y fácil de usar para crear proyectos reales.

Además del hardware, Arduino se complementa con su entorno de programación, el Arduino IDE, que es una aplicación diseñada para escribir, compilar y cargar código en la placa de forma sencilla. Este software utiliza un lenguaje basado en C/C++, pero simplificado para que sea fácil de aprender incluso para principiantes. A través del IDE, el usuario puede programar el comportamiento del microcontrolador, definiendo instrucciones que permiten leer sensores, controlar dispositivos o automatizar procesos. La conexión entre el software y el hardware se realiza mediante el cable USB, que permite transferir el programa directamente a la placa. Gracias a esta integración entre una placa física accesible y un entorno de programación intuitivo, Arduino logró expandirse rápidamente a nivel mundial, convirtiéndose en una herramienta fundamental en la educación, la robótica, la automatización y el Internet de las cosas, representando en esencia la democratización de la electrónica al hacer posible que cualquier persona pueda crear proyectos tecnológicos de manera práctica y eficiente.

### Evolución:

2005: Nace Arduino en el Interaction Design Institute Ivrea como un proyecto enfocado en facilitar el acceso a la programación de microcontroladores, especialmente para estudiantes y diseñadores sin experiencia técnica avanzada. Su objetivo principal era ofrecer una solución económica, sencilla y de código abierto.

2008: Arduino comienza a ganar reconocimiento a nivel internacional gracias a su filosofía open source, su facilidad de uso y el apoyo de una comunidad creciente. Durante este periodo, se expande su uso en entornos educativos, talleres de innovación y proyectos de prototipado rápido.

2010 en adelante: Con la aparición de placas como el Arduino Uno, la plataforma se consolida como un estándar en el aprendizaje de electrónica y programación, siendo adoptada por universidades, desarrolladores independientes y profesionales del área tecnológica.

Actualidad: Arduino es ampliamente utilizado en múltiples campos como la robótica, la automatización, el Internet de las cosas (IoT) y el desarrollo de productos tecnológicos. Su impacto ha sido clave en la democratización de la electrónica, permitiendo que millones de personas en todo el mundo puedan crear proyectos innovadores de manera accesible.






# 2. Periféricos de Arduino y su función

Los periféricos de Arduino son componentes externos que se conectan a la placa con el objetivo de ampliar sus capacidades, permitiéndole interactuar con el entorno físico y digital. Estos dispositivos cumplen funciones fundamentales dentro de un sistema electrónico, ya que hacen posible la adquisición de datos, el procesamiento de información y la ejecución de acciones. Su correcta integración es clave para el desarrollo de proyectos funcionales en áreas como la automatización, la robótica y el Internet de las cosas.

## Sensores (Dispositivos de entrada)

Función:
Los sensores tienen como función principal captar variables del entorno y transformarlas en señales eléctricas que puedan ser interpretadas por el microcontrolador de Arduino.

Descripción:
Estos dispositivos permiten la adquisición de datos físicos como temperatura, luz, humedad, presión, movimiento o distancia. La información obtenida es enviada a la placa, donde es procesada según la programación definida. Los sensores son fundamentales en cualquier sistema automatizado, ya que constituyen el medio a través del cual el sistema obtiene conocimiento del entorno.

Aplicaciones:
Se utilizan en sistemas de monitoreo ambiental, control de condiciones climáticas, sistemas de seguridad, automatización del hogar y proyectos industriales.
* Sensor de temperatura
* Sensor de luz (LDR)
* Sensor de movimiento (PIR)
* Sensor ultrasónico

## Actuadores (Dispositivos de salida)

Función:
Los actuadores se encargan de ejecutar acciones físicas a partir de las señales generadas por Arduino.

Descripción:
Estos componentes convierten las señales eléctricas en respuestas tangibles, como movimiento, luz o sonido. Su funcionamiento depende directamente de las instrucciones programadas en el microcontrolador, lo que permite automatizar procesos y generar respuestas ante determinados estímulos.

Aplicaciones:
Son utilizados en sistemas de control de iluminación, mecanismos automatizados, robótica, alarmas y control de dispositivos eléctricos.

* LEDs
* Motores
* Servomotores
* Relés

## Módulos de comunicación

Función:
Permitir la transmisión y recepción de datos entre Arduino y otros dispositivos o sistemas.

Descripción:
Estos módulos facilitan la conectividad mediante distintos protocolos de comunicación, tanto cableados como inalámbricos. Gracias a ellos, Arduino puede integrarse en redes más amplias, intercambiar información en tiempo real y formar parte de sistemas distribuidos.

Aplicaciones:
Se emplean en proyectos de Internet de las cosas, sistemas de monitoreo remoto, control a distancia y automatización conectada.

* Bluetooth (HC-05)
* WiFi (ESP8266)
* RFID
* Pantallas LCD


## Interfaces de usuario

Función:
Facilitar la interacción entre el usuario y el sistema basado en Arduino.

Descripción:
Estos periféricos permiten mostrar información relevante del sistema o recibir instrucciones por parte del usuario. Son esenciales para mejorar la usabilidad y el control de los proyectos, ya que hacen posible una comunicación directa con el sistema.

Aplicaciones:
Se utilizan en paneles de control, sistemas interactivos, dispositivos educativos y prototipos funcionales.

## Módulos de almacenamiento y expansión

Función:
Almacenar información y ampliar las capacidades funcionales de la placa Arduino.

Descripción:
Estos componentes permiten guardar datos generados durante la ejecución del sistema o añadir nuevas funcionalidades mediante módulos adicionales. Su uso es clave en proyectos que requieren registro de información o escalabilidad.

Aplicaciones:
Se emplean en sistemas de registro de datos, almacenamiento de información histórica y ampliación de capacidades mediante módulos especializados.




# 3. Ficha técnica y pines de conexión de Arduino Uno 

El Arduino Uno es una de las placas más utilizadas dentro de la plataforma Arduino, destacándose por su simplicidad, versatilidad y facilidad de integración en proyectos electrónicos. A continuación, se presentan sus principales características técnicas y la descripción de sus pines de conexión.

- Ficha técnica

Microcontrolador: ATmega328P
Voltaje de operación: 5V
Voltaje de entrada recomendado: 7V – 12V
Voltaje de entrada límite: 6V – 20V
Pines digitales: 14 (de los cuales 6 permiten PWM)
Pines analógicos: 6
Corriente por pin: 20 mA
Memoria Flash: 32 KB
SRAM: 2 KB
EEPROM: 1 KB
Frecuencia de reloj: 16 MHz
Conectividad: USB tipo B
Alimentación: USB o jack de corriente

- Pines de conexión

Los pines del Arduino permiten la interacción con periféricos, y se clasifican según su función:

- Pines digitales (0 - 13)

Función:
Permiten trabajar con señales digitales, es decir, valores de encendido (HIGH) o apagado (LOW).

Características:

Pueden configurarse como entrada o salida

Algunos pines (3, 5, 6, 9, 10, 11) permiten PWM (simulación de señal analógica)

Uso típico:
Control de LEDs, lectura de botones, activación de relés.

- Pines analógicos (A0 - A5)

Función:
Leer señales analógicas provenientes de sensores.

Características:

Convertidor analógico-digital (ADC) de 10 bits

Valores de lectura entre 0 y 1023

Uso típico:
Lectura de sensores de temperatura, luz o potenciómetros.

- Pines de alimentación

Función:
Suministrar energía a la placa y a los componentes conectados.

Principales pines:

5V: salida de voltaje regulado

3.3V: salida de menor voltaje

GND: tierra

Vin: entrada de voltaje externo

- Pines de comunicación

Función:
Permitir la comunicación con otros dispositivos o módulos.

Tipos:

Serial (UART): pines 0 (RX) y 1 (TX)

I2C: A4 (SDA) y A5 (SCL)

SPI: pines 10 (SS), 11 (MOSI), 12 (MISO), 13 (SCK)

- Otros pines importantes

AREF: referencia de voltaje para entradas analógicas
RESET: reinicia el microcontrolador



# 4. Arquitectura, ventajas y funcionalidad de Arduino

La arquitectura de Arduino se basa en un sistema embebido centrado en un microcontrolador, como el ATmega328P en el caso del Arduino Uno. Este microcontrolador actúa como el núcleo de procesamiento, encargado de ejecutar las instrucciones programadas y gestionar la interacción con los periféricos.

A nivel estructural, la arquitectura de Arduino se compone de varios elementos fundamentales:

-Unidad de procesamiento (CPU):
Ejecuta las instrucciones del programa cargado desde el entorno de desarrollo, procesando datos de entrada y generando respuestas.

-Memorias internas:
Incluyen memoria Flash (para almacenar el programa), SRAM (para variables temporales) y EEPROM (para almacenamiento persistente de datos).

-Pines de entrada/salida (I/O):
Permiten la comunicación directa con el entorno físico mediante sensores (entrada) y actuadores (salida), soportando señales digitales y analógicas.

-Módulos de comunicación:
Integran protocolos como UART, SPI e I2C, facilitando la conexión con otros dispositivos y sistemas.

-Sistema de alimentación:
Regula y distribuye la energía necesaria para el funcionamiento de la placa y los componentes conectados.

Esta arquitectura modular y simplificada permite que Arduino funcione como un sistema autónomo capaz de ejecutar tareas específicas en tiempo real.

Funcionalidad:

La funcionalidad de Arduino se basa en su capacidad para leer, procesar y actuar dentro de un entorno determinado. Este flujo de operación se puede describir en tres etapas principales:

Entrada de datos:
Arduino recibe información a través de sensores o señales externas, ya sean digitales o analógicas.

Procesamiento:
El microcontrolador analiza los datos según las instrucciones definidas en el programa cargado mediante el Arduino IDE.

Salida o acción:
En función del procesamiento, se generan respuestas que se traducen en acciones físicas, como activar un motor, encender un LED o enviar información a otro dispositivo.

Este modelo permite desarrollar sistemas automatizados capaces de reaccionar a condiciones específicas en tiempo real, siendo ampliamente utilizado en aplicaciones de control, monitoreo y automatización.

Ventajas:

Arduino presenta múltiples ventajas que explican su popularidad en entornos educativos, profesionales y de innovación tecnológica:

Facilidad de uso:
Su entorno de programación es intuitivo y su lenguaje está basado en C/C++, pero simplificado para facilitar el aprendizaje.

Hardware y software libre:
Al ser una plataforma open source, permite a los usuarios estudiar, modificar y adaptar tanto el hardware como el software según sus necesidades.

Bajo costo:
Comparado con otros sistemas embebidos, Arduino es económico, lo que lo hace accesible para estudiantes y desarrolladores.

Amplia comunidad:
Cuenta con una gran cantidad de documentación, tutoriales y soporte a nivel mundial.

Versatilidad:
Puede utilizarse en una gran variedad de proyectos, desde prototipos simples hasta sistemas más complejos en robótica, domótica e Internet de las cosas.

Compatibilidad con múltiples periféricos:
Su diseño permite la fácil integración con sensores, actuadores y módulos de comunicación.


