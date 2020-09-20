## Overview
This code help to setup a simple php development envirnoment using docker

## Installation steps

### Prereqeusts
You need following packages for installing the application
Git - for downloading the reporsitory
Docker Desktop - All the application will start here

Clone or download the code to any location

```
....
  php:
   ...
    volumes: 
      - ./[your host computer code location]:/var/www/html
    ....
```

### Starting up services
```
docker-compose build && docker-compose up -d
```

