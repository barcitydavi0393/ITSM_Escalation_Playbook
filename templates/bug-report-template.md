# 🐞 Bug Report Template (Engineering Escalation)

## 📌 Metadatos del Ticket
- **Ticket ID:** [Ej: INC-4092]
- **Severity / Priority:** [P2 - High / P3 - Medium]
- **Affected System / Module:** [Ej: Auth Service / POS Checkout Gateway]
- **Reported By:** David Barrios (Technical Support Specialist)

## 📋 Descripción del Problema
[Descripción clara y concisa de lo que está fallando desde la perspectiva del usuario o del sistema].

## 🔄 Pasos para Reproducir (Steps to Reproduce)
1. Navegar a...
2. Ingresar las credenciales con...
3. Hacer clic en el botón de...
4. **Error observado:** El sistema arroja un timeout de pasarela.

## 📊 Comportamiento Esperado vs. Obtenido
- **Expected Result:** La transacción debe completarse y devolver un código HTTP 200 con el recibo en JSON.
- **Actual Result:** La interfaz se congela y arroja un error HTTP 500 Internal Server Error.

## 🔍 Evidencia Técnica Adjunta
- **Logs de Sistema / Consola:** 
  ```text
  [ERROR] 2026-07-29 10:15:20 - Connection refused at /api/v1/checkout
