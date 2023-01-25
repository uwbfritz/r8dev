
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
```
