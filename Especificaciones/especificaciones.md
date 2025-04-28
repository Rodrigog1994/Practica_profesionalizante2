# Caso de Uso: Consultar Cliente

| **Sección**          | **Descripción**                                                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------|
| **Actor Primario**   | Usuario Logueado                                                                                   |
| **Precondición**     | El usuario debe estar logueado.                                                                    |
| **Requerimientos**   | RF01                                                                                               |
| **Normativa**        | 1. El sistema muestra una ventana con una lista de clientes y diferentes opciones.<br>2. El usuario hace click en la opción "consultar cliente".<br>3. El sistema despliega una ventana con un formulario de consulta de cliente, donde puede buscar por cuit o razón social y visualizar los datos del cliente como razón social, cuit, domicilio, teléfono y mail.<br>4. El usuario ingresa el cuit o razón social y hace click en "buscar".<br>&nbsp;&nbsp;- **5.1:** El sistema busca los datos del cliente en la base de datos y los devuelve en pantalla.<br>&nbsp;&nbsp;- **Alternativo 5.1:** El sistema indica que no se encontraron resultados y muestra un mensaje de error: "Vuelve a ingresar los datos". |
| **Postcondiciones**  | Cliente consultado.                                                                                |