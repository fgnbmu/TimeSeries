# Time Series Analysis

Учебный проект по анализу и прогнозированию временных рядов на Python.

## Содержание

| Ноутбук | Тема |
|---|---|
| `01_noise_generation_white_pink_black.ipynb` | Генерация белого, розового и чёрного шума, зашумление сигнала |
| `02_decomposition_stationarity_autocorrelation.ipynb` | Декомпозиция, тест Дики-Фуллера, тренд, ACF/PACF |
| `03_differencing_boxcox_ar_ma_forecasting.ipynb` | Дифференцирование, преобразование Бокса-Кокса, модели AR и MA, метрики |
| `04_moving_average_arima_missing_values_outliers.ipynb` | Скользящее среднее, ARMA/ARIMA, заполнение пропусков, обнаружение выбросов |

## Данные

Датасет продаж (`data.csv`) — временные ряды по четырём категориям: Chemicals, Coal, Petrol, Vehicles (252 наблюдения).

## Стек

- Python 3
- pandas, numpy
- statsmodels (ARIMA, seasonal_decompose, adfuller)
- scikit-learn (OneClassSVM, метрики)
- matplotlib, seaborn
- scipy

## Запуск

```bash
git clone https://github.com/fgnbmu/TimeSeries
cd TimeSeries

pip install pandas numpy statsmodels scikit-learn matplotlib seaborn scipy jupyter

jupyter notebook
```
