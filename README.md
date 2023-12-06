# Деплой приложения на сервер с использованием pm2

Стартеркит проекта по автоматизации деплоя фронтенда и бэкенда при помощи pm2 (pm2 deploy)
* IP адрес 158.160.30.29
* Frontend [https://...](https://mesto-p-kotta.nomoredomainsmonster.ru/)https://mesto-p-kotta.nomoredomainsmonster.ru/
* Backend [https://...](https://api.mesto-p-kotta.nomoredomainsmonster.ru)https://api.mesto-p-kotta.nomoredomainsmonster.ru

Пример .env.deploy
```
DEPLOY_USER="user"
DEPLOY_HOST=192.0.2.1
DEPLOY_PATH="/home/user/mesto"
DEPLOY_REPOSITORY="https://github.com/user/repository.git"
DEPLOY_REF = "origin/master"
```
