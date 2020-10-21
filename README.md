https://bullettime23.github.io/formTask/
Созданное мной приложение позволяет собирать коллекции данных при регистрации, и хранить их на сервере с базой данных, который вы можете скачать в файле ZIP, и запустить на своём компьютере при помощи команды "server". После успешной регистрации приложение отправляет запрос на сервер для получения базы, и показывает полученные данные на экране.
 
ВНИМАНИЕ: если вы запустили базу данных на своём компьютере и собираетесь опубликовать в своём репозитории, обязательно удалите свои конфиденциальные данные из файла DB.js! В противном случае, они могут оказаться  третьих лиц!

Приложение сделано на платформе Angular 10
Сервер с помощью Node.js, Express, lowDB
___________________________________________________________________________________________________________________________________________________________________________ 
WARNING: this application only can collects data when the local server from ZIP is started! Do not sent your JSON (DB) file to anyone, if it contains some confidential data! https://bullettime23.github.io/formTask/ ; http://localhost:3000/

This Aplication consists of two parts:

FIRST - an adaptive interface, that collects and validates users data via inputs and creates a formData object. API sends object to
SECOND part - local DB server, that can be downloaded (JSON server DB). Unpack the server and start it on your computer through "node server" command in your cmd.
The server collects data from API into DB JSON file, and sends the subscribers array to API. 

Good luck ;D

For this project I've used:
- ANGULAR as a frontend framework (page routing, reactive forms, deafult and custom validators, http client...)
- NODE js
- Express as a server framework (cors, lowDB)
