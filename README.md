# Reba_Challenge

Con el fin de cumplir con el desafío del Reba Challenge, analizaremos un dataset acerca de las compras/licitaciones de CABA en lo que va del año 2022. Para ellos, hay algunas cosas que debemos tener en cuenta.

En primer lugar, en este trabajo se asume que los montos de presupuesto y demás que aparecen en el archivo están atados a un tipo de moneda que también figura. Es por esto, que es necesario tener alguna serie de tipo de cambio a mano, por lo que recomiendo el siguiente link: https://www.bcra.gob.ar/PublicacionesEstadisticas/Principales_variables_datos.asp?serie=272&detalle=Tipo%20de%20Cambio%20Mayorista%20($%20por%20US$)%20Comunicaci%F3n%20A%203500%A0-%20Referencia

En dicho link, podremos saber el valor del dolar oficial mayorista en cualquiera de las fechas que querramos. Cabe destacar que implementé esto ya que no encontré una página en la sea posible tomar los datos de forma automática. Por lo cual cada vez que se requiera actualizar el archivo sería conveniente descargar la serie en excel primero para sí luego poder ser importada al script.

Por otro lado, quiero resaltar que para las consignas acerca de montos en rubros y reparticiones, se utilizó el monto total, mientras que en el caso de la clasificación por empresas se implementaron las licitaciones que se encuentran actualmente activas, es decir, los montos de las adjudicaciones.

Por último, para calcular la evolución en el tiempo de la ejecución del presupuesto, se aplica el ratio (Compra completada)/(Compra presupuestada).
