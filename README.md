# Examen-2do-Parcia-
Examen de arquictetura 2do parcial
# Monitor del Sistema - Proyecto Django + Psutil

Este proyecto es una aplicación web creada con Django que permite visualizar información en tiempo real del sistema ya sea dandole clic a un boton de actualizar o esperar 5 segundo el cual mostrara el uso de CPU, memoria RAM, disco duro y datos del sistema operativo. Para obtener esta información se utiliza la librería psutil.

## Descripción del Proyecto

El objetivo es monitorear el estado del sistema:

- Muestra el uso del CPU en porcentaje.
- Indica la memoria RAM usada, total y porcentaje.
- Informa el uso del disco (usado, libre y total).
- Muestra el sistema operativo, su versión y cantidad de núcleos.

##  Instrucciones para Ejecutar el Proyecto Localmente

### 1.copiar los archivos
cd monitor_sistema
Instala las detependencias pip install -r requirements.txt
Ejecucion migraciones iniciales:python manage.py migrate
Ejecutar el servidor:python manage.py runserver
De esa manera podra ejetucar el proyecto.
http://localhost:8000

Integrantes
Bryan David Cruz Suazo 201920010328
Andros Dariel Castro Lopez 202310030142



