# Video de pruebas con Newman

[Descargar el video MP4 sin audio](https://github.com/AaronAvilap/funda-tb3/raw/refs/heads/main/ShareWay-Pruebas-Newman-Sin-Audio.mp4)

Duración: 56 segundos. Resolución: 1600 × 900. Formato H.264. Sin pista de audio.

La grabación muestra una ejecución nueva y real de la colección Postman de Trip Planning & Matching con Newman. La salida del proceso se visualiza en una pantalla de seguimiento; no corresponde a la interfaz gráfica de Postman. Se muestran los códigos HTTP, cuerpos de respuesta, aserciones y resumen del ejecutor.

Resultado: 16 solicitudes y 28 aserciones; 0 fallos. Las respuestas 400 y 404 pertenecen a los casos negativos esperados. El intervalo entre solicitudes se fijó en 2.5 segundos para facilitar la lectura; no es una prueba de rendimiento.

Se utilizó la API local en `http://localhost:8081`, commit `8094f48d18ab37fe70258e78a2b6e6ccbb838cc0`, con datos de prueba y una zona diferente para la ejecución. No se modificó el código ni se utilizaron las otras APIs o el despliegue de Render.

Se adjuntan `resultados-video.json`, `ejecucion-video.log` y la captura del resultado final para contrastar la grabación.
