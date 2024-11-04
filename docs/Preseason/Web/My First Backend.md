---
sidebar_label: 'My First Backend'
sidebar_position: 4
---

# My First Backend

Welcome to backend application with light web framework.

## 🚀 Key Features

- **Framework Requirements**: use Express (JavaScript) / Sinatra (Ruby) / Flask (Python).
- **No database**: necessary information should be hard coded in file.

## 📝 Task Requirements (Gandalf test requirements)

1. **Implement a GET route on `/`**: that returns a random song title by Frank Sinatra from a pool of at least 20 songs.
2. **Implement a GET route on `/birth_date`**: that returns Frank Sinatra's birth date (format "Month DD, YYYY").
3. **Implement a GET route on `/birth_city`**: that returns Frank Sinatra's birth city.
4. **Implement a GET route on `/wives`**: that returns all the names of Frank Sinatra's wives in the format `wife1, wife2, wife3, wife4`.
5. **Implement a GET route on `/picture`**: that redirects to Frank Sinatra's picture.
6. **Implement a GET route on `/public`**: that returns "Everybody can see this page".
7. **Implement a GET route on `/protected`**: that requires HTTP Basic authentication and returns "Welcome, authenticated client" if authorized, otherwise returns a 401 Unauthorized response.

## ⚠️ Error Handling

- Proper handling of unauthorized access for protected routes, returning 401 status codes.
- Handling of invalid routes or requests to provide appropriate error messages (e.g., 404 Not Found).


## 🛠️ Useful resources for acomplishing this task
- [Express Documentation](http://expressjs.com/)
- [HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [HTTP Basic Authentication](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication#basic_authentication)