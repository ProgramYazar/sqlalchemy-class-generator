###READ

Basic tool for generate SqlAlchemy python classes from mysql tables. I dont try with sqlite if you try please send me feedback.

it supports

* enum values
* probably other basic types
* auto increment
* primary key
* accept or not null values 

all classes use Base super class, you can declare Base like:
> Base = declarative_base()

Not: please install sqlalchemy from repo or pip before run this command. i dont use any other library for easy usage.

###USAGE


Make file runnable
> $ chmod +x sqla_class

Run it with parameters
> $ ./sqla_class --db_host localhost --db_user root --db_pass "123456" --db_name your_database_name --db_charset utf8 --filename=out.py

you can use parameters like:

* --key value
* -key value
* key  value
* --key=value
* -key=value
* key=value

If you have a problem send me email (programyazar[at]gmail[dot]com)
