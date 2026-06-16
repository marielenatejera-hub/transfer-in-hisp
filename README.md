# Transfer-In HISP — Repositorio de Productos

Sitio web estático que centraliza la información operativa de los productos de transfer-in (fondeo bancario) para los países HISP: Argentina, México, Chile, Uruguay y Colombia.

## ¿Para qué sirve?

Es una referencia rápida para el equipo de Prevención de Fraude de Money In. Concentra en un solo lugar todo lo que necesitás saber sobre cada producto:

- **¿Cómo funciona cada flujo?** Descripción del mecanismo técnico, desde el ingreso del pago hasta la llamada a RISK.
- **¿Se puede rechazar?** Estado actual de la capacidad de rechazo por producto y site, con links a los porotos de seguimiento cuando aplica.
- **Tablas de BigQuery** asociadas a cada producto para análisis y monitoreo.
- **Links de utilidad** — reportes diarios, dashboards de STO, planes de trabajo y documentos de seguimiento.
- **Comparativa entre productos** — vista unificada de capacidades: interpretación de RISK, marca de fraude STO, info de titularidad, reglas de prevención y alarmas activas.
- **Puntos de dolor** — gaps actuales por resolver en MLC, MLU y MCO, con estado de avance y referencias a iniciativas en curso.

## Productos cubiertos

| Producto | Site | ¿Puede rechazar? |
|----------|------|-----------------|
| CVU ARS | MLA — Argentina (pesos) | ✗ Solo bloqueo cautelar |
| CVU DOL/DCE | MLA — Argentina (dólares) | ✓ Sí |
| CLABE | MLM — México | ✓ Sí |
| TEF | MLC — Chile | ⚠ En revisión |
| URUTEC | MLU — Uruguay | ✓ Sí |
| PSE | MCO — Colombia | ✗ Solo bloqueo cautelar |

## ¿Cómo se actualiza?

Editando directamente el archivo `index.html` y haciendo commit a `main`. GitHub Pages publica los cambios automáticamente en 1-5 minutos.

## Acceso

🔗 https://marielenatejera-hub.github.io/transfer-in-hisp/
