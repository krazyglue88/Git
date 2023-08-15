# Git_pt.1
### JSON
---
### 1. Создать внешний репозиторий c названием JSON.
- На странице профиля в GitHub нажать на ```Repositories``` нажать на ```New```
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
```vim new.json```
нажать на клавишу ```i```
написать текст:
```
{
 "name": "Fedorenko Ivan Vladimirovich",
 "age": 36,
 "number of pets": "null",
 "salary expectations": "995"
}
```
Нажать на ```Esc``` ввести ```:wq + Enter```
### 8. Отправить изменения на внешний репозиторий.
                          git add new.json
                          git commit _m "2nd_commit"
                          git push
9. Создать файл preferences.json
                          touch preferences.json
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
  vim preferences.json              
                нажать на клавишу "i"
                                 написать текст:
{
 "favorite movie": "Mulholland dr.",
 "favorite series": "Twin Peaks",
 "favorite food": "kimchi rice with bacon",
 "favorite time of year": "summer",
 "country you'd like to visit": "USA"
}
                         Нажать на "Esc", ввести: wq + Enter
                            git add preferences.json
                                                      git commit -m "add_preferences"
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
             vim skills.json, жмём клавишу "i", вставляем:
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
      Нажать на "Esc", ввести: wq + Enter
                            git add skills.json
                                              git commit -m "add_skills.json"                        
 12. Отправить сразу 2 файла на внешний репозиторий
                                                  git push
 13. На веб интерфейсе создать файл bug_report.json.
                                                     Add file
                                                             Create new file
                                         Ввести в инпут плэйсхолдера "Name your file": bug_report.json
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
                                                       Commit changes
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 Нажать на Edit this file
 Ввести:
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
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
                                                                    Commit changes
 17. Синхронизировать внешний и локальный репозиторий JSON
                                                        git pull
