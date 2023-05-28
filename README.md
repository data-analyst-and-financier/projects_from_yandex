# My portfolio

Ниже собрана информация о некоторых реализованных мной проектах.

| № п/п|   Название проекта   | Описание проекта | Используемые библиотеки |
|:-----:|:----------------:|:----------------:|:--------------------:|
| 1 |   [Анализ оттока клиентов банка](https://github.com/data-analyst-and-financier/my_portfolio/tree/main/bank_customer_churn_analysis)   | Изучение причин оттока клиентов регионального банка, их сегментация, формирование рекомендаций для возврата/удержания клиентов | `pandas`, `matplotlib.pyplot`, `matplotlib.ticker`, `seaborn`, `scipy`, `numpy`, `plotly.express`, `statistics`|
| 2 | Анализ рынка заведений общепита в Москве |  | `pandas`, `matplotlib.pyplot`,  `plotly.express`, `seaborn`, `numpy`, `json`, `folium`,  `folium.plugins`|




import pandas as pd
import matplotlib.pyplot as plt
import matplotlib.ticker
import seaborn as sns
from scipy import stats as st
import numpy as np
import plotly.express as px
from statistics import variance # используется для расчета дисперсии
import statistics # применяется для расчета моды

