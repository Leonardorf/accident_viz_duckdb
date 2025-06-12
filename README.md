# Accident Viz DuckDB

Este proyecto permite visualizar datos procesados sobre accidentes de tránsito utilizando Jupyter Notebooks, DuckDB y bibliotecas de visualización en Python.

## 📊 Descripción

Utiliza como fuente los datos transformados por el proyecto `dbt_kaggle_project`, específicamente el modelo `accidents_by_year`, y permite:

- Cargar los datos desde una base DuckDB.
- Explorar la evolución anual de los accidentes.
- Graficar cantidad de accidentes, heridos y víctimas fatales por año.

## 🗂️ Estructura del proyecto

```
accident_viz_duckdb/
├── data/
│   └── traffic.duckdb
├── notebooks/
│   ├── accident_viz.ipynb
│   └── .venv/  ← excluido
├── .gitignore
├── requirements.txt
└── README.md
```

## 🚀 Cómo usar

1. Cloná este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/accident_viz_duckdb.git
   ```

2. Instalá las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecutá el notebook:
   ```bash
   jupyter notebook notebooks/accident_viz.ipynb
   ```

## 🔮 Mejoras futuras

- Integración con un dashboard web (Streamlit o Dash).
- Análisis geográfico con mapas.
- Automatización de extracción y actualización de datos.

## 👤 Autor

- Leonardo Villegas

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
