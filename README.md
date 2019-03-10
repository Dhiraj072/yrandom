# Yrandom
Yrandom is a web application to watch random youtube videos. I have been working on this as my pet project.


## Architecture
Yrandom is decomposed into a UI client and various microservices. 

These include:

-   [yrandom-client](https://github.com/Dhiraj072/yrandom-client) - A web UI client which displays the random video
-   [yrandom-api-gateway](https://github.com/Dhiraj072/yrandom-api-gateway) - An API gateway for all incoming HTTP requests
-   [youtube-service](https://github.com/Dhiraj072/youtube-service) - A microservice to get random youtube videos using [Youtube Data API](https://developers.google.com/youtube/v3/)
-   [yrandom-eureka-naming-server](https://github.com/Dhiraj072/yrandom-eureka-naming-server) - Naming server where youtube-service and yrandom-api-gateway instances register

![alt text](https://user-images.githubusercontent.com/12563778/54036766-66447200-41f7-11e9-82b8-f6147f0ce31f.jpg)


## Authors

-   [Dhiraj](https://github.com/dhiraj072)
