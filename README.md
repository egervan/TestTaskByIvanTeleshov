# TestTaskByIvanTeleshov
Developed for solanteq by Ivan Teleshov.

Использовал Spring boot и AngularJS. База данных PostgreSql.
Помимо отображения списка сотрудников реализовано добавление новых и удаление старых записей.
Также задеплоил проект на heroku.com, так что можно сразу посмотреть его в действии: https://teleshovivantesttask.herokuapp.com
 
На github две ветки - master и heroku. Отличаются данными для доступа к БД. Т.е. можно использовать ветку heroku и сразу подключится к БД на heroku.
Для использования ветки master необходимо обеспечить наличе БД 'user_db' на localhost:5432
Во время запуска БД автоматически инициализируется тестовыми данными.
Также реализовал тесты для проверки работоспособности проекта.
