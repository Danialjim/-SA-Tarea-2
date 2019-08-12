# -SA-Tarea-2
Tarea 2 del laboratorio de SA

Datos: 
201313982
Carlos Daniel Alonzo Jimenez

2 Aplicaciones:
- Cliente que requiere servicio de Uber
- Piloto de vehiculo de Uber

1 ESB

3 Servicios:
- Solicitud de servicio de Uber
- Recepcion de solicitud y aviso al piloto
- Rastreo de ubicacion del carro por parte de la administracion.

Ubicacion de servicios:

Recepcion de solicitud: ServiciosWeb/ServicioDePiloto/Controllers/RecepcionSolicitudController.cs
Solicitud de servicio: ServiciosWeb/ServiciosWeb.WebApi/Controllers/SolicitudDeServicioController.cs
Asignacion de piloto: ServiciosWeb/ServicioDePiloto/Controllers/AsignacionPilotoController.cs
Ubicacion del carro: ServiciosWeb/ServicioDeUbicacion.WebApi/Controllers/UbicacionCarroController.cs

La documentacion interna se encuenta en cada una de las carpetas de los servicios.
