# Bit Masks Máscaras de Bits  
  
**Nivel:** 2-Intermedio  
  
Es difícil encontrar una aplicación que no dependa de algún tipo de lógica condicional para implementar su funcionalidad. Esto casi siempre se realiza mediante sentencias como:  
```javascript
if (processAccount === true) {
/* hacer algo */
}
```

Las sentencias if y switch funcionan bien para un número limitado de condicionales, pero ¿qué pasa si tu aplicación tuviera decenas o cientos de condicionales que evaluar? Por suerte, existe otra manera.  
  
El objetivo de la aplicación Máscaras de Bits es demostrar cómo utilizar máscaras de bits para evaluar secuencias largas de interruptores sin tener que depender de cadenas largas de sentencias condicionales.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ver una lista vertical de casillas de verificación (checkboxes) con las siguientes ciudades y sus zonas horarias:  
    - Moscú: GMT +3  
    - París: GMT +2  
    - Berlín: GMT +2  
    - Bruselas: GMT +2  
    - Ámsterdam: GMT +2  
    - Roma: GMT +2   
    - Londres: GMT +1  
    - Dublín: GMT +1  
    - Nueva York: GMT -4  
    - Washington, DC: GMT -4  
    - San Luis: GMT -5  
    - Los Ángeles: GMT -7  
    - Tokio: GMT +9  
    - Pekín: GMT +8  
    - Ciudad Ho Chi Minh: GMT +7  
    - Bombay: GMT +5  
-   [ ] El usuario puede ver una caja de búsqueda de GMT donde se puede ingresar un número entero representando un desfase horario de GMT y un botón ‘Encontrar Ciudades’.  
-   [ ] El usuario puede hacer clic en el botón ‘Encontrar Ciudades’ para mostrar los nombres de las ciudades en ese desfase horario de GMT en un área de resultados.  
  
### Notas para el Desarrollador  
  
Para este ejercicio, el desarrollador debe usar secuencias de 24 bits binarios, cada una correspondiente a una zona horaria de GMT desde +12 hasta -12 para mapear las ciudades a sus zonas horarias.  
  
Las búsquedas deben realizarse combinando una máscara de bits para la zona horaria deseada contra las secuencias de bits específicas de cada ciudad para identificar coincidencias. Determinar si una ciudad cumple con el criterio de búsqueda no debe apoyarse en una sentencia como:  
if (city[i].gmtOffset === searchOffset ) {
/* ¡Encontrado! */
}

En su lugar, debe basarse en una operación a nivel de bits.  
  
## Funcionalidades extra  
  
-   [ ] El usuario puede buscar ciudades que NO estén en la zona horaria GMT ingresada en la caja de búsqueda.  
-   [ ] El usuario puede ver un resumen del conteo de ciudades que cumplieron con el criterio de búsqueda.  
  
## Enlaces y recursos útiles  
  
- [Zonas Horarias del Mundo](https://greenwichmeantime.com/time-zone/definition/)  
- [Operadores Bit a Bit (MDN)](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Bitwise_Operators)  
  
## Proyectos de ejemplo  
  
[Operación Bitwise](https://codepen.io/Lunoware/pen/VBZgQd)  