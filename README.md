# rabbitmq-go

A testing project for rabbitmq with Golang client.

## Getting started
```
$ git clone git@github.com:ctc316/rabbitmq-go.git
$ cd rabbitmq-go
```

Run both RabbitMQ and Go environment on Docker
```
$ docker-compose up -d 
$ docker exec -it go_client1 bash
```

Install go dependency
```
$ go get
```


## Play with it

Access RabbitMQ management platform on Browser
```
$ Url: "localhost:15672"
$ user: "user"
$ password: "password"
```

Send message to RabbitMQ
```
$ go run send.go
```

Receive message from RabbitMQ
```
$ go run receive.go
```

## License
[MIT](https://github.com/ctc316/rabbitmq-go/blob/master/LICENSE)
