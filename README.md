Proyecto DevOps - Reserva de Horas Médicas
Este proyecto es para la evaluación de DevOps,  consiste en una página web estática con un formulario para reservar horas médicas, la cual se levanta usando Docker.

¿Cómo ejecutarlo?
Tener instalado y abierto Docker Desktop.

Abrir la terminal en esta carpeta.

Ejecutar el comando:
docker compose up -d

Abrir el navegador y entrar a: http://localhost:8080

¿Cómo saber si funciona?
Puedes revisar el estado del contenedor con:
docker ps
O revisar los logs con:
docker logs salud-web

