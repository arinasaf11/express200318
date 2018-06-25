# I. Создание веб-приложения с помощью node.js с использованием серверного шаблонизатора
Цель: создать серверное приложение, которое получает массив объектов, каждый из которых имеет свойство login, из адреса https://kodaktor.ru/j/users и использует шаблон pug для вывода в веб-страницу списка этих логинов.  
### 1.Инициализируем проект
`mkdir express_project`
`cd express_project`
`curl -s https://kodaktor.ru/g/eslint_exec`
### 2.Устанавливаем	фреймворк	express и	шаблонизатор	pug, а	также	инструмент	axios
`yarn add express pug	axios`
### 3.Устанавливаем nodemon
`yarn add --dev nodemon`
### 4.Добавляем в файл package.json раздел scripts с командой start:
### 5.Создаем файл index.js в папке ./src
### 6.Создаем файл list.pug в папке ./views
