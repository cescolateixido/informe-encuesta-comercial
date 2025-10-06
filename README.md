# Informe Encuesta Comercial

Este repositorio contiene un informe dinámico generado en RMarkdown a partir de respuestas recopiladas en una hoja de Google Sheets. El informe incluye visualizaciones clave sobre digitalización, etapas educativas y el interés en nuevos proyectos editoriales.

---

## 📦 Requisitos

Antes de compilar el informe, asegúrate de tener instalado:

- R (versión 4.0 o superior)
- Paquetes R necesarios:
  - `tidyverse`
  - `googlesheets4`
  - `rmarkdown`
  - `kableExtra`

Puedes instalar todos los paquetes con:

```r
install.packages(c("tidyverse", "googlesheets4", "rmarkdown", "kableExtra"))
Rscript compilar_informe.R
informe-encuesta/
├── informe.Rmd              # Código fuente del informe
├── informe.html             # Informe generado
├── compilar_informe.R       # Script para compilar y abrir el informe
├── .secrets/                # Token de autenticación (no compartir)
└── README.md                # Este archivo
