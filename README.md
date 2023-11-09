# M12_Auth
 REST API  app with Authorization and Authentication


Запустіть контейнер з базою даних PostgreSQL командою:

```
docker run --name db-postgre -p 5432:5432 -e POSTGRES_PASSWORD=567234 -e POSTGRES_DB=contacts -d postgres


Для взаємодії з побудованим REST API, будемо використовувати Swagger документацію http://127.0.0.1:8000/doc


alembic init migrations
alembic revision --autogenerate -m 'Init'
alembic upgrade head