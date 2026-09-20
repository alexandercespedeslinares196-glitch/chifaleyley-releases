# Sistema Restaurante Chifa LeyLey — Instaladores

Este repositorio sólo aloja los instaladores publicados del sistema. **No contiene código fuente.**

## No hace falta descargar nada de aquí

La actualización es automática: cada copia instalada comprueba por su cuenta si hay una versión
nueva, la descarga en segundo plano sin interrumpir el servicio y la instala al cerrar o al volver
a abrir el sistema.

Los archivos están aquí porque el sistema los descarga desde este repositorio, no para instalarlos
a mano.

## Cómo se comprueba que el instalador es legítimo

Cada versión se anuncia en un manifiesto firmado con la clave privada del proveedor. Antes de
instalar nada, el sistema verifica la firma del manifiesto y el SHA-256 del archivo descargado. Un
instalador alterado o incompleto se descarta y no llega a ejecutarse.

Las versiones publicadas están en [Releases](../../releases).
