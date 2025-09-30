# Social Login

## Versions
- Java: 21
- Spring Boot: 3.5.6

Port: 8181

This project authenticates the user to access a webpage with googe/facebook/github/okta credentials.

## Steps:

- A project needs to be created for:
google:http://console.developers.google.com
facebook: http://developers.facebook.com
okta: https://developer.okta.com

- The generated client_id and xlient_secret is stored in application.properties and login is made possible.

Likewise, successful logout can also be performed by clearing session and cache data.
