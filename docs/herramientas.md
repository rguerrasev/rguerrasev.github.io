# Mi Stack de Herramientas

Esta es la lista de las principales herramientas que utilizo en mi día a día para desarrollo, administración de sistemas y automatización.

---

###  Entorno de Desarrollo y Sistema
#### Windows 11 
Para poder utilizar las herramientas que describo a continuacion es necesario saber en que sistema operativo trabajo.

#### WSL2 (Debian)
Es la base de mi entorno de trabajo. Me permite tener una terminal de Linux nativa y potente directamente en Windows, combinando lo mejor de ambos mundos para scripting y desarrollo.

#### Visual Studio Code
Mi editor de código principal. Su versatilidad, la enorme cantidad de extensiones (especialmente para desarrollo remoto sobre WSL y SSH) y su terminal integrada lo hacen indispensable para cualquier tarea.

#### Docker Desktop
Mi herramienta principal para todo lo relacionado con contenedores. La uso para construir, ejecutar y gestionar imágenes de Docker de forma local, lo que me permite empaquetar aplicaciones y sus dependencias de manera consistente.

Con el clúster de Kubernetes que incluye, puedo probar manifiestos y despliegues de `kubectl` en un entorno de desarrollo seguro antes de llevarlos a un clúster de producción en la nube. Es esencial para validar la orquestación de microservicios.

---

###  Virtualización y Networking

#### VMware Workstation
Lo utilizo para crear y gestionar laboratorios de virtualización completos. Es ideal para probar sistemas operativos, configuraciones de red complejas o entornos aislados que requieren un control total sobre el hardware virtual.

#### GNS3
Una herramienta fundamental para simular redes. La utilizo para diseñar y probar topologías de red con equipos de diferentes fabricantes (Cisco, Juniper, etc.) antes de implementarlas en entornos reales. Es esencial para la práctica y validación de conceptos de networking.