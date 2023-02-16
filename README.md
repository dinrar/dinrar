




## Data Science


| **Проект** | **Задание** |**Что сделано** | **Библиотеки** |
| - | :- |:-|:-|
| [Предсказание температуры в плавильном ковше](https://github.com/dinrar/ds-projects/tree/main/melting_ladle_temperature) | Предсказать температуру в плавильном ковше с заданной метрикой *MAE*. Предоставлены данные о параметрах работы нагревательного устройства (электрической дуги), материалах, поступающих в ковш (сыпучие, проволочные, газ), температуре в ковше в разные моменты времени. | Выполнен анализ и обработка данных, сгенерированы новые признаки, обучены 3 модели машинного обучения (линейная регрессия, случайный лес, градиентный бустинг). Лучший результат получен для модели градиентного бустинга (CatBoost). | catboost, numpy, optuna, pandas, pandas_profiling, seaborn, shap, sklearn, matplotlib |
| [Определение возраста покупателей по фото (CV)](https://github.com/dinrar/ds-projects/tree/main/age_determining_by_photo%20(CV)) | Определить возраст по фотографии с заданной метрикой *MAE*. Предоставлен набор фотографий с лицами людей разного возраста. | Выполнен анализ данных, обучена сверточная нейронная сеть ResNet-50. | pandas, keras |
| [Определение токсичных комментариев (NLP)](https://github.com/dinrar/ds-projects/tree/main/taxi_demand_prediction%20(Time-Series%20Data)) | Разработать инструмент для автоматического выявления токсичных правок с заданной метрикой *f1*. Предоставлен набор комментариев с разметкой токсичности. | Выполнен анализ данных, подготовлены эмбеддинги из части текстов исходного корпуса, обучены 3 модели машинного обучения: дерево решений, случайный лес, логистическая регрессия. Лучший результат получен для модели случайного леса. | sklearn, tqdm, BERT (RoBERTa), numpy, pandas, torch |
| [Прогнозирование заказов такси (time-series data)](https://github.com/dinrar/ds-projects/tree/main/taxi_demand_prediction%20(Time-Series%20Data)) | Предсказать количество заказов такси на час вперед с заданной метрикой *RMSE*. Предоставлены данные о количестве заказов за одинаковые периоды времени. | Выполнен анализ данных, обучены 5 моделей машинного обучения: дерево решений, случайный лес, линейная регрессия, ElasticNet, градиентный бустинг. Лучший результат получен с использованием модели градиентного бустинга. | matplotlib, sklearn, statsmodels.tsa.seasonal, catboost, numpy, pandas, seaborn, shap |
| [Исследование данных о компьютерных играх (EDA, A/B-test)](https://github.com/dinrar/ds-projects/tree/main/video_games_research%20(EDA%2C%20A_B-test)) | Определить признаки, по которым можно выявить потенциально популярную видеоигру. Предоставлены исторические данные о продажах игр, оценках пользователей и экспертов, жанре и платформах, для которых они публиковались, за период до 2015 года (предсказание необходимо сделать на 2016 год). Дополнительно необходимо проверить 2 гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. | Выполнены подготовка и исследовательский анализ данных; определены признаки, по которым можно определить потенциально успешную игру; проверены сформулированные в задании заказчика; даны рекомендации, которые стоит учесть заказчику при планировании рекламной кампании. | scipy, math, numpy, pandas|

## Метрология
### Программное обеспечение (2017-2022)

Надстройка для Excel "URALTEST ADDIN" [(репозиторий)](https://github.com/dinrar/uraltest-excel-addin-project)

Основные этапы разработки:
|Дата|Версия|Изменения|
|-|-|-|
|2022.06|2.0|Добавил возможность подключения новых ВЕ-метров модификации 50 Гц|
|2020.11|2.0|Добавил функцию синхронного запуска измерений двумя мультиметрами 34410|
|2020.06|2.0|Добавил форму панели управления ИПЭП-1|
|2020.05|2.0|Собрал в одну надстройку наработки версии 1 (вариант 1.8g) и наработки по проекту "Протоколы 2.0" - упор сделан на переход от структуры с единым исходным файлом протокола к расширению функционала надстройки (Протоколы 2.0)|
|2020.03|1.8e|Добавил форму панели управления BE-метр|
|2020.01|1.8d|Добавил формы панелей управления генератором 33220,  мультиметром 34410 (2 шт.), осциллографом OX7042|
|2018-2019||Активная разработка экспериментальных функций ("Протоколы 2.0")|
|2017.06|1.1|Добавлен "Считыватель команд управления" для запуска команд управления оборудованием из ячеек листа протокола|
|2017.03|0.9|Прототип - перенес в надстройку макросы из файла "Формы протоколов"|


### Статьи (2019-2020)

|Год|Направление*|Название*|Примечание|
|-|-|-|-|
|2020.12|МПК|[Проблемы подтверждения пригодности переносных намагничивающих устройств с постоянными магнитами и электромагнитов постоянного тока для применения при МПК](https://vk.com/@metrazbor-pm)|Сбор и анализ измерительных данных|
|2020.04|МПК|[Модернизация установки для МПК осей колесных пар и внутренних колец подшипников буксового узла 6733Б](https://vk.com/@metrazbor-6733b)|Отчет о доработке дефектоскопа|
|2019.08|МПК|[Проблемы установок МПК колец подшипников буксового узла типов 6733Б, РМ8617, ТПС 9706А, УМДП-01](https://vk.com/@metrazbor-mpd-rings)|Критика ошибочного принципа, положенного в основу дефектоскопов|
|2019.06|МПК|[МПД. Характеристики, контролируемые при аттестации в качестве испытательного оборудования](https://vk.com/@metrazbor-mpd-props)|Систематизация накопленных данных|
|2019.05|МПК|[МПД. Аттестация, поверка или калибровка?](https://vk.com/@metrazbor-mpd)|Разбор актуального вопроса|
|2019.03|СИ магнитных величин|[Холловские измерители магнитной индукции ленинградского завода «Измеритель»](https://vk.com/@metrazbor-sh1-8)|Исторический экскурс|
|2019.03|СИ магнитных величин|[Приборы магнитометрические для определения концентрации напряжений ИКН](https://vk.com/@metrazbor-ikn)|Исследование метрологических характеристик|
|2019.01|СИ магнитных величин|[Измеритель магнитной индукции ИМП-2](https://vk.com/@metrazbor-imp-2)|Исследование метрологических характеристик|

\* МПД - магнитопорошковые дефектоскопы; МПК - магнитопорошковый контроль; СИ - средства измерений.




