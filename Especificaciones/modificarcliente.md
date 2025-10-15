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
  1. El sistema valida los datos ingresados en el formulario antes de guardar:  
     - Verifica que **Razón Social** no esté vacía.  
     - Verifica que el **CUIT** tenga el formato correcto (11 dígitos, sin letras).  
     - Verifica que los campos obligatorios estén completos.  
     - Opcional: verifica que no exista ya otro cliente con el mismo CUIT.  

    

  3. **Si los datos no son correctos**:  
     - El sistema muestra mensaje de error:  
       - "El campo Razón Social es obligatorio."  
       - "El CUIT ingresado no es válido. Debe tener 11 dígitos."  
       - "El correo electrónico no tiene un formato válido."  
     - El usuario puede corregir los datos y volver a intentar la confirmación sin perder la información previamente cargada.

## Postcondiciones
- El cliente queda actualizado en la base de datos.

