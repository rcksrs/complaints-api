# Complaints System API
📜 System developed for consumers register complaints about products or services offered by companies<br><br>

## 💻 Microservices

The microservices below are part of the complaint system and the source codes can be found by the link provided.

1. Company Service: [https://github.com/rcksrs/company-service](https://github.com/rcksrs/company-service)<br>
2. Complaint Service: [https://github.com/rcksrs/complaint-service](https://github.com/rcksrs/complaint-service)<br>
3. Discovery Service: [https://github.com/rcksrs/discovery-service](https://github.com/rcksrs/discovery-service)<br>
4. Gateway Service: [https://github.com/rcksrs/gateway-service](https://github.com/rcksrs/gateway-service)<br><br>

## 📋 Documentation

The system documentation can be found in the project itself, through the links above informed or through the gateway:

```
https://ra-gateway-service.herokuapp.com/company-service/swagger-ui.html
```

```
https://ra-gateway-service.herokuapp.com/complaint-service/swagger-ui.html
```
<br>

## 💡 Useful Informations
1. Due to the limitations of Heroku's free account, microservices stop automatically after 30 minutes of inactivity, so it's necessary to run each one manually (by accessing the URL) for them to work correctly<br>
2. The systems use an environment variable to connect to the database. It is necessary to set the variable MONGODB_DEV_URL with the MongoDB acess URL.<br>