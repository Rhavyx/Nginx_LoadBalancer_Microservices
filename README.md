### Nginx as Load Balancer  

---  
* Nginx as load balancer of 2 microservices.
* Nginx port exposed: 8011

```
docker-compose up -d --build 
```
  
### RabbitMQ  
```
docker run -d -p 15672:15672 -p 5672:5672 -p 5671:5671 --hostname my-rabbitmq --name my-rabbitmq-container rabbitmq:3-management
```
