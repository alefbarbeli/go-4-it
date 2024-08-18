## web-service-gin:
```
cd /web-service/gin

go run .

```

> get all
```
curl http://localhost:8080/albums
```

> get by id
```
curl http://localhost:8080/albums/2
```

> create one
```
curl http://localhost:8080/albums \
--include \
--header "Content-Type: application/json" \
--request "POST" \
--data '{"id": "4","title":"Zero e Um","artist":"Dead Fish","price": 49.00}'
```
