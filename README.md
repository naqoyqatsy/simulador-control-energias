# Simulador de control de energías · Bomba P-101

Práctica virtual de control de energías peligrosas: cambio de sello mecánico de una bomba centrífuga (escenario ficticio).

- **Modo 1 · Maniobra en terreno:** se operan los dispositivos del diagrama y se decide si intervenir.
- **Modo 2 · Ejercicio de decisiones:** diez pasos de la secuencia operacional, con eventos al azar durante la ejecución.

**Estado:** ejercicio de prueba (v1.3, 21-11-2026). No forma parte de los documentos oficiales. El escenario, los equipos y los datos son ficticios. No reemplaza la observación en terreno ni la evaluación práctica, y sus resultados no son evidencia formal.

El simulador es un archivo HTML autocontenido: no usa recursos externos ni guarda ni envía datos de los usuarios.

## Registro de resultados (v1.3)
Al terminar cada modo, el simulador muestra un **código de resultado** con verificación. El participante lo copia y lo pega en el formulario de registro de Microsoft Forms de EQUANS, donde además ingresa su nombre completo, empresa y centro, y acepta el aviso de tratamiento de datos. El simulador no envía datos por sí mismo.

Formato del código: `SIMCE-P101|versión|modo|fecha y hora|resultado|desempeño %|errores críticos|trampas o etapas|minutos|C:claves críticas|O:claves con observaciones|K:verificación`

`verificar.html` separa los campos, comprueba la verificación de cada código y exporta un CSV para Excel o Power BI. La verificación detecta códigos editados a mano; no es una firma criptográfica.

Configuración: en `index.html`, las constantes `FORM_URL` y `FORM_PREFILL_URL` contienen el vínculo del formulario.
