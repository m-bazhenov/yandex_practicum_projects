# Сборный проект №2. Восстановление золота из руды

## **Описание проекта:**

Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В вашем распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## **Цели проекта:**
1. Проверить, что эффективность обогащения рассчитана правильно:
  - вычислить эффективность на обучающей выборке для признака rougher.output.recovery;
  - найти MAE между расчётами и значением признака;
2. Проанализировать признаки, недоступные в тестовой выборке:
  - ответить на вопрос, что это за параметры?
  - ответить на вопрос, к какому типу относятся?
3. Посмотреть, как меняется концентрация металлов (Au, Ag, Pb) на различных этапах очистки.
3. Сравнить распределения размеров гранул сырья на обучающей и тестовой выборках.
4. Исследовать суммарную концентрацию всех веществ на разных стадиях: в сырье, в черновом и финальном концентратах.
5. Написать функцию для вычисления итоговой sMAPE.
6. Обучить разные модели и оценить их качество кросс-валидацией.
7. Выбрать лучшую модель и проверьте её на тестовой выборке.

## Используемые инструменты
Pandas, Matplotlib, Sklearn, Numpy, Bootstrap, Seaborn
