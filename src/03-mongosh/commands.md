# Connect to container

```sh
docker-compose exec mongodb bash
```

# Connect with mongosh

```sh
mongosh "mongodb://root:********@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://******:******@cluster0.luyxcni.mongodb.net/test"
```

```sh
show dbs
show collections
```

```sh
use("MisAngeles_store")
db.productos.find()
```
