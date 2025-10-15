# Caso de Uso: Modificar Cliente

## 1. Identificación
1.1. Actor primario: Usuario logueado  
1.2. Precondición: El usuario debe estar logueado.  
1.3. Requerimientos: RF01  
1.4. Postcondición: El cliente queda actualizado en la base de datos.

## 2. Flujo Normal
2.1. El sistema muestra una ventana con una lista de clientes y diferentes opciones.  
2.2. El usuario busca por Razón Social o CUIT, selecciona el cliente y  accede a  "Modificar Cliente".  
2.3. El sistema despliega una ventana con los datos precargados del cliente.  
2.4. El usuario modifica los datos y confirma.  
2.5. Los datos del cliente quedan guardados.

## 3. Flujos Alternativos
3.1.  Validación de Datos  
3.1.1. El sistema valida los datos ingresados en el formulario antes de guardar:  
- Verifica que Razón Social no esté vacía.  
- Verifica que el CUIT tenga el formato correcto (11 dígitos, sin letras).  
- Verifica que los campos obligatorios estén completos.  
- Opcional: verifica que no exista ya otro cliente con el mismo CUIT.  

3.1.2. Si los datos no son correctos:  
- El sistema muestra mensaje de error  en pantalla:  
  - "El campo Razón Social es obligatorio."  
  - "El CUIT ingresado no es válido. Debe tener 11 dígitos."  
  - "El correo electrónico no tiene un formato válido."  
- El usuario puede corregir los datos y volver a intentar la confirmación.
