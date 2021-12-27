# Aspect Based Sentiment Analysis

*Петухова Ксения, Смилга Вероника, Казаков Роман, Гриневская Катя*

### Материалы

#### [Отчёт](https://docs.google.com/document/d/1tb1FYYGuMVft6HBTjNvSqmKTybhI1F7eROIzvrS56g0/edit#)

#### Тетрадки

`nlp_project_SA.ipynb` - основной код, в котором применяем CRF;

`statistics_generate_reviews.ipynb` - увеличиваем датасет, генерируя отзывы; считаем небольшую статистику по изначальному датасету;

`BERT_experiments.ipynb` - эксперименты с предобученной моделью [RuBERT for Sentiment Analysis](https://huggingface.co/blanchefort/rubert-base-cased-sentiment) для оценки тональности;

`Experiment_synt_groups.ipynb` - эксперименты с синтаксисом.

#### Файлы `.txt`
`train_reviews.txt` - изначальный корпус отзывов;

`train_aspects.txt`- изначально размеченные аспекты по категориям и тональности;

`train_cats.txt` - изначально размеченные категории по тональности.


`train_split_reviews.txt` - обучающие данные из изначального корпуса отзывов (80%);

`train_split_aspects.txt`- обучающие данные из изначально размеченных аспектов по категориям и тональности;

`train_split_cats.txt` - обучающие данные из изначально размеченных категорий по тональности.


`more_train_split_reviews.txt` - расширенные обучающие данные отзывов;

`more_train_split_aspects.txt`- расширенные обучающие данные аспектов по категориям и тональности;

`more_train_split_cats.txt` - расширенные обучающие данные категорий по тональности.


`dev_reviews.txt` - тестовые данные из изначального корпуса отзывов (20%);

`dev_aspects.txt` - тестовые данные из изначально размеченных аспектов по категориям и тональности;

`dev_cats.txt` - тестовые данные из изначально размеченных категорий по тональности.


`dev_pred_aspects_sent_crf.txt` - предсказанные нами аспекты и их тональности на тестовых данных;

`dev_pred_cats.txt` - тональности для категорий на тестовых данных.
