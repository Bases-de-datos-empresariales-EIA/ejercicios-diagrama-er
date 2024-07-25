# Gestión de Restaurantes

#### Contexto del Negocio

Un restaurante necesita un sistema para gestionar sus productos, pedidos, mesas, y meseros. El objetivo es llevar un registro eficiente de los pedidos y su relación con los productos y las mesas.

### Descripción de los Elementos del Negocio

1. **Restaurante**:
   - **Descripción**: Los restaurantes que administran sus propios productos, mesas, meseros y clientes.
   - **Atributos Clave**: Nombre del restaurante, ubicación, productos, meseros, clientes, mesas.

2. **Mesa**:
   - **Descripción**: Las mesas disponibles en el restaurante donde los clientes pueden sentarse y realizar pedidos.
   - **Atributos Clave**: Número de mesa, capacidad, pedidos asociados, restaurante asociado.

3. **Mesero**:
   - **Descripción**: Los empleados que trabajan en el restaurante y toman los pedidos de los clientes.
   - **Atributos Clave**: Nombre, restaurante asociado, pedidos asociados.

4. **Pedido**:
   - **Descripción**: Los pedidos realizados por los clientes. Cada pedido puede contener múltiples ítems de productos.
   - **Atributos Clave**: Código del pedido, total, mesa asociada, mesero asociado, ítems de productos.

5. **Producto**:
   - **Descripción**: Los diferentes productos disponibles en el restaurante.
   - **Atributos Clave**: Nombre del producto, precio, descripción, restaurante asociado, ítems de pedidos.

6. **Ítem de Pedido**:
   - **Descripción**: Los detalles de los productos en un pedido específico, incluyendo la cantidad de cada producto pedido.
   - **Atributos Clave**: Cantidad, producto asociado, pedido asociado.

### Actividad del Taller

1. **Definición de Entidades y Atributos**:
   - Identificar y definir todas las entidades necesarias basadas en la descripción del negocio.
   - Definir los atributos clave para cada entidad.

2. **Definición de Relaciones**:
   - Determinar cómo se relacionan las entidades entre sí.
   - Definir el tipo de relación (uno a uno, uno a muchos, muchos a muchos) y las restricciones de integridad referencial.

3. **Construcción del Diagrama ERD**:
   - Usar una herramienta de modelado para construir el diagrama entidad-relación.
   - Asegurarse de que todas las entidades y relaciones estén claramente representadas y etiquetadas.
  

# Solución
[Diagrama ER](https://www.figma.com/board/v56o0K9xCsLGH3vjP0A5al/Sistema-de-restaurantes?node-id=0-1&t=g2X5IoLh1QK5xTaU-1)
