## step by step to run this project:

setup database: `docker compose up -d`

starts the server: `go run main.go`

now you're ready to go!

## to test quickly :

GET `http://localhost:8080` - it will return all people stored in db

POST `http://localhost:8080/create` - it will insert a new person in db
