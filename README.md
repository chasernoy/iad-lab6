# iad-lab6

# Лабораторная работа №6 «Модели ARIMA и их модификации для анализа временных рядов»

## Данные
Файлы: 
- `data/day.csv` — датасет по дням (используется для моделирования)
- `data/hour.csv` — датасет по часам
Данные представляют собой статистику проката велосипедов (Bike Sharing Dataset), включающую погодные и календарные признаки.

## Структура репозитория
- `notebooks/lab6.ipynb` — основной ноутбук с анализом (ARIMA, SARIMA, SARIMAX, auto-ARIMA).
- `data/` — папка с исходными датасетами.

## Запуск

### 1) Клонирование репозитория
```bash
git clone https://github.com/chasernoy/iad-lab6.git
cd iad-lab6 ```
### 2) Окружение и зависимости
``` python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install pandas numpy matplotlib statsmodels scikit-learn pmdarima jupyter ```
### 3) Запуск ноутбука
``` python3 -m jupyter notebook ```