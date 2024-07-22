  VISTAS
En la siguiente vista (CREATE VIEW VistaPedidos AS), creamos una tabla de listado de vista,
la cual nos ayuda para simplificar consultas, mejorar la seguridad y organizar mejor los datos. 
En este caso para nuestra base de datos de un buffet,
cramos esta vista para obtener detalles de todos los pedidos con información de clientes y empleados,
asi poder tener seguimiento agil tanto del dinero que sale como  del que entra.

                                           
Tambien me parecio necesario agregar otra vista(CREATE VIEW VistaReservaciones AS),
para obtener las reservaciones con información del cliente y de la mesa a utilizar,
asi poder tener mas organizacion en el establecimiento.
                                            fUNCIONES
Luego de las vistas, agregue una funcion (CREATE FUNCTION IngresosPorCategoria) 
con el fin de Calcular el total de ingresos por categoría en un rango de fechas,
Esta función calcula el total de ingresos generados por una categoría específica de platos en un rango de fechas dado,
con el objetivo de Analizar los ingresos generados por diferentes categorías de platos en un periodo determinado.
(Tablas manipuladas: DetallesPedido, Platos, Categorias)


                                          STORED PROCEDURES
Por ultimo levantamos el procedimiento "CREATE PROCEDURE AgregarCliente" ,
Esto nos permitira agregar de manera mas facil la insercion de nuevos clientes a nuestra tabla,
Lo cual nos garantiza darnos la informacion de la cantidad de comensales que podemos recibir en el establecimiento,
Con mayor precision, Asi garantizar una correcta organizacion.
(Tablas manpiludas: "clientes")
