
# Solución: Práctica 03 - Fase de Escaneo

## Paso 1: Escaneo de red para identificar dispositivos activos
Utiliza `nmap` para descubrir dispositivos en la red local:
```
nmap -sn 192.168.1.0/24
```
**Explicación:** Este comando realiza un "ping scan" para identificar dispositivos activos en el rango de red especificado.

---

## Paso 2: Escaneo de puertos abiertos en un dispositivo específico
Escanea los puertos abiertos en un dispositivo identificado:
```
nmap -sS 192.168.1.10
```
**Explicación:** Este comando realiza un escaneo SYN para enumerar los puertos abiertos de manera eficiente y menos detectable.

---

## Paso 3: Identificación de servicios en los puertos abiertos
Descubre qué servicios están corriendo y sus versiones:
```
nmap -sV -p 22,80,443 192.168.1.10
```
**Explicación:** La opción `-sV` intenta determinar las versiones de los servicios en los puertos especificados (22, 80 y 443 en este ejemplo).

---

## Paso 4: Escaneo de vulnerabilidades
Realiza un escaneo para detectar posibles vulnerabilidades:
```
nmap --script vuln 192.168.1.10
```
**Explicación:** Esto utiliza scripts de Nmap para buscar vulnerabilidades conocidas en el dispositivo objetivo.

---

## Paso 5: Generación de un informe
Guarda los resultados del escaneo en un archivo para referencia futura:
```
nmap -sV 192.168.1.10 -oN escaneo_resultados.txt
```
**Explicación:** La opción `-oN` guarda los resultados en formato de texto legible.

---

## Paso 6: Escaneo avanzado (opcional)
Incluye opciones avanzadas como la detección de sistema operativo:
```
nmap -O 192.168.1.10
```
**Explicación:** La opción `-O` intenta identificar el sistema operativo del dispositivo objetivo basándose en la respuesta de los paquetes enviados.
