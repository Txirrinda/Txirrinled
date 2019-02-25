# Txirrinled
## Información del proyecto
## Componentes utilizados
  ### LDR
  Un LDR es un resistor que varía su valor de resistencia eléctrica dependiendo de la cantidad de luz que incide sobre él. Se le llama, también, fotorresistor o fotorresistencia. El valor de resistencia eléctrica de un LDR es bajo cuando hay luz incidiendo en él (en algunos casos puede descender a tan bajo como 50 ohms) y muy alto cuando está a oscuras (puede ser de varios megaohms).

Los LDR se fabrican con un cristal semiconductor fotosensible como el sulfuro de cadmio (CdS). Esta celdas son sensibles a un rango amplio de frecuencias lumínicas, desde la luz infrarroja, pasando por la luz visible, y hasta la ultravioleta.

La variación de valor resistivo de un LDR tiene cierto retardo, qie es diferente si se pasa de oscuro a iluminado o de iluminado a oscuro.

Por esta razón un LDR no se puede utilizar algunas aplicaciones, en especial en aquellas en que la señal luminosa varía con rapidez. El tiempo de respuesta típico de un LDR está en el orden de una décima de segundo.

La lentitud relativa del cambio es una ventaja en algunos casos, porque así se filtran variaciones rápidas de iluminación que podrían hacer inestable un sensor (por ejemplo cuando está iluminado por un tubo fluorescente alimentado por corriente alterna), En otras aplicaciones (como la detección de luminosidad para saber si es de día o es de noche) la lentitud de la detección no es importante.
 
  ### HC SR04
  El HC-SR04 es un sensor ultrasónico de bajo costo que no sólo puede detectar si un objeto se presenta, como un sensor PIR (Passive Infrared Sensor), sino que también puede sentir y transmitir la distancia al objeto.
Tienen dos transductores, básicamente, un altavoz y un micrófono.
 Ofrece una excelente detección sin contacto (remoto) con elevada precisión y lecturas estables en un formato fácil de usar.
El funcionamiento no se ve afectado por la luz solar o el material negro como telémetros ópticos (aunque acústicamente materiales suaves como telas pueden ser difíciles de detectar).
La velocidad del sonido en el aire (a una temperatura de 20 °C) es de 343 m/s. (por cada grado centígrado que sube la temperatura, la velocidad del sonido aumenta en 0,6 m/s)
  
  ### Buzzer
  Zumbador, buzzer en inglés, es un transductor electroacústico que produce un sonido o zumbido continuo o intermitente de un mismo tono (generalmente agudo). Sirve como mecanismo de señalización o aviso y se utiliza en múltiples sistemas, como en automóviles o en electrodomésticos, incluidos los despertadores
  Inicialmente este dispositivo estaba basado en un sistema electromecánico que era similar a una campana eléctrica pero sin el badajo metálico, el cual imitaba el sonido de una campana.

Su construcción consta de dos elementos, un electroimán o disco piezoeléctrico y una lámina metálica de acero. El zumbador puede ser conectado a circuitos integrados especiales para así lograr distintos tonos.

Cuando se acciona, la corriente pasa por la bobina del electroimán y produce un campo magnético variable que hace vibrar la lámina de acero sobre la armadura, o bien, la corriente pasa por el disco piezoeléctrico haciéndolo entrar en resonancia eléctrica y produciendo ultrasonidos que son amplificados por la lámina de acero.
  ### Arduino Nano
  El Arduino Nano es una pequeña y completa placa basada en el ATmega328 (Arduino Nano 3.0) o el ATmega168 en sus versiones anteriores (Arduino Nano 2.x) que se usa conectándola a una protoboard. Tiene más o menos la misma funcionalidad que el Arduino Duemilanove, pero con una presentación diferente. No posee conector para alimentación externa, y funciona con un cable USB Mini-B.

