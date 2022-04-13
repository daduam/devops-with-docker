```console
> docker images | grep "simple-web-service"

devopsdockeruh/simple-web-service   ubuntu         4e3362e907d5   13 months ago   83MB
devopsdockeruh/simple-web-service   alpine         fd312adc88e0   13 months ago   15.7MB

> docker run -d --name simple_web_service_alpine devopsdockeruh/simple-web-service:alpine

> docker exec -it simple_web_service_alpine sh
```
