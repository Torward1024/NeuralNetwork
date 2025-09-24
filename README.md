# 🚀 Прогнозирование температуры звезды

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.10.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-red)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11%2B-lightgrey)
![Phik](https://img.shields.io/badge/Phik-0.12%2B-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellowgreen)

## 🎯 Цель проекта
Разработать модель машинного обучения для предсказания поверхностной температуры звезд на основе их характеристик, используя методы нейронных сетей и физические законы (закон Вина, закон Стефана-Больцмана, спектральный анализ).

## 📌 Задачи
1) Провести исследовательский анализ данных:
   - Оценить качество данных и устранить пропуски/дубликаты
   - Выполнить категоризацию признаков при необходимости
   - Подготовить обучающую и тестовую выборки
   - Выполнить масштабирование количественных данных
2) Построить и обучить нейронную сеть:
   - Разработать базовую модель нейронной сети
   - Улучшить модель на основе результатов обучения
3) Достигнуть высокой точности предсказания температуры звезд

## 🔍 Описание данных
Данные содержат информацию о 240 звездах, включая:
- **Luminosity (L/Lo)**: светимость звезды относительно Солнца
- **Radius (R/Ro)**: радиус звезды относительно Солнца
- **Absolute Magnitude (Mv)**: абсолютная звездная величина
- **Star Type**: тип звезды (категориальный признак)
- **Star Color**: цвет звезды (категориальный признак)
- **Temperature (K)**: целевая переменная – температура поверхности звезды (в Кельвинах)

## 🛠 Технологический стек
- **Анализ данных**: Pandas, NumPy, Phik, Scipy
- **Визуализация**: Matplotlib, Seaborn
- **ML**: Scikit-learn, PyTorch
- **Другие**: Jupyter Notebook, Git

## 📂 Структура проекта
StarTemperaturePrediction/\
├── neural_network.ipynb
└── README.md # Этот файл

## 🏆 Ключевые метрики
- RMSE: <значение> (указать после обучения модели)

## 📞 Контакты
- Автор: Алексей Рудницкий
- Email: almax1024@gmail.com
- Telegram: @torwad1024