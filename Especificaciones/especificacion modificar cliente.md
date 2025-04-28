# Caso de Uso: Modificar Cliente

| **Sección**          | **Descripción**                                                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------|
| **Actor Primario**   | Usuario Logueado                                                                                   |
| **Precondición**     | El usuario debe estar logueado.                                                                    |
| **Requerimientos**   | RF01                                                                                               |
| **Normativa**        | 1. El sistema muestra una ventana con una lista de clientes y diferentes opciones.<br>2. El usuario busca por razón social o por cuit, selecciona el cliente y hace click en la opción "modificar cliente".<br>3. El sistema despliega una ventana con los datos precargados del cliente, permitiendo modificarlos.<br>4. El usuario modifica los datos y hace click en "confirmar".<br>   - **5.1:** El sistema valida los datos y, en caso de estar correctos, confirma los cambios y guarda la información.<br>   - **Alternativo 5.1:** El sistema indica que los datos no son correctos y muestra un mensaje de error: "Vuelve a ingresar los datos". |
| **Postcondiciones**  | Cliente modificado.                                                                                |