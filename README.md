# CantelSaludable

Sistema de gestión para el Centro de Salud Comunitario de la aldea Cantel, San Pedro Sacatepéquez, San Marcos: pacientes, consultas, escaneo de recetas, dispensación y control de lotes de medicamentos con semáforo de vencimiento.

Proyecto del curso **Análisis de Sistemas II**, Universidad Mariano Gálvez de Guatemala (UMG).
Autor: Diego Roberto Bautista Ixcoy (carné 0903-23-5352).

## Contenido

| Ruta | Qué contiene |
|---|---|
| `prototipo/index.html` | Prototipo navegable de las pantallas S01 a S12. Es un solo archivo, sin instalación. |
| `prototipo/fuente-diseno/` | Archivos originales del prototipo en el visor de diseño (`Main.dc.html` y `canvas.json`). Solo como respaldo; no se abren fuera de ese visor. |
| `docs/openapi.yaml` | Especificación de la API REST (OpenAPI 3.0.3), Anexo D del documento. |
| `docs/diagramas/` | Los 24 diagramas del documento en PNG y su código fuente Mermaid (`.mmd`). |

## Cómo abrir el prototipo

Descargue el repositorio y abra `prototipo/index.html` en un navegador. Para probarlo, toque **Ingresar** sin escribir nada. El botón del encabezado simula perder y recuperar la conexión para ver el contador de cambios pendientes.


## Diagramas

Los archivos `.mmd` se pueden regenerar con Mermaid CLI:

```
npx @mermaid-js/mermaid-cli -i docs/diagramas/fig-5-2-clases.mmd -o fig-5-2-clases.png
```

## Estado

Entrega del documento de análisis y diseño. El sistema todavía no está construido: el prototipo sirve para validar el diseño con el personal del centro.
