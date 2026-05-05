---
description: Sistema educativo argentino. Becas disponibles (Progresar, Manuel Belgrano, internacionales), donde estudiar una carrera priorizando opciones publicas gratuitas, certificaciones tech reconocidas en el mercado y recursos gratuitos para aprender ingles. Usalo para cualquier decision educativa en Argentina.
---

# Skill: /educacion

## Fecha actual

Antes de cualquier WebSearch que incluya año o mes, confirma la fecha del sistema (`Bash: date` o contexto `currentDate`). Nunca asumas ni hardcodees el año — usa siempre el que reporta el sistema.

Guia del sistema educativo argentino y sus oportunidades. Acceso gratuito y de calidad para todos.

## Principios

- **Fuente primaria siempre.** Organismos oficiales, universidades nacionales, portales de becas.
- **Sin montos ni fechas hardcodeados.** Montos de becas y periodos de inscripcion cambian cada año: buscalos en tiempo real.
- **Prioriza opciones gratuitas.** Argentina tiene educacion publica gratuita de calidad — mostrala primero.
- **Lenguaje llano.** Cualquier persona debe poder actuar con lo que lee.
- **Siempre mostra fuente y fecha del dato.**

---

## Comandos

### `/educacion becas [perfil]`

Becas disponibles segun carrera, situacion economica y nivel educativo.

**Paso 1 — Progresar (programa nacional principal):**

WebFetch: `https://becasprogresar.educacion.gob.ar/`

WebSearch: `becas Progresar [año actual] monto requisitos inscripcion`

**Paso 2 — Otras becas:**

WebFetch: `https://www.argentina.gob.ar/educacion/becas`

WebSearch: `becas universitarias Argentina [año actual] [perfil si es especifico]`

**Formato:**

```
🎓 Becas — [perfil]
   Dato al [fecha de hoy]

BECAS PROGRESAR
  Lineas disponibles:
  • Progresar Obligatorio — terminar primaria/secundaria
  • Progresar Superior — universitario/terciario/enfermeria
  • Progresar Formacion Profesional — cursos y oficios

  Monto: $[buscar monto vigente] / mes
    (se liquida 80% mensual + 20% al presentar certificado de regularidad)

  Requisitos basicos:
    • Argentino/a nativo/a o con 2+ anos de residencia en el pais
    • Ingresos del grupo familiar no superen 3 Salarios Minimos, Vitales y Moviles
    • Inscripto como alumno regular en institucion reconocida por el Estado
    • Vacunacion completa o en curso

  Inscripcion: becasprogresar.educacion.gob.ar o app Mi Argentina
  Estado convocatoria: [buscar si esta abierta para el año actual]

OTRAS BECAS ENCONTRADAS
  [presentar las mas relevantes para el perfil indicado]

🔗 Progresar: https://becasprogresar.educacion.gob.ar
🔗 Otras becas: https://www.argentina.gob.ar/educacion/becas
Fuente: Ministerio de Capital Humano / argentina.gob.ar — [fecha]
```

---

### `/educacion universidad [carrera]`

Donde estudiar una carrera en Argentina, con enfasis en opciones publicas gratuitas.

**Paso 1:**

WebSearch: `[carrera] universidades nacionales Argentina gratuita [año actual]`

WebSearch: `mejores facultades [carrera] Argentina`

**Formato:**

```
🏛️ [carrera] — Donde estudiarla
   Dato al [fecha de hoy]

UNIVERSIDADES PUBLICAS (gratuitas e irrestrictas)
  [nombre] — [facultad] — [ciudad]
    Duracion: [anos] | Modalidad: [presencial/virtual/mixta]
    Ingreso: [irrestricto / CBC / curso nivelacion / examen]
    → [URL de la carrera]

  [nombre] — [facultad] — [ciudad]
    ...

TECNICATURAS / CARRERAS CORTAS RELACIONADAS
  [opciones mas rapidas si existen — ideal para quien necesita salida laboral pronto]

MODALIDAD VIRTUAL (para quien no esta en ciudad universitaria)
  [opciones a distancia si existen]

UNIVERSIDADES PRIVADAS (si el usuario las menciona)
  [nombre] — costo orientativo si lo encontras

🔗 Buscador de carreras: https://www.argentina.gob.ar/educacion/universidades
Fuente: busqueda web — [fecha]
```

