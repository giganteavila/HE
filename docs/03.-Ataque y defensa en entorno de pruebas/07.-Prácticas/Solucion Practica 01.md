
# Solución: Práctica 01 - Fase de Reconocimiento

## Ejercicio 1
**Buscar todos los archivos PDF del sitio `github.com`.**
```
site:github.com filetype:pdf
```
**Explicación:** Esto filtra los resultados en Google para mostrar únicamente archivos PDF alojados en `github.com`.

---

## Ejercicio 2
**Buscar cualquier URL que contenga la cadena `intranet/login.php`.**
```
inurl:"intranet/login.php"
```
**Explicación:** La opción `inurl` busca URLs que contengan la cadena exacta indicada. Útil para localizar rutas específicas en aplicaciones web.

---

## Ejercicio 3
**Buscar un listado de directorios con la carpeta `uploads` expuesta.**
```
intitle:"index of" inurl:"/uploads"
```
**Explicación:** `intitle:"index of"` busca páginas de índice (listados de directorios) mientras que `inurl` filtra aquellas con el subdirectorio `/uploads`.

---

## Ejercicio 4
**Buscar documentos Word (`.docx`) que contengan información sensible.**
```
filetype:docx "confidential"
```
**Explicación:** Este dork busca documentos Word (`.docx`) con la palabra clave "confidential". Puede localizar documentos mal protegidos.
