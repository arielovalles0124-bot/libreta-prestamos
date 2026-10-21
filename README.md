# Libreta de Préstamos

Página web de una sola página para llevar préstamos personales a clientes con interés simple. No necesita instalación ni cuenta.

- Cliente con préstamo: nombre, monto, tasa por período, frecuencia (semanal, quincenal o mensual) y fecha.
- Cada pago se divide en rédito (ganancia) y abono a capital.
- Resumen de capital en la calle, ganancias cobradas y ganancias del mes.
- Ganancias por mes y por cliente.
- Respaldo: botones para descargar y cargar un archivo con todos los datos.

## Archivo

`index.html` contiene toda la app (HTML, CSS y JavaScript).

## Dónde se guardan los datos

Los datos de los clientes no están en este repositorio. Cada persona que abre la página guarda sus datos solo en su propio navegador (localStorage). Si borra los datos del navegador o cambia de aparato, los pierde, por eso existe el botón "Descargar respaldo".
