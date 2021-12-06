# XML
**XML Rep for HW2 @ Ksendzov Course**

1. Создайте текстоовый файл как в первом ДЗ по Terminal.
2. Сценарий перенесите в этот файл.
3. Напротив каждого действия - напишите команду в GitBash.
```
Command: cd /Users/macintosh/Desktop/CODING/KSENDZOV/HW2
Перемещаемся в папку, куда будем клонировать репозиторий, который мы только что создали.
```
4. Создать внешний репозиторий c названием XML.
- <img width="1002" alt="JSON01" src="https://user-images.githubusercontent.com/84155505/144822314-489c74c0-b504-497d-a04c-32f521840b39.png">
- <img width="726" alt="XML02" src="https://user-images.githubusercontent.com/84155505/144822717-3c1147f0-6c4d-4d3f-b4cf-27349d675d1b.png">
5. Клонировать репозиторий XML на локальный компьютер.
```
Command: git clone https://github.com/PaulBuzz/XML
Result: Клонирование в «XML»…
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Получение объектов: 100% (3/3), готово.
```
6. Внутри локального XML создать файл “new.xml”.
```
Command: cd XML
Command: touch new.xml
```
7. Добавить файл под гит.
```
Command: git add "new.xml"
```
8. Закоммитить файл.
```
Command: git commit -m "commiting XML file to our rep"
```
9. Отправить файл на внешний GitHub репозиторий.
```
Command: git push
```
10. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
Command: vim new.xml
<?xml version="1.0" encoding="UTF-8"?>
<root>
  <NSF>
    <name>Pavel</name>
    <surname>Buzin</surname>
    <father_name>Aleksandr</father_name>
  </NSF>
  <age>29</age>
  <pets>0</pets>
  <desired_salary>6000</desired_salary>
</root>
```
11. Отправить изменения на внешний репозиторий.
```
Command: git push
Result: Перечисление объектов: 5, готово.
Подсчет объектов: 100% (5/5), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (3/3), готово.
Запись объектов: 100% (3/3), 394 байта | 394.00 КиБ/с, готово. Всего 3 (изменений 0), повторно использовано пакетов 0
To https://github.com/PaulBuzz/XML
```
12. Создать файл preferences.xml.
```
Command: touch preference.xml
```
13. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```
Command: vim preferences.xml
<?xml version="1.0" encoding="UTF-8"?>
<root>
  <fav_movie>25th_hour</fav_movie>
  <fav_TVSHOW>Scrubs</fav_TVSHOW>
  <fav_food>Kebab</fav_food>
  <fav_season>Autumn</fav_season>
  <country_to_visit>Denmark</country_to_visit>
</root>
```
14. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML.
```
Command: vim skills.xml   
<?xml version="1.0" encoding="UTF-8"?>
<root>
  <skill_1>HTTP</skill_1>
  <skill_2>GIT</skill_2>
  <skill_3>VPN</skill_3>
  <skill_4>SQL</skill_4>
  <skill_5>Postman</skill_5>
  <skill_6>Charles</skill_6>
  <skill_7>Fiddler</skill_7>
  <skill_8>Android_Studio</skill_8>
  <skill_9>XCODE</skill_9>
  <skill_10>QA_Theory</skill_10>
</root>
```
15. Сделать коммит в одну строку.
```
Command: git add -A && git commit -m "adding multiple files to the repository"
```
16. Отправить сразу 2 файла на внешний репозиторий.
```
Command: git push 
Добавляет все файлы
```
17. На веб интерфейсе создать файл bug_report.xml.
- <img width="1001" alt="XML01" src="https://user-images.githubusercontent.com/84155505/144826445-46e51959-1f7f-4e35-809b-b6bb49d41f66.png">
- <img width="1401" alt="XML03" src="https://user-images.githubusercontent.com/84155505/144826483-63bc22a4-0f8a-488c-9d1f-dac6a5891d7e.png">
18. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- <img width="1300" alt="JSON05" src="https://user-images.githubusercontent.com/84155505/144827113-5e5bdfbc-b636-4007-8f80-bc8632b544a0.png">
19.На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
- <img width="1277" alt="XML04" src="https://user-images.githubusercontent.com/84155505/144827180-d0e98d7d-2428-41dd-b663-318e858b0b60.png">
20. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- <img width="1330" alt="XML05" src="https://user-images.githubusercontent.com/84155505/144827298-569a8311-ce0b-4b10-bdd3-a4598c740ba8.png">
21. Синхронизировать внешний и локальный репозиторий XML.
```
Command: git pull
```
