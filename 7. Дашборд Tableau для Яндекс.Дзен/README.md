# Дашборд для Яндекс.Дзен
Задача проекта автоматизировать сбор данных о взаимодействиях посетителей сервиса с карточками и агрегировать их в удобный для восприятия и анализа формат дашборда в Tableau.  
___
## Задачи проекта  
1. Выгрузить данные для будущего дашборда
2. Создать дашборд в Tableau по ТЗ от product-менеджера
3. Подготовить презентацию с анализом полученных данных

## Стек технологий и ход работы
Подключение к БД и выгрузка данных сделана с помощью `Python` и библиотек `pandas` и `sqlalchemy`, а также с помощью простого запроса `SQL`. Этот этап работы отражен [в файле Jupyter Notebook](https://github.com/ucylama/learning-project-yandex/tree/master/7.%20Дашборд%20Tableau%20для%20Яндекс.Дзен/data_loading_for_yandex_zen_kovalchuk.ipynb).  
  
Дашборд построен с помощью возможностей **Tableau** по техническому заданию от стейкхолдера задачи. [Изучить дашборд можно по ссылке](https://public.tableau.com/views/ZenYandex/DashboardforZen?:language=en&:display_count=y&publish=yes&:origin=viz_share_link) на сервере Tableau Public.  
![](https://s219vla.storage.yandex.net/rdisk/74a3ca297f2d2f97c88c0256ecadd51f2f773e060a42eff6cd3a019bfda54233/5fd26b2c/W_aS9eeWZ9Ktlq0ZnNUQqTozIlUR-N8gZgdwJlzXq71ixujj4gMEa1Dve1RkDoHgRhqCzvCku72QQGULHMcgDQ==?uid=907701324&filename=внешний%20вид%20дашборда.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=907701324&fsize=1317319&hid=3104190c829489fdfc6480140a033772&media_type=image&tknv=v2&etag=99d8e5810c861b1cb6d751f20ee1bb1d&rtoken=OMQgQ7Zr9c9i&force_default=yes&ycrid=na-5e7ecaa7971fa992878ddd198d23455d-downloader20e&ts=5b6207bd02300&s=f432c7510b0fdbbff7213f35340393aa93062535648b5ef410c1b8faaba66574&pb=U2FsdGVkX18eFqsrpJhh8JcjbxrWP1_Z-qjnsKiApZUWqug__kcX84hFMoSFB6vHbo242GOyGTfVLYN3Y7ZdGw3gNR0GsVnz8DuyPXK84fU)  
Анализ полученных данных был оформлен и опубликован [в презентации](https://yadi.sk/i/0UcB5vwtV50ZnA).
___
Аналитик: Ковальчук Юлия  
Статус проекта: завершен,  октябрь 2020  
 *Проект выполнен в рамках обучения в Яндекс.Практикуме на курсе Data Analyst*