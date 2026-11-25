# Proyecto ML — Efectividad de campañas de marketing

**Universidad Privada del Valle — LI22 Proyecto ML + Exposición**
**Integrante:** Joel Julio Salazar Ferrufino
**Escenario:** N.º 4 — Efectividad de campañas de marketing

## Dataset

- **Nombre:** Bank Marketing (`bank-additional-full.csv`)
- **Fuente:** UCI Machine Learning Repository — https://archive.ics.uci.edu/dataset/222/bank+marketing
- **Referencia:** Moro, S., Cortez, P., & Rita, P. (2014). A data-driven approach to predict the success of bank telemarketing. *Decision Support Systems, 62*, 22–31.
- **Tamaño:** 41.188 registros × 21 columnas (10 numéricas, 10 categóricas + objetivo `y`)
- **Objetivo:** `y` — ¿el cliente contrató un depósito a plazo? (yes/no)

## Modelos

| Enfoque | Algoritmo | Actividad |
|---|---|---|
| Supervisado | Naive Bayes | Predecir si un cliente responde positivamente a la campaña |
| No supervisado | PCA | Reducir dimensiones e identificar componentes principales |
| Refuerzo | Monte Carlo | Simular campañas y evaluar estrategias de contacto/promoción |

## Estructura

```
├── data/
│   ├── raw/            # Datos originales (sin modificar)
│   └── processed/      # Datos limpios generados por 02_preprocessing
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_supervised_model.ipynb
│   ├── 04_unsupervised_model.ipynb
│   ├── 05_reinforcement_learning.ipynb
│   └── 06_model_comparison.ipynb
├── docs/
│   ├── informe_final.pdf
│   └── presentacion.pdf
└── requirements.txt
```

## Cómo ejecutar

```bash
pip install -r requirements.txt
jupyter notebook
```

Ejecutar los notebooks en orden (01 → 06).
