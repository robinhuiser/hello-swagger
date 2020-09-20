# Go Hello Swagger

Project demonstrating implementing a microservice exposing a RESTful API from a swagger spec in Go.

## Prerequisites

* Go
* Swagger CLI (`$ go get -u -v github.com/go-swagger/go-swagger/cmd/swagger`)
* [Glide](https://github.com/Masterminds/glide) (`$ brew install glide`)
* Make (Install Apple developer tools)

## Run the project

~~~bash
# Validates swagger YAML
# Generates swagger code
# Installs deps & binary into path
$ make build

# In terminal #1, run server:
$ hello-swagger --port 8080

# In terminal #2, connect with client
$ curl localhost:8080/hostname
~~~
