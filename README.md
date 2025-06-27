# 🌾 РостАгро — Прогнозирование стоимости агропродукции (2024–2030)

**Решение выполнено для тестового задания компании РостАгро.**  
В проекте используется Jupyter Notebook для анализа и построения прогноза цен на аграрную продукцию.

---

## 📦 Структура репозитория

- `notebooks/eda_and_forecast.ipynb` — основной ноутбук для запуска прогноза и визуализации результатов  
- `data/clean_dataset.xlsx` — подготовленные исторические данные  
- `data/forecast_2024_2030.xlsx` — итоговый файл с прогнозом (создаётся после выполнения ноутбука)  
- `requirements.txt` — список зависимостей для проекта  

---

## 🚀 Быстрый старт

### 1. Клонирование репозитория

```bash
git clone https://github.com/LinkIvan13/rostagro_forecast.git
cd rostagro_forecast


### 2. Создание и активация виртуального окружения
Windows:

python -m venv .venv
.venv\Scripts\activate


Linux/Mac:

python3 -m venv .venv
source .venv/bin/activate


### 3. Установка зависимостей

pip install -r requirements.txt


### 4. Запуск Jupyter Notebook

jupyter notebook
Откройте файл notebooks/eda_and_forecast.ipynb и выполните все ячейки по порядку.

---

## 📺 Видео-демонстрация

🔗 [Посмотреть видео-демонстрацию на Google.Диске](https://drive.google.com/file/d/12EKBdrr6maai9wEN-fTsLLUtGZhSBONZ/view?usp=sharing)

---


🛠️ Используемые библиотеки
pandas

numpy

matplotlib

statsmodels

Все необходимые зависимости перечислены в файле requirements.txt.

📝 Описание задания
Построить прогноз по четырём позициям:

Соевые бобы

Фосфорит

Подсолнечное масло

Пшеница, США SRW

Использована модель экспоненциального сглаживания Холта-Винтерса (тренд, без сезонности).
Итоговый прогноз формируется в файле data/forecast_2024_2030.xlsx.

✅ Проверка выполнения
Убедитесь в наличии файлов:

data/clean_dataset.xlsx

data/forecast_2024_2030.xlsx (будет создан после запуска ноутбука)

Откройте ноутбук notebooks/eda_and_forecast.ipynb и выполните все шаги.

Автор: LinkIvan13