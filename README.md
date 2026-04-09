https://github.com/sebastyxwx/proyecto-movilidad-/blob/147b2aa8a9e29665e4380d981b736e366d3593f1/WhatsApp%20Image%202026-04-05%20at%205.34.03%20PM.jpeg

# 1. Cliente (App móvil / Tablet)
El usuario desde la app puede:
Solicitar rutas (consultar cómo llegar).
Reportar incidentes (accidentes, tráfico, etc.).
# 2. Frontend
Construido con React Native/Expo, actúa como intermediario visual entre el usuario y el servidor.
Envía las solicitudes del usuario al backend.
# 3. Servidor (Backend - Node.js/Express)
Aquí ocurre la lógica principal:
Gestión de usuarios: maneja cuentas y datos.
Motor de rutas: calcula rutas óptimas.
Procesador de incidentes: recibe y analiza reportes.
Actualizador en tiempo real: ajusta la información según cambios (tráfico, incidentes).
# 4. Servicios externos
Se conecta con APIs como:
Google Maps: para mapas y cálculo de rutas.
Notificaciones (FCM): para enviar alertas a los usuarios.
# 5. Base de datos (PostgreSQL)
Guarda información de:
Usuarios
Rutas
Empresa del bus
Incidentes
# 6. Flujo principal
Consulta de rutas:
El usuario solicita una ruta.
El servidor consulta datos y APIs externas.
Devuelve las rutas que le sirven al usuario.
Reporte de incidentes:
El usuario reporta un problema.
El servidor lo procesa y guarda.
Se actualizan rutas y se notifican a otros usuarios.
