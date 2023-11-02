# Дипломная работа
# на тему:
# Бриф «Лаборатории исследований гражданского общества». Государственные деньги у НКО.

## Оглавление
[1. Описание проекта](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/Diplom/README.md#Описание-проекта)
[2. Постановка задачи](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/Diplom/README.md#Постановка-задачи)
[3. Исходные данные](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/Diplom/README.md#Исходные-данны)
[4. Содержание диплома](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/project_1/README.md#Содержание-диплома)

## Описание проекта
В распоряжении есть дамп данных обо всех НКО России, в котором содержится информация о получении государственных грантов, госконтрактов и субсидий, регионе и дате регистрации, а также ОКВЭД (классификатор экономической деятельности).

:arrow_up:[к оглавлению](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/project_1/README.md#Оглавление)

## Постановка задачи
Проверить, есть ли зависимость вероятности получения грантов от государства/госконтрактов:  
➔ от региона регистрации организации;  
➔ от возраста организации;  
➔ от экономической деятельности организации.  
По желанию можно провести любые дополнительные проверки. 

:arrow_up:[к оглавлению](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/project_1/README.md#Оглавление)

## Исходные данные
Источник данных — проект «Открытые НКО» <https://openngo.ru/>  
Дамп данных в формате JSON (актуален на 16.08.2023) <https://openngo.ru/opendata/>  
Описание полей на GitHub <https://github.com/infoculture/openngo-data-reference/wiki/Характеристики-и-расшифровки-открытых-данных>

## Содержание диплома
Глава 1. Анализ исходных данных
Глава 2. Анализ целевого признака
Глава 3. Обработка признаков с типом object
Подглава 3.1. Обработка признака regionCode - код региона
Подглава 3.2. Обработка признака mainOkved - основной ОКВЭД
Подглава 3.3. Обработка признаков с датами
Подглава 3.4. Обработка бинарных признаков
Подглава 3.5. Обработка признака opfType
Глава 4. Корреляционный анализ датасета
Глава 5. Кодирование признаков
Глава 6. Создание моделей машинного обучения
Подглава 6.1. Выборки и метрика
Подглава 6.2. Наивный байесовский классификатор
Подглава 6.3. Логистическая регрессия
Подглава 6.4. Случайный лес
Заключение
Выводы
Приложение - Поиск сведений об основном ОКВЭД организации

:arrow_up:[к оглавлению](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/project_1/README.md#Оглавление)

### Результаты
[Диплом](https://github.com/ASGlazyrin/ASG_SF_Rep/blob/main/Diplom/diplom_glazyrin.ipynb)
[Приложение](https://github.com/ASGlazyrin/ASG_SF_Rep/blob/main/Diplom/search_mainOkved.ipynb)

:arrow_up:[к оглавлению](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/project_1/README.md#Оглавление)

### Исходные данные
[Исходные данные](https://openngo.ru/opendata/)

:arrow_up:[к оглавлению](https://github.com/ASGlazyrin/ASG_SF_Rep/tree/main/project_1/README.md#Оглавление)