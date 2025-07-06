# Recibos de Venta  
**Nivel:** 2-Intermedio  
  
En la [Primera App con Base de Datos](../1-Beginner/First-DB-App.md) pudiste aprender los conceptos básicos sobre cómo usar la base de datos IndexedDB que viene integrada en el navegador. En "Recibos de Venta" llevarás esto un paso más allá creando una aplicación que registre recibos de punto de venta, presumiblemente para conciliar posteriormente con el efectivo en la caja del establecimiento.  
  
El objetivo de Recibos de Venta es implementar la funcionalidad de punto de venta para un comerciante y registrar todas las ventas en una base de datos.  
  
### Requisitos y restricciones  
  
- El desarrollador debe implementar esta aplicación como una aplicación frontend que utilice la base de datos IndexedDB del navegador para registrar todos los recibos de venta.  
- El inventario de artículos disponibles para la venta puede implementarse como un arreglo de objetos en el código fuente de la aplicación. Cada artículo debe definirse con los siguientes atributos:  
    - Número de artículo (único)  
    - Descripción  
    - Precio unitario  
- El desarrollador debe utilizar sus habilidades de UI/UX para crear una ventana agradable y eficiente que facilite la compra de artículos y la visualización del historial de compras.  
- El caso principal de uso para una base de datos en el navegador es mantener información de estado que necesita persistir entre sesiones, o como un área de trabajo para datos temporales. Por ejemplo, datos recuperados de un servidor que deben ser reformateados o depurados antes de presentarse al usuario.  
- Es importante tener en cuenta que, dado que el entorno del navegador del lado del cliente no se puede asegurar, no se debe almacenar información confidencial o datos personales (PII) en una base de datos basada en el navegador.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ver un panel de compra que contiene botones para cada artículo, mostrando el número de artículo, la descripción y el precio unitario, así como botones de 'Limpiar' y 'Pagar'.  
-   [ ] El usuario puede hacer clic en un botón de artículo para realizar una compra.  
-   [ ] El usuario puede ver un campo que muestra el total de la venta, incrementando a medida que se seleccionan artículos.  
-   [ ] El usuario puede ver un panel de recibo mostrando la fecha y hora de la venta, así como todos los artículos seleccionados. Esto incluye número de artículo, descripción y precio unitario.  
-   [ ] El usuario puede hacer clic en el botón 'Limpiar' para borrar todas las compras en cualquier momento antes de pagar.  
-   [ ] El usuario puede hacer clic en el botón 'Pagar' para completar la compra de todos los artículos seleccionados. El monto final total se añadirá al final del panel de recibo y todos los artículos seleccionados se agregarán a la base de datos.  
-   [ ] El usuario puede ver el panel de recibo vacío después de que todos los artículos hayan sido agregados a la base de datos.  
-   [ ] El usuario puede ver un botón de 'Ventas del Día' y otro de 'Limpiar Todo' en la parte inferior de la ventana de la aplicación.  
-   [ ] El usuario puede hacer clic en el botón 'Ventas del Día' para mostrar todos los artículos comprados por todos los clientes en el panel de recibos, junto con el total de todos ellos.  
-   [ ] El usuario puede hacer clic en el botón 'Limpiar Todo' para limpiar el panel de recibos y borrar el registro de todas las compras de la base de datos.  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede ver una imagen en miniatura de los artículos en los botones de artículo.  
-   [ ] El usuario puede ver que el botón 'Limpiar' es reemplazado por los botones 'Borrar Último' y 'Cancelar Todo' debajo del panel de compras.  
-   [ ] El usuario puede hacer clic en el botón 'Borrar Último' para eliminar el último artículo seleccionado del panel de recibo. Esto tiene el efecto de deseleccionar ese artículo.  
-   [ ] El usuario puede hacer clic en el botón 'Cancelar Todo' para limpiar todas las compras realizadas antes de pagar.  
-   [ ] El usuario puede ver un campo de entrada en el panel de entrada donde puede escribir el nombre del cliente en el momento de la compra. El nombre del cliente se añadirá a todos los artículos comprados por ese cliente tanto en el panel de recibo como en las filas añadidas a la base de datos.  
  
## Enlaces y recursos útiles  
  
- [Conceptos de IndexedDB (MDN)](http://tinyw.in/7TIr)  
- [Usando IndexedDB (MDN)](http://tinyw.in/w6k0)  
- [API de IndexedDB (MDN)](http://tinyw.in/GqnF)  
- [Soporte de IndexedDB en los Navegadores](https://caniuse.com/#feat=indexeddb)  
  
## Proyectos de ejemplo  
  
- N/A  