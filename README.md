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
<skill1>postman</skill1>
<skill2>bash</skill2>
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