---

### `/educacion certificaciones [area]`

Certificaciones tecnicas reconocidas en el mercado, como prepararlas y acceder gratuitamente.

Areas reconocidas: `tech`, `programacion`, `cloud`, `datos`, `seguridad`, `redes`, o termino libre.

**Paso 1:**

WebSearch: `certificacion [area] Argentina empleadores [año actual]`

WebSearch: `[area] certificacion gratuita Argentina [año actual] preparacion`

**Paso 2 — Programas oficiales:**

WebSearch: `Argentina Programa Codo a Codo becas tech [año actual] inscripcion`

**Formato:**

```
📜 Certificaciones — [area]
   Dato al [fecha de hoy]

MAS PEDIDAS EN EL MERCADO ARGENTINO
  [Nombre cert.] — [organismo: AWS/Google/Microsoft/CompTIA/etc]
    Nivel: [basico/intermedio/avanzado]
    Relevancia local: [por que la piden en Argentina]
    Costo del examen: [USD/ARS si encontras — en USD generalmente]
    Preparacion gratuita: [URL concreta]

  [Nombre cert.] — ...

PROGRAMAS GRATUITOS EN ARGENTINA
  Argentina Programa / Codo a Codo:
  WebSearch: `Argentina Programa [año actual] inscripcion [area]`
  [presentar lo que este activo]

PLATAFORMAS DE PREPARACION SIN COSTO
  [plataforma] — [URL] — [que cubre]
  [plataforma] — [URL] — [que cubre]

Fuente: busqueda web — [fecha]
```

---

### `/educacion ingles`

Recursos gratuitos para aprender ingles desde cero o mejorar.

**Paso 1:**

WebSearch: `aprender ingles gratis Argentina [año actual] plataformas`

WebSearch: `programa ingles gratuito Argentina gobierno [año actual]`

**Formato:**

```
🌐 Ingles — Recursos Gratuitos
   Dato al [fecha de hoy]

PLATAFORMAS SIN COSTO
  Duolingo:             duolingo.com — gamificado, bueno para arrancar y mantener el habito
  BBC Learning English: bbc.co.uk/learningenglish — comprension auditiva y gramatica
  British Council:      learnenglish.britishcouncil.org — estructurado por nivel
  LibreVox:             librivox.org — audiolibros en ingles (nivel intermedio/avanzado)
  Cambridge English:    cambridgeenglish.org/learning-english — preparacion oficial

PROGRAMAS OFICIALES EN ARGENTINA
  [buscar y presentar los activos en el año actual]
  WebSearch: `ingles gratuito Argentina programa gobierno [año actual]`

CERTIFICACIONES ACCESIBLES
  Cambridge A2 Key / B1 Preliminary — examen pago, preparacion gratuita
  IELTS / TOEFL — requeridos para posgrados en el exterior y visas
  Consulate-sponsored exams — buscar becas de examenes en embajadas

CAMINO DE AUTOESTUDIO
  A1–A2 (principiante): Duolingo diario + BBC Learning English basico
  B1–B2 (intermedio):   Podcasts (6 Minute English BBC), series con subtitulos en ingles
  C1+ (avanzado):       Lectura de prensa en ingles, clases de conversacion con nativos (italki, Preply)

Fuente: busqueda web — [fecha]
```

---

## Manejo de errores

- Si becasprogresar.educacion.gob.ar no carga, busca con WebSearch `becas Progresar [año actual]`.
- Si los montos de becas son de mas de 3 meses atras, avisalo claramente.
- Si el usuario pregunta por una carrera muy especifica, hace WebSearch antes de responder.
- Nunca garantices que una beca esta abierta sin verificarlo con una busqueda actual.
- Si el usuario pregunta por costos de universidades privadas, aclara que los aranceles cambian con frecuencia y que debe consultar directamente.

## Tono

Claro y sin jerga academica. El objetivo es que cualquier persona — sin importar si termino el secundario — pueda usar la respuesta para actuar hoy. Prioriza siempre las opciones gratuitas.
