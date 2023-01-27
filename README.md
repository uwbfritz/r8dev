
# WDS Development Container

```
├── config
│   ├── apache2.conf         # Apache 2.4 config  
│   └── php.ini              # php.ini  - adjust as necessary
├── docker-compose.yml       # docker-compose file -- usage: docker-compose up -d
├── Dockerfile               # Dockerfile (build-file) -- usage: docker build -t uwbfritz/wdsdev:latest .
├── README.md                # This file
└── devenv                   # Development environment script wrapper
```

- Your database will persist
- Composer installed
- Drush installed

### Usage:
```
./devenv    # Obtain a list of options

Usage: devenv [function] [param]

Functions:

   build  - Build the docker image
   load  - Load the database from a sql file
   dump  - Dump the database to a sql file
   clone  - Clone the repo into the html directory
   start  - Start the development environment
   stop  - Stop the development environment
   attach  - Attach to the frontend container
   attachto  - Attach to an active container
   destroy  - Destroy the development environment
   destroyall  - Destroy all containers, images, volumes, networks, and your dev environment
```
