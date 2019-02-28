# Rocketseat Bootcamp

[Rocketseat Bootcamp](https://github.com/Rocketseat/bootcamps) is focused on NodeJS, React and React Native. It is based on hands-on development of several apps with different approaches, from MVC with templating views (nunjucks), to REST APIs with React and React Native front-end consuming those APIs.

# MarketPlace App

This app consists of a Market Place REST API, where users can:

- signUp to the platform
- create, update and delete Ads of things to be sold (with price and description)
- get a list (.json) of all published Ads
- Send a Purchase intention to other users for their items,
- Receive emails for Purchase intentions from other users,
- Approve a Purchase intention to confirm the sell

### Technical features:

- Each session and action is validated using JsonWebToken
- The app makes use of Redis to send the Purchase intention emails
- The [Sentry](https://sentry.io) service is configured for nicely managing errors.

## Stack

- NodeJS
- Express
- MongoDB
- Docker
- Redis
- Nodemailer
- JsonWebToken
- Sentry

## How to use it

TODO
