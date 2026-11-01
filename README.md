# Evidencias ShareWay — Sprint 2 (TB3)

Evidencias de documentación OpenAPI y pruebas obtenidas localmente el 1 de noviembre de 2026.

## Sección 5.3.2.5 — versión final

- [Descargar Word de la sección final](https://github.com/AaronAvilap/funda-tb3/raw/refs/heads/main/ShareWay-5.3.2.5-Version-Final.docx)
- [Consultar la sección final en PDF](ShareWay-5.3.2.5-Version-Final.pdf)

Documento de 26 páginas elaborado según las indicaciones de la plantilla: introducción, operaciones y parámetros, ejemplos de respuesta, enlaces a Swagger, 15 figuras explicadas y trazabilidad de repositorios y commits. Usa Times New Roman de 12 puntos en el cuerpo, tablas sin fondos de color y el formato del informe original. Distingue las ejecuciones locales de los enlaces de despliegue y conserva las diferencias observadas del contrato.

## Descargas de evidencias

- [ZIP con capturas, registros y resultados](ShareWay-evidencias-Sprint2.zip)
- [Documento Word con figuras y explicaciones](ShareWay-evidencias-Sprint2.docx)

El ZIP incluye 57 capturas PNG, un índice HTML, solicitudes y respuestas en JSON, contratos OpenAPI y registros de las pruebas. Para ver el índice, descarga y descomprime el ZIP y abre `indice.html`.

## Resultados y alcance

Se ejecutaron 28 casos funcionales: 27 devolvieron el estado HTTP esperado y 1 falló. Trip Execution devolvió HTTP 500 al intentar iniciar un viaje sin pasajeros abordados, en lugar del 409 esperado.

Las suites existentes terminaron sin fallos. Los detalles y las diferencias de conteo del runner de Payments están documentados en el material adjunto. Trip Execution compiló sin errores y se comprobó con pruebas funcionales; no contiene una suite automatizada en la versión revisada.

Se usaron bases locales aisladas y datos ficticios. Esta evidencia no acredita el despliegue en Render ni la integración automática de extremo a extremo. Los eventos de Payments se enviaron manualmente y sus JWT se generaron exclusivamente para la instancia de prueba. No se modificó el código de las APIs.
