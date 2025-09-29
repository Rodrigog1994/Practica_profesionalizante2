# Caso de Uso: Modificar Cliente

## Actor Primario
Usuario logueado

## Precondición
El usuario debe estar logueado.

## Requerimientos
- RF01

## Flujo Normal
1. El sistema muestra una ventana con una lista de clientes y diferentes opciones.
2. El usuario busca por Razón Social o CUIT, selecciona el cliente y hace clic en la opción **"Modificar Cliente"**.
3. El sistema despliega una ventana con los datos precargados del cliente, permitiendo modificarlos.
4. El usuario modifica los datos y hace clic en **"Confirmar"**.
5. Los datos del cliente quedan modificados en la base de datos.

## Flujo Alternativo
- **5-A. Validación de Datos:**  
  El sistema valida los datos.  
  - Si son correctos, confirma y guarda la información.  
  - Si no son correctos, muestra un mensaje de error:  
    *"Vuelve a ingresar los datos"*.

## Postcondiciones
- El cliente queda actualizado en la base de datos.
