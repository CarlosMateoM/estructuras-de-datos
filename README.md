

Problema 10.6 del capitulo 10 / Estructuras de datos en Java - Luis Jayones Aguilar.
---------------------------------------------------------------------------------------------

TEMA: Colas.

Planteamiento del problema.
---------------------------------------------------------------------------------------------

El supermercado Esperanza quiere simular los tiempos de atención al cliente a la
hora de pasar por la caja. Los supuestos de los que se parte para la simulación son los
siguientes:
• Los clientes forman una única fila. Si alguna caja está libre, el primer cliente de
la fila es atendido. En el caso de que haya mas de un caja libre, la elección del
número de caja por parte del cliente es aleatoria.

• El número de cajas del que se dispone para atención a los clientes es de tres, salvo
que haya mas de 20 personas esperando en la fila; entonces se habilita una cuarta
caja, que se cierra cuando no quedan clientes esperando. El tiempo de atención
de cada una de las cajas está distribuido uniformemente: la caja 1 entre 1,5 y 2,5
minutos; la caja 2 entre 2 y 5 minutos, la caja 3 entre 2 y 4 minutos. La caja 4,
cuando está abierta, tiene un tiempo de atención entre 2 y 4,5 minutos.

• Los clientes llegan a la salida en intervalos de tiempo distribuidos uniformemente,
con un tiempo medio de 1 minuto.

El programa de simulación se debe realizar para 7 horas de trabajo. Se desea obtener
una estadística con los siguientes datos:

• Clientes atendidos durante la simulación.

• Tamaño medio de la fila de clientes.

• Tamaño máximo de la fila de clientes.

• Tiempo máximo de espera de los clientes.

• Tiempo en que está abierto la cuarta caja.

