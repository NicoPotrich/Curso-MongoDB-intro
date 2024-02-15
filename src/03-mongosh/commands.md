## Connect to container and run mongodb shell

``` sh
docker-compose exec mongodb bash
```


## Connect with mongosh

``` sh
mongosh "[<url de conexion>](mongodb://root:******@localhost:27017/?tls=false)" 
mongosh "mongodb+srv://nicoadmin:******@cluster0.qa49oo6.mongodb.net/" 
```

``` sh
show dbs
show collections
```

``` sh
use "<data-base>"
db.products.find()
```



