## To test it:

```
curl http://localhost:8080/albums
```


```
curl http://localhost:8080/albums \
--include \
--header "Content-Type: application/json" \
--request "POST" \
--data '{"id": "4","title":"Zero e Um","artist":"Dead Fish","price": 49.00}'
```
