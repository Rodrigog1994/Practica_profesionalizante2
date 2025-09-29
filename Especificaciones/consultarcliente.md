Caso de Uso: Consultar Cliente
Sección	Descripción
Actor principal	Usuario registrado
Precondición	El usuario debe estar logueado.
Requisitos	RF01
Normativa	1. El sistema muestra una ventana con una lista de clientes y diferentes opciones.
2. El usuario hace clic en la opción "consultar cliente".
3. El sistema abre una ventana con un formulario de consulta de cliente, donde puede buscar por cuit o razón social y visualizar los datos del cliente como razón social, cuit, domicilio, teléfono y mail.
4. El usuario ingresa el cuit o razón social y hace clic en "buscar".
  - 5.1: El sistema busca los datos del cliente en la base de datos y los devuelve en pantalla.
  - Alternativa 5.1: El sistema indica que no se encontraron resultados y muestra un mensaje de error: "Vuelve a ingresar los datos".
Postcondiciones
