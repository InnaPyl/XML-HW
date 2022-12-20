# XML
 21. Создать внешний репозиторий c названием XML.    
```
Repositories --> New --> Name:XML --> Check "Add a README file" --> Press "Create repository"
```
 22. Клонировать репозиторий XML на локальный компьютер.
```
Копируем ссылку https://github...
В терминале Bash вводим команды
git init
git clone https://github...
```
 23. Внутри локального XML создать файл “new.xml”.
```
1. cd JSON/
2. touch new.json
```
 24. Добавить файл под гит.
```
git add new.xml
```
 25. Закоммитить файл.
```
git commit -m "First"
```
 26. Отправить файл на внешний GitHub репозиторий.
```
git push
```
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе. Всё написать в формате XML.
```
cat > new.xml  --> ^C  ИЛИ vim new.xml
<main>
<name>Inna</name>
<surname>Pyl</surname>
<age>35</age>
<gender>female</gender>
<profesion>qa</profesion>
</main>
```
 28. Отправить изменения на внешний репозиторий.
```
1. git commit -m "Second"  
2. git push
```
 29. Создать файл preferences.xml
```
touch preferences.xml
```
 30. В файл preferences.xml добавить информацию о своих предпочтениях в формате XML.
```
cat > preferences.xml  --> ^C  ИЛИ vim preferences.xml
<my preferences>
<my favorive movie>AmelY</my favorive movie>
<my farourite serial>Sex in the city</my farourite serial>
<my favourite dish>pasta</my favourite dish>
<my favourite city>Barselona</my favourite city>
</my preferences>
```
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```cat > skills.xml  --> ^C  ИЛИ vim skills.xml
<skills>
<skill1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.</skill1>
<skill2>Что такое клиент-серверная архитектура.</skill2>
<skill3>HTTP Методы запросов на сервер.</skill3>
<skill4>Коды ответов HTTP сервера.</skill4>
<skill5>Структуры HTTP запросов и ответов.</skill5>
<skill6>Что такое JSON, XML. Их структура.</skill6>
<skill7>Тестирование API через Postman (JS, автотесты API).</skill7>
<skill8>Снятие и чтение логов c внешнего сервера.</skill8>
<skill9>Снифинг http web трафика через Charles и Fiddler.</skill9>
<skill10>Dev Tools веб браузеров (Google Chrome, FireFox).</skill10>
<skill11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</skill11>
<skill12>Мобильное тестирование.</skill12>
<skill13>Особенность iOS, Android, гайдлайны.</skill13>
<skill14>Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</skill14>
<skill15>Сборка Android приложений на Android Studio.</skill15>
<skill16>ADB (управление андройд девайсами).</skill16>
<skill17>Настройка прокси и vpn на iOS и Android.</skill17>
<skill18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</skill18>
<skill19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</skill19>
<skill20>Основы bash скриптинг, автоматизация рутинных задач на сервере.</skill20>
<skill21>Доступ к удалённым серверам.</skill21>
<skill22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</skill22>
<skill23>База данных Postgres (установка, настройка и использование).</skill23>
<skill24>Нереляционная база данных Redis (установка, настройка и использование).</skill24>
<skill25>Нагрузочное тестирование в Jmeter.</skill25>
<skill26>Методология разработки Scrum.</skill26>
<skill27>Python. (Изучение основ. Создание клиент серверного приложения)</skill27>
</skills>
```
 32. Сделать коммит в одну строку.
```
git add . && git commit -m "Third"
```
 33. Отправить сразу 2 файла на внешний репозиторий.
```
git push
```
 34. На веб интерфейсе создать файл bug_report.xml.
```
Add file --> Create new file --> Name: bug_report.xml
```
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
Скролить вниз, добавить имя, нажать Commit
```
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```
Choose bug_report.xml --> Edit this file
<bug_report>
  <ID>номер</ID>
  <summary>краткое описание</summary>
  <description>полное описание</description>
  <environment>окружение</environment>
  <steps_to_reproduce>шаги воспроизведения</steps_to_reproduce>
  <actual_result>фактический результат</actual_result>
  <expected_result>ожидаемый результат</expected_result>
  <severity>серьезность</severity>
  <priority>приоритет</priority>
  <additional_information>дополнения</additional_information>
</bug_report>
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
Скролить вниз, добавить имя, нажать Commit
```
 38. Синхронизировать внешний и локальный репозиторий XML
```
git pull
```
