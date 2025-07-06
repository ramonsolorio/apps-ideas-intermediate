# Generador de Credenciales con Código QR  
**Nivel:** 2-Intermedio  
  
En algún momento de tu carrera, probablemente te verás involucrado en la coordinación de un evento patrocinado por la empresa o de un Meetup técnico local. Es común que en este tipo de reuniones los asistentes quieran intercambiar información de contacto entre ellos.  
  
¿Pero cómo hacerlo? Los asistentes pueden intercambiar tarjetas de presentación o anotar el correo electrónico o nombre de usuario en redes sociales, pero eso puede ser lento y propenso a errores. ¿No sería mejor poder escanear las credenciales de los demás para captar esta información rápidamente y de manera más confiable?  
  
Si respondiste "¡Sí!" a esta pregunta, entonces el Generador de Credenciales con Código QR es una app que te interesará crear. El objetivo de esta aplicación es recopilar el nombre, correo electrónico, y los nombres de cuenta de Twitter y GitHub de un asistente, y luego imprimir una credencial con un código QR que pueda ser escaneado con un smartphone.  
  
### Requisitos y restricciones  
  
- Para esta aplicación, querrás usar el paquete NPM [QRCode Generator](https://www.npmjs.com/package/qrcode-generator) para codificar la información recogida del asistente en un código QR.  
- Para probar tu implementación, necesitarás descargar un lector de códigos QR en tu smartphone o tablet. Hay muchos lectores de este tipo gratuitos. Consulta la tienda de aplicaciones de tu dispositivo para encontrar el que más se adapte a tus necesidades.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ver un panel de entrada con campos para el nombre del asistente, dirección de correo electrónico, nombre de usuario de Twitter, nombre de usuario de GitHub, y los botones 'Cancelar' y 'Crear'.  
-   [ ] El usuario puede introducir datos en estos campos. El nombre y el correo electrónico del asistente son obligatorios, pero los nombres de cuenta de Twitter y GitHub son opcionales.  
-   [ ] El usuario puede hacer clic en el botón 'Cancelar' para limpiar todos los campos de entrada, así como el panel de la credencial (ver abajo) si ya ha sido creada.  
-   [ ] El usuario puede hacer clic en el botón 'Crear' para generar una imagen con la credencial del asistente.  
-   [ ] El usuario puede ver un mensaje de error si se cumple alguna de las siguientes condiciones:  
    - Los campos obligatorios están vacíos.  
    - No se ha ingresado un nombre y apellido.  
    - El campo de correo electrónico no tiene un formato válido.  
    - El nombre de usuario de Twitter no comienza con '@'.  
-   [ ] El usuario puede ver en pantalla un panel con la credencial que contiene esta información, además de un código QR que codifica dicha información.  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede ver un botón 'Imprimir' debajo del panel de la credencial.  
-   [ ] El botón 'Imprimir' solo está habilitado después de que los campos se validan y la credencial se muestra.  
-   [ ] El usuario puede corregir los campos de entrada y hacer clic en 'Crear' para actualizar la credencial.  
-   [ ] El usuario puede hacer clic en el botón 'Imprimir' para reproducir la credencial en una etiqueta o papel impreso.  
-   [ ] El símbolo '@' se añade automáticamente al nombre de usuario de Twitter para que no deba escribirse manualmente.  
  
## Enlaces y recursos útiles  
  
- [Código QR (Wikipedia)](https://es.wikipedia.org/wiki/Código_QR)  
- [QRCode Generator](https://www.npmjs.com/package/qrcode-generator)  
  
## Proyectos de ejemplo  
  
[Generador de QRCode](https://kazuhikoarase.github.io/qrcode-generator/js/demo/)  