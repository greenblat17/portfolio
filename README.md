# Portfolio of Alexander Zhuravlev

    Portfolio: 
        - Java Developer
        - СS student at Saint Petersburg Electrotechnical University
        - https://github.com/greenblat17

## Учебная практика в ЛЭТИ
    Сервис ввода, индексации и поиска txt-образов документов в базе данных
    
    Особенности:
        - аутентификация пользователей
        - создание индекса базы данных документов (построения нового индекса всей базы документов)
        - индексация вновь добавленных в БД документа
        - очистка индекса от удаленных из БД версий документов
        - поиск релевантных документов по введенной строке
    
    Стэк:
        - Java 17, Spring Boot, Spring Security, Apache Solr, PostgreSQL, Lombok, Maven, Thymeleaf
        - Тестирование: Junit 5, Mockito
        - Приложение упаковано в docker сontainer и разворачивается с помощью docker-compose.
        - Файлы docker и docker-compose приложены к проекту
    
    Ссылка:
        - https://github.com/greenblat17/index-document

## Социальная сеть
    Особенности:
        - Регистрация и JWT-аутентификация
        - Загружать фото профиля
        - Отправлять сообщения, содержащие текст и изображения
        - Просмотр ленты новостей, формирующейся из постов пользователей, на которых оформлена подписка
        - 
    
    Стэк:
        - Java 17, Spring Boot, Spring Security, Spring Dat JPA,  PostgreSQL, Swagger, Maven
    
    Ссылка:
        - https://github.com/greenblat17/social-media
    

## Приложение для учета возраста 
    Особенности:
        - Считывание текстового файла при запуске 
        - Поиск среднего возраста человека по имени
        - Если имени нет в БД, сервер обращается к стороннему API
        - Статистика по частотности запросов в разрезе имен
        - Статистика по имени с наибольшим возрастом
    
    Стэк:
        - Java 17, Spring Boot, H2database, PostgreSQL, Lombok, Maven, Thymeleaf
        - Тестирование: Junit 5, Mockito
    
    Ссылка:
        - https://github.com/greenblat17/person-data

## Телеграм бот для генерации пароля
    Особенности:
        - Пароль создается по алгоритму, который всем известен
        - Для каждого сервиса создается новый пароль
        - Пользователь вводит только секретное слово и секретные цифры

    Стэк:
        - Golang, telegram-bot-api

    Ссылка:
        - https://github.com/greenblat17/password-generator

## Приложение обмена валют
    Особенности:
        - Просмотр и редактирования списка валют и обмен курсов
        - Возможность совершать расчет конвертации произвольных сумм из одной валюты в другую
    
    Стэк:
        - Java, Servlets, JDBC, PostgreSQL, Lombok, Maven
        - Тестирование: Junit5
    
    Ссылка:
        - https://github.com/greenblat17/currency-exchange
    
## Приложение списка дел (монолит)
    Особенности:
        - Аутентификация и авторизация пользователей на JWT
        - Возможность добавлять задачи, указывать категории и их приоритет
        - Возможность искать задачи по названию, категории, приоритету
    
    Стэк:
        - Spring Boot, Spring Data, Spring Security, REST API, PostgreSQL, Lombok, Maven, 
    
    Ссылка:
        - https://github.com/greenblat17/todo-backend

## Приложение списка дел (Spring Сloud)
    Особенности:
        ToDo приложение реализовал на микросервисной архитектурые
        Микросервисы: мс задачи, мс регистрации пользователей. У каждого микросервиса своя база данных
    
    Стэк:
        - Java 17, Spring boot, Spring Cloud, Spring Data, Spring Security, REST API, Lombok, PostgreSQL, Maven, Discovery Eureka
    
    Ссылка:
        - https://github.com/greenblat17/planner-microservices
