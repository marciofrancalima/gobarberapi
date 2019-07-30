# GoBarber API (Node.js)

API developed in Node.js for a barber shop.

To access the web version (ReactJS) go to:
```
https://github.com/marciofrancalima/gobarberweb
```

## Technologies

Technologies used to develop this application:

-  [Node.js](https://nodejs.org/en/)
-  [Docker](https://www.docker.com/)
-  [Postgres](https://www.postgresql.org/)
-  [Mongo](https://www.mongodb.com/)
-  [Redis](https://redis.io/)
-  [Sequelize](http://docs.sequelizejs.com/)
-  [Mongoose](https://mongoosejs.com/)
-  [Express](https://github.com/expressjs/express)
-  [Multer](https://github.com/expressjs/multer)
- [JSON Web Token (JWT)](https://jwt.io/)
- [Yup](https://github.com/jquense/yup)

ESLint, Prettier and EditorConfig were also used to maintain the code pattern.

## Functionalities

- Registration of users (customers or service providers) with avatar;
- Service Scheduling;
- Schedule listing (provider)
- JWT Authentication
- Data Validation
- Scheduling notification, email service with NodeMailer and more.

## How To Use

Follow the instructions below to run an application:

```bash
# Clone this repository
$ git clone https://github.com/marciofrancalima/gobarberapi.git (or use ssh)

# Go into the repository
$ cd gobarberapi

# Install dependencies
$ yarn install

# Run the app
$ yarn dev
```

Before running the application make sure you have the migrations created in the database:

```js
yarn sequelize db:migrate
```

---

Made with ♥ by Márcio França Lima. [Contact me](https://www.linkedin.com/in/m%C3%A1rcio-fran%C3%A7a-lima-916454187/)
