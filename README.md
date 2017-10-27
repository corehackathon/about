# CoRe Hackathon

BI-хакатон на данных Яндекс.Метрики и коллтрекинга Comagic

# Полезные ссылки
- [Группа для участников в Facebook](https://www.facebook.com/groups/CoReHackathon/)
- [Репозиторий с данными для участников хакатона](https://github.com/corehackathon/data)
- [Справка по полям выгрузки комеджика](https://www.comagic.ru/support/api/data-api/Reports/)
- [Справка по статусам звонков comagic](https://www.comagic.ru/blog/posts/jul/novye_vidy_obrashcheniy_rasskazhut_o_byudzhete_potrachennom_zrya/)
- [Справка по хитам выгрузки метрики](https://tech.yandex.ru/metrika/doc/api2/logs/fields/hits-docpage/)
- [Справка по сессиям выгрузки метрики](https://tech.yandex.ru/metrika/doc/api2/logs/fields/visits-docpage/)

# Программа #

## Приветствие (пятница 14.00 - 14.30)

## Доклады (пятница 14.30 - 18.00) ##

14:00 - 14:30 - Открытие CoReHackathon. Приветственное слово организаторов.  
14:30 - 15:00 - Презентация задания. Илья Бродский, менеджер по продукту   CoMagic.  
15:00 - 15:30 -  Кейсы применения CoMagic в недвижимости. Нюансы и хаки.  Никита Семенов, руководитель отдела по работе с партнёрами CoMagic.  

15:30 - 16:00 - Перерыв. Кофе-брейк.  

16:00 - 16:30 - Сессия вопросов и ответов. Виктор Тарнавский, руководитель департамента аналитических продуктов Яндекс.Метрики  
16:30 - 17:00 - Инструменты бизнес-анализа. Антон Ватов, эксперт по технологическому развитию партнеров Microsoft Azure  
17:00 - 17:45 - Как разработать полезную BI - систему за ночь? Максим Уваров, основатель NeedForData  


## Хакатон (пятница 19.00 - суббота 11.00)

## Презентация работ (суббота 11.30 - 14.00)

# Задание

1. Построить саму сквозную модель данных. А именно соединить сырые данные по сессиям Метрики с нашими данным по звонкам. Для этого нужно будет объединить данные по visitor_id и дате сессии и звонка соответственно. Далее эти данные можно обогатить данными из Директа или данными по хитам, для выполнения следующих заданий.  
2. Рекомендательные дашборды для оптимизации контекстной рекламы, а именно Яндекс Директа. Возможные элементы рекламных кампаний, по которым система может выдавать рекомендации:  
    - Расчет оптимальной ставки, оптимального бюджета 
    - Изменение/добавление страниц приземления
    - Коррекция ключевых слов/объявлений
    - другое на выбор участников
3. Работа с Микроконверсиями, как решение проблемы недостатка статистики по оптимизации рекламы. Микроконверсии можно строить на основе хитовых данных.  
4. Рекомендательные дашборды по распределению бюджета между Источниками/Каналами трафика. Возможно на основе кастомной модели атрибуции, которую можно будет построить.  

Все задания не обязательно выполнять. Можно взять какое то одно или несколько на выбор участников. Так же разрешается придумать свои интересные вещи на основе этих данных, т.е. вышеописанное задание это не четкий регламент как нужно действовать, можно придумать что-то свое. 

Единственное требование - решение должно приносить бизнес ценность.

# Оформление работ и презентация результатов #

1. У каждой команды должен быть свой собственный репозиторий на github с описанием BI системы
2. README.md Должен быть оформлен по [шаблону](https://github.com/corehackathon/exampleBI/blob/master/README.md)
3. Презентация команд проходит вживую, для презентации на сцену выходят все желающие от команды
4. Презентация ведется с презентационного компьютера _без установленного Power BI_. Во время презентации необходимо продемонстрировать загруженную в облако и опубликованную BI-систему. Если есть желание показать код, связи таблицы, то все это необходимо вставить в презентацию. 
5. Файл BI-системы можно загрузить в раздел Releases (на гитхаб, либо на внешний ресурс вроде Яндекс.Диска. Ссылочку на bi-систему в описании необходимо предоставить

# Есть вопросы? #

Экспертов на хакатон у нас мало. Возникающие вопросы просьба задавать в [группе Facebook](https://www.facebook.com/groups/CoReHackathon/) или спрашивать у экспертов лично. Но лучше в группе. 
