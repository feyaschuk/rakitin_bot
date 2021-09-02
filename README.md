#### Описание:
Бот для нотификации при появлении новых публикаций на авторском сайте Ракитина А. (murders.ru).

### Позволяет:
* регулярно делать запросы к сайту, парсить главную страницу и проверять, есть ли новые публикации
* получать оповещение в Телеграмме о новых статьях
* получать оповещение в Телеграмме об ошибках в работе бота

### Используемые технологии:
* beautifulsoup4==4.9.3
* pycparser==2.20
* pyparsing==2.4.7
* pytest==6.2.1
* python-dotenv==0.13.0
* python-telegram-bot==12.7
* requests==2.23.0
* heroku==0.1.4

### Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```bash
git clone https://github.com/feyaschuk/rakitin_bot.git
```
```bash
cd rakitin_bot
```
Cоздать и активировать виртуальное окружение:
```bash
python3 -m venv env
```
```bash
source env/bin/activate (Mac OS, Linux) или source venv/Scripts/activate (Win10)
```
```bash
python3 -m pip install --upgrade pip
```
Установить зависимости из файла requirements.txt:
```bash
pip install -r requirements.txt
```

В основной директории добавьте файл .env, в котором укажите свои ключи для Telegramma.

* TELEGRAM_TOKEN = 
* TELEGRAM_CHAT_ID =

Запустить проект:
```bash
python3 manage.py runserver
```
