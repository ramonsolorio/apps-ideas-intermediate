# Arte con Hilos (StringArt)  
**Nivel:** 2-Intermedio  
  
El propósito de Arte con Hilos es brindar al desarrollador práctica en la creación de un gráfico animado sencillo, usar geometría en el algoritmo de animación, y crear algo visualmente agradable de observar.  
  
StringArt dibuja una sola línea multicolor que se mueve suavemente hasta que uno de sus extremos toca un lado de la ventana que la contiene. En el punto donde toca, se aplica un efecto de "rebote" para cambiar su dirección.  
  
Se crea un efecto de onda al conservar solo entre 10 y 20 imágenes de la línea a medida que se mueve. Las imágenes más antiguas se desvanecen progresivamente hasta desaparecer.  
  
No se permiten librerías de animación. Solo debes usar HTML/CSS/JavaScript puro (Vanilla).  
  
## Historias de Usuario  
  
-   [ ] Comenzar dibujando una línea multicolor en una posición aleatoria dentro de los límites de la ventana que la contiene.  
-   [ ] Cada 20ms, dibujar una nueva copia de la línea en una nueva posición basada en una trayectoria, es decir, la distancia incremental desde la línea anterior según los puntos extremos.  
-   [ ] Cuando cualquiera de los extremos de la línea toque el límite de la ventana contenedora, cambiar su dirección y alterar aleatoriamente su ángulo.  
-   [ ] Desvanecer progresivamente la intensidad de las líneas antiguas, de tal manera que solo las 10-20 líneas más recientes sean visibles para crear la sensación de movimiento o "onda".  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede especificar la longitud de la línea y su velocidad.  
-   [ ] El usuario puede especificar la cantidad de líneas dentro de la ventana, todas moviéndose en trayectorias y velocidades diferentes.  
  
## Enlaces y recursos útiles  
  
-   [Usando animaciones y transiciones multi-paso](https://css-tricks.com/using-multi-step-animations-transitions/)  
-   [Conceptos básicos de animación](https://www.khanacademy.org/computing/computer-programming/programming/animation-basics/a/what-are-animations)  
  
## Proyectos de ejemplo  
  
Este proyecto es muy similar, pero tiene una ventana de contención pequeña y es monocromática:    
[Daniel Cortes](https://codepen.io/dgca/pen/dpxreO)  