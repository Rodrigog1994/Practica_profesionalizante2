# Caso de Uso: Agregar Cliente

## Actor Primario
Usuario

## Precondición
El usuario debe estar logueado.

## Requerimientos
- RF01

## Flujo Normal
1. El sistema muestra una ventana con un listado de clientes y diferentes opciones.
2. El usuario hace clic en la opción **"Agregar Cliente"**.
3. El sistema despliega una ventana con un formulario de alta de cliente.
4. El usuario completa los datos del cliente:
   - Nombre y Apellido
   - Dirección
   - Teléfono
   - Correo Electrónico
   - Razón Social
   - CUIT
   - Domicilio Tributario y Mail
5. El usuario hace clic en **"Guardar"**.
6. El cliente se guarda en la base de datos.

## Flujo Alternativo
- **3-1. Validación de Datos:**  
  El sistema valida los datos y si encuentra información errónea o incompleta (campos obligatorios, tipos de datos, longitud), informa al usuario y no permite avanzar hasta que se corrijan.

## Postcondiciones
- El cliente queda registrado en la base de datos.
