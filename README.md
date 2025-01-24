# Descriptions 
is a web application built using HTML, CSS, and JavaScript that allows users to search for movies, view their descriptions, ratings, and additional details.

## Technologies used:
*  `HTML` for structuring the webpage.
*  `CSS` for styling and responsive design.
*  `JavaScript` for dynamic functionality and data handling.

## Purpose:
To simplify movie searches and provide users with quick access to essential information, including ratings and key movie details.

## Getting Started (ENGLISH)

Before using and creating your own version of this website, you will need to:

1. **Generate an API key** from the [OMDb API website](https://www.omdbapi.com/).  
   You can sign up for free and get your key after registering.
   
2. **Create a `key.js` file** in your project and insert your API key into it.  

### Example of `key.js` file:
```javascript
// key.js
const API_KEY = "your_api_key";
export default API_KEY;

Secure your API key:
Make sure that the key.js file is not exposed in a public repository. Use .gitignore to exclude it from version control.
# Exclude the key.js file
key.js

## Перед началом работы (РУССКИЙ)
Перед использованием и созданием своего такого сайта, вам понадобится:
1. Создать и подключить свой API-ключ на сайте [OMDb API](https://www.omdbapi.com/).
2. После этого создайте файл `key.js` в вашем проекте и добавьте в него ваш API-ключ.

### Пример файла key.js:
```javascript
// key.js
const API_KEY = "ваш_ключ_API";
export default API_KEY;

## Важные заметки / Important Notes

- **Ваш API-ключ должен быть защищён.**  
  Не добавляйте `key.js` в публичные репозитории! Используйте файл `.gitignore` для исключения этого файла из контроля версий.

- **Your API key must be protected.**  
  Do not include `key.js` in public repositories! Use a `.gitignore` file to exclude it from version control.
  
### Пример файла `.gitignore`:
---

Example of .gitignore file:

# Exclude the key.js file
key.js
This format is easy to read and clearly explains the importance of keeping the API key secure, both in Russian and English.

## Notes / Заметки

- **The API key is necessary** for the app to fetch movie data from the OMDb database.  
  **API-ключ необходим** для работы приложения, чтобы получать данные о фильмах из базы OMDb.

- **Always keep your API key private** and avoid exposing it in public repositories.  
  **Всегда держите свой API-ключ в секрете** и избегайте его публикации в открытых репозиториях.

---

By following these steps, you can ensure the security of your API key and prevent any unauthorized access to the data.

---

### Пояснения:
1. **Двуязычность**: Инструкции даны на русском и английском языках для удобства пользователей.
2. **Пример кода**: Включён пример файла `key.js` с указанием, как импортировать API-ключ.
3. **Предупреждение**: Добавлены советы по защите ключа с использованием `.gitignore`.

Готово для использования в вашем проекте! Если нужно добавить что-то ещё, дайте знать.



## License:
This project uses the: [MIT](https://github.com/istbega/MovieFinder/blob/main/LICENSE)


To contact the author of the project, write to email behinmaksym@gmail.com
