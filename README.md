## Aston - Discovery Server
Часть микросервисного приложения [aston-project](https://github.com/gedfalk/aston-project).

Центральный реестр микросервисов, в него будут попадать:
- user-service
- notification-service
- api-gateway
- config-server
- eureka-server

### 🚀 Быстрый старт
```shell
# 1. Поднимаем докер из aston-project

# 2. 
git clone https://github.com/gedfalk/aston-discoveryServer
cd aston-discoveryServer

mvn spring-boot:run

# 3. Запускаем aston-configServer
# 4. Запускаем aston-apiGateway
# 5. Запускаем aston-project (user-service)
# 6. Запускаем aston-notificationProject (notification-service)
```
---

### 📡 Проверка

- http://localhost:8761
