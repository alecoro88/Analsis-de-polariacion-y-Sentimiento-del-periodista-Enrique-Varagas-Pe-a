# Análisis de Polarización y Sentimiento en Facebook - Enrique Vargas Peña

Este repositorio contiene un proyecto académico de PLN donde se analizan las publicaciones del periodista paraguayo Enrique Vargas Peña y las respuestas de los usuarios en Facebook.

## Contenido
- Análisis de sentimiento con modelos RoBERTuito
- Agrupamiento temático con KMeans y t-SNE
- Visualizaciones (heatmaps, t-SNE, barras apiladas)
- Métricas IAE, ICE y TCV

## Archivos
- `Proyecto_TopicsII.ipynb`: Notebook principal
- `facebook.csv`: Corpus base extraído
- `publicaciones_analisis_sentimiento.csv`: Datos enriquecidos
- `Analisis_Sentimiento_VargasPena.docx`: Informe académico completo
- `images/`: Visualizaciones principales

## Requisitos
```bash
pip install pandas matplotlib seaborn sklearn spacy pysentimiento transformers
