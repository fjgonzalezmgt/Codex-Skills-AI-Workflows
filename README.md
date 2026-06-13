# Codex Skills & AI Workflows

Repositorio maestro para organizar skills, flujos de trabajo y activos reutilizables de IA aplicada a trabajo tecnico.

El objetivo no es acumular experimentos sueltos. El objetivo es construir una capa de capacidades reutilizables para acelerar trabajo profesional en calidad, excelencia operacional, analitica, documentacion tecnica y automatizacion asistida por IA.

Este repositorio funciona como indice estrategico de la familia de repos relacionados con Codex Skills y AI Workflows.

---

## Proposito

Crear una estructura ordenada para desarrollar, documentar y mantener skills que ayuden a convertir criterio tecnico en artefactos utiles:

- diagramas editables;
- plantillas tecnicas;
- automatizaciones documentales;
- flujos de analisis;
- generadores de activos;
- asistentes especializados para calidad, OPEX, analitica y sistemas de gestion.

La tecnologia aqui se entiende como soporte al criterio profesional. No reemplaza validacion, trazabilidad ni responsabilidad tecnica.

---

## Ubicacion dentro del portfolio

Este repositorio pertenece a la linea:

```text
Codex Skills / AI Workflows
```

Dentro del ecosistema general de GitHub, la estructura queda asi:

