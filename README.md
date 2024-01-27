Stored Procedure: OrdenarTabla
Permite ordenar una tabla específica en base a un campo de ordenamiento y el tipo de orden (ascendente o descendente).

Parámetros de Entrada:

nombre_tabla (VARCHAR(255)): Nombre de la tabla que se desea ordenar.
campo_ordenamiento (VARCHAR(255)): Nombre del campo por el cual se va a ordenar la tabla.
orden (VARCHAR(10)): Tipo de orden, puede ser 'ASC' (ascendente) o 'DESC' (descendente).
Objetivo/Beneficio:
Facilita la obtención de datos ordenados según los criterios definidos, brindando flexibilidad en la presentación de la información.

Tablas Utilizadas:
No interactúa directamente con tablas, es más un facilitador para la presentación de datos ordenados.

Stored Procedure: GestionarRegistros
Realizar dos acciones en una tabla específica: insertar un nuevo registro o eliminar un registro existente.

Parámetros de Entrada:

nombre_tabla (VARCHAR(255)): Nombre de la tabla en la que se realizará la acción.
accion (INT): Tipo de acción a realizar (1 para inserción, 2 para eliminación).
valores (TEXT): Valores a insertar en caso de acción de inserción o ID del registro a eliminar en caso de acción de eliminación.
Objetivo/Beneficio:
Proporciona una interfaz estandarizada para realizar operaciones de inserción y eliminación en diferentes tablas del proyecto.

Tablas Utilizadas:
Interactúa directamente con la tabla especificada en nombre_tabla.
