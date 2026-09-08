---
name: gobierno-corporativo-compliance-cl
description: Activa cuando el usuario trabaja compliance penal/económico, Modelo de Prevención de Delitos (MPD), Ley 21.595 (Delitos Económicos), Ley 20.393 (Responsabilidad Penal de Personas Jurídicas), Ley 19.913 (UAF, lavado de activos), Ley 21.459 (Delitos Informáticos, ángulo de responsabilidad penal empresarial), gobierno corporativo, directorios, NCG 461 CMF (ESG/sostenibilidad), canal de denuncias, código de ética, o evaluar si un programa de cumplimiento es efectivo. **NO activa para** protección de datos personales/Ley 19.628-21.719 — usar `proteccion-datos-personales-cl`; **NO activa para** ciberseguridad técnica/Ley 21.663 — usar `infraestructura-ciberseguridad`; **NO activa para** gobernanza de IA — usar `gobernanza-ia-cl`; **NO activa para** probidad del sector público — usar 01-edu-administracion-publica-phd.
---

# Gobierno Corporativo y Compliance Penal/Económico (Chile) — experta autónoma

Skill de referencia legal, verificada artículo por artículo contra la Ley 21.595 (que sustituye el
núcleo de la Ley 20.393), la Ley 19.913 (UAF) y la NCG 461 (CMF) — enriquecida con los G20/OCDE
Principles of Corporate Governance y la guía DOJ de evaluación de programas de cumplimiento. Absorbe el
eje penal/económico que antes vivía disperso — incluida la Ley 21.459 (Delitos Informáticos), reubicada
aquí desde `infraestructura-ciberseguridad` por ser derecho penal, no control técnico.

## Metodología de razonamiento

1. **Identificar si el hecho encaja en el catálogo de "delito económico"** (Ley 21.595 Art. 1°, remite a
   leyes sectoriales + Código Penal) — no razonar en abstracto sobre "gravedad económica".
2. **Verificar el presupuesto central de responsabilidad de la persona jurídica**: ¿el delito se vio
   "favorecido o facilitado" por la falta de un MPD efectivo (Art. 3° Ley 20.393)? Sin este nexo, no hay
   responsabilidad penal de la empresa aunque el delito haya ocurrido.
3. **Auditar el MPD contra los 4 elementos del Art. 4°** (identificación de riesgo, protocolos + canal de
   denuncia, responsable independiente, auditoría por terceros) — y contra las 3 preguntas DOJ (¿bien
   diseñado? ¿aplicado de buena fe con recursos reales? ¿funciona en la práctica?) para distinguir un MPD
   real de uno de papel.
4. **Distinguir MPD (Ley 20.393) de prevención de lavado de activos (Ley 19.913)** — regímenes paralelos,
   fiscalizadores distintos (tribunales/Ministerio Público vs. UAF), pueden coexistir en una misma
   organización. Ver tabla comparativa en `references/especifico/`.
5. **Si hay un sistema informático involucrado en el delito**: evaluar si encaja en la Ley 21.459
   (delitos informáticos) — y si el MPD había identificado ese riesgo específico (Art. 4° N°1).
6. **Si la organización es emisor de valores/fiscalizada por la CMF**: verificar obligaciones de la NCG
   461 (Memoria Anual, ESG) — no aplica a la generalidad de organizaciones (ej. no aplica a un SLEP).
7. **Enriquecer con OCDE/DOJ solo después de resolver con la ley chilena** — nunca presentar un principio
   OCDE o un criterio DOJ como si fuera obligación legal chilena por sí solo.
8. **Generar documentos** (matriz de riesgos, código de ética, reglamento de canal de denuncias, acta de
   encargado de prevención, modelo de prevención de delitos) solo después de resolver 1-6 — nunca generar
   una plantilla sin haber verificado primero qué exige el Art. 4° para ESE caso concreto.

**Regla de cierre**: citar artículo exacto y verificar contra `sources/especifico/` antes de cualquier
juicio de "tiene/no tiene MPD adecuado" — es una determinación de alto riesgo (afecta responsabilidad
penal), nunca una opinión genérica.

## Tabla de decisión
| La tarea trata de… | Ir a |
|---|---|
| Qué es delito económico, responsabilidad de la persona jurídica, MPD (4 elementos), penas | `references/especifico/mapa-delitos-economicos-mpd.md` |
| Delitos informáticos con ángulo de responsabilidad penal empresarial | `references/especifico/mapa-delitos-economicos-mpd.md` (sección Ley 21.459) |
| Prevención de lavado de activos, UAF, sujetos obligados, ROS | `references/especifico/mapa-delitos-economicos-mpd.md` (sección Ley 19.913 + tabla comparativa) |
| Memoria Anual, ESG, gobierno corporativo para emisores CMF | `references/especifico/mapa-delitos-economicos-mpd.md` (sección NCG 461) |
| Evaluar si un programa de compliance es "real" o de papel | `references/complementario/crosswalk-ocde-doj.md` (3 preguntas DOJ) |
| Responsabilidades del directorio, disclosure, sostenibilidad (marco comparado) | `references/complementario/crosswalk-ocde-doj.md` (6 capítulos OCDE) |
| Generar plantilla de documento (matriz riesgos, código ética, canal denuncias, MPD) | `plantillas/ley-21595/templates/` |
| Ciberseguridad técnica, control del sistema | skill `infraestructura-ciberseguridad` |
| Protección de datos personales | skill `proteccion-datos-personales-cl` |
| Gobernanza de IA | skill `gobernanza-ia-cl` |

## Reglas de oro
1. La responsabilidad penal de la empresa depende del nexo "favorecido o facilitado por falta de MPD" —
   no basta con que el delito haya ocurrido dentro de la organización.
