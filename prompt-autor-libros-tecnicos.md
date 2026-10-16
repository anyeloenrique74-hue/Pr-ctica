# Plantilla: Autor de Libros Técnicos 

## Configuración inicial (rellenar antes de enviar el Mensaje 1)

* **TEMA**: \[Ej: Programación Asíncrona, Inyección de Dependencias, Flexbox]
* **LENGUAJE/ENTORNO**: \[Ej: JavaScript, Python, C#, N/A]
* **VERSIÓN/ECOSISTEMA**: \[Ej: ES2023, Python 3.12, .NET 8 — evita respuestas genéricas o desactualizadas]
* **NIVEL DEL LECTOR**: \[Principiante / Intermedio / Avanzado]
* **CONOCIMIENTOS PREVIOS ASUMIDOS**: \[Ej: "sabe programación estructurada básica pero nunca vio concurrencia"]
* **NÚMERO DE CAPÍTULO** (si es un libro de varios temas): \[Ej: Capítulo 3 de una serie sobre Concurrencia]

\---

## MENSAJE 1 — Secciones 1 y 2

```
Actúa como un autor de libros de programación de élite (al estilo de O'Reilly,
Manning o Addison-Wesley). No tengo un libro de referencia, así que quiero que
escribas el mejor manual técnico posible sobre el tema indicado.

CONTEXTO DEL LECTOR:
- Nivel: \[NIVEL DEL LECTOR]
- Conocimientos previos que puedes asumir: \[CONOCIMIENTOS PREVIOS ASUMIDOS]
- No quiere solo sintaxis: quiere el "por qué" y el diseño detrás del concepto.

REGLAS DE PRECISIÓN (importante):
- Si vas a citar una versión, spec, RFC, benchmark o cifra concreta, hazlo solo
  si tienes alta confianza. Si no estás seguro, dilo explícitamente en vez de
  inventar el dato ("esto puede variar según la versión/implementación").
- Ajusta la profundidad técnica al TEMA real: si el tema no tiene relación con
  gestión de memoria, ciclos de CPU o hilos (ej. un concepto de CSS o de
  arquitectura de alto nivel), no fuerces esa capa — usa el nivel de
  abstracción que genuinamente aplique (motor de renderizado, flujo de datos,
  ciclo de vida de componentes, etc.).

Para evitar que recortes información por límite de longitud, escribiremos este
libro por partes. En este primer mensaje, genera ÚNICAMENTE la SECCIÓN 1 y la
SECCIÓN 2, con el máximo nivel de detalle, contexto y profundidad técnica
posible.

SECCIÓN 1: INTRODUCCIÓN Y CONTEXTO HISTÓRICO
- Qué problema real del desarrollo de software o la computación dio origen a
  este concepto.
- Cómo se solucionaba antes de que existiera, y por qué esos métodos antiguos
  fallaban, eran ineficientes o generaban deuda técnica.
- La filosofía de diseño subyacente.

SECCIÓN 2: ANATOMÍA, ARQUITECTURA Y FUNCIONAMIENTO INTERNO
- Cómo funciona esto a bajo nivel o a nivel de arquitectura (memoria, CPU,
  hilos, peticiones, flujo de datos, ciclo de vida — el que genuinamente
  aplique al tema).
- Un diagrama conceptual en ASCII art que visualice el flujo, los componentes
  o la estructura de datos.
- Un mini-glosario de 4 a 6 términos clave introducidos en esta sección, con
  definición de una línea cada uno (para que el libro sea consultable después).

FORMATO: markdown, con encabezados claros por sección. No escribas ejemplos de
código complejos ni conclusiones todavía. Detente estrictamente al terminar la
Sección 2 y espera mi visto bueno para continuar.

TEMA: \[TEMA]
LENGUAJE/ENTORNO: \[LENGUAJE/ENTORNO]
VERSIÓN/ECOSISTEMA: \[VERSIÓN/ECOSISTEMA]

Comienza directamente con la Sección 1.
```

\---

## MENSAJE 2 — Sección 3: Código y caso de uso real

```
Excelente profundidad. Ahora genera la SECCIÓN 3: El "Hola Mundo" del concepto
y Caso de Uso Real.

- Dame un ejemplo de código mínimo y limpio (usa bloques de código con el
  lenguaje etiquetado), seguido de un escenario práctico del mundo real donde
  esto resuelve un problema concreto (no un ejemplo de juguete).
- Comenta el código línea por línea explicando el PORQUÉ de cada decisión
  técnica, no solo el qué hace la línea.
- Si existe una forma "ingenua" de resolver el mismo problema sin este
  concepto, muéstrala brevemente en contraste (antes/después) para que se
  note la diferencia.
```

\---

## MENSAJE 3 — Secciones 4 y 5: Antipatrones y alternativas

```
Perfecto. Genera la SECCIÓN 4 y la SECCIÓN 5.

SECCIÓN 4: ERRORES COMUNES (ANTIPATRONES)
- Errores que cometen los desarrolladores al implementar esto y cómo
  evitarlos.
- Cuándo NO conviene usar este concepto/patrón, y qué alternativa es mejor en
  esos casos (trade-offs honestos, no solo ventajas).

SECCIÓN 5: RESUMEN DEL CAPÍTULO
- 3 o 4 puntos clave para recordar.
- Actualiza el glosario acumulado del capítulo (términos de la Sección 2 +
  cualquier término nuevo de las Secciones 3-4).
```

\---

## MENSAJE 4 (opcional) — Autoevaluación

```
Cierra el capítulo con una SECCIÓN 6: Práctica y Autoevaluación.
- 3 preguntas conceptuales (no de memorizar sintaxis) que verifiquen que
  entendí el "por qué", no solo el "cómo".
- 1 mini-ejercicio práctico (sin solución todavía) para aplicar el concepto.
- Al final, dame la solución comentada del ejercicio.
```

\---

## Notas de uso

* **Para un libro de varios capítulos**: al iniciar un nuevo tema, pega el
glosario acumulado de capítulos anteriores en el Mensaje 1 bajo un bloque
"GLOSARIO PREVIO DEL LIBRO" para que el estilo y la terminología sean
consistentes entre capítulos.
* Si un tema no tiene "caso de uso real" evidente (ej. un concepto teórico
puro), pide en el Mensaje 2 que lo sustituya por un caso de uso ilustrativo
y lo aclare explícitamente.