Características
Microcontrolador: Atmel ATmega328 (ATmega168 versiones anteriores)
Tensión de Operación (nivel lógico): 5 V
Tensión de Entrada (recomendado): 7-12 V
Tensión de Entrada (límites): 6-20 V
Pines E/S Digitales: 14 (de los cuales 6 proveen de salida PWM
Entradas Analógicas: 8 Corriente máx por cada PIN de E/S: 40 mA
Memoria Flash: 32 KB (ATmega328) de los cuales 2KB son usados por el bootloader (16 KB – ATmega168)
SRAM: 2 KB (ATmega328) (1 KB ATmega168)
EEPROM: 1 KB (ATmega328) (512 bytes – ATmega168)
Frecuencia de reloj: 16 MHz
Dimensiones: 18,5mm x 43,2mm
Energía
El Arduino Nano posee selección automática de la fuente de alimentación y puede ser alimentado a través de:

Una conexión Mini-B USB.
Una fuente de alimentación no regulada de 6-20V (pin 30).
Una fuente de alimentación regulada de 5V (pin 27)
Al alimentar el arduino a través del Mini USB, el CH340 proporciona una salida de 3.3V en el pin 16 de la placa. Por ende, cuando se conecta a una fuente externa (no USB), los 3.3V no se encuentran disponibles.

### Diodos Led´s
   La estructura del chip de los diodos LED, al contrario de lo que ocurre con los diodos comunes, no emplea cristales de silicio (Si) como elemento semiconductor, sino una combinación de otros tipos de materiales, igualmente semiconductores, pero que poseen la propiedad de emitir fotones de luz de diferentes colores cuando lo recorre una corriente eléctrica.

Un diodo LED emisor de luz roja, por ejemplo, emplea un chip compuesto por arseniuro de galio y aluminio (GaAlAs), mientras que para emitir luz azul utiliza un chip de nitruro de galio (GaN). Todas las combinaciones empleadas en la fabricación del chip de un diodo LED, poseen también dos polaridades o regiones diferentes: una negativa “N” correspondiente al cátodo y otra positiva “P” correspondiente al ánodo, al igual que ocurre con los diodos comunes de silicio (Si).
  
  ### PCB
  Es una superficie constituida por caminos, pistas o buses de material conductor laminadas sobre una base no conductora. El circuito impreso se utiliza para conectar eléctricamente a través de las pistas conductoras, y sostener mecánicamente, por medio de la base, un conjunto de componentes electrónicos. Las pistas son generalmente de cobre, mientras que la base se fabrica generalmente de resinas de fibra de vidrio reforzada, cerámica, plástico, teflón o polímeros como la baquelita.

También se fabrican de celuloide con pistas de pintura conductora cuando se requiere que sean flexibles para conectar partes con movimiento entre sí, evitando los problemas del cambio de estructura cristalina del cobre, que hace quebradizos los conductores de cables y placas.

La producción de las PCB y el montaje de los componentes puede ser automatizada.1​ Esto permite que en ambientes de producción en masa, sean más económicos y fiables que otras alternativas de montaje (p. e.: wire-wrap o entorchado, ya pasado de moda). En otros contextos, como la construcción de prototipos basada en ensamblaje manual, la escasa capacidad de modificación una vez construidos y el esfuerzo que implica la soldadura de los componentes2​ hace que las PCB no sean una alternativa óptima. Igualmente, se fabrican placas con islas y / barras conductoras para los prototipos, algunas según el formato de las Protoboards.
  
  ### Impresion 3D 
  Una impresora 3D es una máquina capaz de realizar réplicas de diseños en 3D, creando piezas o maquetas volumétricas a partir de un diseño hecho por ordenador, descargado de internet o recogido a partir de un escáner 3D. Surgen con la idea de convertir archivos de 2D en prototipos reales o 3D. Comúnmente se ha utilizado en la prefabricado de piezas o componentes, en sectores como la arquitectura y el diseño industrial. En la actualidad se está extendiendo su uso en la fabricación de todo tipo de objetos, modelos para vaciado, piezas complicadas, alimentos, prótesis médicas (ya que la impresión 3D permite adaptar cada pieza fabricada a las características exactas de cada paciente), etc.

La impresión 3D en el sentido original del término se refiere a los procesos en los que secuencialmente se acumula material en una cama o plataforma por diferentes métodos de fabricación, tales como polarización, inyección de aporte, inyección de aglutinante, extrusión de material, cama de polvo, laminación de metal, depósito metálico.
