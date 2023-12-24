# REST API in Golang

This is sample code for showing how to create rest API in golang. 

Before you test API, get these Go packages

  go get github.com/gorilla/mux
  go get github.com/lib/pq
  go get database/sql
  
GET movies
GET - localhost:8000/movies

POST movies
POST localhost:8000/movies/?movieid=1&moviename=sdgds

Delete movies
DELETE localhost:8000/movies/

