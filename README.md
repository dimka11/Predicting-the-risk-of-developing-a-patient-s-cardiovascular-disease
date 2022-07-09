# Прогнозирование риска развития сердечно-сосудистого заболевания пациента
## Чемпионат - Ярославская область

Dataset (Kaggle):

https://www.kaggle.com/datasets/dimka11/predicting-the-risk-cardiovascular-disease

### Решение:

EDA блокнот:

TBA ...

Model, train, inference блокнот:

TBA ...


Задача — разработать модель машинного обучения, цель которой —
предсказание наличия сердечно-сосудистых заболеваний. Данные
содержат опрос реальных пациентов и их диагнозы, включая такие
непрямые показатели, как образование, этнос, вид работы и многие другие.
В рамках чемпионата вам необходимо классифицировать
наличие/отсутствие у пациента следующих заболеваний:

● Артериальная гипертензия;

● Острое нарушение мозгового кровообращения;

● Стенокардия, ИБС, инфаркт миокарда;

● Сердечная недостаточность.

В качестве метрики выступает Recall.


$$ Recall = \frac{TP}{TP+FN}  $$

&nbsp; Так как конечная задача преполагает мультиклассовое предсказание,
то для каждой категории будет рассчитана своя метрика, которая будет
усреднена. Такой полученный усредненный Recall для всего
тренировочного датасета и будет является оценкой точности решения
участника.
