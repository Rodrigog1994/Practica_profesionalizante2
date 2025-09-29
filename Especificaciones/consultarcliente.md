# Caso de Uso: Consultar Cliente

## Actor Primario
Usuario registrado

## Precondición
El usuario debe estar logueado.

## Requerimientos
- RF01

## Flujo Normal
1. El sistema muestra una ventana con una lista de clientes y diferentes opciones.
2. El usuario hace clic en la opción **"Consultar Cliente"**.
3. El sistema abre una ventana con un formulario de consulta de cliente, donde puede buscar por CUIT o Razón Social y visualizar los datos del cliente:
   - Razón Social  
   - CUIT  
   - Domicilio  
   - Teléfono  
   - Mail  
4. El usuario ingresa el CUIT o Razón Social y hace clic en **"Buscar"**.
5. El sistema busca los datos del cliente en la base de datos y los devuelve en pantalla.

## Flujo Alternativo
- **5-A. Cliente no encontrado:**  
  El sistema indica que no se encontraron resultados y muestra un mensaje de error:  
  *"Vuelve a ingresar los datos"*.

## Postcondiciones
- El usuario obtiene la información del cliente o recibe un mensaje de error en caso de no hallarlo.
