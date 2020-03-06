# Pro Spring Boot 2nd Edition
Pro Spring Boot 2nd Edition - Apress
## Chapter 1 Spring Framework 5


Run your tomcat. Go to a browser, and click the http://localhost:8080/todo URL

How can you get the JSON response? Open a terminal and execute the following command.

```
$ curl -H "Accept: application/json" localhost:8080/todo/toDos

[ {
  "id" : "7fd921cfd2b64dc7b995633e8209f385",
  "description" : "Buy Milk",
  "created" : "2018-09-23 15:00:01",
  "modified" : "2018-09-23 15:00:01",
  "completed" : false
}, {
  "id" : "5820a4c2abe74f409da89217bf905a0c",
  "description" : "Read a Book",
  "created" : "2018-09-02 16:00:01",
  "modified" : "2018-09-02 16:00:01",
  "completed" : false
}, {
  "id" : "a44b6db26aef49e39d1b68622f55c347",
  "description" : "Go to Spring One 2018",
  "created" : "2018-09-18 12:00:00",
  "modified" : "2018-09-18 12:00:00",
  "completed" : false
} ]  

```