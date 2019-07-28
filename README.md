# R2RML

Create a tool that transforms relational data to RDF based on arbitrary R2RML mappings

## Installation


## Usage
- files in `model` will be added to SQL-DB


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Start Docker with Database

```
docker-compose -f docker-my-sql.yml up
```

## Connect to mysql when docker is running:
```
mysql -h 127.0.0.1 -P 3306 -u root -D mysql-development
```

## Fill database with sql script
```
mysql -h 127.0.0.1 -P 3306 -u root -D mysql-development < python/sql/fillDatabases.sql 
```