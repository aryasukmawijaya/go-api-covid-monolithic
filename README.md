API Covid-19 Monolithic
=========

A simple API Covid-19 running on monolithic architecture.

Getting started
---------------

First, you need to have mysql database service and run .sql file in sql folder. Then setup the config file named .server.toml, in this configuration file you should set the database host, port, user, password, and database name.

After that, you can run this command:
```
go run main.go
```

Open a browser and enter url /summary
