<a id="go"></a>

# GIT Homework 1 XML

## --> **[XML](#XML)** <--

## --> **[New.xml](#new.xml)** <--

## --> **[Preferences.xml](#preferences.xml)** <--

## --> **[Skills.xml](#skills.xml)** <--

## --> **[Bug_report.xml](#bug_report.xml)** <--

<a id="XML"></a>

[в начало](#go)

## **XML**

1.  Создать внешний репозиторий c названием XML:
    New > Name > public > Add a README file > Create repository

2.  Клонировать репозиторий XML на локальный компьютер:
    GitHub: Code > copy link, GitBash: clone > insert link

3.  Внутри локального XML создать файл “new.xml”:
    touch new.xml

4.  Добавить файл под гит.:
    git add new.xml

5.  Закоммитить файл:
    git commit -m "text"

6.  Отправить файл на внешний GitHub репозиторий:
    git push

7.  Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML:

8.  Отправить изменения на внешний репозиторий:
    git add new.xml, git commit -m"text", git push

9.  Создать файл preferences.xml:
    touch preferences.xml

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате xml:

-

11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML:
    touch sklls.xml

12. Сделать коммит в одну строку:
    git commit -am "text"

13. Отправить сразу 2 файла на внешний репозиторий:
    git push

14. На веб интерфейсе создать файл bug_report.xml:
    add file > Create new file > name/bug_report.xml > commit changes

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
    Commit message > Commit changes

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML:
    bug_report.xml > Edit this file > New text in bug_report.xml

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
    Commit message > Commit changes

18. Синхронизировать внешний и локальный репозиторий:
    git pull

<a id="new.xml"></a>

[в начало](#go)

## **New.xml**

```
<questionnaire>
    <Full_Name>
        <Last_name=Senya />
        <First_name=Довженко />
    </Full_Name>
    <Others>
         <Age_years=52 />
         <Number_of_pets=2 />
         <Salary=from $3000 />
    </Others>
</questionnaire>
```

<a id="preferences.xml"></a>

[в начало](#go)

## **Preferences.xml**

```
<Preferences>
       <Films_Darling=Avatar />
       <Series_Darling=Policeman from Rublyovka/>
       <Season_Darlin=Summer />
       <country_to_visit=India, Cambodia />
</Preferences>

<Preferences>
        <Films_Darling>Avatar</Films_Darling>
        <Series_Darling>Policeman from Rublyovka</Series_Darling>
        <Season>Summer</Season>
        <country_to_visit>India, Cambodia</country_to_visit>
</Preferences>
```

<a id="skills.xml"></a>

[в начало](#go)

## **Skills.xml**

```
<?xml version="1.0" encoding="UTF-8"?>
<Soft_Hard_Skills>
    <Course_program>Программа курса</Course_program>
        <!-- Предварительное распределение по категориям -->
        <base_theory>Базовая теория</base_theory>
           <x>Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п. SDLC, ST Снятие и чтение логов c внешнего сервера.</x>
           <x>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</x>
           <x>Основы bash скриптинг, автоматизация рутинных задач на сервере</x>
           <x>Что такое JSON, XML. Их структура</x>
        <base_theory>Базовая теория</base_theory>
        <HTTP>HTTP</HTTP>
           <x>HTTP Методы запросов на сервер</x>
           <x>Структуры HTTP запросов и ответов</x>
           <x>Снифинг http web трафика через Charles и Fiddler</x>
        <HTTP>HTTP</HTTP>
        <Testing>Тестирование</Testing>
           <x>Тестирование API через Postman JS, автотесты API</x>
           <x>Нагрузочное тестирование в Jmeter</x>
           <x>Мобильное тестирование</x>
        <Testing>Тестирование</Testing>
        <Mobail>Мобил</Mobail>
           <x>Особенность iOS, Android, гайдлайны</x>
           <x>Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</x>
           <x>ADB (управление андройд девайсами)</x>
           <x>Сборка Android приложений на Android Studio</x>
           <x>Настройка прокси и vpn на iOS и Android</x>
           <x>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android</x>
        <Mobail>Мобил</Mobail>
        <Database>Базы данных</Database>
           <x>База данных Postgres (установка, настройка и использование)</x>
           <x>Нереляционная база данных Redis (установка, настройка и использование)</x>
           <x>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</x>
        <Database>Базы данных</Database>
        <Server>Сервер</Server>
           <x>Что такое клиент-серверная архитектура</x>
           <x>Доступ к удалённым серверам</x>
           <x>Прочее Снятие и чтение логов c внешнего сервера</x>
        <Server>Сервер</Server>
        <Others>Прочее</Others>
        <!-- Категории находящиеся в очереди на распределение-->
           <x>Dev Tools веб браузеров (Google Chrome, FireFox)</x>
           <x>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</x>
           <x>Методология разработки Scrum</x>
           <x>Техники тест-дизайна (Классы эквивалентности, граничные значения, комбинаторные техники (Попарный, ортогональный, базовый выбор, каждый выбор), состояния и переходы)</x>
           <x>Python. (Изучение основ. Создание клиент серверного приложения)</x>
        <Others>Прочее</Others>
    <Course_program>Программа_курса</Course_program>
</Soft_Hard_Skills>
```

<a id="bug_report.xml"></a>

[в начало](#go)

## **Bug_report.xml**

```

```
