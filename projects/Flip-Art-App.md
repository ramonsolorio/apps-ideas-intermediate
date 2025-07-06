# Flip Art  
**Nivel:** 2-Intermedio  
  
Muchos desarrolladores han descubierto que añadir animaciones a una aplicación es una técnica útil que añade impacto a la interfaz de usuario, la hace más atractiva para sus usuarios y ayuda a explicar temas complejos. Pero, como desarrollador, ¿cómo se crean estas animaciones y cómo saber qué imágenes generan animaciones efectivas?  
El objetivo de la app Flip Art es abordar ambas necesidades proporcionando una forma sencilla de recolectar y organizar un conjunto de imágenes en una secuencia animada que pueda reproducirse y ajustarse para lograr el impacto y efecto deseados.  
  
### Requisitos y restricciones  
  
Los desarrolladores no deben depender de librerías de animación o de gráficos para implementar esta app. En su lugar, intenta usar Javascript puro, CSS y HTML.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ver los siguientes componentes principales en la ventana de la app:  
    - Panel de configuración que contiene los elementos para personalizar el proceso de animación.  
    - Botones de operación.  
    - Panel de visualización donde se presentarán las animaciones.  
  
### Panel de configuración  
  
-   [ ] El usuario puede ver ocho miniaturas que contendrán fotogramas individuales de la animación.  
-   [ ] El usuario puede ver un botón debajo de cada miniatura: ‘+’  
-   [ ] El usuario puede hacer clic en el botón ‘+’ para añadir una nueva imagen a una miniatura vacía.  
-   [ ] El usuario puede ver un diálogo para abrir archivos al hacer clic en el botón ‘+’ para permitir que se cargue una imagen `.jpg` en la miniatura.  
-   [ ] El usuario puede ver que la etiqueta del botón ‘+’ cambia a ‘-’ después de que una miniatura está cargada.  
-   [ ] El usuario puede hacer clic en el botón ‘-’ para eliminar o reemplazar una miniatura.  
-   [ ] El usuario puede ver un control deslizante de 'Velocidad de transición'.  
-   [ ] El usuario puede ajustar el control deslizante de 'Velocidad de transición' de lento a rápido para ajustar el tiempo de transición entre las miniaturas en la Animación.  
  
### Botones de operación  
  
-   [ ] El usuario puede ver dos botones: 'Limpiar configuración' e 'Iniciar animación'  
-   [ ] El usuario puede ver el botón 'Iniciar animación' deshabilitado hasta que al menos se haya añadido una miniatura mediante el Panel de configuración.  
-   [ ] El usuario puede hacer clic en el botón 'Limpiar configuración' para borrar todas las miniaturas del panel de configuración.  
-   [ ] El usuario puede hacer clic en el botón 'Iniciar animación' para comenzar el panel de visualización de la animación.  
-   [ ] El usuario puede ver que la etiqueta del botón 'Iniciar animación' cambia a 'Detener animación' una vez que la animación ha comenzado.  
-   [ ] El usuario puede hacer clic en el botón 'Detener animación' para detener la animación en el panel de visualización.  
-   [ ] El usuario puede ver que la etiqueta del botón 'Detener animación' cambia nuevamente a 'Iniciar animación' cuando la animación ha sido detenida.  
  
### Panel de visualización de la animación  
  
-   [ ] El usuario puede ver las miniaturas añadidas en el Panel de configuración mostradas cuando se hace clic en el botón 'Iniciar animación'.  
-   [ ] El usuario puede ver que las miniaturas transicionan de una a otra a la velocidad definida por el control deslizante de 'Velocidad de transición'.  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede ver que el borde alrededor de la miniatura en el Panel de configuración se resalta cuando esa miniatura se muestra en el panel de visualización.  
-   [ ] El usuario puede añadir dinámicamente cualquier número de miniaturas en lugar de estar limitado solo a ocho.  
-   [ ] El usuario puede escuchar sonidos únicos asociados con la modificación de miniaturas en el Panel de configuración.  
-   [ ] El usuario puede ver un desplegable de tipo de transición en el Panel de configuración para definir el efecto de transición entre las miniaturas en el panel de visualización: ease, ease-in, ease-out, ease-in-out.  
-   [ ] El usuario puede arrastrar y soltar miniaturas para reordenarlas.  
-   [ ] El usuario puede guardar la animación como un archivo `.gif`.  
  
## Enlaces y recursos útiles  
  
- [Cómo hacer una animación tipo flip book](https://www.youtube.com/watch?v=Njl-uqnmBGA)  
- [Animación en CSS (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/animation)  
- [Usando transiciones CSS (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)  
- [Transición CSS (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)  
  
## Proyectos de ejemplo  
  
[FlipAnim](http://flipanim.com/)  