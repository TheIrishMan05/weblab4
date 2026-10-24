# Машкин Григорий Андреевич P3230, вариант: 52199055

Необходимо было написать приложение с разделением ролей, регистрацией и авторизацией с сохранением данных в БД(Oracle DB) для определения попадания точек по графику. Backend: Spring, frontend: Vue.js

### Что использовалось для написания лабораторной?

1. Client-side: Vue.js, HTML + CSS
2. Server-side: Spring Boot, Spring Web, Spring Data, Spring Security, Hibernate, JPA.
3. СУБД: Oracle
4. Server: TomEE 10.1.30
5. Сборка проекта: Docker

### Как запустить лабораторную?

```
    git clone https://github.com/TheIrishMan05/weblab4.git
    cd weblab4/lab4backend
    ./gradlew build bootJar
    cd ..
    docker-compose up --build
```

Примечание: при холодном запуске БД приложение может подниматься больше обычного(около 10 минут).
### Project design

+ Страница регистрации
  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/80df1177-1db0-45cc-84f4-b4a70119aed3" />

+ Страница авторизации

<img width="1912" height="1080" alt="image" src="https://github.com/user-attachments/assets/cda370e1-c60f-44c8-a2b6-e854ddf55325" />

+ Главная страница
  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/593e2b7f-cf07-4233-9a48-251e5428bddc" />
