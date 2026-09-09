# Component_A

Computes a 20-day moving average on daily closing prices and plots it against the close.

## Setup

```bash
python -m venv .venv
.venv\Scripts\activate   # Windows
pip install -r requirements.txt
```

## Run

```bash
python src/analysis.py
```

Reads `data/prices.csv`, writes the chart to `outputs/plot.png`.
