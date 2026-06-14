# Codex Skills & AI Workflows

Repositorio maestro de mi línea de trabajo para organizar skills, flujos asistidos por IA y activos reutilizables aplicados a trabajo técnico.

Estoy usando este espacio para construir, ordenar y documentar una capa propia de capacidades reutilizables para acelerar trabajo profesional en calidad, excelencia operacional, analítica, documentación técnica y automatización asistida por IA.

El objetivo no es acumular pruebas sueltas. El objetivo es convertir criterio técnico en herramientas, plantillas, diagramas, flujos y skills que pueda reutilizar en proyectos reales.

---

## Propósito

Este repo organiza una línea de trabajo en desarrollo orientada a crear skills que ayuden a producir artefactos técnicos útiles:

- diagramas editables;
- plantillas técnicas;
- automatizaciones documentales;
- flujos de análisis;
- generadores de activos;
- asistentes especializados para calidad, OPEX, analítica y sistemas de gestión.

La tecnología aquí se entiende como soporte al criterio profesional. No reemplaza validación, trazabilidad ni responsabilidad técnica.

---

## Ubicación dentro del portfolio

Este repositorio pertenece a la línea:

```text
Codex Skills / AI Workflows
```

Dentro del ecosistema general de GitHub, esta es la estructura que estoy construyendo:

```text
fjgonzalezmgt/

Core Portfolio
├── quality-analytics-toolkit
├── qms-intelligence
└── operational-analytics-automation

Codex Skills / AI Workflows
├── Codex-Skills-AI-Workflows        # índice maestro de esta línea
├── drawingskills                    # activo: diagramas draw.io editables desde Codex
├── writingskills                    # activo: artículos, newsletters, guías, manuales y libros en LaTeX
├── codex-qms-skills                 # en desarrollo: QMS, CAPA, auditorías, documentación
├── codex-quality-tools-skills       # en desarrollo: SPC, MSA, FMEA, DOE, causa raíz
├── codex-analytics-skills           # en desarrollo: analítica, BI, datos y automatización
└── codex-documentation-skills       # en desarrollo: documentación técnica y activos estructurados

Applied Analytics Projects
├── voice-of-customer-analytics
├── supply-chain-analytics
└── powerbi-python-projects

Learning / Experiments
├── notebooks
├── prototypes
└── small-tests
```

---

## Estado actual de la línea

