# Política de seguridad

## Reporte de vulnerabilidades

Si descubres una vulnerabilidad en cualquier sistema de MinKura:

1. **No abras un issue público.** Usa el reporte privado de vulnerabilidades de GitHub (pestaña *Security* → *Report a vulnerability*) del repositorio afectado, o
2. Escribe a **cristian.rraga95@hotmail.com** con el asunto `[SECURITY] <sistema>`.

Incluye: descripción, impacto, pasos para reproducir y evidencia (si aplica).

## Alcance

Todos los repositorios de la organización `minkura`.

## Compromiso

- Acuse de recibo en un máximo de 72 horas.
- Confidencialidad del reporte hasta su resolución.
- Crédito público al reportero si lo desea (con su consentimiento).

## Prácticas internas

- Escaneo de secretos (Gitleaks) y de dependencias en CI desde el día uno.
- Secretos fuera de git (variables de entorno / gestor de secretos).
- Aprobación humana para cambios a `main` y despliegues a producción.
