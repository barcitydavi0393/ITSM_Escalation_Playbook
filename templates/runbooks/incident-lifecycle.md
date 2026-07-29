# ⚡ Incident Management & SLA Lifecycle Runbook

## 1. Clasificación del Incidente
- **P1 (Critical):** Caída total del servicio o pérdida de datos transaccionales en vivo. (Respuesta < 15 min).
- **P2 (High):** Funcionalidad crítica afectada sin alternativa temporal (Workaround). (Respuesta < 1 hora).
- **P3 (Medium / Low):** Consultas de usuario, fallas estéticas o errores menores de navegación. (Respuesta < 4 horas).

## 2. Flujo de Escalación (L1 -> L2 -> Engineering)
1. **Fase de Diagnóstico Inicial (L1/L2):** Validación de red (`ping`, `tracert`), revisión de logs y verificación del estado de las bases de datos mediante consultas SQL básicas.
2. **Aislamiento de Causa Raíz:** Determinación de si el problema recae en el cliente (red local/navegador) o en el servidor (API/Base de datos).
3. **Escalamiento Formal:** Adjuntar el *Bug Report Template* completado si el defecto requiere intervención directa de los ingenieros de software.
