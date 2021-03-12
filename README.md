
Запуск
1. Сделать клон проекта, и при запуске добавить свой токен.
2. docker build -f docker/Dockerfile docker/ -t telegram-bot
3. docker run -d -p 8443:8443 -v /data/:/data/ telegram-bot bot.py your_token
