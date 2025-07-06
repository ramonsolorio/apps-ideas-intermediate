# Slackbot de Zonas Horarias – TZ  
**Nivel:** 2-Intermedio  
  
Los miembros de un equipo a menudo necesitan averiguar la zona horaria de los demás como primer paso para encontrar horarios para reuniones o sesiones de programación en pareja. Para facilitar esto, el bot de zona horaria para Slack acepta una lista de nombres de usuario de Slack y muestra la zona horaria de cada usuario en un formato apilado como el siguiente:  
  

```
      -12 -11 -10 -9 -8 -7 -6 -5 -4 -3 -2 -1 0 +1 +2 +3 +4 +5 +6 +7 +8 +9 +10 +11 +12 +13 +14
Fred                           X
Nisha                                                       X
Ming                                                              X
  .
  .
  .
```
  
Ten en cuenta que este formato se proporciona solo con fines descriptivos. Al implementarlo, se puede usar un formato más agradable y fácil de usar.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ingresar `/tz <nombre-usuario> <nombre-usuario>...<nombre-usuario>` para mostrar una representación tabular mostrando la zona horaria de cada usuario.  
-   [ ] El usuario puede ver la información mostrada utilizando colores alternos en las filas para mejorar la claridad y legibilidad.  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede ver la zona horaria de la persona mostrada junto a su nombre. Por ejemplo, 'IST' para la Hora Estándar de la India.  
  
## Enlaces y recursos útiles  
  
Más información sobre zonas horarias [aquí](https://www.timeanddate.com/time/current-number-time-zones.html)  
  
## Proyectos de ejemplo  
  
[Rápidamente determina en qué país y zona horaria están tus compañeros de trabajo esta semana usando esta herramienta](https://lifehacker.com/quickly-determine-what-country-and-time-zone-your-cowor-1833011887)  