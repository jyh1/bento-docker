# Set up Workflow Instance

Use the [.env](./.env) file for configuration. Some important fields:

|  Field |  Usage  |
|:---------:|:------------------------:|
| CODALAB | The url of the CodaLab backend you want to use. Make sure it is accessible in your backend machine. |
| PORT | Port number of the app.|
| PUBLICUSER | The user name whose tool folder is public.|
| MYSQLDATA | System location to store the mysql data. |


Set up everything with:
```
docker-compose up -d
```

If success, you should be able to access the app at `http://localhost:$PORT/workflow/`.