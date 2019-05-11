# Alhambra-ReceptorIR

### Construcción de un receptor IR con modulación , basado en el fototransistor TSOP2238

Documentación sobre cómo fabricar un receptor de infrarrojos modulado a 38 Khz para la placa FPGA Icezum Alhambra o Alhambra II.

**Nota** :  Esta construcción sirve de apoyo a mi Cuaderno sobre comunicación y control mediante infrarrojos con la placa Icezum Alhambra y Alhambra II . 

Ver en este enlace : (https://github.com/makerventura/FPGAs_Infrarrojos-Comunicacion-y-Control.git)



![IMG_20190420_203822](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_203822.jpg)



Para construir este circuito receptor  me he basado en el esquema indicado como estándar en su hoja técnica :

![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/circuito_receptorIR.png)

al que le he añadido un led estárdar con su resistencia de absorción entre Vs y OUT para que me sirva simplemente como avisador de que el fototransistor está pasando de estado reposo "1" a estado "0" y por tanto recibiendo señales .

Aquí os dejo el esquemático del circuito electrónico en fritzing :



![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/receptorIR.png)



Así como unas fotos de la primera versión que hice del circuito usando una placa perforada ,



![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190421_111542.jpg)



![IMG_20190421_111555](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190421_111555.jpg)



### Instrucciones para la construcción del Alhambra ReceptorIR

Como complemento al cuaderno que he preparado para Comunicación y Control por infrarrojos en la placa FPGA Icezum Alhambra he diseñado y construido un pequeño receptor IR al que he denominado Alhambra_ReceptorIR, y que documento a continuación basado en el circuito anterior de fritzing.

Me ha servido como excusa perfecta para poner en práctica algunas ideas tanto de concepto , como constructivas y sobre materiales que había visto en las redes y que tenía guardadas a la espera de encontrar una ocasión ideal para poder aplicarlas .

Hacía tiempo que tenía ganas de hacer un montaje utilizando impresión 3D al estilo de los desarrollos planos de toda la vida que hacíamos en cartulina para después montar el desarrollo en el espacio .

Como tenía que ser algo sencillo , decidí que este montaje eléctrico podía ser la ocasión ideal para intentar armarlo mediante una forma básica de **Prisma** .

Además el circuito eléctrico en sí era también bastante sencillo y no requería de un ordenamiento espacial muy complejo para aislar entre si los cables o pistas de conexión .

Una vez en faena , me di cuenta de que el circuito tal y como yo lo había esbozado en papel ( vista 2 D ) admitía su armado tridimensional sin más que ordenar un poco las pistas eléctricas . De ahí surgió la idea de dibujar las **canaletas** de las pistas de conexión al estilo de un **circuito impreso**  y probar la utilización de la cinta de cobre adhesiva que compré para hacer el teclado siguiendo las instrucciones de Obijuan , rellenando dichas canaletas con cinta de cobre conductora adhesiva .

A continuación os dejo unas instrucciones para construirlo y una imágenes del proceso :

- Material necesario .

  - 1 fototransistor TSOP2238 . ( 38 Khz ) . Se puede usar perfectamente un TSOP2236 , a 36 Khz . Yo lo he probado y también funciona aunque la frecuencia portadora sea un poco distinta . En caso de cambiar a otros tipo de fototransistores , tener mucho cuidado con la disposición de las 3 patillas del transistor porque una mala conexión ocasionará daños irreparables en el sensor . Buscar la datasheet correspondiente . El circuito impreso del Alhambra ReceptorIR está diseñado para la disposición de patillas del TSOP2238 .
  - 1 Led de 5 mm
  - 1 resistencia de 220 Ω
  - 1 resistencia de 120 Ω
  - 1 condensador de 1 µF
  - 1 conector hembra 3 pines
  - Cinta de cobre adhesiva . Para este montaje vale cualquier ancho de cinta .
  - Pieza impresa en 3D

  

- Instrucciones de montaje .

  ​	Aquí os dejo una serie de fotos con el montaje paso a paso que realicé :

  **Notas importantes de mi experiencia al construirlo :**

  Os recomiendo que dupliquéis la cantidad de lámina de cobre adhesiva a utilizar , es decir que antes de recortar las tiras de cobre peguéis superpuesta una lámina encima de otra para tener unas tiras del doble de grosor ( 2 x 0.2 mm) . De esa manera las tiras de cobre son más resistentes y aguantan mucho mejor las dobleces que hay que hacer en las caras del prisma para cerrarlo y darle la forma final .

  También os recomiendo que hagáis dentro de lo posible **tiras completas de cobre , evitando los empalmes en los cruces** . Mi experiencia me dice que aunque la cinta de cobre que compré se supone que es conductora por las dos caras , en los empalmes la conductividad **NO** está del todo asegurada . En caso de que no os quede más remedio que hacer un empalme , lo mejor es unirlo bien mediante un pequeño punto de soldadura de estaño .

  

  ![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/Alhambra_receptorIR.bmp)

  

  ![](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_174254.jpg)

  

  ![IMG_20190420_174556](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_174556.jpg)

  

  ![IMG_20190420_185734](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_185734.jpg)

  

  ![IMG_20190420_200704](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_200704.jpg)

  

  ![IMG_20190420_200730](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_200730.jpg)

  

  ![IMG_20190420_201535](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_201535.jpg)

  

  ![IMG_20190420_202618](https://raw.githubusercontent.com/makerventura/Mundo_FPGA_libre/master/Imagenes/IMG_20190420_202618.jpg)

  



Antes de armarlo definitivamente , os recomiendo que hagáis pruebas de continuidad en todas las pistas y comprobéis que funciona perfectamente .