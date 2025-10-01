# Social Login

## Project Details
- **Java Version:** 21
- **Spring Boot Version:** 3.5.6
- **Port:** 8181

This project enables user authentication to access a webpage using **Google**, **Facebook**, **GitHub**, or **Okta** credentials.

---

## Setup Steps

1. **Create Projects on Developer Platforms:**
    - Google: [console.developers.google.com](https://console.developers.google.com)
    - Facebook: [developers.facebook.com](https://developers.facebook.com)
    - Okta: [developer.okta.com](https://developer.okta.com)

2. **Obtain Credentials:**
    - Generate `client_id` and `client_secret` for each provider.
    - Store them in the `application.properties` file.

3. **Frontend Integration:**
    - The frontend is built using the **Thymeleaf** template engine in Spring Boot.

4. **Logout Functionality:**
    - Users can log out by clearing **session** and **cache** data.

---
