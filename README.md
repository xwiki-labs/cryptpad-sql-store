# cryptpad-sql-store

Storage API for cryptpad implemented using [knex.js](http://knexjs.org/) to expose a variety of sql datastores.

## Status

Experimental.

## Why?

To provide a Cryptpad data store which fits in well with a sysadmin's existing database tooling.

## Install

Installation requirements for this module depend on which back end you would like to use.

See the [knex documentation](http://knexjs.org/#Installation) for more details.

```
cd /path/to/cryptpad;
npm install cryptpad-sql-store;
```

## Configure

```
{
    storage: 'cryptpad-sql-store',
    sqlDialect: 'sqlite3',
    dbConnection: {
        filename: './mydb.db',
    },
}
```

## License

Available under the AGPLv3.0.
