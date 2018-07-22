# NODE with restful example using expressjs

## Using -> http://expressjs.com/

## Using -> Docker:
``` docker build -t alexsrosa/node-api-restful:alpha . ``` 
``` docker run -d -p 8081:8080 alexsrosa/node-api-restful:alpha ``` 
``` docker container list -a ``` 
``` docker stop <container> ``` 

``` docker login ``` 
``` docker push alexsrosa/node-api-restful:alpha ``` 

### Others commands:
``` docker container prune ``` 
``` docker container ls ``` 
``` docker container ps ``` 

## Routers: 
- GET -> http://localhost:8081/votes
- GET -> http://localhost:8081/votes/1
- PUT -> http://localhost:8081/votes