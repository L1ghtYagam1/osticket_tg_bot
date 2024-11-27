# osticket_tg_bot
Telegram Bot для отправки заявок в osTicket
# Aiogram Bot for osTicket Integration

Это бот для Telegram, который интегрируется с системой тикетов osTicket, позволяя пользователям отправлять заявки через Telegram.

## Требования

- Python 3.7+
- Библиотеки:
  - aiogram
  - requests

Вы можете установить их с помощью pip:


pip install aiogram requests
Настройка
Создайте новый бот в Telegram через BotFather и получите API токен.

Укажите полученный API токен в переменной API_TOKEN в коде.

Получите API ключ для вашего osTicket и укажите его в переменной OSTICKET_API_KEY.

Укажите URL вашего osTicket API в переменной OSTICKET_API_URL.

Пример:

python
Копировать код
API_TOKEN = 'ваш-API-токен'
OSTICKET_API_URL = 'https://ваш-домен/osticket/api/tickets.json'
OSTICKET_API_KEY = 'ваш-API-ключ'
Запуск
После настройки выполните следующий код:

bash
Копировать код
python bot.py
Взаимодействие с ботом
При первом запуске бот запросит ваш email.
После этого выберите отель, категорию и тему заявки.
Опишите вашу проблему, и бот отправит заявку в систему osTicket.
Лицензия
Этот проект распространяется под лицензией MIT.

