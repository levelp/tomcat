# tomcat
Tomcat 8.0.30

Распаковать .zip архив в папку, например в D:\tomcat

Запуск tomcat - переходим в каталог D:\tomcat
``` cmd
catalina.bat run
```

Открыть страницу: http://localhost:8080/

Добавление пользователя
-----------------------
В файле tomcat\conf\tomcat-users.xml
``` xml
  <role rolename="manager-gui"/>
  <user username="admin" password="123" roles="manager-gui"/>
```
