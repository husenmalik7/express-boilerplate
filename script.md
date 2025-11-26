# #Script

## database

```
psql --username postgres

CREATE DATABASE express_1;
GRANT ALL ON DATABASE express_1 TO developer;
ALTER DATABASE express_1 OWNER TO developer;
```

```
DROP DATABASE express_1;
```

## migrations

```
npm run migrate create "create table authentications"

npm run migrate
```
