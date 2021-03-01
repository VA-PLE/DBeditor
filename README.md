Add the database to the container:
```docker exec -i editdb_mariadb mysql -udb -pdb db < DUMP.sql```

Create a dump:
```docker exec -i editdb_mariadb mysqldump -udb -pdb db > NEW_DUMP.sql```

PMA url: http://pma.docker.localhost:9999
