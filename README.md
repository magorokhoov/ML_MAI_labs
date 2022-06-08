### Горохов Михаил Антонович
Группа: М8О-308Б-19

Почта: magorokhoov@gmail.com

# Лабораторная работа №0

## Цель работы

Выбрать набор данных. Поставить задачу, которую необходимо решить с помощью эти данных. Определить что нужно получить на выходе, как это измерять, посмотреть на сами данные. Определить являются ли данные грязными или чистыми. Есть ли у данных пропуски. Как зависят между собой признаки. Вывести матрицу корреляции. Показать попарные корреляции между признаками. Посмотреть на зависимости и на основе этого построить визуализацию и выводы.

## Задача

На наборе данных о смерти из-за сердечной недостаточности подготовить данные для решения бинарной классификации вероятной смерти от признаков. С помощью датасета необходимо определить, что влияет на преждевременную смерть.

## Набор данных

* age - возраст пациента

* anaemia - анемия, Снижение эритроцитов или гемоглобина (boolean)

* creatinine_phosphokinase - Уровень фермента CPK в крови (мкг/л)

* diabetes - есть ли диабет (boolean)

* ejection_fraction - Процент крови, покидающей сердце при каждом сокращении (в процентах)

* high_blood_pressure - Гипертония (boolean)

* platelets - Тромбоциты в крови (килотромбоциты/мл)

* serum_creatinine - Уровень сывороточного креатинина в крови (мг/дл)

* serum_sodium - Уровень сывороточного натрия в крови (мэкв/л)

* sex - пол пациента

* smoking - курит ли пациент (boolean)

* time - Период наблюдения (дни)

* DEATH_EVENT - умер ли пациент в течение периода наблюдения (логическое значение)

Пояснение по поводу boolean данных:

* Sex - Пол пациента Мужской = 1, Женский = 0

* Age - Возраст пациента

* Diabetes - 0 = Нет, 1 = Да

* Anaemia - 0 = Нет, 1 = Да

* high_blood_pressure — 0 = Нет, 1 = Да

* smoking - 0 = Нет, 1 = Да

* DEATH_EVENT — 0 = нет, 1 = да



## Выполненные действия над датасетом

1. Был скачан [датасет](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data "датасет").

2. С помощью pandas датасет был преобразован в удобный для работы вид.

3. Были просмотрены данные датасета, признаки и их типы. Датасет был проверен на повторение данных, а также пустые данные.

4. Были проанализированы числовые данные. Произведён поиск выбросов среди них. Была выведена матрица корреляции. Были просмотрены ассимметрия и эксцесс.

5. Были построены корреляции различных признаков с признаком наличия болезни сердца. По корреляциям были сделаны выводы.


# Лабораторная работа №1
