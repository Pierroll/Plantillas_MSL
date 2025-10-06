# Plantillas_MSL — Plantillas para Mapeos Sistemáticos / Scoping Reviews (estudiantes)

Repo público con **plantillas listas** por fases para conducir un **Mapeo Sistemático de Literatura (MSL)** o **Scoping Review** orientado a estudiantes (Ing. de Software y áreas afines).

> Si tu estudio es clínico con metaanálisis u otra variante, adapta las plantillas (PRISMA 2020, PROSPERO, AMSTAR-2, RoB2, etc.).

## 📁 Estructura
```
└── 📁Repositorio_General
    └── 📁CHECKLIST FINAL
        ├── checklist_final_entregables.md
    └── 📁Fase 1 - Protocolo
        ├── osf_registro_checklist.md
        ├── protocolo_mapeo_herramientas_screening.md
    └── 📁Fase 2 - Búsqueda
        ├── cadenas_busqueda_completas.xlsx
        ├── log_busqueda.md
    └── 📁Fase 3 - Screening
        ├── acuerdo_interevaluador.md
        ├── estudios_excluidos_textocompleto.xlsx
        ├── prisma_flow_template.md
    └── 📁Fase 4 - Clasificación y Extracción
        ├── base_datos_extraccion_completa.xlsx
        ├── esquema_clasificacion.md
        ├── justificaciones_clasificacion_muestra.md
    └── 📁Fase 5 - Análisis
        ├── analisis_temporal.xlsx
        ├── brechas_identificadas.md
        ├── matriz_fase_pricing.xlsx
        ├── tablas_frecuencias.xlsx
    └── 📁Fase 6 - Visualisación
        ├── visualizaciones_readme.md
    └── 📁Fase 7 - Reporte
        ├── capitulo_mapeo_sistematico_outline.md
        ├── prisma_scr_checklist_placeholder.md
    └── 📁PRODUCTOS SUPLEMENTARIOS
        ├── lista_estudios_incluidos.xlsx
    ├── .gitignore
    ├── LICENSE
    └── README.md
```
## 🚀 Uso rápido
1. **Protocolo (Fase 1):** completa `protocolo_mapeo_herramientas_screening.md` y registra en OSF (checklist incluido).
2. **Búsqueda (Fase 2):** documenta `cadenas_busqueda_completas.xlsx`, exporta `.RIS/.BIB` y escribe `log_busqueda.md`.
3. **Screening (Fase 3):** llena plantilla de números PRISMA, usa `estudios_excluidos_textocompleto.xlsx` y calcula **Kappa**.
4. **Extracción (Fase 4):** centraliza en `base_datos_extraccion_completa.xlsx` y normaliza con `esquema_clasificacion.md`.
5. **Análisis (Fase 5):** usa `tablas_frecuencias.xlsx`, `matriz_fase_pricing.xlsx`, `analisis_temporal.xlsx` para tus gráficas.
6. **Visualización (Fase 6):** genera heatmaps, bubble plots y barras (ver `fase-6-visualizacion/visualizaciones_readme.md`).
7. **Reporte (Fase 7):** escribe tu capítulo con `capitulo_mapeo_sistematico_outline.md` y marca **PRISMA-ScR**.

## 📦 Clonar
```bash
git clone https://github.com/Pierroll/Plantillas_MSL.git
cd Plantillas_MSL
🧭 Convenciones de nombres
minúsculas y guiones: base_datos_extraccion_completa.xlsx

nada de espacios; evita tildes en nombres de archivo

datos sensibles no se suben (usa OSF público cuando aplique)

🧪 Adaptaciones comunes
Clínico con metaanálisis: PROSPERO, PRISMA 2020, AMSTAR-2, RoB2, forest/funnel plots.

Cualitativo/meta-síntesis: CASP/JBI, ENTREQ/COREQ, síntesis temática.

Observacionales: STROBE, ROBINS-I.

Humanidades/Derecho: más literatura gris, bases jurídicas.

🤝 Contribuir
Lee CONTRIBUTING.md para estilo de ramas/commits y PRs.

📝 Licencia
MIT — uso y adaptación académica permitidos. Atribuye si te fue útil 🙌

go
Copiar código

### `CONTRIBUTING.md`
```markdown
# Guía de Contribución

¡Gracias por tu interés en mejorar estas plantillas! Este repo busca ofrecer recursos **claros y prácticos** para estudiantes.

## 🧭 Flujo de trabajo
1. **Issue primero**: abre un Issue describiendo la mejora/bug.
2. **Rama** desde `main`:
   - `feat/<descripcion-corta>` para nuevas plantillas o mejoras
   - `fix/<descripcion-corta>` para arreglos
3. **PR pequeño** y descriptivo, vinculado al Issue.

## ✍️ Estilo de commits (Conventional Commits)
- `feat:` nueva plantilla o funcionalidad
- `fix:` corrección
- `docs:` cambios en README/guías
- `chore:` mantenimiento/limpieza

Ejemplos:
feat(fase-4): agregar columnas de validación a base de extracción
fix(fase-3): corregir encabezados en estudios_excluidos_textocompleto.xlsx
docs(readme): aclarar pasos para PRISMA-ScR

markdown
Copiar código

## 🌿 Ramas y PRs
- Base: `main`
- Mantén PRs pequeños (<300 líneas si es posible) y enfocados en un objetivo.
- Incluye ejemplos/archivos de muestra si agregas columnas o formatos nuevos.

## 🧱 Estándares de archivos
- **Nombres**: minúsculas y guiones (`kebab-case`), sin espacios.
- **Formatos preferidos**: `.md`, `.xlsx`, `.csv`, `.docx` (plantillas mínimas); evita binarios pesados.
- **Estructura**: coloca cada archivo en su **fase** correspondiente.

## 🔐 Datos y privacidad
- No subas datos personales/sensibles.
- Para datasets grandes o resultados, usa OSF como repositorio público y enlaza.

## 🧪 Versionado
- **SemVer**: `vMAJOR.MINOR.PATCH`
- Etiqueta versiones estables:
  ```bash
  git tag -a v1.0.0 -m "Primera versión pública"
  git push origin v1.0.0
✅ Checklist para PR
 Archivos ubicados en la carpeta correcta por fase

 Nombres de archivo en kebab-case

 README/guía actualizada si cambias flujos

 Ejemplo mínimo incluido (si aplica)

📄 Licencia
Al contribuir aceptas que tu aporte se licencie bajo MIT.

cpp
Copiar código
