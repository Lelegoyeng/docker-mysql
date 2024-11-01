### Run

`````
docker-compose up --build -d
`````

### Detail Options

`````
Username: root
Password: lelegoyeng
Database: db_lelegoyeng
Port: 3306
`````

### Backup DB from command docker exec
`````
docker exec db_mysql /usr/bin/mysqldump -u root -p lelegoyeng db_lelegoyeng > /tmp/backup.sql
`````
