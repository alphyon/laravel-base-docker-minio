# Base project Laravel Momotolabs
This a base config to manage projects with laravel v9.21.2

## Include
 **Larastan** for analyse code use this command
```
./vendor/bin/phpstan analyse
```

**Laravel ide helper** for help some references in IDE, this automatical update when execute some composer command

**Laravel pint** for style code fixed for use run this command

```
./vendor/bin/pint
```

also is publish the stub from made easy changes in templates for code generate with laravel commands


## to run dockerized project:

1. create copy of `.env.example` and rename to `.env`
2. in the file `.env` add or change the value of the var `PROJECT_NAME` this value is the name to rename the 
containers an internal volumes.
3. execute the command `docker-compose build` or `docker-compose up -d`
4. have fun coding :)

## Check the makefile.
In this project, a file with the name `Makefile` is added, which contains a series of commands to facilitate some repetitive tasks of development and work with docker containers and other commands that have been abbreviated to be used in an easier way.

