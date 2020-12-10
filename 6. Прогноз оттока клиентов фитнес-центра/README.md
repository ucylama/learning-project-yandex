# Прогноз оттока клиентов фитнес-центра
Исследование проведено для сети фитнес-центров с целью снизить процент оттока клиентов. Для решения поставленных задач изучены обезличенные данные анкет клиентов, данные об абонементах и посещениях клиентов.  
___
## Задачи проекта  
* выявить закономерности в поведении клиентов, предшествующем оттоку,  
* построить модель для прогноза оттока клиентов,  
* дать рекомендации по удержанию клиентов.  
  
## Стек технологий  
Анализ проведен с помощью возможностей языка программирования Python с использованием библиотек:  
```python
import pandas as pd
import numpy as np

# визуализация данных
import plotly.graph_objects as go
import plotly.express as px
from plotly.subplots import make_subplots
import seaborn as sns
import matplotlib.pyplot as plt

# построение моделей
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier
from sklearn.cluster import KMeans
from scipy.cluster.hierarchy import dendrogram, linkage
# оценка метрик
from sklearn.metrics import accuracy_score, precision_score, recall_score, roc_auc_score, silhouette_score
```
## Результаты исследования  
Построена модель прогноза оттока клиентов в следующем месяце с помощью алгоритма логической регрессии (показала наилучшие метрики).  
  
Выделены 4 кластера клиентов и даны подробные описания типичного пользовательского поведения и других данных для каждого.  
  
Даны рекомендации по улучшению качества работы с клиентами с учетом особенностей каждого кластера.  
____
Аналитик: Ковальчук Юлия  
Статус проекта: завершен, ноябрь 2020  
*Проект выполнен в рамках обучения в Яндекс.Практикуме на курсе Data Analyst*