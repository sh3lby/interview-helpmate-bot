# Телеграм Бот для подготовки к собеседованию по фронтенд-разработке

Бот написан на **Node JS** с использованием библиотек:
* [grammY](https://grammy.dev/)
* [random-js](https://www.npmjs.com/package/random-js)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [nodemon](https://www.npmjs.com/package/nodemon)
### Инструкция по обновлению бота

На сервере в консоле
```
pm2 stop index.js
```
```
pm2 delete index.js
```
После этого подтянуть изменения на сервер

```
git pull origin main
```
И снова запустить бота
```
pm2 start index.js
```