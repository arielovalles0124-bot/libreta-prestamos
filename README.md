# Libreta de Préstamos

Página web para llevar préstamos personales a clientes con interés simple, compartida entre dos personas.

- Entrada con usuario y contraseña.
- Préstamos y pagos guardados en una base de datos (Supabase); lo que anota una persona lo ve la otra.
- Cada pago se divide en rédito (ganancia) y abono a capital.
- Resumen de capital en la calle, ganancias cobradas y ganancias del mes, por mes y por cliente.
- Respaldo: botones para descargar y cargar un archivo con todos los datos.

## Archivos

- `index.html`: la app (HTML, CSS y JavaScript).
- `supabase.js`: librería de conexión con la base de datos (supabase-js 2.45.4).

Ambos archivos deben estar en la misma carpeta.

## Seguridad

La página incluye la clave pública (publishable) del proyecto, que está pensada para ir en páginas web. El acceso a los datos lo controlan las reglas de la base de datos: solo usuarios que hayan iniciado sesión pueden leer o escribir, y el registro libre de cuentas está desactivado. Las cuentas se crean a mano en el panel de Supabase.

Nunca se debe poner en este repositorio la clave secreta (service_role) ni la contraseña de la base de datos.
