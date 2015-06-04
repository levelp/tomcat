# tomcat
Tomcat 8.0.20

Запуск
``` cmd
catalina.bat run
```

Открыть страницу: http://localhost:8080/

Добавление пользователя
-----------------------
``` xml
  <role rolename="manager-gui"/>
  <user username="admin" password="123" roles="manager-gui"/>
```
