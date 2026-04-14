## Установка прокета

### Требования

- .NET 10

- PostgreSQK 18



### Установка

1. Клонировать репозиторий
   
   ```
   https://github.com/vankadulapa/KursWEBSchool
   ```

2. Создать БД
   
   ```
   psql -U postgres -c "CREATE DATABASE school ENCODING 'UTF8';"
   psql -U postgres -d school -f database/schema.sql
   psql -U postgres -d school -f database/seed.sql
   ```
   
   

3. Запустить проект
   
   ```
   cd src
   dotnet run
   ```
   
   
