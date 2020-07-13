# README #

Steps :
1.) Create a database name my_database.sql and V1_Create_tables.sql
2.) Download Zip file and extract in local directory.
3.) Run in netbeans.

### Docker Compose

We use Docker Compose to launch this application. Here is how to do it:

```
docker-compose up -d --build
```

See in the docker-compose.yml file for which ports it listens on.

### Database migrations

We use Flyway to manage the different SQL scripts for each change to the database schema.
Docker Compose should run flyway scripts automatically. Simply add scripts under flyway/sql/
and make sure to follow the numbering system of flyway.

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
