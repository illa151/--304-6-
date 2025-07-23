# Backend (Java)

## Опис
Простий HTTP сервер на Java, який повертає "Hello, World!" на ендпоінті `/hello`.

## Запуск
1. Скомпілюйте Main.java:
   ```sh
   javac Main.java
   ```
2. Запустіть сервер:
   ```sh
   java Main
   ```
3. Перейдіть у браузері за адресою: [http://localhost:8080/hello](http://localhost:8080/hello)

## Залежності
- Java 8 або новіше (JDK)
- Вбудований HttpServer (com.sun.net.httpserver)
