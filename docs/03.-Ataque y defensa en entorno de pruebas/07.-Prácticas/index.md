# Fase de Formación de Paloma en Postexplotación
Una vez finalizado el curso de formación de **Luis**, y tras haber impartido una serie de formaciones esenciales al resto de integrantes técnicos del equipo, es el turno del curso formativo al que asistirá **Paloma**.

El equipo cree que una fase muy importante de la metodología de pruebas de auditoría consiste en poder manejar correctamente un equipo comprometido y utilizarlo para comprometer sistemáticamente otros equipos en la red. No es un concepto novedoso, de hecho, creen que forma parte de las **TTP (Tácticas, Técnicas y Procedimientos)** utilizados por los atacantes en una intrusión dirigida.

**Teresa** piensa que el conocimiento de estas técnicas les puede ayudar tanto a comprobar el efecto de la intrusión como a optimizar la respuesta a incidentes.


## **Paloma y su motivación por aprender**

Por su parte, Paloma está deseando iniciar el curso, ya que la formación práctica que ha realizado **Luis** en la empresa le ha resultado fascinante. Ella quiere recoger el testigo y aprender las técnicas específicas que utilizan los atacantes para moverse por una red comprometida. Por supuesto, después quiere enseñar a sus compañeros el conocimiento adquirido, igual de bien que lo ha hecho Luis.

**Paloma** ha iniciado la formación en Postexplotación que le prometieron en la empresa. Ella es la segunda persona seleccionada este año para realizar los cursos de formación y tiene una gran responsabilidad con ello, no solo por aprovechar al máximo el curso, sino porque, cuando termine, deberá impartir varios talleres formativos internos.

Paloma quiere transmitir a sus compañeros todos los conceptos aprendidos tras el curso. Además, le pareció muy buena idea el enfoque práctico que realizó Luis en su curso, y planea realizar los talleres de la misma manera.


## **Conocimientos previos y preparación**

El acceso a este curso requiere tener conocimientos previos de explotación, ya que la mayoría de las técnicas aplicadas se realizan sobre un equipo previamente comprometido. Esta última parte no le preocupa en exceso, ya que, en los talleres formativos realizados con Luis, han trabajado estos conceptos realizando varios ejercicios prácticos que le permitieron familiarizarse con distintos vectores de ataque.

Sin tiempo que perder, **Paloma** se dispone a iniciar el curso.



## **Primeros conceptos y sorpresas**

Terminado el primer tema del curso formativo, Paloma está totalmente perpleja. Nunca habría imaginado que una shellcode como **Meterpreter** permitiera tantas opciones para administrar un sistema de manera remota.

Una de las opciones que le han parecido más curiosas es el comando **"hashdump"** del propio Meterpreter, que extrae automáticamente los hashes **NTLM** de las contraseñas de los usuarios locales de la máquina víctima (**Microsoft Windows**).

Paloma se pregunta:

- "¿Qué opciones tengo con este tipo de hash?"
- "¿Y si encuentro otros tipos de hash utilizados en el sistema?"
- "¿Se podrá utilizar el mismo proceso de cracking que aplicamos para redes Wi-Fi para intentar averiguar la contraseña de estos hashes?"

La curiosidad de **Paloma** es más fuerte que el sueño, y decide despejar estas dudas en el siguiente tema del curso.

## **Retos en redes segmentadas**

Según avanza el curso, Paloma no deja de aprender nuevos conceptos y técnicas de **Postexplotación**. Sin embargo, reflexiona sobre las prácticas realizadas:

- "Hasta ahora, sólo hemos comprometido máquinas accesibles y las hemos administrado de manera remota."

Dado que el semestre anterior participó en un proyecto de diseño de redes en la empresa, **Paloma** sabe que su organización utiliza una segmentación de redes. Existen ciertas redes a las que únicamente es posible acceder desde un segmento de red concreto o una **VLAN específica**.

**Paloma** entiende que esta segmentación no es exclusiva de su empresa; la mayoría de las organizaciones implementan segregación de redes para evitar accesos no deseados.

Estas restricciones, piensa **Paloma**, limitan en gran medida la fase de Postexplotación, ya que:

1. Sólo se han explotado sistemas remotos accesibles.
2. La segmentación de redes restringe la capacidad de acceder a otros equipos que puedan presentar vectores de acceso.

Decidida a resolver sus dudas, **Paloma** envía un correo al personal docente preguntando sobre estas limitaciones.



## **Respuesta del instructor**

El instructor encargado del grupo de aprendizaje responde a **Paloma**, explicando que los factores que expone son efectivamente limitantes. Sin embargo, existen técnicas como el **Pivoting**, que permiten solventar esta problemática y explorar redes segmentadas.

**Paloma**, motivada por la respuesta, afirma que el curso en el que está participando resolverá todas sus dudas.



## **Últimos capítulos del curso**

Con el curso a punto de finalizar, **Paloma** se enfrenta a nuevas inquietudes:

- "¿Qué sucede si pierdo la conexión con la máquina remota? ¿Tendré que volver a comprometerla?"

Estas dudas comienzan a disiparse al leer el título del último capítulo:

- **"Instalación de puertas traseras."**

**Paloma** piensa para sí misma:

- "Seguro que este capítulo me ayuda a resolver todas mis dudas."