# snippetsbox

Snippets storage

app start
```sh
go run cmd/web/* -addr=":9999"
```

получить справку по флагам
```sh
go run cmd/web/* -help
```

пустить логи приложения в файл при запуске
```sh
go run cmd/web/* >> /tmp/info.log 2 >> /tmp/error.log
```