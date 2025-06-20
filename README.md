# Curso-Ciencia-de-datos

## Sesion 3 Proyecto

Este repositorio contiene evidencia de lo trabajado durante la Sesión 3 del curso de Herramientas de Productividad en Ciencia de Datos. A continuación se documentan los pasos realizados desde la terminal de RStudio.

---

### Paso 1: Acceso a la carpeta del curso

Se usó el comando `cd` para moverse desde la terminal a la carpeta donde se encuentra el proyecto del curso en el disco local.

![image](https://github.com/user-attachments/assets/eb117cc2-23bf-41c7-856e-22198b2e79c8)

---

### Paso 2: Listado de contenido ordenado

Se listaron los archivos y carpetas dentro del directorio actual con `ls -l`, y se ordenaron alfabéticamente usando `sort -k5 -n`. Esto permite organizar la visualización del contenido del curso.

![image](https://github.com/user-attachments/assets/59aab064-6ccd-484b-b785-3935a361b061)

---

### Paso 3: Lectura de archivo PDF desde terminal

Se usó `cat` para mostrar el contenido del archivo PDF `WK_Herramientas_de_productividad.pdf` y `wc -l` para contar el número de líneas. Esto demuestra lectura básica desde consola.

![image](https://github.com/user-attachments/assets/c7c54cfe-d5d9-4b02-95c1-0af60f6f1dff)

---

### Paso 4: Visualización de archivos con tamaño legible

Se usó `ls -lhS | head -5` para mostrar los archivos más pesados en formato legible (MB). Esto ayuda a identificar qué archivos ocupan más espacio.

![image](https://github.com/user-attachments/assets/b15effba-91f3-4fc4-b554-8cab00fa2493)

---

### Paso 5: Extracción de datos por campo usando `awk`

Se aplicó el comando `date` con `awk` para extraer cada campo de la fecha actual (día, mes, año, etc.), demostrando cómo filtrar salidas específicas desde consola.

![image](https://github.com/user-attachments/assets/a72960a9-6d21-4640-b551-1e4c95c54e5c)

---

### Paso 6: Filtrado por extensión

Se utilizó `ls *.pdf` para mostrar únicamente los archivos con extensión `.pdf`, mostrando cómo hacer filtros rápidos de tipo de archivo.

![image](https://github.com/user-attachments/assets/114d39b2-6630-42ed-a498-88542b22b3eb)

---

### Paso 7: Creación de archivos y patrones con comodines

Se crearon dos archivos (`Gomez.txt` y `Gamez.txt`) con `touch`, y se usaron patrones como `G?mez.txt` para listar ambos. Esto sirve para manejar archivos usando expresiones regulares simples.

![image](https://github.com/user-attachments/assets/b5ca8f8e-df0d-4226-a695-5ac9c40ad51c)

---

### Paso 8. Crear repositorio en GitHub llamado `ProyectoHerramientasProductividad`.

Fui a GitHub, seleccioné “New repository”, asigné el nombre solicitado y lo creé sin archivos iniciales para vincularlo desde RStudio.

---

### Paso 9. Crear un token de acceso y guardarlo en `token.txt`.

Generé un token fine-grained con acceso específico al repositorio. Lo copié y lo guardé dentro de la carpeta del proyecto como `token.txt`.

---

### Paso 10. Copiar la URL del repositorio remoto.

Abrí el repositorio en GitHub y copié el enlace HTTPS:  
`https://github.com/Ady-dot/ProyectoHerramientasProductividad.git`

---

### Paso 11. Abrir la terminal en RStudio y moverme al directorio del proyecto.  

Usé el comando `cd` para llegar a mi carpeta en  
`/d/OneDrive/CUCEI/CUCEI 2025/TTT-UDG Ciencia de Datos/3 Herramientas de productividad/ProyectoHerramientasProductividad`

![image](https://github.com/user-attachments/assets/68be3d6e-9bcd-4a95-861d-4441757fd8d7)

---

### Paso 12. Inicializar repositorio local con Git.

Ejecuté:
```bash
git init ProyectoHerramientasProductividad
cd ProyectoHerramientasProductividad
```
Con esto creé el repositorio local en mi computadora.

![image](https://github.com/user-attachments/assets/370e657c-1ea1-4ff2-ba45-f9d37c63070d)

---

### Paso 13. Conectar el repositorio local con el remoto. 

Ejecuté:
```bash
git remote add origin https://github.com/Ady-dot/ProyectoHerramientasProductividad.git
```
Esto enlaza mi carpeta local con el repositorio en GitHub.

![image](https://github.com/user-attachments/assets/8464cfbe-4ed5-4903-ab0b-e0760d91359b)

---

### Paso 14. Crear y escribir el archivo `README.md`.

Documenté cada uno de los pasos realizados en la terminal, agregando capturas de pantalla y explicaciones claras de los comandos utilizados.

---

### Paso 15. Crear script `Sesion3_Script.sh`.

Se tiene contemplado generar un archivo shell que automatice la creación y carga del reporte. El archivo debe comenzar con `#!/bin/bash` e incluir comandos de Git para hacer push del trabajo final a GitHub.

