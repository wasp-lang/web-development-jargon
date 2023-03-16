# Web Development Jargon

The world of web development has been evolving at an exponential rate for the last two decades. New terms and acronyms are being introduced daily. By providing a glossary, we hope to make learning web development easier.

Examples are presented in JavaScript (ES2015). [Why JavaScript?](https://github.com/wasp-lang/web-development-jargon/wiki/Why-JavaScript%3F)

__Table of Contents__
<!-- RM(noparent,notop) -->
* [API](#api)
* [GraphQL](#graphql)
* [REST](#rest)


<!-- /RM -->

## API

API (Application Programming Interface) is a way for two or more computer programs to communicate with each other. In the context of web app development, API often refers to the communication protocol between a client (front-end) and a server (back-end). Examples of such protocols are [REST](#rest) or [GraphQL](#graphql).

Another common usage is when referring to consuming a third-party service from your web page, e.g., invoking a GitHub API to fetch all repositories of a specific user:

```js
const url = 'https://api.github.com/users/{username}/repos';

fetch(url)
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));
```

__Using it in a sentence__
* *Hey, I just added a new route for billing to our back-end API! Just Make sure the client is authenticated when performing a request.*
* *Have you already tried out the new GPT-4 API? Can't wait to build an app that will use it to generate a cover letter from your CV.*


__Sources__
* [Wikipedia entry on API](https://en.wikipedia.org/wiki/API)

## GraphQL

## REST
