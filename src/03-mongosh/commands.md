## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:example@localhost:27017/?authMechanism=DEFAULT"
mongosh "mongodb+srv://wilmer_admin:wilmer_admin@mongodb-01.31jxbcf.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```
