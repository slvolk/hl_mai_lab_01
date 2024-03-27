# Задание 02: Stateful сервис 
 
Цель 
Получение практических навыков в построении сервисов, работающих с данными. 
Задание 
Разработать приложение на языке C++ осуществляющее хранение сущностей согласно вашего варианта задания. Для выявленных в предыдущем задании вызовов между сервисами создайте REST интерфейс.  
 
Должны выполняться следующие условия: 
	Данные должны храниться в СУБД MariaDb; 
	Должны быть созданы таблицы для каждой сущности из вашего задания; 
	Интерфейс к сущностям должен предоставляться в соответствии со стилем REST; 
	API должен быть специфицирован в OpenAPI 3.0 (должен хранится в index.yaml); 
	Должен быть создан скрипт по созданию базы данных и таблиц, а также наполнению СУБД тестовыми значениями; 
	Для сущности, отвечающей за хранение данных о человеке (клиенте), должен быть реализован интерфейс поиска по маске фамилии и имени. 
 
Рекомендуема последовательность выполнения работы: 
•	Создайте схему БД 
•	Создайте таблицу 
•	Создайте скрипт для первичного наполнение БД и выполните 
•	Реализуйте REST-сервис на C++ с помощью POCO 
•	Сделайте спецификацию с OpenAPI с помощью Postman и сохраните ее в index.yml 
•	Протестируйте сервис 
•	Создайте Dockerfile для вашего сервиса 
•	Протестируйте его работу в Docker 
•	Опубликуйте на github проект 
