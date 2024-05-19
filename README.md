Hello everyone, this is my first bot, which is written in Docker + database with replication. To run it, you need to create a .env next to docker-compose and enter the following data:
```
TOKEN = YOUR_TOKEN
RM_HOST = YOUR_IP_FOR_SSH
RM_PORT = 22
RM_USER = YOUR_USER_FOR_SSH
RM_PASSWORD = YOUR_PASSWORD_FOR_SSH

DB_USER = postgres
DB_DATABASE = YOUR_DB_FOR_SSH
DB_PASSWORD = Qq12345
DB_PORT = 5432
DB_HOST = db_image

DB_REPL_USER = replicator 
DB_REPL_PASSWORD = Qq12345
DB_REPL_HOST = db_repl_image
DB_REPL_PORT = 5434
```

After that, you go into your bot and launch it
