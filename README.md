# Enviroment Go with Docker

Use the following command to run the script:
<br>

```bash
docker run -it --name nginx -d -p 8000:80 --mount type=volume,source=data,target=/usr/share/nginx/html nginx bash
```

<br>

And after that you will see bash terminal, run the following command:

<br>

```bash
go run main.go
```