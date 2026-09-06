# Стационарность временных рядов

ДЗ: 6 рядов из `Series/`, приведение к стационарности. Всё в `time_series_stationarity.ipynb`.

| ряд | преобразование |
|---|---|
| sales | log + Δ₁ + сезонные дамми |
| robberies | log + Δ₁ |
| airline | log + Δ₁ + Δ₁₂ |
| temp | минус месячные средние |
| dowjones | log + Δ₁ |
| births | минус линейный тренд и дамми дней недели |

Проверка: ADF + KPSS + ACF.

```bash
pip install -r requirements.txt
```
