# Guía Rápida de Comandos de Linux

Una colección de comandos que uso frecuentemente, organizados por categoría.

---

### Navegación y Gestión de Archivos

* `ls`: Lista el contenido de un directorio.
  * `ls -la`: Muestra archivos ocultos, permisos y otros detalles.
* `cd`: Cambia de directorio.
  * `cd ..`: Sube un nivel. `cd ~`: Va al directorio "home".
* `mkdir`: Crea un nuevo directorio.
  * `mkdir -p mi/ruta/anidada`: Crea toda la estructura de directorios de una vez.
* `pwd`: Muestra el directorio de trabajo actual.
* `rm`: Elimina archivos o directorios.
  * `rm -r mi_directorio`: Borra un directorio y todo su contenido.
* `cp`: Copia archivos o directorios.
  * `cp archivo.txt /nueva/ruta/`: Copia un archivo a otra ubicación.
* `mv`: Mueve o renombra archivos y directorios.
  * `mv archivo_viejo.txt archivo_nuevo.txt`: Renombra un archivo.

---

### Búsqueda y Procesamiento de Texto

* `grep`: Busca patrones de texto dentro de archivos.
  * `grep "error" archivo.log`: Encuentra todas las líneas que contienen la palabra "error".
* `find`: Busca archivos y directorios según criterios (nombre, tamaño, etc.).
  * `find . -name "*.py"`: Encuentra todos los archivos Python en el directorio actual.
* `awk` y `sed`: Herramientas potentes para procesar y manipular texto en la línea de comandos.

---

### Monitoreo del Sistema

* `top` o `htop`: Muestra los procesos en ejecución y el uso de recursos en tiempo real (`htop` es más visual y recomendado).
* `df`: Muestra el uso de espacio en disco de los sistemas de archivos.
  * `df -h`: Formato legible para humanos (KB, MB, GB).
* `free`: Muestra la cantidad de memoria RAM libre y usada.
  * `free -h`: Formato legible.
* `lscpu`: Muestra información sobre la CPU (arquitectura, núcleos, etc.).
* `lsof`: Lista los archivos abiertos por los procesos.
  * `lsof -i :80`: Muestra qué proceso está usando el puerto 80.

---

### Diagnóstico de Red

* `ping`: Envía paquetes a un host para verificar conectividad.
* `nslookup` o `dig`: Realiza consultas DNS para resolver nombres de dominio. `dig` es más potente.
  * `dig google.com`: Muestra la información DNS de google.com.
* `traceroute`: Muestra la ruta (los saltos) que toman los paquetes para llegar a un host.
* `curl` o `wget`: Herramientas para transferir datos desde o hacia un servidor (ej. descargar archivos o probar APIs).

---

### Gestión de Permisos

* `chmod`: Cambia los permisos de un archivo o directorio.
* `chown`: Cambia el propietario y el grupo de un archivo o directorio.