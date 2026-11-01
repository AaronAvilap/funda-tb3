# Evidencias ShareWay — Sprint 2 (TB3)

Evidencias de documentación OpenAPI y pruebas obtenidas localmente el 1 de noviembre de 2026.

## Descargas

- [ZIP con capturas, registros y resultados](ShareWay-evidencias-Sprint2.zip)
- [Documento Word con figuras y explicaciones](ShareWay-evidencias-Sprint2.docx)

El ZIP incluye 57 capturas PNG, un índice HTML, solicitudes y respuestas en JSON, contratos OpenAPI y registros de las pruebas. Para ver el índice, descarga y descomprime el ZIP y abre `indice.html`.

## Resultados y alcance

Se ejecutaron 28 casos funcionales: 27 devolvieron el estado HTTP esperado y 1 falló. Trip Execution devolvió HTTP 500 al intentar iniciar un viaje sin pasajeros abordados, en lugar del 409 esperado.

Las suites existentes terminaron sin fallos. Los detalles y las diferencias de conteo del runner de Payments están documentados en el material adjunto. Trip Execution compiló sin errores y se comprobó con pruebas funcionales; no contiene una suite automatizada en la versión revisada.

Se usaron bases locales aisladas y datos ficticios. Esta evidencia no acredita el despliegue en Render ni la integración automática de extremo a extremo. Los eventos de Payments se enviaron manualmente y sus JWT se generaron exclusivamente para la instancia de prueba. No se modificó el código de las APIs.
