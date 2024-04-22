# SSN-and-Markov-Clustering-for-Constitutive-Protein-Design
/SSN-and-Markov-Clustering-for-Constitutive-Protein-Design
│
├── README.md                 # Instrucciones generales, descripción del proyecto y cómo ejecutarlo
├── environment.yml           # Especificaciones del entorno Conda para asegurar la reproducibilidad
├── requirements.txt          # Requerimientos de pip si hay dependencias no disponibles en Conda
│
├── data/                     # Datos utilizados y generados por el proyecto
│   ├── raw/                  # Datos crudos inalterados
│   └── processed/            # Datos procesados y listos para análisis
│
├── docs/                     # Documentación del proyecto
│   ├── project_report.pdf    # Reporte detallado del proyecto
│   └── meeting_notes.txt     # Notas de reuniones del equipo de proyecto
│
├── notebooks/                # Jupyter notebooks para análisis y visualización
│   ├── Exploratory_Analysis.ipynb
│   └── Results_Visualization.ipynb
│
├── scripts/                  # Scripts que forman la parte ejecutable del proyecto
│   ├── data_preparation.py   # Preparar y procesar datos
│   ├── markov_clustering.py  # Implementar el algoritmo de clustering
│   └── protein_design.py     # Scripts para el diseño de proteínas
│
├── src/                      # Módulos de código fuente utilizados en el proyecto
│   ├── __init__.py
│   ├── data_utils.py
│   ├── clustering_utils.py
│   └── design_utils.py
│
├── tests/                    # Pruebas unitarias para el código
│   ├── test_data_utils.py
│   ├── test_clustering_utils.py
│   └── test_design_utils.py
│
└── results/                  # Resultados generados por los scripts, como gráficos y modelos de salida
    ├── figures/              # Figuras y gráficos generados
    └── models/              # Modelos de proteínas diseñados
