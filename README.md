# Полезная информация

В этом репозитории будут храниться и обновляться ссылки на полезные материалы. Кроме этого, я постепенно сформирую список вопросов к экзамену, которые охватят большую часть материала курса и, возможно, будут выноситься на обсуждение во время лекций.

## Пример оформления формулы
![equation](http://www.sciweavers.org/tex2img.php?eq=1%2Bsin%28mc%5E2%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=)


## Основные источники теоретической информации

Курс лекций от Константина Вячеславовича Воронцова, где в сжатом виде изложены основные концепции, которые мы затронем в этом семестре - частично или полностью.
http://www.machinelearning.ru/wiki/images/6/6d/Voron-ML-1.pdf

Его же курс лекций, доступный на youtube, на случай, если читать будет излишне обременительно.
https://youtu.be/qLBkB4sMztk

Лекции и практические материалы от Соколова Евгения
https://github.com/esokolov

## Для развития практических навыков программирования на python

https://www.dataquest.io/

# Курсы МФТИ

## Для тех, кто хочет интересные лекции по Python от увлечённого лектора (вполне заменяет какой-нибудь сериал)
https://youtu.be/KdZ4HF1SrFs

## Для тех, кто хочет устранить пробел в тервере
https://youtu.be/sC1SYl0TGD8

# Отчётность за семестр

## Условия получения автомата

1. Рассказать об алгоритме обратного распространения ошибки, который используется для обучения нейронных сетей. Информация здесь: [https://youtu.be/WjwA5DqxL-c]

*К сожалению, мы не успеваем познакомиться с нейронными сетями в должной мере в этом семестре, но это может стать отличной возможностью для желающих получить оценку, минуя экзамен. По-моему, "автомат" заслуживают люди, которые опережают программу курса и готовы поработать больше остальных.*

2. Полноценно ответить на все вопросы о модели, которая изучалась Вашей группой.

*"Полноценно" означает, что ни одна формула и ни один символ не остались за рамками вашего понимания. Все формулы необходимо уметь выводить, все объекты, которые в них фигурируют, интерпретировать.*

3. Интерпретировать код в script-файлах, результаты его выполнения. Уметь вызывать использованные классификаторы с разными параметрами. Знать свойства и методы объектов, с которыми работаем после обучения модели. 

## Условие на получение допуска к экзамену

**Сдать задания по программированию: код своей модели + задание на генерацию случайных величин.**

## Полезные замечания, которые помогут избежать недопонимания: 

0. Цель: полезные знания для дальнейшей работы и исследований. Всё что ведёт к вашему профессиональному росту в области анализа поощряется.
1. Дополнительные вопросы могут быть по любой части вашего раздела.
2. Чёткое понимание структуры материала и взаимосвязей между моделями важнее зубрёжки.
3. Если в вашем разделе нет описания объекта, который используется в вашей модели, это не является поводом не разбираться с ним (например, если примеры ядерного сглаживания и виды ядер не приводятся у вас, но непараметрические методы присутствуют, значит необходимо залезть в нужный раздел и понять, что такое ядра, какие они бывают и как их использовать).
4. На парах мы были сильно ограничены по времени, поэтому опускали те немногие теоремы, которые встречались, или приводили их без доказательств, но понимать их нужно.
5. При подготовке вопросов пользоваться можно любыми источниками, задача найти максимально полный и чёткий ответ. 
6. В видео лекциях К.В. Воронцова обычно больше поясняющих примеров и комментариев.
7. Стремитесь разбираться с теоретической частью так, чтобы можно было выписать простой пример на листик и "потрогать" как это устроено. Верно и обратное: если программируете, подумайте, какие разделы из теоретической части были затронуты и какие параметры можно поискать в описании методов.
8. Оценка тем выше, чем глубже ваше понимание и умение работать с тем, что вы изучали. Время затраченное на поиск ответов и количество попыток сдачи в оценке не учитываются.

## Вопросы к экзамену

1. Общая формальная постановка задачи машинного обучения (обязательный вопрос для всех). Детерминированный и вероятностный подходы к моделированию.
2. Метрические методы классификации
* Метод k-ближайших соседей
* Отбор объектов для обучения модели, алгоритм STOLP, эталоны
* Особенности процедуры "cross-validation" для метрических методов классификации
3. Байесовские методы классификации
* Наивный байесовский классификатор
* Непараметрические методы оценки плотности и классификации
* Нормальный дискриминантный анализ
4. Линейные методы классификации
* Стохастический градиентный спуск
* Логистическая регрессия
* Метод опорных векторов
* Ядра и спрямляющие пространства, ROC-кривая
5. Методы восстановления регрессии
* Сингулярное разложение и методы борьбы с мультиколлинеарностью
* Метод главных компонент
* Нелинейная регрессия

_Выбиратор вопросов напишем на python, он раздаст их случайным образом. Каждому достанется 2 вопроса, 1 обязательно из своей темы, 2-й из чужой. Чужой вопрос нужно понимать, и уметь находить метод в script-файлах и вызывать. Код по своим моделям разобрать досконально._
