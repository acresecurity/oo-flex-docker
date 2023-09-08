

## Getting Started

1. Clone this repo `git clone https://bitbucket.org/ooaccess/flex-docker.git`
2. Change directory to the repo `cd flex-docker`
3. Edit `.env` file.
4. Run `docker-compose up -d`

## Config .env

### linux
```shell
cp .env.template .env
vim .env
```

### Windows
```shell
copy .env.template .env
code .env
```

### Required Settings

```ini
# Hostname or IP address of the database server, can include the instance name as well.
#   myServerAddress
#   myServerAddress\myInstanceName
databaseServer=
# SQL database name 
databaseName=
# SQL authentication username
databaseUsername=
# SQL authentication password
databasePassword=
```