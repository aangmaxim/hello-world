# module_2

# Разведывательный анализ данных (EDA)

## Цель проекта

1. Сформулировать предположения и гипотезы для дальнейшего построения модели.

2. Проверить качество данных и очистить их, если это необходимо.

3. Определиться с параметрами модели.

## Задача проекта

Отследить влияние условий жизни учащихся в возрасте от 15 до 22 лет на их успеваемость по математике, чтобы на ранней стадии выявлять студентов, находящихся в группе риска

## Данные

Данные в основном состоят из номинативных переменных, хоть иногда выражены в числе с ссылкой.
Данные достаточно хорошо формализованы. Ошибок мало.

## Этапы работы

1. Отсмотр данных
2. Анализ данных
3. Корреляционный анализ
4. Анализ номинативных переменных
5. Вывод

## Выводы

1. В данных немного пустых значений. Минимально заполнены на 89%.

2. Вбросы найдены только в столбце *absences*, поэтому можно сказать, что данные достаточно чистые.

3. Отрицательная слабая корреляция между столбцами *failures* и *score* может говорить, что, чем меньше неудач вне школы, тем выше успеваемость.

4. Самые важные параметры, которые предлагается использовать в дальнейшем для построения модели, это *failures*, *age*, *studytime*, *goout*, *Mjob*, *higher*


## Вопросы саморефлексии

### 1. Какой частью своей работы вы остались особенно довольны?

Особенно остался доволен конечным результатом, может я все напутал и все неправильно, но пока все хорошо

### 2. Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?

Написать более причесанный код

### 3. Что интересного и полезного вы узнали в этом модуле?

Новые инструменты ttest_ind и combinations

### 4. Что является вашим главным результатом при прохождении этого проекта?

Новые знания и опыт, еще бы порешать такие задачи

### 5. Какие навыки вы уже можете применить в текущей деятельности?

Использую pd и plot уже на работе, почти слез с excel

### 6. Планируете ли вы дополнительно изучать материалы по теме проекта?

Постараюсь еще раз пройти, после изучения доп. материалов

## Ссылка на github

`https://github.com/aangmaxim/hello-world`