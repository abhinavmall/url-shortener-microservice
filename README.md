[![CircleCI](https://circleci.com/gh/abhinavmall/url-shortener-microservice.svg?style=svg)](https://circleci.com/gh/abhinavmall/url-shortener-microservice)

# FreeCodeCamp API Basejump: URL Shortener Microservice
## User stories:
1. I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
2. If I pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain an error instead.
3. When I visit that shortened URL, it will redirect me to my original link.

## Example creation usage:

```js
https://url-shortener-62805.herokuapp.com/add/https://techcrunch.com/
```

## Example creation output:

```js
{"original_url":"https://techcrunch.com/","short_url":"https://url-shortener-62805.herokuapp.com/44f6536"}
```

## Usage:

```
https://url-shortener-62805.herokuapp.com/44f6536
```

### Will redirect to:

```
https://techcrunch.com/
