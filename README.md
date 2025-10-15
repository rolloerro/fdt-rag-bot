# 🤖 FDT RAG Bot

Телеграм-бот на Python для поиска и ответов по медицинским PDF-документам (например, "001_onco.pdf") с использованием Retrieval-Augmented Generation (RAG).

---

## 🚀 Возможности
- Читает PDF-файлы и разбивает их на предложения.  
- Отвечает на вопросы на основе содержимого документа.  
- Использует Sentence Transformers для семантического поиска.  
- Защищён — токены и секреты хранятся в `.env`.

---

## ⚙️ Установка и запуск

```bash
# 1. Клонируй репозиторий
git clone https://github.com/rolloerro/fdt-rag-bot.git
cd fdt-rag-bot

# 2. Создай виртуальное окружение и активируй
python3 -m venv venv
source venv/bin/activate

# 3. Установи зависимости
pip install -r requirements.txt

# 4. Создай файл .env и добавь туда:
# TELEGRAM_BOT_TOKEN=твой_токен

# 5. Запусти бота
python3 fdtpromo_bot.py
🧩 Стек

Python 3.10+

python-telegram-bot

sentence-transformers

PyPDF2

dotenv

📄 Структура
fdt-rag-bot/
├── fdtpromo_bot.py       # Основной код бота
├── requirements.txt      # Зависимости
├── .gitignore

👨‍💻 Автор

rolloerro
Telegram | GitHub | TARS team 🚀 

