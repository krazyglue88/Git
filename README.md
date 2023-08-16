# Git_pt.1
### JSON
---
### 1. Создать внешний репозиторий c названием JSON.
На странице профиля в GitHub нажать на ```Repositories``` нажать на ```New```
Ввести в инпут "Name" - ```JSON```, радиобаттон поставить в значение ```public```,
нажать на ```Create Repository```        
### 2. Клонировать репозиторий JSON на локальный компьютер.
```git clone HTTPS/SSH```
### 3. Внутри локального JSON создать файл “new.json”.
```cd JSON```
```touch new.json```
### 4. Добавить файл под гит
```git add new.json```
### 5. Закоммитить файл.
```git commit -m "1st_commit"```
### 6. Отправить файл на внешний GitHub репозиторий.
```git push```
### 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```vim new.json``` нажать ```Enter``` ```i```
написать текст:
```
{
 "name": "Fedorenko Ivan Vladimirovich",
 "age": 36,
 "number of pets": "null",
 "salary expectations": "995"
}
```
```Esc``` ```:wq``` ```Enter```
### 8. Отправить изменения на внешний репозиторий.
```git add new.json```
```git commit _m "2nd_commit```
```git push```
### 9. Создать файл preferences.json
```touch preferences.json```
### 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```vim preferences.json``` нажать ```Enter``` ```i```
написать текст:
```
{
 "favorite movie": "Mulholland dr.",
 "favorite series": "Twin Peaks",
 "favorite food": "kimchi rice with bacon",
 "favorite time of year": "summer",
 "country you'd like to visit": "USA"
}
```
```Esc``` ```:wq``` ```Enter```
```git add preferences.json```
```git commit -m "add_preferences```
### 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```vim skills.json``` нажать ```Enter``` ```i``` написать:
```
{
 "1": "Базовая теория",
 "2": "Клиент-серверная архитектура",
 "3": "Структуры HTTP запросов и ответов",
 "4": "JSON, XML",
 "5": "Тестирование API через Postman (JS, автотесты API)",
 "6": "Снятие и чтение логов c внешнего сервера",
 "7": "Снифинг http web трафика через Charles и Fiddler",
 "8": "Dev Tools веб браузеров (Google Chrome, FireFox)",
 "9": "Мобильное тестирование",
 "10": "Сборка iOS приложений на XCode",
 "11": "Сборка Android приложений на Android Studio",
 "12": "ADB",
 "13": "Настройка прокси и vpn на iOS и Android",
 "14": "Командная строка (terminal) Linux",
 "15": "Основы bash скриптинг, автоматизация рутинных задач на сервере",
 "16": "Основы SQL",
 "17": "База данных Postgres",
 "18": "Нереляционная база данных Redis",
 "19": "Нагрузочное тестирование в Jmeter",
 "20": "Методология разработки Scrum",
 "21": "Техники тест-дизайна",
 "22": "Python"
}
```
```Esc``` ```:wq``` ```Enter```
```git add skills.json```
```git commit -m "add_skills.json```                        
### 12. Отправить сразу 2 файла на внешний репозиторий
```git push```
### 13. На веб интерфейсе создать файл bug_report.json.
```Add file```
```Create new file```
### 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit changes```
### 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```Edit this file```
Ввести:
```
 {
  "ID": "1",
  "Summary": "Не отображается футер на всех страницах сайта при переключении в мобильную версию",
  "Product": "Apteki.kg",
  "Environment": "Build:1.52.9/Browser:Google Chrome 113.0.5672.93/OS: WINDOWS 11",
  "Prerequisites": "В девелоперской консоли в браузере выбрать разрешение экрана - iPhone SE",
  "Steps to reproduce": "Проскроллить до самого низа главной страницы сайта",
  "Expected result": "Страница оканчивается разделом с дополнительными ссылками ",
  "Actual result": "Раздел с дополнительными ссылками отсутствует"
}
```             
### 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit changes```
### 17. Синхронизировать внешний и локальный репозиторий JSON
```git pull```
### XML
---
### 1. Создать внешний репозиторий c названием XML.
На странице профиля в GitHub нажать на ```Repositories``` нажать на ```New```
Ввести в инпут "Name" - ```XML``` радиобаттон поставить в значение ```public```
нажать на ```Create Repository```
### 2. Клонировать репозиторий XML на локальный компьютер.
```git clone HTTPS/SSH```
### 3. Внутри локального XML создать файл “new.xml”.
```cd XML```
```touch new.xml```
### 4. Добавить файл под гит.
```git add new.xml```
### 5. Закоммитить файл.
```git commit -m "add_xml"```
### 6. Отправить файл на внешний GitHub репозиторий.
```git push```
### 7.  Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```vim new.xml``` нажать ```Enter``` ```i```
написать текст:
```
<new>
 <name>Fedorenko Ivan Vladimirovich</name>
 <age>36</age>
 <number_of_pets>null</number_of_pets>
 <salary_expectations>995</salary_expectations>
</new>
```
```Esc``` ```:wq``` ```Enter```
### 8. Отправить изменения на внешний репозиторий.
```git add new.xml```
```git commit -m "update_new.xml"```
```git push``` 
### 9.Создать файл preferences.xml
```touch preferences.xml```
### 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```vim preferences.xml``` нажать ```Enter``` ```i```
написать текст:
```
<preferences>
        <favorite_movie>Mulholland dr.</favorite_movie>
        <favorite_series>Twin Peaks</favorite_series>
        <favorite_food>kimchi rice with bacon</favorite_food>
        <kimchi rice with bacon>summer</favorite_time_of_year>
        <country_you_would_like_to_visit>USA</country_you_would_like_to_visit>
</preferences>
```
```Esc``` ```:wq``` ```Enter```
### 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```vim skills.xml``` нажать ```Enter``` ```i```
написать текст:
```
<skills>
        <1>Базовая теория</1>
        <2>Клиент-серверная архитектура</2>
        <3>Структуры HTTP запросов и ответов</3>
        <4>JSON,XML</4>
        <5>Тестирование API через Postman (JS, автотесты API)</5>
        <6>Снятие и чтение логов c внешнего сервера</6>
        <7>Снифинг http web трафика через Charles и Fiddler</7>
        <8>Dev Tools веб браузеров (Google Chrome, FireFox)</8>
        <9>Мобильное тестирование</9>
        <10>Сборка iOS приложений на XCode</10>
        <11>Сборка Android приложений на Android Studio</11>
        <12>ADB</12>
        <13>Настройка прокси и vpn на iOS и Android</13>
        <14>Командная строка (terminal) Linux</14>
        <15>Основы bash скриптинг, автоматизация рутинных задач на сервере</15>
        <16>Основы SQL</16>
        <17>База данных Postgres</17>
        <18>Нереляционная база данных Redis</18>
        <19>Нагрузочное тестирование в Jmeter</19>
        <20>Методология разработки Scrum</20>
        <21>Техники тест-дизайна</21>
        <22>Python</22>
</skills>
```
```Esc``` ```:wq``` ```Enter```
### 12. Сделать коммит в одну строку.
```git add . && git commit -m "add_preferences_skills"```
### 13. Отправить сразу 2 файла на внешний репозиторий.
```git push```
### 14. На веб интерфейсе создать файл bug_report.xml.
```Add file```
```Create new file```
Ввести в инпут плэйсхолдера "Name your file": ```bug_report.xml```
### 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit change```
### 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
Нажать на ```Edit this file```
Ввести:
```
<bug_report>
  <ID>1</ID>
  <Summary>Не отображается футер на всех страницах сайта при переключении в мобильную версию</Summary>
  <Product>Apteki.kg</Product>
  <Environment>Build:1.52.9/Browser:Google Chrome 113.0.5672.93/OS: WINDOWS 11</Environment>
  <Prerequisites>В девелоперской консоли в браузере выбрать разрешение экрана - iPhone SE</Prerequisites>
  <Steps_to_reproduce>Проскроллить до самого низа главной страницы сайта</Steps_to_reproduce>
  <Expected_result>Страница оканчивается разделом с дополнительными ссылками</Expected_result>
  <Actual_result>Раздел с дополнительными ссылками отсутствует</Actual_result>
</bug_report>
```
### 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit changes```
### 18. Синхронизировать внешний и локальный репозиторий XML
```git pull```
### TXT
---
### 1. Создать внешний репозиторий c названием TXT.
На странице профиля в GitHub нажать на ```Repositories``` нажать на ```New```
Ввести в инпут "Name" - ```TXT``` радиобаттон поставить в значение ```public```
нажать на ```Create Repository```
### 2. Клонировать репозиторий TXT на локальный компьютер.
```git clone HTTPS/SSH```
### 3. Внутри локального TXT создать файл “new.txt”.
```cd XML```
```touch new.txt```
### 4. Добавить файл под гит.
```git add new.txt```
### 5. Закоммитить файл.
```git commit -m "add_txt"```
### 6. Отправить файл на внешний GitHub репозиторий.
```git push```
### 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```vim new.txt``` нажать ```Enter``` ```i```
написать текст:
```
name: Fedorenko Ivan Vladimirovich
age: 36
number of pets: 0
salary expectations: 995$
```
```Esc``` ```:wq``` ```Enter```
### 8. Отправить изменения на внешний репозиторий.
```git add new.txt```
```git commit -m "update_new.txt"```
```git push```
### 9. Создать файл preferences.txt
```touch preferences.txt```
### 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```vim preferences.txt``` нажать ```Enter``` ```i```
написать текст:
```
favorite movie: Mulholland dr.
favorite series: Twin Peaks
favorite food: kimchi rice with bacon
country you would like to visit: USA
```
```Esc``` ```:wq``` ```Enter```
### 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```vim skills.txt``` нажать ```Enter``` ```i```
написать текст:
```
1) Базовая теория
2) Клиент-серверная архитектура
3) Структуры HTTP запросов и ответов
4) JSON,XML
5) Тестирование API через Postman (JS, автотесты API)
6) Снятие и чтение логов c внешнего сервера
7) Снифинг http web трафика через Charles и Fiddler
8) Dev Tools веб браузеров (Google Chrome, FireFox)
9) Мобильное тестирование
10) Сборка iOS приложений на XCode
11) Сборка Android приложений на Android Studio
12) ADB
13) Настройка прокси и vpn на iOS и Android
14) Командная строка (terminal) Linux
15) Основы bash скриптинг, автоматизация рутинных задач на сервере
16) Основы SQL
17) База данных Postgres
18) Нереляционная база данных Redis
19) Нагрузочное тестирование в Jmeter
20) Методология разработки Scrum
21) Техники тест-дизайна
22) Python
```
```Esc``` ```:wq``` ```Enter```
### 12. Сделать коммит в одну строку.
```git add . && git commit -m "add_preferences_skills"```
### 13. Отправить сразу 2 файла на внешний репозиторий.
```git push```
### 14. На веб интерфейсе создать файл bug_report.txt.
```Add file```
```Create new file```
Ввести в инпут плэйсхолдера "Name your file": ```bug_report.txt```
### 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit change```
### 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
Нажать на ```Edit this file```
Ввести:
```
ID: 1
Summary: Не отображается футер на всех страницах сайта при переключении в мобильную версию
Product: Apteki.kg
Environment: Build:1.52.9/Browser:Google Chrome 113.0.5672.93/OS: WINDOWS 11
Prerequisites: В девелоперской консоли в браузере выбрать разрешение экрана - iPhone SE
Steps to reproduce: Проскроллить до самого низа главной страницы сайта
Expected result: Страница оканчивается разделом с дополнительными ссылками
Actual result: Раздел с дополнительными ссылками отсутствует
```
### 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```Commit changes```
### 18. Синхронизировать внешний и локальный репозиторий TXT
```git pull```
