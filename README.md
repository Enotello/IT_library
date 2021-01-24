# Проект: ЭБС (Электронная Библиотечная система)
Целью данного проекта является разработка системы, обслуживающей библиотеки.
## Ссылки на репозитории проекта:
- [Back end проекта](https://github.com/Enotello/BiblEmployeBack)
- [Front end проекта](https://github.com/Enotello/BiblEmployeFront)

## Решаемые задачи:
- Разработка нового электронного каталога.
- Разработка единой базы читателя.
- Разработка единого читательского билета.

## Участники:
| Учебная группа| ФИО |
| ------------- | -----:|
| 191-361  |  Серегин М.С..|
| 191-361  |  Ермолин. А. А. |
| 191-321  |  Кудряшова А. В. |
| 191-361  | Марвах. М. Р. |
| 191-321  |  Мартынова А. А. |
| 191-321  |  Павлова Н. В. |
| 191-723  | Брехова Е. В |
| 191-361    | Смирнов Е. И. |
| 191-721  |  Шибанов А. Д. |

## Поставленные задачи участников:

### Серегин Матвей - Руководитель разработки
- Описание и реализация методологии разработки Agile
- Изучение и документирование информации об электрнонных библиотечных системах
- Проектирование системы в целом и отдельных её состовляющих
- Планирование и описание историй для дальнейшего разбиенния их на задачи
- Создание подкоманд разработки для более быстрой реализации эпика
- Настройка системы управления проектами Jira
- Составление списка задач на каждый спринт и их подробное описание
- Контроль работы как каждой подкоманды, так и каждого участника
- Обучение участников команды новыми технологиями разработки
- Составление документации и подробное описание процессов, происходящих в разрабатываемой системе
- Контроль выполения задач и отладки кода по завершению спринта
- Подготовка и выступления на командных собраниях
- Написание кода отдельных частей системы(например, скрипт для считывания штрих-кода книги и тд.)

### Екатерина Брехова
- Создать модальное окно об успешном возврате книги
- Реализовать отправку запроса на добавление книги
- Добавить кнопку сканировать на главную страницу
- Прописать логику для авторизации
- Прописать логику для регистрации
- Добавить валидацию для форм регистрации и авторизации
- Реализовать функционал для возвращения книги в библиотеку
- Реализовать рабочий вариант авторизации и регистрации
- Создать страницу авторизации и регистрации
- Командная работа над задачей(BF-18)
- Проделать операции из родительской задачи(BF-22)
- Создание layouta для всех страниц кабинета библиотекаря

### Алексей Ермолин
- Настроить мягкое удаление
- Определить тестовые данные в сущности "example_book"
- Добавить тестовые данные
- Перенести концепт БД в СУБД
- Создать схему БД
- Создание и настройка бд
- Проведение нагрузочного тестирования сервера
- Консультации других студентов по вопросам БД
- Ведение резервного сервера
- Нормализация БД

### Кудряшова Анастасия
- Написать документацию к созданным методам
- Изменить контроллеры для добавления книги в систему
- Прописать модели для каждой сущности в БД
- Написать документацию к созданным методам
- Реализовать модели для сущностей, связанных с "book_examples"
- Настроить среду разработки backend a
- Командная работа над задачей(BF-23)
- Консультирование по вопросам Backend
- Изучение необходимых библиотек
- Написание отчетов по деятельности подгруппы Backend

### Марвах Марк
- Отображение модального окна об успехе добавления
- Добавить валидацию
- Реализовать отправку запроса для добавления книги
- Реализовать функционал для добавления книги
- Создать страницу добавления книги в систему
- Установить React js и настроить окружение для разработки
- Создать страницу с формой для поиска книги и таблицу-каталог всех книг
- Участвовать на общих встречах команды
- Ознакомиться с нужными библиотеками по CSS и JS
- Разработать сайт для сайта

### Мартынова Анастасия
- Написать документацию к созданным методам
- Создать api методы для получения данных о книге по коду или isbn
- Разобрать данные, которые можно с данных сервисов
- Найти сервисы где по коду isbn или торговому коду можно найти информацию о книге
- Реализовать функцию поиска книги по ее торговому номеру
- Проделать операции из родительской задачи(BF-31)
- Командная работа над задачей(BF-23)
- Провести анализ различных онлайн-библиотек
- Выступления на общекомандных встречах
- Консультирование других участников по вопросам Backend

### Наталья Павлова
- Изменить сущности для реализации пользовательской авторизации
- Командная работа над задачей(BF-24)
- Настроить мягкое удаление
- Добавить тестовые данные
- Создать схему БД
- Создание и настройка бд
- Ведение отчетов по БД
- Нормализация БД
- Выступление на общекоманднхы встречах
- Консультация других групп по вопросам работы подгруппы "IT"

### Смирнов Егор
- Контролировать изменения внутри базы данных
- Перевести сайт на работу по протоколу https
- Предоставить уровни доступа к БД
- Настроить разворачивание резервной копии определенной части системы
- Создание резервной копии части системы после публикации
- Настроить резервное копирование
- Настроить логирование систем
- Настроить работу с удаленными репозиториями
- Настроить сервер для разработки
- Контролировать согласованность основного и резервного серверов

### Александр Шибанов
- Изменить метод books addExampleBook
- Реализовать методы поиска книги по коду isbn и торговому коду из внешних сервисов
- Написать документацию к созданным методам
- Изменение статуса, найденной книги и добавление ответа на запрос
- Добавить функционал для получения состояния книги
- Прописать роуты и контроллеры для получения book_example_id
- Разработать функционал для возврата книги в библиотеку
- Ограничить доступ к api неавторизированному пользователю
- Реализовать добавление токена и выдачу токена
- Написать документацию к созданным методам для сущности users
- Добавить метод авторизации пользователя
- Добавить метод регистрации пользователя
- Реализовать регистрацию и авторизацию пользователя
- Проделать операции из родительской задачи(BF-31)
- Продумать и описать объекты данных
