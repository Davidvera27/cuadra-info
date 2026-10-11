# Política de Privacidad de Cuadra

Última actualización: 11 de octubre de 2026.

Cuadra es una aplicación personal de finanzas, desarrollada y usada por una sola persona, su dueño. Esta política explica qué datos de Google usa y qué hace con ellos.

## Qué datos de Google usa

Si el dueño autoriza la conexión con su cuenta de Gmail, Cuadra solicita un único permiso:

- `https://www.googleapis.com/auth/gmail.readonly`: lectura de los mensajes de correo.

Cuadra usa ese permiso solo para leer los correos de notificación de movimientos que los bancos envían a la cuenta del dueño y que este marcó con una etiqueta propia. No lee los demás correos, aunque técnicamente el permiso lo permita.

## Para qué los usa

De cada correo de notificación Cuadra extrae el valor, la fecha, la hora y el destinatario del movimiento, y con ellos propone un movimiento en la contabilidad personal del dueño. No usa los datos para ningún otro fin.

## Qué guarda y dónde

- Los datos extraídos de cada correo (valor, fecha, destinatario) y el identificador del mensaje, para no registrarlo dos veces.
- El token de acceso de Google, cifrado.
- Todo se guarda en la base de datos del dueño. No se envía a terceros.

Cuadra no guarda el contenido completo de los correos ni sus archivos adjuntos.

## Con quién los comparte

Con nadie. Los datos no se venden, no se alquilan, no se usan para publicidad y no se transfieren a terceros. Tampoco se muestran a personas distintas del dueño de la cuenta, salvo que la ley lo exija.

## Cumplimiento con la política de Google

El uso que hace Cuadra de la información recibida de las APIs de Google cumple la [Política de datos de usuario de los servicios de las APIs de Google](https://developers.google.com/terms/api-services-user-data-policy), incluidos los requisitos de uso limitado.

## Cómo revocar el acceso y borrar los datos

- Para revocar el acceso, el dueño puede quitar Cuadra en https://myaccount.google.com/permissions en cualquier momento. Cuadra deja de poder leer su correo de inmediato.
- Para borrar los datos guardados, basta con pedirlo al contacto de abajo o eliminarlos directamente de la base de datos.

## Cambios en esta política

Si esta política cambia, se actualizará esta página y la fecha de arriba.

## Contacto

davidrestrepovera@gmail.com
