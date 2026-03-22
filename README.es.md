---

**Idioma / Language / Langue / Lingua / Idioma:**
[EN](README.md) | [FR](README.fr.md) | [ES](README.es.md) | [IT](README.it.md) | [PT](README.pt.md)

> *Versiones multilingües producidas con [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — pipeline de traducción SFL-first del mismo autor.*

---

# sfl-arquitectura-llm-primero

**© 2026 Simon Drury (sjd_datascapes)**

---

## Qué es esto

Una especificación pública y fechada de una arquitectura LLM basada en la Lingüística Funcional Sistémica (LFS).

La afirmación central: la lingüística funcional sistémica — y en particular las metafunciones ideacional, interpersonal y textual — constituye el marco correcto para el diseño de LLM, la ingeniería de prompts y la orquestación de agentes. No se trata de aplicar la LFS *por encima* de un LLM. Se trata de la LFS como *sistema operativo* del LLM.

---

## El problema con el diseño actual de los LLM

Los LLM actuales y sus prompts de sistema son:

- ideacionalmente subespecificados (sin arquitectura de campo/dominio con principios)
- interpersonalmente incoherentes (sin modelado principiado del rol, la postura o el tenor)
- textualmente ad hoc (sin estructura principiada de género, registro o flujo de información)

Resultado: los usuarios dedican un tiempo considerable a corregir fallos de nivel sistema que nunca deberían haberse incorporado.

---

## La arquitectura LFS-first

### 1. El registro como parámetro de diseño primario

Toda interacción con un LLM está gobernada por un contexto de situación. Las tres variables de registro — campo, tenor, modo — deben codificarse explícitamente como parámetros de nivel sistema, no inferirse de forma estocástica.

- **Campo**: ¿Qué dominio de actividad está en juego? ¿Qué estructura de conocimiento lo rige?
- **Tenor**: ¿Cuál es la relación de roles? ¿Qué estructuras de obligación y afecto se aplican?
- **Modo**: ¿Cuál es el canal retórico? ¿Qué densidad y flujo de información se esperan?

### 2. Las metafunciones como sistema de tipificación de agentes

Las tres metafunciones no son meras categorías analíticas. En una arquitectura LFS-first, se convierten en roles funcionales para agentes y subprocesos:

- **Agente ideacional**: gestiona el conocimiento del dominio, la construalión experiencial, las relaciones lógicas
- **Agente interpersonal**: gestiona la postura, la valoración, la obligación, la modalidad, las relaciones de rol
- **Agente textual**: gestiona la cohesión, la estructura informativa, la secuenciación genérica, la progresión temática

### 3. El género como especificación de salida

La salida no es «una respuesta». Es una instancia de género — un proceso social por etapas orientado a un objetivo. El género debe especificarse explícitamente antes de la generación, no inferirse de las características superficiales del prompt.

### 4. Ingeniería de prompts LFS-first

Los prompts no son instrucciones en lenguaje natural. Son operadores meta-textuales sobre un espacio funcional sistémico. Un prompt LFS-first bien formado especifica:

- el registro del texto objetivo
- la estructura de género esperada
- la ponderación metafuncional requerida
- los parámetros de valoración y modalidad

---

## Implementaciones

Los siguientes repositorios implementan aspectos de esta arquitectura:

- [systemic_func_context-wrapper](https://github.com/simon-drury/systemic_func_context-wrapper) — envoltorio de instrucción LFS para prompts
- [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — agente de traducción multilingüe basado en LFS
- [browser_bridge_-sfl-playground-extension_sjd_datascapes](https://github.com/simon-drury/browser_bridge_-sfl-playground-extension_sjd_datascapes) — análisis LLM multi-modelo LFS-first
- [numerai-sfl-pipeline](https://github.com/simon-drury/numerai-sfl-pipeline) — pipeline multi-agente informado por LFS

---

## Licencia

Esta especificación es de libre uso para uso personal, académico y de código abierto no comercial.
Cualquier uso comercial (que genere ingresos directa o indirectamente) requiere una licencia separada del autor.

Se agradece el contacto si se prevé un uso comercial. Las condiciones de licencia están abiertas a discusión.

**Contacto**: simondrury2010@gmail.com | [LinkedIn](https://www.linkedin.com/in/simon-drury-60b881293)

---

*Primera publicación: marzo de 2026. Fechado en GitHub como constancia de anterioridad.*
