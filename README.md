# U12 Post 2 - Validacion Arquitectonica

## Resumen
Repositorio basado en el Post 1 con reglas ArchUnit, ADRs y pipeline de CI.

## Validacion Arquitectonica
- Regla 1: el dominio no depende de infraestructura ni adaptadores.
- Regla 2: los controladores solo acceden a la facade.
- Regla 3: los puertos del dominio son interfaces.
- Regla 4: los procesadores implementan ProcesadorPedido.
- Regla 5: la infraestructura no accede a adaptadores REST.

## ADRs
- docs/adr/ADR-001.md
- docs/adr/ADR-002.md
- docs/adr/ADR-003.md

## Capturas
![Pipeline verde](img/pipeline-verde.png)
![Pipeline rojo](img/pipeline-rojo.png)

## Notas
- Las capturas se guardan en la carpeta img/.
