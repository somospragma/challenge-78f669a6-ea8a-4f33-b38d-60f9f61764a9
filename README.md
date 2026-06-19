# Automatización de prueba funcional en aplicación móvil Android

Una empresa de fintech necesita mejorar la calidad de su aplicación móvil Android. Para ello, se ha decidido implementar pruebas automatizadas utilizando Appium. El objetivo es crear un caso de prueba funcional que valide una funcionalidad clave de la aplicación.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Automatización de pruebas móviles |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 3-4 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: JDK 17+, Maven 3.9+, IDE con soporte Java.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `mvn compile` en la raíz. Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Exploración del dominio y selección de caso de prueba

**Objetivo:** Identificar una funcionalidad clave de la aplicación para automatizar su prueba.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Investiga la aplicación móvil Android de la empresa de fintech.
- Identifica una funcionalidad que sea crítica para el negocio y que pueda ser validada mediante una prueba automatizada.
- Documenta la funcionalidad seleccionada y describe los pasos manuales necesarios para ejecutar la prueba.

**Entregable:** Documentación de la funcionalidad seleccionada y los pasos manuales de la prueba.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda que la funcionalidad debe ser crítica y tener un impacto significativo en el negocio.
- Piensa en las diferentes formas en que los usuarios interactúan con la aplicación y cómo eso puede afectar la prueba.

</details>

### Fase 2: Diseño del caso de prueba

**Objetivo:** Diseñar un caso de prueba funcional que valide la funcionalidad seleccionada.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Basándote en la documentación de la funcionalidad seleccionada y los pasos manuales de la prueba, diseña un caso de prueba funcional.
- Identifica los elementos de la interfaz de usuario que necesitas interactuar para ejecutar la prueba.
- Define los criterios de aceptación para la prueba.

**Entregable:** Caso de prueba funcional diseñado con los elementos de la interfaz de usuario y los criterios de aceptación.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda que el caso de prueba debe ser claro y conciso.
- Piensa en los diferentes escenarios que pueden ocurrir durante la ejecución de la prueba y cómo manejarlos.

</details>

### Fase 3: Implementación del caso de prueba

**Objetivo:** Implementar el caso de prueba funcional utilizando Appium.

**Tiempo estimado:** 1-2 horas

**Instrucciones:**

- Utiliza Appium para implementar el caso de prueba funcional diseñado en la fase anterior.
- Ejecuta la prueba y verifica que se cumplan los criterios de aceptación definidos.
- Documenta los resultados de la prueba y cualquier problema encontrado.

**Entregable:** Caso de prueba funcional implementado y documentado con los resultados y problemas encontrados.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda que Appium es una herramienta para automatizar pruebas en aplicaciones móviles.
- Piensa en las diferentes formas en que puedes interactuar con los elementos de la interfaz de usuario utilizando Appium.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un caso de prueba funcional y por qué es importante en la automatización de pruebas móviles?
- **paraQueSirve**: ¿Para qué sirve la automatización de pruebas móviles en el contexto de una aplicación financiera?
- **comoSeUsa**: ¿Cómo se utiliza Appium para implementar casos de prueba funcionales en aplicaciones móviles Android?
- **erroresComunes**: ¿Cuáles son los errores comunes que pueden ocurrir durante la implementación de casos de prueba funcionales con Appium?
- **queDecisionesImplica**: ¿Qué decisiones implica la implementación de un caso de prueba funcional con Appium en una aplicación móvil Android?

## Criterios de Evaluacion

- Identificación de una funcionalidad clave de la aplicación para automatizar su prueba.
- Diseño de un caso de prueba funcional con elementos de la interfaz de usuario y criterios de aceptación.
- Implementación del caso de prueba funcional utilizando Appium.
- Ejecución de la prueba y verificación de los criterios de aceptación.
- Documentación de los resultados de la prueba y problemas encontrados.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
