# [URL Shortener Microservice](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/url-shortener-microservice)

## Language and Framework
![Javascript](https://img.shields.io/badge/Language-Javascript-brightgreen) ![Expres](https://img.shields.io/badge/Framework-Express-brightgreen)

___
## User Stories
- [x] You can POST a URL to /api/shorturl and get a JSON response with original_url and short_url properties. Here's an example: { original_url : 'https://freeCodeCamp.org', short_url : 1}

- [x] When you visit /api/shorturl/<short_url>, you will be redirected to the original URL.

- [x] If you pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain { error: 'invalid url' }

___

This is a Node.js (with Express.js) little application which is part of the FCC Back End Certification. It shortens any given url which is in a valid format. Given the short url it will redirect you to the main site.

Example 
```
https://www.google.com -> {"original_url":"https://www.google.com","short_url":18}

going to /app/shorturl/18 -> redirects to [https://www.google.com]
```
