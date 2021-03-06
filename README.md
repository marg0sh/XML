#### 1. Создайте текстоовый файл как в первом ДЗ по Terminal.
```
touch GIT_Homework_1.txt
```

#### 2. Сценарий перенесите в этот файл.
```
vim GIT_Homework_1.txt
```
*нажать i для редактирования, копирование Ctrl+C, вставка Ctrl+Insert*

#### 3. На против каждого действия - напишите команду в GitBash
*Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.*
  
https://github.com/marg0sh/JSON
  
https://github.com/marg0sh/XML
  
https://github.com/marg0sh/TXT


## XML
#### 21. Создать внешний репозиторий c названием XML.
*веб интерфейс github.com, залогинитьс, перейти в Repositories, создание новой репозитории New, имя XML, Add a ReadMe file, Create repository*

#### 22. Клонировать репозиторий XML на локальный компьютер.
*в веб интерфейсе Code - HTTPS - COPY*
```
cd ..
git clone https://github.com/marg0sh/XML.git
```

#### 23. Внутри локального XML создать файл “new.xml”.
```
cd XML
touch new.xml
```

#### 24. Добавить файл под гит.
```
git add new.xml
```

#### 25. Закоммитить файл.
```
git commit -m 'Create new.xml'
```

#### 26. Отправить файл на внешний GitHub репозиторий.
```
git push
```

#### 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
vim new.xml
```
*режим редактироваие i*
```xml
<xml>
        <Full_name>Zaitseva Margarita Olegovna</Full_name>
        <Age>34</Age>
        <Number_of_pets>1</Number_of_pets>
        <Future_desired_salary>50000$</Future_desired_salary>
</xml>
```
*выйти из vim нажатием Esc :wq Enter*

#### 28. Отправить изменения на внешний репозиторий.
```
git commit -m 'Update new.xml' && git push
```

#### 29. Создать файл preferences.xml
```
toush preferences.xml
```

#### 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```
vim preferences.xml
```
*режим редактироваие i*
```xml
<xml>
	<Favorite_movie>Queen of the Damned</Favorite_movie>
        <Favorite_series>Black Mirror</Favorite_series>
        <Favorite_food>Fast Food</Favorite_food>
        <Favorite_time_of_the_year>Summer</Favorite_time_of_the_year>
        <Side_you_would_like_tovisit>USA</Side_you_would_like_tovisit>
</xml>
```
*выйти из vim нажатием Esc :wq Enter*

#### 31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```
vim skills.xml
```
*режим редактироваие i*
```xml
<xml>
        <skill_1>Базовая теория. Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п. SDLC, STLC.</skill_1>
        <skill_2>Что такое клиент-серверная архитектура.</skill_2>
        <skill_3>HTTP Методы запросов на сервер.</skill_3>
        <skill_4>Коды ответов HTTP сервера.</skill_4>
        <skill_5>Структуры HTTP запросов и ответов.</skill_5>
        <skill_6>Что такое JSON, XML. Их структура.</skill_6>
        <skill_7>Тестирование API через Postman (JS, автотесты API).</skill_7>
        <skill_8>Снятие и чтение логов c внешнего сервера.</skill_8>
        <skill_9>Снифинг http web трафика через Charles и Fiddler.</skill_9>
        <skill_10>Dev Tools веб браузеров (Google Chrome, FireFox).</skill_10>
        <skill_11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</skill_11>
        <skill_12>Мобильное тестирование.</skill_12>
        <skill_13>Особенность iOS, Android, гайдлайны.</skill_13>
        <skill_14>Сборка iOS приложений на XCode.</skill_14>
        <skill_15>Сборка Android приложений на Android Studio.</skill_15>
        <skill_16>ADB (управление андройд девайсами).</skill_16>
        <skill_17>Настройка прокси и vpn на iOS и Android.</skill_17>
        <skill_18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</skill_18>
        <skill_19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</skill_19>
        <skill_20>Основы bash скриптинг, автоматизация рутинных задач на сервере.</skill_20>
        <skill_21>Доступ к удалённым серверам.</skill_21>
        <skill_22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</skill_22>
        <skill_23>База данных Postgres (установка, настройка и использование).</skill_23>
        <skill_24>Нереляционная база данных Redis (установка, настройка и использование).</skill_24>
        <skill_25>Нагрузочное тестирование в Jmeter.</skill_25>
        <skill_26>Методология разработки Scrum.</skill_26>
        <skill_27>Python. (Изучение основ. Создание клиент серверного приложения)</skill_27>
</xml>
```
*выйти из vim нажатием Esc :wq Enter*

#### 32. Сделать коммит в одну строку.
```
git add . && git commit -m 'Update file'
```

#### 33. Отправить сразу 2 файла на внешний репозиторий.
```
git push
```

#### 34. На веб интерфейсе создать файл bug_report.xml.
*веб интерфейс Add file - Create new file создание файла - название bug_report.json*

#### 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
*коммит Create bug_report.xml и сохранить*

#### 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
*редактирование файла*
```xml
<xml>
	<ID>ID</ID>
	<Summary>Summary</Summary>
	<Description>Description</Description>
	<Actual_result>Actual result</Actual_result>
	<Expected_result>Expected result</Expected_result>
	<Attachments>Attachments</Attachments>
	<Priority>Priority</Priority>
	<Severity>Severity</Severity>
	<Status>Status</Status>
</xml>
```

#### 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
*Update bug_report.json - Commit changes*

#### 38. Синхронизировать внешний и локальный репозиторий XML
```
git pull
```

