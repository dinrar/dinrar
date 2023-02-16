<a id='link1'></a>

## Data Science

<p align="center">
<b>
Проекты Data Science
</b>
</p>

[(Репозиторий)](https://github.com/dinrar/ds-projects)

| **Проект** | **Задание** | **Библиотеки** |
|-|-|-|
| [Предсказание температуры в плавильном ковше](https://github.com/dinrar/ds-projects/tree/main/melting_ladle_temperature) | Предсказать температуру в плавильном ковше с заданной метрикой *MAE*.  | catboost, numpy, optuna, pandas, pandas_profiling, seaborn, shap, sklearn, matplotlib |
| [Определение возраста покупателей по фото (CV)](https://github.com/dinrar/ds-projects/tree/main/age_determining_by_photo%20(CV)) | Определить возраст по фотографии с заданной метрикой *MAE*. | pandas, keras |
| [Определение токсичных комментариев (NLP)](https://github.com/dinrar/ds-projects/tree/main/taxi_demand_prediction%20(Time-Series%20Data)) | Разработать инструмент для автоматического выявления токсичных правок с заданной метрикой *f1*. | sklearn, tqdm, BERT (RoBERTa), numpy, pandas, torch |
| [Прогнозирование заказов такси (time-series data)](https://github.com/dinrar/ds-projects/tree/main/taxi_demand_prediction%20(Time-Series%20Data)) | Предсказать количество заказов такси на час вперед с заданной метрикой *RMSE*. | matplotlib, sklearn, statsmodels.tsa.seasonal, catboost, numpy, pandas, seaborn, shap |
| [Исследование данных о компьютерных играх (EDA, A/B-test)](https://github.com/dinrar/ds-projects/tree/main/video_games_research%20(EDA%2C%20A_B-test)) | Определить признаки, по которым можно выявить потенциально популярную видеоигру; проверить две гипотезы. | scipy, math, numpy, pandas|

<a href="#link1"><img src='https://img.shields.io/badge/К началу-&#x21A9-blue'></a>

## Метрология

<p align="center">
<b>
Надстройка для Excel "URALTEST ADDIN" (VBA)
</b>
</p>

[(Репозиторий)](https://github.com/dinrar/uraltest-excel-addin-project)

Надстройка добавляет на ribbon-панель Excel вкладку, функционал которой позволяет решать 2 основные задачи:
1. упрощение процессов создания и ведения протоколов измерений;
2. автоматизация процесса взаимодействия с измерительным оборудованием.

Основные этапы разработки:
|Дата|Версия|Изменения|
|-|-|-|
|2022.06|2.0|Добавил возможность подключения новых ВЕ-метров модификации "50 Гц"|
|2020.11|2.0|Добавил функцию синхронного запуска измерений двумя мультиметрами 34410|
|2020.06|2.0|Добавил форму панели управления ИПЭП-1|
|2020.05|2.0|Добавил наработки по проекту "Протоколы 2.0" в надстройку версии 1.8g. Основная цель - переход от структуры с единым исходным файлом форм протоколов к возможности взаимодействия с любым протоколом через добавленные команд на лист PropsOut|
|2020.03|1.8e|Добавил форму панели управления BE-метр|
|2020.01|1.8d|Добавил формы панелей управления генератором 33220,  мультиметром 34410 (2 шт.), осциллографом OX7042|
|2018-2019||Разработка экспериментальных функций в параллельной ветке (проект "Протоколы 2.0")|
|2017.06|1.1|Добавил "Считыватель команд управления" для запуска команд управления оборудованием из ячеек листа протокола (для управления Н4-11, Н4-17, АКИП 1135)|
|2017.03|0.9|Выделил макросы из файла "Формы протоколов" в формат надстройки|

<a href="#link1"><img src='https://img.shields.io/badge/К началу-&#x21A9-blue'></a>
___

<p align="center">
<b>
Статьи
</b>
</p>

|Дата|Направление*|Название*|Примечание|
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

<a href="#link1"><img src='https://img.shields.io/badge/К началу-&#x21A9-blue'></a>
