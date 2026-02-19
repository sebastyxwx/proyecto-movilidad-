# proyecto-movilidad-
# Arquitectura del Sistema: [ProyectoMovilidad]


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
