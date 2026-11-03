# Essential Marketing — agentes de IA para marketing local

Sistema de 10 agentes de IA (skills de Claude) que cubren el trabajo de marketing de una agencia unipersonal para pequeños negocios locales en España, empezando por Valencia: estrategia, marca, ventas, contenido, creatividad, redes sociales, automatización, publicidad de pago y datos.

Cada agente hace solo su área, lee el documento aprobado del anterior, registra su trabajo en un documento con cabecera estándar y espera la aprobación del operador antes de pasar el relevo. Ningún material llega al cliente sin esa aprobación.

## Los 10 agentes

| # | Agente | Estado |
|---|--------|--------|
| 1 | Gestión (`essential-gestao`) | v1.0, validado |
| 2 | Estrategia y Mercado (`essential-estrategia`) | v1.1, validado |
| 3 | Marca y Posicionamiento (`essential-marca`) | v1.0, validado |
| 4 | Ventas y Conversión | pendiente |
| 5 | Copy y Contenido | pendiente |
| 6 | Creativo | pendiente |
| 7 | Social Media | pendiente |
| 8 | Automatización e Integraciones | pendiente |
| 9 | Publicidad de Pago | pendiente |
| 10 | Datos y Rendimiento | pendiente |

## Cómo funciona el ciclo

1. **Gestión** abre la cuenta, valida el briefing (16 preguntas bloqueantes) y mantiene el panel de seguimiento.
2. **Estrategia y Mercado** produce dos documentos: Diagnóstico Estratégico y Estrategia de Crecimiento a 90 días.
3. Cada agente siguiente recibe los documentos aprobados, trabaja solo en su área y entrega con estado "pendiente de aprobación".
4. Solo el operador aprueba. Un documento modificado después de aprobarse pasa a una versión nueva.

## Reglas de diseño

- Nunca inventar datos, métricas, precios, competidores ni fuentes. Todo dato lleva fuente y fecha, o se marca como "sin dato" o [verificar].
- Nunca prometer resultados comerciales: las metas son hipótesis.
- Los agentes solo se activan al llamarlos por su nombre.
- Los datos de cada cuenta se mantienen separados.
- Las skills no contienen credenciales ni datos de clientes.

## Contenido

- `agentes/`: texto de cada skill (en portugués de Brasil, el idioma de trabajo del operador).
- `CHANGELOG.md`: versiones y resultado de las pruebas.

## Estado

Proyecto en construcción. Los agentes se prueban con cuentas ficticias antes de usarse con clientes. Cuando se valida una skill nueva, se actualiza este repositorio.
