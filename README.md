Spring Data REST builds on top of Spring Data repositories, analyzes your application’s domain model and exposes hypermedia-driven HTTP resources for aggregates contained in the model.

This App runs on Java 1.8

# spring-data-rest
Exposes a discoverable REST API for your domain model using HAL as media type

# Access H2 DB from browser
http://localhost:9090/h2-console  
jdbc:h2:mem:testdb

# HAL, "Hypertext Application Language", is an open specification describing a generic structure for RESTful resources.
# HAL Browser for Spring Data REST
http://localhost:9090/browser/index.html#/  
http://localhost:9090/users
http://localhost:9090/users/103
http://localhost:9090/users?page=1&size=2
http://localhost:9090/users/search/findByEmail?email=pat@gmail.com
http://localhost:9090/users/search/findByName?name=Tom