| Repo | Estado | Función |
|---|---|---|
| [drawingskills](https://github.com/fjgonzalezmgt/drawingskills) | Activo | Crear diagramas editables de draw.io/diagrams.net desde Codex. |
| [writingskills](https://github.com/fjgonzalezmgt/writingskills) | Activo | Crear artículos, newsletters, guías, manuales y libros a partir de plantillas LaTeX de Quality Analytics. |
| `codex-qms-skills` | En desarrollo | Skills para QMS, CAPA, auditorías, evidencia y documentación técnica. |
| `codex-quality-tools-skills` | En desarrollo | Skills para herramientas de calidad como SPC, MSA, FMEA, DOE y causa raíz. |
| `codex-analytics-skills` | En desarrollo | Skills para análisis de datos, KPIs, validación de consistencia y documentación de pipelines. |
| `codex-documentation-skills` | En desarrollo | Skills para documentación técnica, SOPs, checklists, formatos y materiales de formación. |

La intención es avanzar esta línea de forma gradual. Primero consolido casos de uso claros, después los convierto en skills estables y finalmente los separo en repos propios cuando ya tienen estructura, ejemplos y criterios de validación.

---

## Repos activos

### [drawingskills](https://github.com/fjgonzalezmgt/drawingskills)

Librería de skills para crear diagramas editables de draw.io/diagrams.net desde Codex.

Incluye capacidades para:

- Lean Six Sigma;
- mejora continua;
- calidad;
- SIPOC, VSM, DMAIC, PDCA, A3, Ishikawa/fishbone y swimlanes;
- arquitectura técnica;
- infraestructura, cloud y Kubernetes;
- analítica, BI, lakehouse y MLOps;
- bibliotecas reutilizables de shapes.

Uso principal:

```text
Convertir descripciones técnicas en diagramas editables, versionables y reutilizables.
```

### [writingskills](https://github.com/fjgonzalezmgt/writingskills)

Skill de Codex para crear artículos, newsletters, guías, manuales y libros a partir de plantillas LaTeX de Quality Analytics.

Incluye capacidades para:

- generación de proyectos LaTeX para artículos y newsletters;
- generación de proyectos LaTeX para libros, guías, manuales o cursos;
- uso de plantillas editoriales reutilizables;
- estructura de capítulos, figuras y metadatos;
- instalación de la skill en el entorno local de Codex;
- soporte para documentos técnicos en español o inglés.

Uso principal:

```text
Convertir conocimiento técnico en documentos estructurados, editables y consistentes con la línea editorial de Quality Analytics.
```

---

## Skills en desarrollo

Esta sección documenta los frentes que estoy construyendo dentro de esta línea. No son ideas externas ni una lista aspiracional; son áreas de trabajo que iré convirtiendo en repos o módulos conforme maduren.

### codex-qms-skills

Trabajo en desarrollo para asistir tareas relacionadas con sistemas de gestión de calidad.

Capacidades en construcción:

- análisis de procedimientos;
- preparación de auditorías;
- clasificación de hallazgos;
- soporte a CAPA;
- trazabilidad documental;
- revisión de evidencia;
- estructura de SOPs e instructivos.

### codex-quality-tools-skills

Trabajo en desarrollo para herramientas clásicas de calidad y mejora continua.

Capacidades en construcción:

- SPC;
- MSA / Gage R&R;
- FMEA / AMEF;
- DOE;
- causa raíz;
- Pareto;
- AQL;
- planes de control;
- análisis de capacidad.

### codex-analytics-skills

Trabajo en desarrollo para analítica aplicada a operaciones.

Capacidades en construcción:

- limpieza y perfilado de datos;
- generación de KPIs;
- validación de consistencia;
- análisis exploratorio;
- preparación de datasets;
- interpretación de resultados;
- documentación de pipelines.

### codex-documentation-skills

Trabajo en desarrollo para documentación técnica y activos estructurados.

Este frente se diferencia de `writingskills` porque no se limita a crear proyectos LaTeX. Su foco será asistir flujos documentales específicos: SOPs, checklists, formatos técnicos, reportes de auditoría, documentación de proyectos y materiales de formación.

Capacidades en construcción:

- generación de guías;
- reportes técnicos;
- checklists;
- formatos de auditoría;
- documentación de proyectos;
- resúmenes ejecutivos;
- materiales de formación.

---

## Criterios para activar un nuevo repo de skills

Antes de separar un frente de trabajo en un repo propio, valido estas preguntas:

1. Qué trabajo técnico acelera?
2. Qué artefacto produce?
3. Qué criterio profesional requiere validación humana?
4. Qué datos, entradas o contexto necesita?
5. Qué riesgos existen si se usa mal?
6. Cómo se valida la salida?
7. Puede reutilizarse en más de un proyecto?

Si la respuesta no es clara, lo mantengo como experimento o módulo interno antes de convertirlo en repo independiente.

---

## Estándar mínimo de cada skill repo

Cada repositorio de skills debe incluir:

```text
README.md
skills/
examples/
references/
scripts/
tests/ or validation/
```

Y documentar:

- propósito;
- alcance;
- instalación;
- prompts de uso;
- ejemplos;
- criterios de validación;
- límites conocidos;
- riesgos de uso;
- oportunidades futuras.

---

## Principios de diseño

### 1. Artefactos editables sobre salidas cerradas

Siempre que sea posible, las skills deben producir archivos editables, versionables y auditables.

Ejemplos:

- `.drawio` en lugar de imágenes planas;
- `.tex` y `.md` en lugar de texto suelto;
- `.json` o `.yaml` cuando convenga trazabilidad;
- scripts reutilizables en lugar de pasos manuales repetidos.

### 2. Criterio técnico antes que automatización

Una skill solo tiene valor si mejora una decisión, reduce fricción o aumenta consistencia.

Automatizar sin criterio solo acelera variabilidad.

### 3. Validación explícita

Todo flujo debe tener algún mecanismo de validación:

- validación estructural;
- revisión humana;
- pruebas de ejemplo;
- criterios de aceptación;
- comparación contra fuentes o requisitos.

### 4. Separación entre exploración y capacidad estable

No todo experimento merece convertirse en skill.

Una skill debe ser reutilizable, explicable y suficientemente estable para documentarse.

---

## Relación con Quality Analytics

Esta línea de repos complementa el posicionamiento de Quality Analytics:

```text
Calidad + OPEX + Data Analytics + IA aplicada
```

Su función es convertir conocimiento técnico en capacidades operativas reutilizables.

La aplicación principal está en:

- sistemas de gestión de calidad;
- mejora continua;
- analítica aplicada;
- documentación técnica;
- automatización de reportes;
- visualización de procesos;
- soporte a decisiones operativas.

---

## Roadmap de trabajo

### Fase 1 - Base de la línea

- Consolidar este repo como índice maestro.
- Mantener `drawingskills` como primer repo activo de la línea.
- Integrar `writingskills` como skill activa para producción documental.
- Definir convención de nombres para repos en desarrollo.

### Fase 2 - Estandarización

- Crear plantilla base para repos de skills.
- Definir README mínimo.
- Crear checklist de validación.
- Documentar estructura recomendada de carpetas.

### Fase 3 - Desarrollo de nuevos frentes

- Desarrollar skills para QMS.
- Desarrollar skills para herramientas de calidad.
- Desarrollar skills para analítica aplicada.
- Desarrollar skills para documentación técnica.

### Fase 4 - Integración con activos profesionales

- Conectar skills con guías, plantillas y casos de Quality Analytics.
- Crear ejemplos orientados a problemas reales de calidad, operaciones y datos.
- Publicar casos demostrables en el portfolio técnico.

---

## Convención de nombres

Para repos de esta línea:

```text
codex-[dominio]-skills
```

Repos activos con nombre histórico:

```text
drawingskills
writingskills
```

Repos en desarrollo:

```text
codex-qms-skills
codex-quality-tools-skills
codex-analytics-skills
codex-documentation-skills
codex-powerbi-skills
codex-python-automation-skills
```

Para los repos activos existentes, una opción futura sería renombrarlos a:

```text
codex-drawio-skills
codex-writing-skills
```

No es obligatorio hacerlo de inmediato. Lo importante es mantener clara su función dentro de esta línea.

---

## Nota de uso

Este repositorio no reemplaza los proyectos principales del portfolio.

Funciona como capa de infraestructura profesional para construir, probar y organizar skills que puedan apoyar mejores decisiones, documentación más consistente y artefactos técnicos reutilizables.
