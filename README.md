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
        - Сервис регистрации и авторизации пользователей на JWT token
        - Возможность выкладывать посты, лайкать их, а также вступать в группы
    
    Стэк:
        - Java 17, Spring Boot, Spring Security, REST API, PostgreSQL, Lombok, Swagger, Maven
        - Тестирование: Junit 5, Mockito
    
    Ссылка:
    - https://github.com/greenblat17/social-network
    

## Приложение для анализа тектсового файла
    Особенности:
        Создать web-приложение на Java, которое может cчитывать из текстового файла строки формата имя_возраст. Например: Андрей_27. Предоставлять веб-    интерфейс с полем ввода для произвольного имени. После отправки имени на сервер в ответ должен прийти возраст, соответствующий этому имени. Если имени нет в перечне, то должно возвращаться произвольное положительное целое число. Также аредоставлять возможность ведения просмотра статистики запросов по каждому имени:
        - вывод частотности запросов в разрезе имён
        - вывод имени с наибольшим возрастом
        Приложение будет поддерживать работу с внешним сервисом, который будет возвращать возраст произвольных имен, если их нет в текстовом файле
    
    Стэк:
        - Java 17, Spring Boot, H2database, PostgreSQL, Lombok, Maven, Thymeleaf
        - Тестирование: Junit 5, Mockito
    
    Ссылка:
        - https://github.com/greenblat17/person-data

## Приложение обмена валют
    REST API для описания валют и обменных курсов. Позволяет просматривать и редактировать списки валют и обменных курсов, и совершать расчёт конвертации произвольных сумм из одной валюты в другую.
    
    Стэк:
        - Java, Servlets, JDBC, PostgreSQL, Lombok, Maven
        - Тестирование: Junit5
    
    Ссылка:
        - https://github.com/greenblat17/currency-exchange
    
## Приложение списка дел (монолит):
    Особенности:
        - Аутентификация и авторизация пользователей на JWT
        - Возможность добавлять задачи, указывать категории и их приоритет
        - Возможность искать задачи по названию, категории, приоритету
    
    Стэк:
        - Spring Boot, Spring Data, Spring Security, REST API, PostgreSQL, Lombok, Maven, 
    
    Ссылка:
        - https://github.com/greenblat17/todo-backend

## Приложение списка дел (Spring cloud):
    Особенности:
        ToDo приложение реализовал на микросервисной архитектурые
        Микросервисы: мс задачи, мс регистрации пользователей. У каждого микросервиса своя база данных
    
    Стэк:
        - Java 17, Spring boot, Spring Cloud, Spring Data, Spring Security, REST API, Lombok, PostgreSQL, Maven, Discovery Eureka
    
    Ссылка:
        - https://github.com/greenblat17/planner-microservices
