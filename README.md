[![UNIE Universidad](https://www.fsie.es/documentos/imagenes/Ventajas_afiliados/2024/UNIE/Brand_Unie_Vertical_Positive.png)](https://www.universidadunie.com/programas/master-formacion-permanente-virtual-inteligencia-artificial-deep-learning)

# Máster en Inteligencia Artificial y Deep Learning

## Machine Learning — Principal Component Analysis: Iris Dataset

Asignatura Machine Learning del Máster en IA y Deep Learning de UNIE. Practical Lab: Principal Component Analysis

---

## Summary

End-to-end PCA pipeline applied to the [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) (150 instances, 4 numerical features, 3-class target). The notebook covers:

- Exploratory data analysis: feature distributions, correlation heatmap, pairplot
- Standardisation and its importance for PCA
- Manual PCA via eigendecomposition of the covariance matrix
- Scikit-learn `PCA`: scree plot, cumulative explained variance, component loadings
- 2-D and 3-D projections of the principal components
- Biplot — overlaying sample scores and feature loading vectors
- Reconstruction error vs number of components
- PCA as preprocessing for a k-NN downstream classifier

## Project Structure

```
datasets/               # (empty — Iris is loaded directly from sklearn)
src/
└── introduction_principal_component_analysis.ipynb
```

## Quick Start

```bash
# Create and activate environment
python3 -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook src/
```

---

## Disclaimer

Provided as is, for academic use only.

## Copyright and License

- Notebook: [MIT License](LICENSE)
- Data: [CC0: Public Domain](https://archive.ics.uci.edu/ml/datasets/iris)

Developed and tested on Python ≥ 3.10. Dependencies: see `requirements.txt`.
