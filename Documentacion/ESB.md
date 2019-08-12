La direccion en donde se encuentra el ESB es:
ServiciosWeb/Tarea 2/ESB.cs

La aplicacion de cliente interactua con el ESB el cual es el encargado de interactuar con los 3 servicios descritos en cada una de sus documentaciones, al finalizar el ciclo le notifica al cliente y al piloto cada uno de sus mensajes.

Posee las siguientes funciones:

/*
* public void SolicitarServicio(int id); -> Funcion que sirve para la solicitud de un nuevo servicio de Uber para el cliente.
* int id -> ID del cliente que solicita el servicio
*/
public static void SolicitarServicio(int id);

/*
* public void RecepcionSolicitudYAvisoPiloto(int id); -> Funcion que sirve para la recepcion del servicio del cliente.
* int id -> ID del cliente que solicita el servicio
*/
public static void RecepcionSolicitudYAvisoPiloto(int id);


/*
 * public void SolicitudUbicacion(int id); -> Funcion que sirve para la solicitud de la ubicacion del carro.
 * int id_piloto -> ID del piloto
*/
public static void SolicitudUbicacion(int id_piloto);

Se utilizo el estandar de codigo por defecto en visual studio c#
