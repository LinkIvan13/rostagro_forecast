# РостАгро Прогнозирование

Прогнозирование стоимости агропродукции на период 2024–2030 гг.  
Решение выполнено в виде Jupyter Notebook с детализированными ячейками для запуска и проверки результатов.

---

## 📦 Структура репозитория

- `notebooks/eda_and_forecast.ipynb` — основной ноутбук для запуска прогноза и визуализации результатов
- `data/clean_dataset.xlsx` — подготовленные исторические данные
- `data/forecast_2024_2030.xlsx` — итоговый файл с прогнозом (формируется после выполнения ноутбука)

---

## 🚀 Быстрый старт

### 1. Клонировать репозиторий

```bash
git clone https://github.com/LinkIvan13/rostagro_forecast.git
cd rostagro_forecast

2. Создать виртуальное окружение и активировать
Windows:
python -m venv .venv
.venv\Scripts\activate

Linux/Mac:
python3 -m venv .venv
source .venv/bin/activate


3. Установить зависимости
pip install -r requirements.txt


4. Запустить Jupyter Notebook
jupyter notebook
Откройте файл notebooks/eda_and_forecast.ipynb и выполните все ячейки по порядку.

## 📺 Видео-демонстрация

[Смотреть видео-демо на Google Drive](https://drive.google.com/file/d/12EKBdrr6maai9wEN-fTsLLUfGZhSBONZ/view?usp=sharing)


⚙️ Используемые библиотеки
pandas

numpy

matplotlib

statsmodels

Все необходимые зависимости перечислены в файле requirements.txt.

📝 Описание задания
Построить прогноз по четырём позициям:

Soybeans

Phosphate rock

Sunflower oil

Wheat, US SRW

Используется модель Holt-Winters Exponential Smoothing (тренд, без сезонности).

Итоговый прогноз формируется в файле data/forecast_2024_2030.xlsx.

📂 Проверка выполнения
Проверьте наличие файлов:

data/clean_dataset.xlsx

data/forecast_2024_2030.xlsx (будет создан после запуска ноутбука)

Откройте ноутбук notebooks/eda_and_forecast.ipynb и выполните все шаги.

Автор: LinkIvan13