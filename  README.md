# RostAgro Forecasting

Прогнозирование стоимости агропродукции на период 2024–2030 гг.  
Решение выполнено в виде Jupyter Notebook с возможностью автоматического воспроизведения и валидации результатов.

## 📦 Структура репозитория

- `notebooks/eda_and_forecast.ipynb` — основной ноутбук для запуска прогноза и визуализации результатов
- `data/clean_dataset.xlsx` — подготовленные исторические данные
- `data/forecast_2024_2030.xlsx` — файл с итоговым прогнозом

## 🚀 Быстрый старт

1. **Клонировать репозиторий:**
   ```bash
   git clone https://github.com/LinkIvan13/rostagro_forecasting.git
   cd rostagro_forecasting
   

Создать виртуальное окружение и активировать:

python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/Mac:
source .venv/bin/activate


Установить зависимости:

pip install -r requirements.txt


Запустить Jupyter Notebook:

jupyter notebook
Затем открыть файл notebooks/eda_and_forecast.ipynb и выполнить все ячейки.

📊 Видео-демонстрация
[![Видео-демонстрация](https://drive.google.com/file/d/12EKBdrr6maai9wEN-fTsLLUtGZhSBONZ/view?usp=sharing)]

Смотреть видео-демо

⚙️ Используемые библиотеки
pandas

numpy

matplotlib

statsmodels

Все требования указаны в requirements.txt.



📝 Описание задания
Прогноз строится по четырём позициям: Soybeans, Phosphate rock, Sunflower oil, Wheat, US SRW
Модель: Holt-Winters Exponential Smoothing (тренд, без сезонности).


Для проверки:

Убедитесь, что в папке data есть файлы clean_dataset.xlsx и forecast_2024_2030.xlsx.

Откройте ноутбук и выполните по шагам.

Автор: LinkIvan13