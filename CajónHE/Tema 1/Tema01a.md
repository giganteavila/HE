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

|            TIPO DE CIBERDELITO             |  2016 |  2017 |   2018 |   2019 |   2020 |   2021 |
| :----------------------------------------: | ----: | ----: | -----: | -----: | -----: | -----: |
|             Fraude informático             | 45894 | 60511 |  88760 | 192375 | 257907 | 267011 |
|           Amenazas y coacciones            | 11473 | 11270 |  11906 |  12782 |  14066 |  17319 |
|         Falsificación informática          |  2697 |  2961 |   3095 |   4275 |   6289 |  10476 |
|      Acceso e interceptación ilícita       |  2579 |  2505 |   2750 |   4004 |   4653 |   5342 |
|              Contra el honor               |  1524 |  1537 |   1423 |   1422 |   1550 |   1426 |
|              Delitos sexuales              |  1188 |  1312 |   1393 |   1774 |   1783 |   1628 |
| Interferencia en los datos y en el sistema |  1110 |  1102 |   1015 |   1473 |   1590 |   2138 |
| Contra la propiedad intelectual/industrial |   121 |   109 |    217 |    197 |    125 |    137 |
|          Contra la salud pública           |     0 |     0 |      0 |      0 |      0 |      0 |
|                   TOTAL                    | 66586 | 81307 | 110603 | 218302 | 287963 | 305477 |

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