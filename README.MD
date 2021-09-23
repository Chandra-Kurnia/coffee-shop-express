<br />
<p align="center">
<div align="center">
  <img height="150" src="/src/asset/img/coffe_copy_huh6kh.png"/>
</div>
  <h3 align="center">Backend Coffee Shop</h3>
  <p align="center">
    <a href="https://github.com/aryairama/coffee-shop-express"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://bit.ly/_coffee_shop">View Demo</a>
    ·
    <a href="https://github.com/aryairama/coffee-shop-express/issues">Report Bug</a>
    ·
    <a href="https://github.com/aryairama/coffee-shop-express/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Setup .env example](#setup-env-example)
- [Rest Api](#rest-api)
- [Contributing](#contributing)
- [Related Project](#related-project)
- [Our Team](#our-team)
- [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

Coffee Shop is a Foods & Beverages ordering application. This apps give you (customers) some features to order your favorite foods or beverages. The customers also have some opportunity to use some promo code before directly checkout to the payment page. In payment page you can pick your payments method so it's flexible what kind of money do you have. Also the customers will be able to edit their profile such as photo, username, address, and phone number if they have to change their identity

### Built With

- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [JSON Web Tokens](https://jwt.io/)
- [Nodemailer]('https://nodemailer.com/about/')
- and other

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* [nodejs](https://nodejs.org/en/download/)

### Requirements
* [Node.js](https://nodejs.org/en/)
* [Postman](https://www.getpostman.com/) for testing
* [Database](https://drive.google.com/drive/folders/1Q5ubAjPce-lO6aj9XUIeOxdjzr0hfLEI?usp=sharing)

### Installation

- Clone This Back End Repo
```
git clone https://github.com/aryairama/coffee-shop-express.git
```
- Go To Folder Repo
```
cd coffee-shop-express
```
- Install Module
```
npm install
```
- Make a new database and import [coffee-shop.sql](https://drive.google.com/drive/folders/1Q5ubAjPce-lO6aj9XUIeOxdjzr0hfLEI?usp=sharing)
- <a href="#setup-env-example">Setup .env</a>
- Starting application
```
npm run serve
```

### Setup .env example

Create .env file in your root project folder.

```env
# Database
DB_HOST = [DB_HOST]
DB_USER = = [DB_USER]
DB_NAME = [DB_NAME]
DB_PASSWORD = [DB_PASSWORD]
DB_PORT = [DB_PORT]
# Aplication
PORT = [PORT_APLICATION]
# Secret key for jwt token
ACCESS_TOKEN_SECRET = [SECRET_KEY_JWT]
REFRESH_TOKEN_SECRET = [SECRET_KEY_JWT]
VERIF_EMAIL_TOKEN_SECRET = [SECRET_KEY_JWT]
FORGOT_PASSWORD_TOKEN_SECRET = [SECRET_KEY_JWT]
# Redis
HOST_REDIS = [REDIS_HOST]
PORT_REDIS = [REDIS_PORT]
AUTH_REDIS = [REDIS_AUTH]
PATH_REDIS = [REDIS_UNIX_SOCKET]
PREFIX_REDIS = [PREFIX-REDIS]
# IP/SOCKET
# Sendmailer SMTP
NODEMAILER_HOST = [SMTP_HOST]
NODEMAILER_PORT = [SMTP_PORT]
NODEMAILER_SECURE = [OPTION_SECURE_SMTP]
NODEMAILER_AUTH_USER = [USER_SMTP]
NODEMAILER_AUTH_PASS = [PASSWORD_SMTP]
# FrontEnd
URL_FRONTEND = [URL_FRONT_END]
# Origin Cookie
CORS_ORIGIN = ['http://localhost:3000','http://localhost:4000']
CREDENTIALS = [TRUE/FALSE]
```

## Rest Api

You can view my Postman collection [here](https://www.postman.com/crimson-meadow-842892/workspace/coffee-shop-team)
</br>
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/10655215-168761c3-7ebe-46a7-9775-6b983942f29e?action=collection%2Ffork&collection-url=entityId%3D10655215-168761c3-7ebe-46a7-9775-6b983942f29e%26entityType%3Dcollection%26workspaceId%3D0b518684-09b1-448c-8aa8-4e1800bbb6df)

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## Related Project
:rocket: [`Backend Coffee-Shop`](https://github.com/aryairama/coffee-shop-express)

:rocket: [`Frontend Coffee-Shop`](https://github.com/aryairama/coffe-shop-next)

:rocket: [`Demo Coffee-Shop`](https://bit.ly/_coffee_shop)


## Our Team

<center>
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/aryairama">
          <img width="100" src="https://avatars.githubusercontent.com/u/73978824?v=4" alt="Arya Irama Wahono"><br/>
          <sub><b>Arya Irama Wahono</b></sub> <br/>
          <sub>Full Stack Web Developer</sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/Chandra-Kurnia">
          <img width="100" src="https://avatars.githubusercontent.com/u/75248269?v=4" alt="Chandra Kurniawan"><br/>
          <sub><b>Chandra Kurniawan</b></sub> <br/>
          <sub>Back End Developer</sub>
        </a>
      </td>
    </tr>
  </table>
</center>

<!-- CONTACT -->
## Contact

My Email : aryairama987@gmail.com

Project Link: [https://github.com/aryairama/coffee-shop-express](https://github.com/aryairama/coffee-shop-express)
