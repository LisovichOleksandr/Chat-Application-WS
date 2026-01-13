💬 Chat Application (Spring Boot + WebSocket + STOMP)

Простий веб-чат, реалізований на базі Spring Boot, WebSocket, STOMP та SockJS.
Проєкт створений як навчальний та портфоліо-проєкт для демонстрації роботи з реальним часом у Java backend.

🚀 Функціональність

🔌 Підключення клієнтів через WebSocket

📡 Обмін повідомленнями в реальному часі (STOMP)

👥 Публічний чат (broadcast)

⌨️ Надсилання повідомлень кнопкою або клавішею Enter

🧵 Підтримка SockJS (fallback для браузерів без WebSocket)

🎨 Простий інтерфейс на Bootstrap

🛠️ Використані технології
Backend

Java 21

Spring Boot 4

Spring WebSocket

Spring MVC

STOMP Message Broker

Lombok

Frontend

HTML5

Bootstrap 5

JavaScript

SockJS

STOMP.js

Шаблонізатор

Thymeleaf

📂 Структура проєкту
src
 └── main
     ├── java
     │   └── li.chat.app
     │       ├── config
     │       │   └── WebSocketConfig.java
     │       ├── controller
     │       │   └── ChatController.java
     │       └── model
     │           └── ChatMessage.java
     └── resources
         ├── templates
         │   └── chat.html
         └── application.yml

🔧 Конфігурація WebSocket

Endpoint підключення:

/chat


Вхідні повідомлення:

/app/sendMessage


Канал підписки:

/topic/messages

▶️ Як запустити проєкт
1️⃣ Клонувати репозиторій
git clone https://github.com/your-username/chat-application.git
cd chat-application

2️⃣ Запустити застосунок
mvn spring-boot:run

3️⃣ Відкрити в браузері
http://localhost:8080/chat

📸 Як це працює

Користувач відкриває сторінку чату

Вводить ім’я та повідомлення

Повідомлення надсилається через STOMP

Сервер ретранслює повідомлення всім підписаним клієнтам

Повідомлення миттєво з’являється у всіх учасників чату

🎯 Мета проєкту

Закріпити знання Spring WebSocket

Зрозуміти роботу STOMP Message Broker

Навчитись будувати real-time застосунки

Створити якісний портфоліо-проєкт

👤 Автор

Олександр Лісович
Java / Spring Boot Developer

📌 Плани на майбутнє

🔐 Авторизація користувачів

🗂️ Кілька чат-кімнат

🕒 Час повідомлень

💾 Збереження історії в базі даних

👨‍💻 Приватні повідомлення
