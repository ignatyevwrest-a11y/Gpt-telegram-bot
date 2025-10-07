# GPT-5 Telegram Bot 🤖

## 🚀 Установка и запуск локально

1. Установи зависимости:
   ```bash
   pip install -r requirements.txt
   ```

2. Создай `.env` или установи переменные окружения:
   ```bash
   export TELEGRAM_TOKEN="твой_токен_бота"
   export OPENAI_API_KEY="твой_openai_api_key"
   ```

3. Запусти:
   ```bash
   python main.py
   ```

---

## ☁️ Деплой на Render / Railway

1. Залей проект на GitHub.
2. Создай новый Web Service.
3. Добавь переменные окружения:
   ```
   TELEGRAM_TOKEN = твой_токен_бота
   OPENAI_API_KEY = твой_openai_api_key
   ```
4. Render сам запустит `python main.py`.

✅ Готово! Бот будет работать 24/7.
