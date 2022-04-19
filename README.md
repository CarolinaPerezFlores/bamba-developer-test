## Bamba Developer Test
## DEMO:
![Alt Text](resources\imgs\demo.gif)

### Preguntas a responder:

- Mejoras en 'La vida real':  
Cifrar token que generé para listar el booking.  
Agregar más películas, diferentes funciones.  
Crear una vista para consultar el booking.





- Cambios para mostrar diferentes películas:  
Crearía el modelo 'Película', haría haría una relación belongsTo hacia el modelo Booking.



- ¿Cómo evitar que dos usuarios agenden el mismo asiento en la misma sala para el mismo horario?  
Al momento de traer los asientos específicos de cada sala, consultaría los id´s de cada haciento agendado (booking). Después de compararlos, adjuntaría un estatus en en número de haciento de la sala, en la respueta del request.






