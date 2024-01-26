Данная Postman collection состоит из следующих методов  

POST - создание Issue. Из тела ответа в Environments добавляются переменные issues_number и issuesid  

GET - получение списка issue. В ответе имеется визуализация ответа. Так же есть проверка наличия issue  с телом как при создании.   

PATCH - изменение названия issue. Скрпит проверяет изменилось ли название на необхидимое.  

POST - с помощью mutattion в GraphQL удаляется issue  

GET - получение списка issue. Скрипт по id проверяет удалилась ли нужное issue.   

---
+ Документация для API GitHub issues  
https://docs.github.com/en/rest/issues/issues?apiVersion=2022-11-28#about-issues  

+ Документация о mutation  
https://docs.github.com/en/graphql/guides/forming-calls-with-graphql#about-mutations  

+ Документация о удалении issue  
https://docs.github.com/en/graphql/reference/mutations#deleteissue  

