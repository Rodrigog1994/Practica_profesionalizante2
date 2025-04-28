# Caso de Uso: Agregar Cliente

**Actor Primario:** Usuario

**Precondición:** Usuario Logueado

**Requerimientos:** RF01

**Normal**

1. El sistema muestra una ventana con un listado de clientes y diferentes opciones.

2. El usuario hace clic en la opción "Agregar Cliente".

3. El sistema despliega una ventana con un formulario de alta de cliente.

4. El usuario completa los datos del cliente:
   - Nombre y Apellido
   - Dirección
   - Teléfono
   - Correo Electrónico
   - Razón Social
   - CUIT
   - Domicilio Tributario y Mail

5. El usuario hace clic en "Guardar".

**Flujo Alternativo**

3-1. El sistema valida los datos y:
   - Si encuentra datos erróneos o incompletos (campos obligatorios, tipos de datos, longitud), informa al usuario y no permite avanzar hasta que se corrijan.

**Postcondiciones:** Un nuevo usuario ha sido agregado.