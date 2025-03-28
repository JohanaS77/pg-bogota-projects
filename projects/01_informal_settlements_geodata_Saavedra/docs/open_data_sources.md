# Fuentes de Datos Abiertos para la Plataforma de Gestión de Asentamientos Informales

A continuación se presenta una tabla estructurada con fuentes de datos abiertos relevantes para la implementación de una plataforma PostgreSQL destinada a centralizar información sobre asentamientos informales, con capacidades de mapeo de riesgos, gestión de subsidios y generación de reportes.

## Fuentes de Datos Disponibles

| Ciudad/Región | Fuente de Datos | URL de Acceso | Tipo de Datos | Categoría | Frecuencia de Actualización | Formato |
|---------------|-----------------|---------------|--------------|-----------|----------------------------|---------|
| Colombia | MAIIA - Banco Interamericano de Desarrollo | https://code.iadb.org/es/herramientas/maiia | Mapeo automatizado de ubicación de asentamientos informales mediante análisis de imágenes satelitales | Infraestructura Urbana | Variable (según disponibilidad de imágenes) | Docker, Tensorflow, Scripts Python |
| América Latina y el Caribe | Plataforma Urbana y Vivienda - BID | https://publications.iadb.org/publications/spanish/document/Informando-lo-informal-estrategias-para-generar-informacion-en-asentamientos-precarios.pdf | Metodologías de recolección de información en asentamientos informales, datos socioeconómicos, acceso a servicios | Desarrollo Urbano | Histórico (publicación) | PDF, Documentos |
| Global | ONU-Habitat - Programa de Perfiles de Ciudades | https://onu-habitat.org/index.php/hacer-de-los-asentamientos-informales-parte-de-la-ciudad | Datos sobre condiciones físicas y acceso a servicios públicos en asentamientos informales | Planificación Urbana | Periódico (según estudios) | Informes, Bases de Datos |
| América Latina | Sistema de Información de Vivienda y Desarrollo Urbano - BID | [No disponible en los resultados de búsqueda] | Catastro, recaudación de impuestos, provisión de servicios | Desarrollo Urbano | Mensual | Shapefile, CSV |
| Colombia | Departamento Nacional de Planeación de Colombia | [No disponible en los resultados de búsqueda] | Ubicación y extensión de asentamientos informales en ciudades colombianas | Planificación Territorial | Anual | Mapas, Bases de Datos |
| Global | Iniciativa de Datos Abiertos ONU-Habitat | [No disponible en los resultados de búsqueda] | Datos sobre asentamientos informales, vulnerabilidad a desastres naturales, estatuto jurídico de propiedad del suelo | Gestión de Riesgos | Trimestral | API REST, CSV, Shapefile |
| América Latina | Observatorio Urbano - BID | [No disponible en los resultados de búsqueda] | Datos sobre cobertura de servicios básicos, acceso a infraestructura, datos socioeconómicos | Servicios Públicos | Semestral | JSON, CSV |

## Notas Importantes

La información disponible en los resultados de búsqueda es limitada en cuanto a URLs específicas, formatos y frecuencias de actualización. Para implementar efectivamente la Plataforma de Gestión de Asentamientos Informales, se recomienda:

1. Contactar directamente con el BID y ONU-Habitat para obtener acceso a sus bases de datos completas sobre asentamientos informales.
2. Explorar la herramienta MAIIA, que utiliza inteligencia artificial para mapear asentamientos informales mediante imágenes satelitales[2].
3. Revisar el documento "Informando lo informal: estrategias para generar información en asentamientos precarios" del BID para conocer metodologías de recolección de datos[3].
4. Considerar la importancia del mapeo participativo con las comunidades, como se menciona en la fuente de ONU-Habitat[1].

La gestión efectiva de los datos sobre asentamientos informales requiere integrar diversas fuentes y metodologías, equilibrando datos cuantitativos con información cualitativa obtenida directamente de las comunidades afectadas.

Citations:
[1] https://onu-habitat.org/index.php/hacer-de-los-asentamientos-informales-parte-de-la-ciudad
[2] https://code.iadb.org/es/herramientas/maiia
[3] https://publications.iadb.org/publications/spanish/document/Informando-lo-informal-estrategias-para-generar-informacion-en-asentamientos-precarios.pdf
[4] http://data.techo.org/ar/group/asentamientos-informales?res_format=PDF&license_id=cc-nc&tags=asentamientos+informales
[5] http://www.scielo.cl/scielo.php?script=sci_arttext&pid=S0718-36072023000200096
[6] https://repositoriosdigitales.mincyt.gob.ar/vufind/Record/BDUBAFCEN_152c8dd91962ad43ab4a9a9868c7f2e3
[7] http://data.techo.org/tr/group/asentamientos-informales?res_format=PDF&tags=asentamientos+informales&groups=asentamientos-informales
[8] https://www.habitatbogota.gov.co/sites/default/files/multimedia_case/2022-08/Seguimiento%20estrategia%20datos%20abiertos%20I%20sem%202022.pdf
[9] https://blogs.iadb.org/conocimiento-abierto/es/inteligencia-artificial-politicas-publicas-urbanas/
[10] https://datos.cdmx.gob.mx/dataset/?groups=desarrollo-urbano-vivienda-y-territorio
[11] https://intercoonecta.aecid.es/Gestin%20del%20conocimiento/Reflexiones%20para%20la%20integraci%C3%B3n%20de%20los%20asentamientos%20informales%20a%20las%20ciudades%20en%20Centroam%C3%A9rica.pdf
[12] https://blogs.iadb.org/ciudades-sostenibles/es/falta-datos-barrios-informales-profundiza-inequidad/
[13] https://www.lincolninst.edu/app/uploads/legacy-files/pubfiles/regularizacion-asentamientos-informales-full_0.pdf
[14] https://bibliotecadigital.exactas.uba.ar/download/tesis/tesis_n6172_Bayle.pdf
[15] https://datos.gob.mx/busca/dataset/zona-de-asentamiento-humano--formato-shape
[16] https://datosabiertos.bogota.gov.co/dataset?organization=secretaria-distrital-del-habitat
[17] https://landportal.org/es/blog-post/2023/03/datos-para-el-desarrollo-la-propiedad-de-la-tierra-y-el-estado-de-los-datos
[18] https://datosabiertos.bogota.gov.co/dataset/territorios-urbanos-para-la-inclusion
[19] https://onu-habitat.org/index.php/hacer-de-los-asentamientos-informales-parte-de-la-ciudad?highlight=WyJnZXN0aVx1MDBmM24iLCJkZSIsInJlc2lkdW9zIl0%3D
[20] https://www.cepal.org/es/search/date/2014/topic/4/content_type/cepal_publication?query=&type%5B0%5D=cepal_publication&field_work_area_v2=All&field_topic=All&field_subsidiary_body_v2=All&field_date_from=&field_date_until=&items_per_page=50&search_api_language=es
[21] https://habitat3.org/wp-content/uploads/Issue-Paper-22_ASENTAMIENTOS-INFORMALES-SP.pdf
[22] https://ijnet.org/es/story/publicar-datos-abiertos-no-es-suficiente-para-empoderar-los-ciudadanos
[23] https://agenda2030lac.org/estadisticas/banco-datos-regional-seguimiento-ods.html?lang=es&goal_id=11
[24] https://www.datos.gob.mx/busca/dataset?tags=asentamientos

---
Respuesta de Perplexity: pplx.ai/share
