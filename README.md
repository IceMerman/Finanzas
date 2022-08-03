# Finanzas
Implementación de administrador contable de finanzas en Django.

Este proyecto permite llevar un registro diario de movimientos financieros.

Utiliza como concepto fundamental "nodos", donde un nodo puede ser un bolsillo, una cuenta bancaria, e incluso una deuda a una entidad/persona.

# Caracteristicas

 - Registro de cada movimiento, indicando el "nodo" fuente y el "nodo" receptor.
 - Los registro almacenan información de categorías, etiquetas, y una dirección a un archivo de soporte subido por el usuario, ejemplo: facturas

# Carecateristicas futuras

 - Resumen de cada nodo por intervalos de tiempo definidos
 - Representación mediante grafo
 - Animación de los movimientos financieros entre grafos
 - Analiticas de movimientos financieros
 - Para tarjetas de crédito considerar tasas de interes y número de cuotas

# Diagrama Entidad-Eelacion (ER)

Diagrama entidad relación de aplicativo de finanzas

<img margin="auto" alt="Diagrama ER" src="https://i.imgur.com/3POnmHZ.png" />