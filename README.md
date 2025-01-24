# MovieFinder – Web Application for Movie Search and Ratings

**MovieFinder** is a web application built using **HTML**, **CSS**, and **JavaScript** that allows users to search for movies, view their descriptions, ratings, and additional details.

## Technologies Used:
* `HTML` for structuring the webpage.
* `CSS` for styling and responsive design.
* `JavaScript` for dynamic functionality and data handling.

## Purpose:
To simplify movie searches and provide users with quick access to essential information, including ratings and key movie details.

---

## Getting Started (ENGLISH)

Before using and creating your own version of this website, you will need to:

1. **Generate an API key** from the [OMDb API website](https://www.omdbapi.com/).  
   You can sign up for free and get your key after registering.
   
2. **Create a `key.js` file** in your project and insert your API key into it.

### Example of `key.js` file:
```javascript
// key.js
const API_KEY = "your_api_key"; // replace with your actual key
export default API_KEY;
```

Secure your API key:
Make sure that the key.js file is not exposed in a public repository. Use .gitignore to exclude it from version control.
Example of .gitignore file: 
# Exclude the key.js file
key.js

Перед началом работы (РУССКИЙ)

Перед использованием и созданием своего сайта, вам потребуется:

    Создать и подключить свой API-ключ на сайте OMDb API.
    После этого создайте файл key.js в вашем проекте и добавьте в него ваш API-ключ.

Пример файла key.js:
// key.js
const API_KEY = "ваш_ключ_API"; // замените на ваш ключ
export default API_KEY;

Важные заметки / Important Notes

    Ваш API-ключ должен быть защищён.
    Не добавляйте key.js в публичные репозитории! Используйте файл .gitignore для исключения этого файла из контроля версий.

    Your API key must be protected.
    Do not include key.js in public repositories! Use a .gitignore file to exclude it from version control.
```javascript
Example of .gitignore file:
# Exclude the key.js file
key.js
```

Notes / Заметки

    The API key is necessary for the app to fetch movie data from the OMDb database.
    API-ключ необходим для работы приложения, чтобы получать данные о фильмах из базы OMDb.

    Always keep your API key private and avoid exposing it in public repositories.
    Всегда держите свой API-ключ в секрете и избегайте его публикации в открытых репозиториях.

By following these steps, you can ensure the security of your API key and prevent any unauthorized access to the data.

License:

This project uses the: MIT License [MIT](https://github.com/istbega/MovieFinder/blob/main/LICENSE)

Contact:
To contact the author of the project, email: behinmaksym@gmail.com


