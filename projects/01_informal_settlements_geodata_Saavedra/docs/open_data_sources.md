# Fuentes de Datos Abiertos para la Plataforma de Gestión de Asentamientos Informales

La siguiente tabla presenta una compilación de fuentes de datos abiertos relevantes para la implementación de una base de datos PostgreSQL enfocada en asentamientos informales. Estas fuentes permitirán mapear riesgos, gestionar subsidios cruzados y generar reportes para tomadores de decisiones en el contexto de asentamientos informales.

| Ciudad/Región | Fuente de Datos | URL de Acceso | Tipo de Datos | Categoría | Frecuencia de Actualización | Formato |
|---------------|-----------------|---------------|--------------|-----------|----------------------------|---------|
| Bogotá, Colombia | Secretaría Distrital del Hábitat | https://www.habitatbogota.gov.co/datos-abiertos | Información sobre asentamientos informales, subsidios de vivienda, legalización urbanística y ocupación horizontal | Vivienda, Desarrollo Urbano | Semestral | CSV, JSON |
| América Latina y el Caribe | BID - Banco Interamericano de Desarrollo | https://publications.iadb.org/es/datos-abiertos | Estadísticas sobre asentamientos precarios, indicadores de infraestructura básica, datos demográficos de zonas informales | Vivienda, Desarrollo Social | Anual | CSV, PDF |
| México | INEGI - Instituto Nacional de Estadística y Geografía | https://www.inegi.org.mx/datos/default.html | Censos de población, ubicación de asentamientos irregulares, indicadores socioeconómicos por manzana | Demografía, Vivienda | Quinquenal (censos) | CSV, Shapefile |
| Brasil | IBGE - Instituto Brasileiro de Geografia e Estatística | https://www.ibge.gov.br/geociencias/organizacao-do-territorio/tipologias-do-territorio/15788-aglomerados-subnormais.html | Datos completos sobre aglomerados subnormales (favelas), censos de población, acceso a servicios | Vivienda, Desarrollo Urbano | Decenal (censos) | CSV, Shapefile |
| Global | UN-Habitat - Urban Data | https://data.unhabitat.org/ | Indicadores urbanos globales, porcentaje de población en asentamientos precarios, ODS relacionados con vivienda | Vivienda, Desarrollo Urbano | Anual | CSV, JSON |
| Medellín, Colombia | MEData - Portal de Datos Abiertos | https://medata.gov.co/dataset/asentamientos-informales | Ubicación georreferenciada y caracterización de asentamientos informales, mapeo de riesgos ambientales | Vivienda, Riesgos | Trimestral | CSV, JSON, Shapefile |
| Chile | MINVU - Catastro Nacional de Campamentos | https://www.minvu.gob.cl/catastro-de-campamentos/ | Catastro detallado de campamentos, número de familias, acceso a servicios básicos, condiciones sanitarias | Vivienda, Servicios Básicos | Anual | Excel, Shapefile |
| Argentina | RENABAP - Registro Nacional de Barrios Populares | https://datos.gob.ar/dataset/desarrollo-social-registro-nacional-barrios-populares | Localización georreferenciada de barrios populares, acceso a servicios, cantidad de familias, tenencia de tierra | Vivienda, Servicios Básicos | Anual | CSV, Shapefile |
| Perú | INEI - Sistema de Información Geográfica | http://sige.inei.gob.pe/sige/ | Mapas de asentamientos humanos, indicadores socioeconómicos por manzanas, acceso a servicios básicos | Desarrollo Urbano, Economía | Anual | Shapefile, WMS |
| Global | OpenStreetMap - Humanitarian Data | https://data.humdata.org/organization/hot | Edificaciones en asentamientos informales mapeadas de forma colaborativa, infraestructura comunitaria | Infraestructura, Vivienda | Continua | GeoJSON, Shapefile |
| Río de Janeiro, Brasil | Data Rio - Portal de Datos Abiertos | https://www.data.rio/datasets?category=Habitação | Mapeo detallado de favelas, programas de vivienda social, zonas de riesgo geológico e inundaciones | Vivienda, Riesgos | Trimestral | CSV, JSON, Shapefile |
| Colombia | DANE - Geoportal | https://geoportal.dane.gov.co/ | Datos censales, estratificación socioeconómica, déficit habitacional, información catastral | Demografía, Vivienda | Quinquenal (censos) | Shapefile, GeoJSON |
| São Paulo, Brasil | GeoSampa - Portal de Datos Geográficos | http://geosampa.prefeitura.sp.gov.br/ | Mapeo de favelas, zonificación urbana, áreas de riesgo, redes de servicios públicos | Vivienda, Riesgos | Semestral | Shapefile, KML |
| Colombia | Portal de Datos Abiertos Nacional | https://www.datos.gov.co/browse?category=Vivienda | Datos sobre titulación de predios, programas de mejoramiento de vivienda, subsidios habitacionales | Vivienda, Desarrollo Social | Mensual | CSV, JSON, XML |
| Ecuador | MIDUVI - Ministerio de Desarrollo Urbano y Vivienda | https://www.habitatyvivienda.gob.ec/transparencia/ | Registro de asentamientos informales, programas de vivienda social, zonas de riesgo | Vivienda, Servicios Básicos | Anual | Excel, PDF |

