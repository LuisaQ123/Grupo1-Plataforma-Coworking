
=======
**RF-03 Cancelación de Reserva**

**HU-03 – Cancelar Reserva**

Como usuario registrado
quiero cancelar una reserva existente
para liberar la sala reservada

**Criterios de Aceptación**

   • Solo puede cancelar sus propias reservas.
   
   • Si cancela con menos de 2 horas de anticipación, se aplica penalización.
   
   • El sistema debe actualizar la disponibilidad.
   
   • Debe mostrarse mensaje de cancelación exitosa.

## RNF

### RNF-01 Seguridad:
El sistema debe almacenar las contraseñas cifradas.

### RNF-02 Disponibilidad:
El sistema debe estar disponible al menos el 95% del tiempo mensual.

**Tabla de Trazabilidad:**

| HU    | RF                         | Caso de prueba                                                                                                                                         |    Estado        |
|-------|--------------------------- |--------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| HU-01 |RF-01 Registro de Usuario   | Verificar que el usuario pueda registrarse con correo válido, contraseña ≥ 8 caracteres, correo no registrado y que se muestre mensaje de éxito        |   Pendiente     |
| HU-02 |RF-02 Reserva de Sala       | Verificar que un usuario autenticado pueda reservar una sala disponible, que no permita horarios ocupados, muestre el costo y genere confirmació       |   Pendiente      |
| HU-03 |RF-03 Cancelación de Reserva| Verificar que el usuario pueda cancelar solo sus reservas, aplicar penalización si es menor a 2 horas y actualizar disponibilidad con mensaje de éxito |   Pendiente      |