```text
fjgonzalezmgt/

Core Portfolio
├── quality-analytics-toolkit
├── qms-intelligence
└── operational-analytics-automation

Codex Skills / AI Workflows
├── Codex-Skills-AI-Workflows        # indice maestro de esta linea
├── drawingskills                    # skills para crear diagramas draw.io editables desde Codex
├── codex-qms-skills                 # futuro: QMS, CAPA, auditorias, documentacion
├── codex-quality-tools-skills       # futuro: SPC, MSA, FMEA, DOE, causa raiz
├── codex-analytics-skills           # futuro: analitica, BI, datos y automatizacion
└── codex-documentation-skills       # futuro: guias, reportes, SOPs, formatos tecnicos

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

## Repos activos

### drawingskills

Libreria de skills para crear diagramas editables de draw.io/diagrams.net desde Codex.

Incluye capacidades para:

- Lean Six Sigma;
- mejora continua;
- calidad;
- SIPOC, VSM, DMAIC, PDCA, A3, Ishikawa/fishbone y swimlanes;
- arquitectura tecnica;
- infraestructura, cloud y Kubernetes;
- analitica, BI, lakehouse y MLOps;
- bibliotecas reutilizables de shapes.

Uso principal:

```text
Convertir descripciones tecnicas en diagramas editables, versionables y reutilizables.
```

Repositorio:

```text
https://github.com/fjgonzalezmgt/drawingskills
```

---

## Repos futuros sugeridos

### codex-qms-skills

Skills para asistir trabajo relacionado con sistemas de gestion de calidad.

Posibles capacidades:

- analisis de procedimientos;
- preparacion de auditorias;
- clasificacion de hallazgos;
- soporte a CAPA;
- trazabilidad documental;
- revision de evidencia;
- estructura de SOPs e instructivos.

### codex-quality-tools-skills

Skills para herramientas clasicas de calidad y mejora continua.

Posibles capacidades:

- SPC;
- MSA / Gage R&R;
- FMEA / AMEF;
- DOE;
- causa raiz;
- Pareto;
- AQL;
- planes de control;
- analisis de capacidad.

### codex-analytics-skills

Skills para analitica aplicada a operaciones.

Posibles capacidades:

- limpieza y perfilado de datos;
- generacion de KPIs;
- validacion de consistencia;
- analisis exploratorio;
- preparacion de datasets;
- interpretacion de resultados;
- documentacion de pipelines.

### codex-documentation-skills

Skills para convertir conocimiento tecnico en documentos consistentes.

Posibles capacidades:

- generacion de guias;
- reportes tecnicos;
- checklists;
- formatos de auditoria;
- documentacion de proyectos;
- resumenes ejecutivos;
- materiales de formacion.

---

## Criterios para crear un nuevo repo de skills

Antes de crear un nuevo repositorio, debe existir una respuesta clara a estas preguntas:

1. Que trabajo tecnico acelera?
2. Que artefacto produce?
3. Que criterio profesional requiere validacion humana?
4. Que datos, entradas o contexto necesita?
5. Que riesgos existen si se usa mal?
6. Como se valida la salida?
7. Puede reutilizarse en mas de un proyecto?

Si la respuesta no es clara, conviene mantenerlo como experimento dentro de un repo existente antes de separarlo.

---

## Estandar minimo de cada skill repo

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

- proposito;
- alcance;
- instalacion;
- prompts de uso;
- ejemplos;
- criterios de validacion;
- limites conocidos;
- riesgos de uso;
- oportunidades futuras.

---

## Principios de diseno

### 1. Artefactos editables sobre salidas cerradas

Siempre que sea posible, las skills deben producir archivos editables, versionables y auditables.

Ejemplos:

- `.drawio` en lugar de imagenes planas;
- `.md` en lugar de texto suelto;
- `.json` o `.yaml` cuando convenga trazabilidad;
- scripts reutilizables en lugar de pasos manuales repetidos.

### 2. Criterio tecnico antes que automatizacion

Una skill solo tiene valor si mejora una decision, reduce friccion o aumenta consistencia.

Automatizar sin criterio solo acelera variabilidad.

### 3. Validacion explicita

Todo flujo debe tener algun mecanismo de validacion:

- validacion estructural;
- revision humana;
- pruebas de ejemplo;
- criterios de aceptacion;
- comparacion contra fuentes o requisitos.

### 4. Separacion entre exploracion y capacidad estable

No todo experimento merece convertirse en skill.

Una skill debe ser reutilizable, explicable y suficientemente estable para documentarse.

---

## Relacion con Quality Analytics

Esta linea de repos complementa el posicionamiento de Quality Analytics:

```text
Calidad + OPEX + Data Analytics + IA aplicada
```

Su funcion es convertir conocimiento tecnico en capacidades operativas reutilizables.

La aplicacion principal esta en:

- sistemas de gestion de calidad;
- mejora continua;
- analitica aplicada;
- documentacion tecnica;
- automatizacion de reportes;
- visualizacion de procesos;
- soporte a decisiones operativas.

---

## Roadmap inicial

### Fase 1 - Ordenar base

- Consolidar este repo como indice maestro.
- Documentar `drawingskills` como primer repo activo de la linea.
- Definir convencion de nombres para futuros repos.

### Fase 2 - Estandarizar estructura

- Crear plantilla base para repos de skills.
- Definir README minimo.
- Crear checklist de validacion.
- Documentar estructura recomendada de carpetas.

### Fase 3 - Expandir capacidades

- Crear skills para QMS.
- Crear skills para herramientas de calidad.
- Crear skills para analitica aplicada.
- Crear skills para documentacion tecnica.

### Fase 4 - Integrar con activos profesionales

- Conectar skills con guias, plantillas y casos de Quality Analytics.
- Crear ejemplos orientados a problemas reales de calidad, operaciones y datos.
- Publicar casos demostrables en el portfolio tecnico.

---

## Convencion de nombres recomendada

Para repos nuevos:

```text
codex-[dominio]-skills
```

Ejemplos:

```text
codex-qms-skills
codex-quality-tools-skills
codex-analytics-skills
codex-documentation-skills
codex-powerbi-skills
codex-python-automation-skills
```

Para el repo existente `drawingskills`, una opcion futura seria renombrarlo a:

```text
codex-drawio-skills
```

No es obligatorio hacerlo de inmediato. Lo importante es mantener clara su funcion dentro de esta linea.

---

## Nota de uso

Este repositorio no reemplaza los proyectos principales del portfolio.

Funciona como capa de infraestructura profesional para construir, probar y organizar skills que puedan apoyar mejores decisiones, documentacion mas consistente y artefactos tecnicos reutilizables.
