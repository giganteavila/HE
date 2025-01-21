# 02.-Análisis y recolección de datos en redes inalámbricas

La **monitorización de redes inalámbricas** consiste en observar el espectro radioeléctrico para determinar y caracterizar las distintas señales de redes Wi-Fi disponibles. Esta fase inicial en pruebas de hacking ético permite identificar redes y sus características:

## **Características a Monitorear**

1. **SSID**:
	- Indica el nombre de la red.
	- Ayuda a identificar redes de interés, como domésticas o empresariales, basándose en el nombre.

2. **BSSID**:
	- Dirección MAC del Punto de Acceso que publica la red.
	- Esencial para monitorizar un punto de acceso específico y capturar paquetes de red.

3. **Canales Operativos**:
	- Las redes Wi-Fi utilizan canales no consecutivos para evitar interferencias.
	- Conocer el canal permite fijar la señal para capturar paquetes.

4. **Tipo de Red y Seguridad**:
	- Clasificación de la red: OPEN, WEP, WPA-PSK, WPA/WPA2-Enterprise.
	- Ayuda a determinar qué pruebas realizar dependiendo del tipo de red.

5. **Clientes Conectados**:
	- Número de clientes conectados al Punto de Acceso.
	- Algunas técnicas son más efectivas en redes con múltiples clientes conectados.

## **Tipos de Paquetes Analizados**

1. **Beacon Frames**:
	- Anuncios de los Puntos de Acceso para informar sobre el SSID, BSSID y tipo de red.
	- Siempre se transmiten sin cifrar.

2. **Tramas de Gestión**:
	- Paquetes que garantizan la conexión Wi-Fi o emiten órdenes (autenticación, desconexión, asociación).
	- Estos paquetes tampoco van cifrados y contienen información útil para análisis.

> **Nota**: La monitorización se centra en capturar y analizar estos paquetes propagados por el espectro radioeléctrico.