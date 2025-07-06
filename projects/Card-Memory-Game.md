# Juego de Memoria con Cartas  
**Nivel:** 2-Intermedio  
  
El juego de memoria con cartas es un juego en el que debes hacer clic en una carta para ver qué imagen hay debajo e intentar encontrar la imagen coincidente entre las demás cartas.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ver una cuadrícula con n x n cartas (`n` es un número entero). Todas las cartas están inicialmente boca abajo (estado `oculto`)  
-   [ ] El usuario puede hacer clic en un botón para comenzar el juego. Al hacer clic en este botón, comenzará un temporizador  
-   [ ] El usuario puede hacer clic en cualquier carta para revelar la imagen que está debajo (cambiar al estado `visible`). La imagen permanecerá visible hasta que el usuario haga clic en una segunda carta  
  
Cuando el usuario hace clic en la segunda carta:  
-   [ ] Si hay una coincidencia, las dos cartas serán eliminadas del juego (ya sea ocultándolas/eliminándolas o dejándolas en estado `visible`)  
-   [ ] Si no hay coincidencia, las dos cartas volverán a su estado original (`oculto`)  
-   [ ] Cuando se hayan encontrado todas las parejas, el usuario puede ver un cuadro de diálogo mostrando un mensaje de felicitaciones con un contador que muestra el tiempo que tomó completar el juego  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede elegir entre varios niveles de dificultad (Fácil, Medio, Difícil). Una mayor dificultad implica: disminuir el tiempo disponible para completar el juego y/o aumentar el número de cartas  
-   [ ] El usuario puede ver las estadísticas del juego (número de veces que ganó/perdió, mejor tiempo para cada nivel)  
  
## Enlaces y Recursos Útiles  
  
-   [Wikipedia](https://en.wikipedia.org/wiki/Concentration_(game))  
  
## Proyectos de Ejemplo  
  
-   [Flip - juego de memoria con cartas](https://codepen.io/zerospree/full/bNWbvW)  
-   [Juego de memoria](https://jdmedlock.github.io/memorygame/)  
-   [SMB3 Juego de memoria](https://codepen.io/hexagoncircle/full/OXBJxV)  
-   [BHMBS - Juego de memoria](https://barhouum7.github.io/JS-MemoryGame.github.io/)  