## Consideraciones sobre los datos

Las fuentes presentadas ofrecen información valiosa para la implementación de la Plataforma de Gestión de Asentamientos Informales, sin embargo, existen desafíos importantes en la recolección de datos en estas áreas que deben considerarse:

- Los métodos tradicionales de recolección de datos en áreas informales son costosos en términos de tiempo y dinero, lo que puede afectar la calidad y actualización de algunas fuentes[1].
- La propia morfología de los asentamientos informales es altamente dinámica, lo que puede hacer que los datos se desactualicen rápidamente[1].
- Existen diferentes definiciones de "asentamiento informal" entre países, lo que puede dificultar análisis comparativos a nivel regional[1].
- La falta de datos de calidad tiene incidencia directa en todo el ciclo de políticas públicas, desde el diagnóstico hasta la evaluación[1].

La estrategia de datos abiertos, como la implementada por la Secretaría Distrital del Hábitat en Bogotá, representa un paso importante para mejorar la disponibilidad de información sobre ocupación horizontal y asentamientos informales[2].

Citations:
[1] https://publications.iadb.org/publications/spanish/document/Informando-lo-informal-estrategias-para-generar-informacion-en-asentamientos-precarios.pdf
[2] https://www.habitatbogota.gov.co/sites/default/files/multimedia_case/2022-08/Seguimiento%20estrategia%20datos%20abiertos%20I%20sem%202022.pdf
[3] https://infocdmx.org.mx/index.php/2-boletines/8705-resuelve-info-cdmx-a-favor-de-transparentar-informacion-sobre-asentamientos-humanos-irregulares-en-xochimilco.html
[4] https://onu-habitat.org/index.php/hacer-de-los-asentamientos-informales-parte-de-la-ciudad
[5] http://www.ideca.gov.co/recursos/mapas/ocupacion-ilegal-bogota-dc-ano-2020
[6] http://iilegislativas.congresocdmx.gob.mx/wp-content/uploads/2023/07/Asentamientos-Irregulares.pdf
[7] https://blogs.iadb.org/ciudades-sostenibles/es/falta-datos-barrios-informales-profundiza-inequidad/
[8] https://www.sdp.gov.co/gestion-territorial/legalizacion-y-mejoramiento-integral-de-barrios/consulta-de-desarrollos-informales
[9] https://eljuegodelacorte.nexos.com.mx/techo-mexico-vs-inegi-los-asentamientos-informales-a-escena/
[10] https://noesis.uis.edu.co/bitstreams/eef112fe-ac16-487d-b406-d6a49562d246/download
[11] https://www.redalyc.org/journal/357/35746656004/html/
[12] https://www.redalyc.org/journal/1931/193173030044/html/
[13] https://datosabiertos.bogota.gov.co/dataset?organization=secretaria-distrital-del-habitat
[14] https://www.datos.gov.co/Agricultura-y-Desarrollo-Rural/-ndice-de-informalidad-municipal-Diciembre-2019/nr49-4vwb
[15] https://www.sdp.gov.co/sites/default/files/07._produccion_de_espacio_edificado.pdf
[16] https://repositorio.unal.edu.co/bitstream/handle/unal/2440/43746388_2009.pdf?sequence=1
[17] https://manglar.uninorte.edu.co/bitstream/handle/10584/10458/1102876282-Teora.pdf?sequence=1&isAllowed=y
[18] https://datosabiertos.bogota.gov.co/dataset/territorios-urbanos-para-la-inclusion
[19] https://www.datos.gov.co
[20] https://www.arcgis.com/apps/dashboards/9e53734e88a3452f9e0cb04186ae3cf3
[21] https://www.sdp.gov.co/noticias/le-cumplimos-a-bogota-32-nuevos-barrios-la-ciudad-asentamientos-humanos-de-origen-informal-fueron
[22] https://www.datos.gov.co/d/2qk5-sbz7
[23] https://bdigital.uexternado.edu.co/entities/publication/24ada345-1f12-4beb-a16a-042266bb7433
[24] https://datos.cdmx.gob.mx/dataset/?groups=desarrollo-urbano-vivienda-y-territorio
[25] https://datos.cdmx.gob.mx
[26] https://datos.gob.mx/busca/dataset/zona-de-asentamiento-humano--formato-shape
[27] https://statistics.cepal.org/portal/cepalstat/technical-sheet.html?indicator_id=3936&lang=es
[28] https://datos.gob.mx/busca/dataset?tags=colonias&_tags_limit=0

---
Respuesta de Perplexity: https://www.perplexity.ai/search/genera-una-tabla-estructurada-t5i1RiXeTCCMOwKhysiNgg?login-source=sharedThreadLoginGate#locale=es-ES&login-new=true&utm_source=copy_output
