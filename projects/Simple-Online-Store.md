# Tienda Online Simple  
**Nivel:** 2-Intermedio  
  
En el proyecto [Página de Aterrizaje de Producto](../1-Beginner/Product-Landing-Page.md) creaste una página de aterrizaje para ofrecer a tus usuarios información sobre un producto y así, con suerte, aumentar la tasa de conversión de tu sitio.  
  
El objetivo de la Tienda Online Simple es ofrecer a tus usuarios la posibilidad de seleccionar un producto para comprar, ver la información de la compra, añadirlo a un carrito de compras en línea, y finalmente, comprar los productos del carrito.  
  
### Restricciones  
  
- En un inicio, puedes implementar tu inventario de productos como un arreglo de objetos Javascript si desarrollas en Javascript. Para otros lenguajes, siéntete libre de elegir la solución en memoria que prefieras.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede hacer clic en un botón `Ver Productos` en la Página de Aterrizaje para mostrar la Página de Productos.  
-   [ ] El usuario puede ver una tarjeta para cada producto en la Página de Productos, que muestre la miniatura, nombre, precio, una descripción corta y un botón `Seleccionar`.  
-   [ ] El usuario puede ver una página de Detalles del Producto cuando hace clic en el botón `Seleccionar`, la cual muestra la misma información de la tarjeta del producto, pero también un id único, una descripción larga, botón `Agregar al Carrito` y un botón `Ver Más Productos`.  
-   [ ] El usuario puede ver un mensaje de confirmación cuando el producto se ha añadido al carrito de compras.  
-   [ ] El usuario puede hacer clic en el botón `Ver Más Productos` para volver a la Página de Productos.  
-   [ ] El usuario puede ver un botón de `Carrito de Compras` tanto en la Página de Aterrizaje como en la de Productos. Sugerencia: una barra superior podría ser una buena ubicación común para este botón.  
-   [ ] El usuario puede hacer clic en el botón `Carrito de Compras` para mostrar la página del Carrito de Compras, que contiene el id, nombre, precio y un campo para la cantidad ordenada por cada producto añadido previamente al carrito.  
-   [ ] El usuario puede ver el monto total de la compra en la página del Carrito de Compras, calculado como la suma de las cantidades multiplicadas por el precio unitario de cada producto ordenado.  
-   [ ] El usuario puede ajustar la cantidad ordenada de cualquier producto para actualizar el monto total de la compra.  
-   [ ] El usuario puede hacer clic en un botón `Realizar Pedido` en la página del Carrito de Compras para completar la orden. El usuario verá un número de confirmación cuando la orden haya sido emitida.  
-   [ ] El usuario puede hacer clic en un botón `Cancelar Pedido` en la página del Carrito de Compras para cancelar la orden. El usuario verá las cantidades y el monto total de la compra restablecidos a cero.  
-   [ ] El usuario puede hacer clic en un botón `Ver Más Productos` en la página del Carrito de Compras para volver a la Página de Productos. Si la orden aún no se ha realizado, esto no borra los productos ya añadidos al carrito.  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede ver un mensaje de error si la cantidad ordenada excede la cantidad "en existencia" del producto.  
-   [ ] El usuario puede especificar una dirección de facturación y otra de envío al colocar la orden desde la página del Carrito de Compras.  
-   [ ] El usuario puede ver los gastos de envío sumados al total de la compra.  
-   [ ] El usuario puede ver los impuestos sobre la venta sumados al total de la compra.  
-   [ ] El desarrollador implementará el inventario de productos en un archivo externo o una base de datos.  
  
## Enlaces y recursos útiles  
  
Hay muchísimas páginas de sitios eCommerce por ahí. Puedes usar [Dribbble](https://www.dribbble.com) y [Behance](https://www.behance.net) para inspirarte.  
  
## Proyectos de ejemplo  
  
-   [Animaciones para eCommerce](https://codepen.io/RSH87/pen/RagqEv)  