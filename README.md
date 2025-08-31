# Titanic survival prediction
Классический датасет с Kaggle — предсказание выживания пассажиров «Титаника».   
Цель проекта — показать навыки работы с: 
- табличными данными;
- feature engineering; 
- построением моделей ML; 
- интерпретацией результатов.

# Структура проекта
- `data/` — исходные данные (не загружаются в GitHub).  
- `notebooks/` — Jupyter ноутбуки с поэтапной работой:
  1. EDA
  2. Feature Engineering
  3. Modeling
  4. Interpretation  
- `src/` — вспомогательные скрипты для подготовки данных и моделей.  
- `requirements.txt` — список зависимостей.

# Этапы проекта
1. **EDA** — анализ распределений и зависимостей (пол, возраст, класс билета).
2. **Feature Engineering** — новые признаки: `FamilySize`, `IsAlone`, `Title`.
3. **Модели** — Logistic Regression, Random Forest, XGBoost, CatBoost.
4. **Интерпретация** — SHAP, Feature Importance, визуализации.

# Как запустить
1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/username/titanic-ml-project.git
   cd titanic-ml-project
2. Установить зависимости:
   ```bash
   pip install -r requirements.txt
3. Запустить ноутбук:
   ```bash
   jupyter notebook notebooks/01_eda.ipynb
