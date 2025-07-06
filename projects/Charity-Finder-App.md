# Buscador de Organizaciones Benéficas  
**Nivel:** 2-Intermedio  
  
Con la aplicación Buscador de Organizaciones Benéficas no solo mejorarás tus habilidades como desarrollador web, sino que también tendrás la oportunidad de ver cómo puedes aportar un bien al mundo. El objetivo de esta app es utilizar la API de organizaciones de [Global Giving](https://www.globalgiving.org/) para proporcionar a tus usuarios una lista de organizaciones benéficas globales que puedan buscar para encontrar aquella que coincida con sus intereses filantrópicos.  
  
### Restricciones  
  
- Dado que la aplicación pide al usuario elegir y contribuir a una causa benéfica, es importante que la presentación de la información sea clara y concisa.  
- Igualmente importante es que la UI/UX sea pulida y atractiva de usar.  
- Aunque esto es cierto para todas las apps, es aún más relevante aquí, ya que cada usuario que abandona el sitio representa la pérdida de una oportunidad de hacer el bien (ver ['¿Qué es la conversión en un sitio web?'](##useful-links-and-resources) abajo).  
  
## Historias de Usuario  
  
-   [ ] El usuario puede ver un encabezado de página que contiene el nombre de la aplicación.  
-   [ ] El usuario puede ver una vista general del propósito de la aplicación en formato de pantalla de bienvenida.  
-   [ ] El usuario puede ver un área de búsqueda que contiene un conjunto de campos desplegables que le permiten especificar criterios de búsqueda para organizaciones benéficas, incluyendo:  
    - Nombre de la organización  
    - País de origen de la organización  
    - Países a los que la organización sirve  
-   [ ] El usuario puede ver un botón de 'Buscar'  
-   [ ] El usuario puede hacer clic en el botón 'Buscar' para mostrar tarjetas de información de las organizaciones coincidentes en un área de resultados de búsqueda.  
-   [ ] El usuario puede ver tarjetas de información de organizaciones en los resultados de búsqueda que contienen:  
    - ID  
    - Nombre  
    - Dirección  
    - Logo  
-   [ ] El usuario puede hacer clic en el logo en la tarjeta de información de la organización para abrir una nueva ventana con la página de inicio de la organización.  
-   [ ] El usuario puede ver un pie de página con enlaces a tu cuenta de GitHub y tus redes sociales, incluyendo íconos de redes sociales (como el ícono de Twitter).  
  
## Funcionalidades Extra  
  
-   [ ] El usuario puede ver un desplegable para los temas en los que se centra la organización benéfica.  
-   [ ] El usuario puede seleccionar múltiples opciones en los campos desplegables de búsqueda.  
-   [ ] El usuario puede ver un enlace a proyectos (por ejemplo, 'PROYECTO') en la tarjeta de información de la organización.  
-   [ ] El usuario puede hacer clic en el enlace del proyecto para mostrar una página con información sobre el proyecto de Global Giving asociado a la organización.  
    Pista: revisa la estructura del JSON devuelto por la API para entender la relación entre proyectos y organizaciones.  
  
## Enlaces y Recursos Útiles  
  
- [¿Qué es la conversión en un sitio web?](https://www.marketing91.com/what-is-website-conversion/)  
- [Global Giving API](https://www.globalgiving.org/api/)  
- Ejemplo de XML de un proyecto devuelto por la API:  
  
```xml  
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<projects numberFound="26842">
    <hasNext>true</hasNext>
    <nextProjectId>367</nextProjectId>
    <project>
        <active>false</active>
        <activities>To fund the training of health professionals including nurses, psychologists, and social workers, and buy medicine and equipment.</activities>
        <additionalDocumentation>https://www.globalgiving.org/pfil/359/projdoc.doc</additionalDocumentation>
        <approvedDate>2004-06-01T12:43:27-04:00</approvedDate>
        <contactAddress>28 Pine Street</contactAddress>
        <contactCity>Mechanic Falls</contactCity>
        <contactCountry>United States</contactCountry>
        <contactPostal>04256</contactPostal>
        <contactState>Maine</contactState>
        <contactUrl>http://groups.yahoo.com/group/FOCUSonCambodia</contactUrl>
        <country>Cambodia</country>
        <funding>8239.33</funding>
        <goal>55000.00</goal>
        <id>359</id>
        <image id="0">
            <imagelink size="small">
                <url>https://www.globalgiving.org/pfil/359/pict_grid1.jpg</url>
            </imagelink>
            <imagelink size="thumbnail">
                <url>https://www.globalgiving.org/pfil/359/pict_thumbnail.jpg</url>
            </imagelink>
            <imagelink size="medium">
                <url>https://www.globalgiving.org/pfil/359/pict_med.jpg</url>
            </imagelink>
            <imagelink size="large">
                <url>https://www.globalgiving.org/pfil/359/pict_grid7.jpg</url>
            </imagelink>
            <imagelink size="extraLarge">
                <url>https://www.globalgiving.org/pfil/359/pict_large.jpg</url>
            </imagelink>
            <imagelink size="original">
                <url>https://www.globalgiving.org/pfil/359/pict_original.jpg</url>
            </imagelink>
            <title>Improving the Health of Children in Cambodia</title>
        </image>
        <imageGallerySize>1</imageGallerySize>
        <imageLink>https://www.globalgiving.org/pfil/359/pict.jpg</imageLink>
        <iso3166CountryCode>KH</iso3166CountryCode>
        <longTermImpact>This project will help improve the mental and physical health of orphaned children in Cambodia.  This project will also ensure the sustainability of the Nutrition Center in Child Mental Health Center.</longTermImpact>
        <need>Our beneficiaries will be orphaned children suffering from AIDS/HIV and other diseases and children with mental health problems whose parents do not know how to cope because they were deprived of family experiences by the forced separations of the Pol Pot regime. At the Nutrition Center in Phnom Penh, we will help urban orphans from brothels and hospitals that have abandoned them. At the Child Mental Health Center, we will help families, largely the working poor, from all over Cambodia.</need>
        <numberOfDonations>102</numberOfDonations>
        <organization>
            <activeProjects>0</activeProjects>
            <addressLine1>1062 Lewiston Road</addressLine1>
            <addressLine2></addressLine2>
            <bridgeId>5824171103</bridgeId>
            <city>New Gloucester</city>
            <countries>
                <country>
                    <iso3166CountryCode>KH</iso3166CountryCode>
                    <name>Cambodia</name>
                </country>
            </countries>
            <country>United States</country>
            <id>10</id>
            <iso3166CountryCode>US</iso3166CountryCode>
            <mission>The mission of FOCUS is to pursue humanitarian programs that include medical aid, school construction and supplies, distribution of rice and rice seeds, road improvements, agricultural improvements, fish farms, basic housing, hospital restoration, school scholarships, and loans for infrastructure improvements. We want to help disadvantaged youth and their families, if they have any, in a country where the infrastructure is still weak due to Khmer Rouge depredations.</mission>
            <name>Friends of Cambodia in the U.S.  (FOCUS)</name>
            <postal>4260</postal>
            <state>Maine</state>
            <themes>
                <theme>
                    <id>health</id>
                    <name>Health</name>
                </theme>
            </themes>
            <totalProjects>2</totalProjects>
            <url></url>
        </organization>
        <progressReportLink>https://www.globalgiving.org/projects/educating-children-of-cambodia/updates/</progressReportLink>
        <projectLink>https://www.globalgiving.org/projects/educating-children-of-cambodia/</projectLink>
        <region>Asia and Oceania</region>
        <remaining>46760.67</remaining>
        <status>funded</status>
        <summary>To help abandoned children, many afflicted with HIV/AIDS, and children with mental health problems. We want to address lack of food, medicine and staff training.</summary>
        <themeName>Health</themeName>
        <title>Improving the Health of Children in Cambodia</title>
        <type>project</type>
    </project>
</projects>
```
## Proyectos de Ejemplo

[Playing with card layout](https://codepen.io/bradjdouglas/pen/xOZJRz)