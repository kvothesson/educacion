# educacion

Plugin de Claude Code — sistema educativo argentino y sus oportunidades.

## Que hace

`/educacion` te orienta en el ecosistema educativo argentino: becas disponibles (Progresar, Manuel Belgrano, internacionales), donde estudiar una carrera priorizando opciones publicas gratuitas, certificaciones tech que pide el mercado y recursos sin costo para aprender ingles.

## Instalacion

```bash
claude --plugin-dir /ruta/a/educacion
```

## Comandos y ejemplos

### `/educacion becas estudiante universitario sin trabajo`

```
🎓 Becas — estudiante universitario sin trabajo
   Dato al 4 may 2026

BECAS PROGRESAR
  Lineas disponibles:
  • Progresar Superior — universitario/terciario/enfermeria  ← aplica directamente

  Monto: $35.000 / mes
    (se liquida $28.000 mensual + $7.000 al presentar certificado de regularidad al final del ciclo)

  Requisitos basicos:
    • Argentino/a con 2+ anos de residencia
    • Ingresos del grupo familiar no superen 3 SMVM (~$870.000 en may 2026)
    • Inscripto como alumno regular en universidad o terciario reconocido
    • Sin empleo en relacion de dependencia o con ingresos bajos

  Inscripcion: becasprogresar.educacion.gob.ar o app Mi Argentina
  Estado convocatoria: inscripcion Superior cerrada (abrio 6–30 abr 2026) — verificar reapertura

OTRAS BECAS
  • Beca Manuel Belgrano — para estudiantes de carreras prioritarias (ingenieria, salud, docencia)
  • Becas de tu universidad — muchas universidades nacionales tienen programas propios
    Consulta en la secretaria de bienestar estudiantil de tu facultad

🔗 Progresar: https://becasprogresar.educacion.gob.ar
🔗 Otras becas: https://www.argentina.gob.ar/educacion/becas
Fuente: argentina.gob.ar / ambito.com — 4 may 2026
```

---

### `/educacion universidad ciencias de la computacion`

```
🏛️ Ciencias de la Computacion / Informatica — Donde estudiarla
   Dato al 4 may 2026

UNIVERSIDADES PUBLICAS (gratuitas e irrestrictas)
  UBA — Facultad de Ciencias Exactas y Naturales — CABA
    Duracion: 5 anos | Modalidad: presencial
    Ingreso: CBC (Ciclo Basico Comun, 1 ano)
    → exactas.uba.ar/carreras/licenciatura-en-ciencias-de-la-computacion

  UNLP — Facultad de Informatica — La Plata
    Duracion: 5 anos | Modalidad: presencial
    Ingreso: irrestricto con curso de ingreso
    → info.unlp.edu.ar

  UNC — FAMAF — Cordoba
    Duracion: 5 anos | Modalidad: presencial
    → famaf.unc.edu.ar

  UNQ — Universidad Nacional de Quilmes
    Modalidad: virtual disponible
    → unq.edu.ar

TECNICATURAS CORTAS (2–3 anos, salida laboral mas rapida)
  • Tecnicatura en Programacion — UTN, UNQ y otras
  • Tecnicatura Universitaria en IA — varias UU.NN. desde 2024

MODALIDAD VIRTUAL
  UNQ y otras ofrecen opciones a distancia — buscar con WebSearch `informatica virtual universidad nacional Argentina [año actual]`

🔗 Buscador de carreras: https://www.argentina.gob.ar/educacion/universidades
Fuente: busqueda web — 4 may 2026
```

---

### `/educacion certificaciones cloud`

```
📜 Certificaciones — Cloud
   Dato al 4 may 2026

MAS PEDIDAS EN EL MERCADO ARGENTINO
  AWS Solutions Architect Associate — Amazon Web Services
    Nivel: intermedio | La mas pedida en ofertas de trabajo tech en AR
    Costo del examen: ~USD 150
    Preparacion gratuita: aws.amazon.com/training/digital/

  Google Cloud Associate Cloud Engineer — Google
    Nivel: intermedio | Crece fuerte en empresas medianas
    Costo del examen: ~USD 200
    Preparacion gratuita: cloud.google.com/training/free

  Azure Fundamentals (AZ-900) — Microsoft
    Nivel: basico | Buena entrada si ya usas productos Microsoft
    Costo del examen: ~USD 165
    Preparacion gratuita: learn.microsoft.com (Microsoft Learn)

PROGRAMAS GRATUITOS EN ARGENTINA
  Argentina Programa — incluye modulos de cloud e infraestructura
  WebSearch: `Argentina Programa [año actual] cloud inscripcion`

PLATAFORMAS DE PREPARACION SIN COSTO
  A Cloud Guru (trial): acloudguru.com
  freeCodeCamp: freecodecamp.org — modulos de AWS y DevOps
  YouTube — canales: TechWorld with Nana, AWS con Fafis (en español)

Fuente: busqueda web — 4 may 2026
```

---

### `/educacion ingles`

```
🌐 Ingles — Recursos Gratuitos
   Dato al 4 may 2026

PLATAFORMAS SIN COSTO
  Duolingo:             duolingo.com — habito diario, bueno para principiantes
  BBC Learning English: bbc.co.uk/learningenglish — comprension auditiva real
  British Council:      learnenglish.britishcouncil.org — por nivel (A1 a C1)
  LibreVox:             librivox.org — audiolibros en ingles (intermedio/avanzado)
  Cambridge English:    cambridgeenglish.org/learning-english — preparacion oficial

PROGRAMAS OFICIALES
  Embajada de EE.UU. — English Access Microscholarship (para jovenes 14–18)
  Buscar activos: WebSearch "ingles gratuito Argentina gobierno 2026"

CERTIFICACIONES
  Cambridge B1 Preliminary — preparacion gratuita en cambridgeenglish.org
  IELTS / TOEFL — requeridos para posgrados en el exterior

CAMINO PRACTICO
  Principiante:  Duolingo 15 min/dia + BBC Learning English (episodios cortos)
  Intermedio:    6 Minute English (BBC Podcast) + series con subtitulos en ingles
  Avanzado:      Leer prensa en ingles (The Guardian, BBC) + conversacion con nativos

Fuente: busqueda web — 4 may 2026
```

## Fuentes

- **Becas Progresar:** [becasprogresar.educacion.gob.ar](https://becasprogresar.educacion.gob.ar)
- **Becas del Estado:** [argentina.gob.ar/educacion/becas](https://www.argentina.gob.ar/educacion/becas)
- **Buscador de carreras:** [argentina.gob.ar/educacion/universidades](https://www.argentina.gob.ar/educacion/universidades)
- **Argentina Programa:** [argentina.gob.ar/economia/conocimiento/argentina-programa](https://www.argentina.gob.ar/economia/conocimiento/argentina-programa)

Este plugin no almacena ni transmite informacion del usuario. Montos y fechas de becas se consultan en tiempo real — nunca hardcodeados.
