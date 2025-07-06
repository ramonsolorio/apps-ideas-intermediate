# Directorio de Podcasts  
**Nivel:** 2-Intermedio  
  
En la aplicación [GitHub Status](../1-Beginner/GitHub-Status-App.md) aprendiste cómo usar el paquete Request para extraer información de una página web. El Directorio de Podcasts continúa este proceso y te presenta otro paquete para web scraping - [Puppeteer](https://github.com/GoogleChrome/puppeteer).  
  
Aunque Request es un paquete útil, no está diseñado específicamente para web scraping como lo está Puppeteer. A medida que adquieras experiencia con web scraping, descubrirás que existen sitios web y aplicaciones donde el scraping se facilita usando una herramienta como Puppeteer que está construida para este propósito.  
  
Es importante tener en cuenta que, aunque el web scraping es útil en ciertas ocasiones, el uso de una API o de una fuente de datos como un archivo o una base de datos siempre es preferible a extraer información directamente desde una página. La razón es que incluso cambios menores en el estilo de la página pueden hacer que tu scraper deje de funcionar. Por ejemplo, un cambio en el nombre de una clase CSS de la que depende tu lógica de scraping.  
  
El objetivo de la aplicación Directorio de Podcasts es obtener los episodios más recientes de los podcasts [Javascript Jabber](https://www.podbean.com/podcast-detail/d4un8-57595/JavaScript-Jabber-Podcast) y [Techpoint Charlie](https://www.podbean.com/podcast-detail/k76vd-8adc7/Techpoint-Charlie-Podcast) de [Podbean](https://www.podbean.com), y crear una nueva página que muestre una lista combinada de episodios, ordenados por fecha de emisión.  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ver una tabla de episodios de podcast.  
-   [ ] El usuario puede ver filas en esta tabla que muestran un icono de episodio (clickeable), el título del episodio y la fecha de emisión original.  
-   [ ] El usuario puede desplazarse por la lista.  
-   [ ] El usuario puede hacer clic en el icono del episodio para acceder a la página de ese episodio en el sitio web de Podbean.  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede ver filas en la tabla de episodios con colores de fondo alternos.  
-   [ ] El usuario puede ver un resumen sobre la tabla de episodios que muestre el número de episodios por cada podcast.  
-   [ ] El usuario puede ver una casilla de verificación junto a cada nombre de podcast en el resumen sobre la tabla de episodios.  
-   [ ] El usuario puede hacer clic en el botón de opción junto al nombre del podcast para incluir episodios de ese podcast en la tabla de episodios.  
  
## Enlaces y recursos útiles  
  
- [Puppeteer](https://github.com/GoogleChrome/puppeteer)  
- [Web Scraping con un Navegador Headless: tutorial de Puppeteer (en inglés)](https://www.toptal.com/puppeteer/headless-browser-puppeteer-tutorial)  
- [querySelectorAll](https://developer.mozilla.org/en-US/docs/Web/API/ParentNode/querySelectorAll)  
  
### ¡Sugerencia!  
Puedes usar el siguiente código para ayudarte a empezar con este proyecto. Puedes ejecutarlo usando el comando de la línea de comandos `node puptest`.  
  
```js  
// puptest.js  
const puppeteer = require('puppeteer');  
const run = async () => {  
  return new Promise(async (resolve, reject) => {  
    try {  
      const browser = await puppeteer.launch();  
      const page = await browser.newPage();  
      await page.goto("https://www.podbean.com/podcast-detail/d4un8-57595/JavaScript-Jabber-Podcast");  
      let episodeLinks = await page.evaluate(() => {  
        return Array.from(document.querySelectorAll('a.title')).map((item) => ({  
          url:  item.getAttribute('href'),  
          text: item.innerText  
        })  
        );  
      });  
      browser.close();  
      return resolve(episodeLinks);  
    } catch (e) {  
      return reject(e);  
    }  
  })  
}  
run().then(console.log).catch(console.error);  
```

- Cuando hayas completado este proyecto, revisa el proyecto avanzado [Mi Biblioteca de Podcasts](../3-Advanced/MyPodcast-Library-app.md)  
  
## Proyectos de ejemplo  
  
N/A 