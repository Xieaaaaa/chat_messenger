# chat_messenger
Разработка клиент-серверного приложения для обмена сообщениями
## Установка и запуск
1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/Xieaaaaa/chat_messenger.git
   cd chat-messenger
   ```

2. **Настройка серверной части:**
   bash
   cd server
   npm install
   ```
   - Создайте файл `.env` в папке `server` и укажите настройки (например, `JWT_SECRET`, `DB_URL`).
   - Запустите сервер:
     ```bash
     npm start
     ```

3. **Настройка клиентской части:**
   ```bash
   cd ../client
   npm install
   ```
   - Запустите клиент:
     ```bash
     npm start
     ```

4. **Доступ к приложению:**
   - Клиент будет доступен по адресу: `http://localhost:3000`.
   - Сервер будет работать на `http://localhost:5000`.


## Тестовые данные
Для тестироания созданы два пользователя:

1)Иванов Иван

Email:
```bash
Ivanov.23V@yandex.ru
```
Password: 
```bash
123456789pass
```
2)Дмитрий Сидоров

Email:
```bash
Sidorov.23V@yandex.ru
```
Password:
```bash
123456789pass
```
