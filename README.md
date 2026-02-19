#Arquitectura del Sistema: [Proyecto-movilidad]


## Entradas (Inputs)
* Ubicacion actual del usuario (GPS en tiempo real)
* Destino ingresado por el usuario (dirección o nombre del lugar)
* Ubicación en tiempo real del bus (GPS del bus)
* Base de datos de rutas disponibles
* Hora y fecha actual en el sistema
* Informacion de trafico o contratiempo

## Procesos (Throughput)
* Validación del destino ingresado por el usuario
* Establece que ruta pasa por el destino seleccionado
* Calculo de tiempo de llegada a la ubicacion del usuario
* Calculo de tiempo de llegada al destino
* Actualización en tiempo real segun movimiento del bus

## Salidas (Outputs)
* Ruta recomendada al usuario
* Placa,Numero de ruta y Nombre de empresa del bus
* Tiempo estimado de llegada del bus a la ubicacion del usuario
* Tiempo total estimado del recorrido
* Mapa con el recorrido sugerido
* Notificaciones de retrasos o cambios en la ruta

## Usuarios y Roles
* **Administrador:**
* Gestiona rutas y recorrido
* Actualiza horarios
* Supervisa tiempos de cada ruta
* Administra permisos y configuraciones del sistema
  
* **Usuario:**
* Consulta rutas disponibles
* Ingresa destino
* Visualiza tiempos estimados
* Recibe notificaciones en tiempo real
  
## Información Manejada
* Datos de ubicación en tiempo real de cada bus
* Información de rutas y recorrido
* Tiempos estimados y tiempos reales de llegada
* Incidencias o reportes del sistema