2. Un MPD "de papel" (documento sin aplicación real ni auditoría externa) no cumple el Art. 4° — aplicar
   las 3 preguntas DOJ para verificarlo.
3. MPD (responsabilidad penal general) y prevención de lavado de activos (UAF) son regímenes distintos,
   pueden coexistir — no asumir que uno cubre al otro.
4. La pena de extinción de la persona jurídica NO aplica a empresas públicas creadas por ley ni a
   servicios de utilidad pública cuya interrupción cause daño grave (Art. 9°) — relevante para SLEP.
5. NCG 461 (CMF) no aplica a toda organización — solo a emisores de valores y entidades fiscalizadas por
   la CMF.
6. Nunca presentar OCDE/DOJ como obligación legal chilena — son método de evaluación, no ley.

## Fuentes — capa específica (íntegras, integridad verificada)
- `sources/especifico/ley-21595-delitos-economicos.pdf` — 28 págs., Ley 21.595 (BCN, 17-ago-2023) —
  sustituye Arts. 2-12 de la Ley 20.393, vigente desde 1-sep-2024.
- `sources/especifico/ley-20393-responsabilidad-penal-personas-juridicas.pdf` — 16 págs., texto original
  2009 (BCN) — leer junto con las sustituciones de la Ley 21.595, no aislado.
- `sources/especifico/ley-19913-uaf-lavado-activos.pdf` — 24 págs. (BCN).
- `sources/especifico/ley-21459-delitos-informaticos.pdf` — 6 págs. (BCN) — reubicada desde
  `infraestructura-ciberseguridad`.
- `sources/especifico/ncg-461-2021-cmf-sostenibilidad-gobierno-corporativo.pdf` (29 chunks) +
  `ncg-519-2024-cmf-modifica-461.pdf` (6 chunks) — CMF, oficiales.

## Fuentes — capa complementaria
- `sources/complementario/doj-evaluation-corporate-compliance-programs-2024.pdf` — DOJ EE.UU.,
  actualizado sep-2024, oficial y gratuito.
- `sources/complementario/oecd-g20-principios-gobierno-corporativo-2023.pdf` — OCDE/G20, oficial y
  gratuito.
- **Pendiente de adquisición (de pago, no descargadas)**: ISO 37301 (sistemas de gestión de compliance),
  ISO 37001 (antisoborno), ISO 31000 (gestión de riesgos).
- **Libros solicitados, no localizados como copia legítima**: "The Handbook of Compliance", "Corporate
  Governance" (Monks & Minow), "Compliance 360°" — comerciales, no se buscan copias no autorizadas.

## Plantillas heredadas de `compliance-cl` (repo de terceros, retirado 2026-09-08)
`compliance-cl` era un repo git de un tercero (`Lelemon-studio/compliance-cl`, MIT), no de Pepe — por eso
se retiró completo de `~/.claude/skills/` (archivado en `~/.claude/skills_deprecated/`) y sus dos packs
de plantillas se repartieron a las skills propias de cada dominio: `packs/ley-21595/` (5 plantillas:
acta encargado prevención, código de ética, matriz de riesgos, modelo de prevención de delitos,
reglamento canal de denuncias) → `plantillas/ley-21595/` de esta skill; `packs/ley-21719/` (8 plantillas
de datos personales) → `proteccion-datos-personales-cl/plantillas/ley-21719/`. También se heredó
`plantillas/controls.md` (crosswalk de controles entre 21.719/21.595/ISO/SOC2, copiado a ambas skills) y
metodología operativa de apoyo (`metodologia-base-heredada.md`, `output-model.md`,
`cuando-acudir-a-abogado.md`, `revisiones-periodicas.md`, `instructivo-situaciones.md`) — contenido de
terceros, no re-verificado línea por línea contra `sources/especifico/`, usar como apoyo operativo, no
como fuente citable con el mismo estándar que `references/especifico/`. Nota de calidad verificada
2026-09-08: `plantillas/ley-21595/templates/modelo-prevencion-delitos.md` alinea correctamente con los 4
elementos del Art. 4° ya verificado — la única imprecisión detectada es que `pack.md` sugiere
"supervisión externa **anual**" cuando el texto literal del Art. 4° N°4 dice solo "evaluaciones
periódicas" sin frecuencia fija — tratar "anual" como buena práctica sugerida, no como cita literal de
la ley.

## Grafo — con qué otras skills se combina y cómo
- **`proteccion-datos-personales-cl`** (independiente, dominios distintos): ambas skills pueden aplicar
  al mismo cliente simultáneamente (ej. una brecha de datos que además es delito informático) pero
  resuelven preguntas distintas — esta skill nunca interpreta la Ley 19.628/21.719.
- **`infraestructura-ciberseguridad`** (complementa): esa skill previene técnicamente el delito
  informático; esta skill resuelve la responsabilidad penal de la empresa si ocurre igual.
- **`gobernanza-ia-cl`** (complementa): si el proyecto de ley de IA finalmente asigna fiscalización a la
  Agencia de Protección de Datos (ver `gobernanza-ia-cl`), podría cruzar con el régimen de responsabilidad
  penal de esta skill si el uso de IA configura un delito económico.
- **01-edu-administracion-publica-phd** (deriva-a): probidad del sector público es un régimen distinto
  (Ley 20.880), no delitos económicos — derivar ahí si la consulta es sobre probidad pública, no penal.
- Matriz de riesgo institucional general (metodología CAIGG DT-70): sin skill activa por ahora (la
  skill dedicada quedó retirada, pendiente reconstrucción) — la matriz de riesgo de delito (Art. 4° N°1)
  queda autónoma en esta skill mientras tanto.
