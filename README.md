# TFM: Integración multiómica en lupus

Repositorio del Trabajo de Fin de Máster centrado en la integración de datos transcriptómicos, proteómicos séricos y variables clínicas en una cohorte propia de pacientes con lupus eritematoso sistémico (LES).

## Objetivo

Analizar la relación entre perfiles moleculares y actividad clínica mediante estrategias de integración multiómica, con especial interés en biomarcadores y firmas asociadas al LES.

## Estructura del repositorio

```text
.
├── data/        # Datos de entrada
├── scripts/     # Scripts de análisis en R Markdown
├── results/     # Resultados generados (HTML, PDF, etc.)
└── styles/      # Archivos de estilo y formato
```

## Contenido

- `data/`: archivos de datos utilizados como entrada del análisis.  
- `scripts/`: informes y análisis en formato `.Rmd`.  
- `results/`: resultados exportados; incluye informes HTML y, en el futuro, memoria y presentación en PDF.  
- `styles/`: archivos auxiliares de formato, como `apa.csl` y `estilos.css`.

## Reproducibilidad

El repositorio está organizado para separar datos, código y resultados, siguiendo una estructura orientada a la trazabilidad y la reproducibilidad del análisis bioinformático.

## Consideraciones sobre los datos

Los datos clínicos y ómicos pueden estar sujetos a restricciones éticas y de confidencialidad. Por ello, este repositorio puede no incluir todos los datos originales y prioriza la documentación del flujo de análisis y de los resultados derivados.
