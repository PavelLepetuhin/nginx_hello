## Собираем образ
```bash
docker build . --tag=nginx:hello
```

## Запускаем контейнер из образа и пробрасываем порт
```bash
docker run --name my-nginx-server -d -p 8081:80 nginx:hello
```