<h1 align="center">A simplified Jira clone built with React and Node</h1>

<div align="center">Auto formatted with Prettier, tested with Cypress 🎗</div>

<h3 align="center">
  <a href="https://jira.ivorreic.com/">Visit the live app</a> |
  <a href="https://github.com/oldboyxx/jira_clone/tree/master/client">View client</a> |
  <a href="https://github.com/oldboyxx/jira_clone/tree/master/api">View API</a>
</h3>

![Tech logos](https://i.ibb.co/DVFj8PL/tech-icons.jpg)

![App screenshot](https://i.ibb.co/W3qVvCn/jira-optimized.jpg)

## What is this and who is it for 🤷‍♀️

I do React consulting and this is a showcase product I've built in my spare time. It's a very good example of modern, real-world React codebase.

There are many showcase/example React projects out there but most of them are way too simple. I like to think that this codebase contains enough complexity to offer valuable insights to React developers of all skill levels while still being _relatively_ easy to understand.

## Features

- Proven, scalable, and easy to understand project structure
- Written in modern React, only functional components with hooks
- A variety of custom light-weight UI components such as datepicker, modal, various form elements etc
- Simple local React state management, without redux, mobx, or similar
- Custom webpack setup, without create-react-app or similar
- Client written in Babel powered JavaScript
- API written in TypeScript and using TypeORM

## Setting up development environment 🛠

- Install [postgreSQL](https://www.postgresql.org/) if you don't have it already and create a database named `jira_development`.
- `git clone https://github.com/oldboyxx/jira_clone.git`
- Create an empty `.env` file in `/api`, copy `/api/.env.example` contents into it, and fill in your database username and password.
- `npm run install-dependencies`
- `cd api && npm start`
- `cd client && npm start` in another terminal tab
- App should now be running on `http://localhost:8080/`

## Running cypress end-to-end tests 🚥

- Set up development environment
- Create a database named `jira_test` and start the api with `cd api && npm run start:test`
- `cd client && npm run test:cypress`

## What's missing?

There are features missing from this showcase product which should exist in a real product:

### Migrations 🗄

We're currently using TypeORM's `synchronize` feature which auto creates the database schema on every application launch. It's fine to do this in a showcase product or during early development while the product is not used by anyone, but before going live with a real product, we should [introduce migrations](https://github.com/typeorm/typeorm/blob/master/docs/migrations.md).

### Proper authentication system 🔐

We currently auto create an auth token and seed a project with issues and users for anyone who visits the API without valid credentials. In a real product we'd want to implement a proper [email and password authentication system](https://www.google.com/search?q=email+and+password+authentication+node+js&oq=email+and+password+authentication+node+js).

### Accessibility ♿

Not all components have properly defined [aria attributes](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA), visual focus indicators etc. Most early stage companies tend to ignore this aspect of their product but in many cases they shouldn't, especially once their userbase starts growing.

### Unit/Integration tests 🧪

Both Client and API are currently tested through [end-to-end Cypress tests](https://github.com/oldboyxx/jira_clone/tree/master/client/cypress/integration). That's good enough for a relatively simple application such as this, even if it was a real product. However, as the app grows in complexity, it might be wise to start writing additional unit/integration tests.

## Contributing

I will not be accepting PR's on this repository. Feel free to fork and maintain your own version.

## License

[MIT](https://opensource.org/licenses/MIT)

<hr>

<h3>
  <a href="https://jira.ivorreic.com/">Visit the live app</a> |
  <a href="https://github.com/oldboyxx/jira_clone/tree/master/client">View client</a> |
  <a href="https://github.com/oldboyxx/jira_clone/tree/master/api">View API</a>
</h3>
Contribution: 2020-04-01 20:00

Contribution: 2020-04-03 20:00

Contribution: 2020-04-06 20:00

Contribution: 2020-04-10 20:00

Contribution: 2020-04-11 20:00

Contribution: 2020-04-11 20:01

Contribution: 2020-04-12 20:00

Contribution: 2020-04-12 20:01

Contribution: 2020-04-13 20:00

Contribution: 2020-04-13 20:01

Contribution: 2020-04-13 20:02

Contribution: 2020-04-14 20:00

Contribution: 2020-04-14 20:01

Contribution: 2020-04-14 20:02

Contribution: 2020-04-16 20:00

Contribution: 2020-04-18 20:00

Contribution: 2020-04-18 20:01

Contribution: 2020-04-18 20:02

Contribution: 2020-04-19 20:00

Contribution: 2020-04-21 20:00

Contribution: 2020-04-21 20:01

Contribution: 2020-04-21 20:02

Contribution: 2020-04-22 20:00

Contribution: 2020-04-22 20:01

Contribution: 2020-04-23 20:00

Contribution: 2020-04-27 20:00

Contribution: 2020-04-27 20:01

Contribution: 2020-04-28 20:00

Contribution: 2020-04-28 20:01

Contribution: 2020-04-28 20:02

Contribution: 2020-04-29 20:00

Contribution: 2020-05-01 20:00

Contribution: 2020-05-02 20:00

Contribution: 2020-05-02 20:01

Contribution: 2020-05-02 20:02

Contribution: 2020-05-03 20:00

Contribution: 2020-05-03 20:01

Contribution: 2020-05-03 20:02

Contribution: 2020-05-04 20:00

Contribution: 2020-05-04 20:01

Contribution: 2020-05-04 20:02

Contribution: 2020-05-09 20:00

Contribution: 2020-05-10 20:00

Contribution: 2020-05-10 20:01

Contribution: 2020-05-15 20:00

Contribution: 2020-05-15 20:01

Contribution: 2020-05-16 20:00

Contribution: 2020-05-16 20:01

Contribution: 2020-05-16 20:02

Contribution: 2020-05-17 20:00

Contribution: 2020-05-17 20:01

Contribution: 2020-05-20 20:00

Contribution: 2020-05-20 20:01

Contribution: 2020-05-22 20:00

Contribution: 2020-05-22 20:01

Contribution: 2020-05-22 20:02

Contribution: 2020-05-23 20:00

Contribution: 2020-06-01 20:00

Contribution: 2020-06-01 20:01

Contribution: 2020-06-01 20:02

Contribution: 2020-06-02 20:00

Contribution: 2020-06-02 20:01

Contribution: 2020-06-02 20:02

Contribution: 2020-06-03 20:00

Contribution: 2020-06-03 20:01

Contribution: 2020-06-04 20:00

Contribution: 2020-06-04 20:01

Contribution: 2020-06-06 20:00

Contribution: 2020-06-08 20:00

Contribution: 2020-06-08 20:01

Contribution: 2020-06-09 20:00

Contribution: 2020-06-09 20:01

Contribution: 2020-06-11 20:00

Contribution: 2020-06-11 20:01

Contribution: 2020-06-15 20:00

Contribution: 2020-06-15 20:01

Contribution: 2020-06-16 20:00

Contribution: 2020-06-16 20:01

Contribution: 2020-06-16 20:02

Contribution: 2020-06-17 20:00

Contribution: 2020-06-18 20:00

Contribution: 2020-06-18 20:01

Contribution: 2020-06-19 20:00

Contribution: 2020-06-19 20:01

Contribution: 2020-06-20 20:00

Contribution: 2020-06-21 20:00

Contribution: 2020-06-21 20:01

Contribution: 2020-06-23 20:00

Contribution: 2020-06-25 20:00

Contribution: 2020-06-25 20:01

Contribution: 2020-06-27 20:00

Contribution: 2020-06-28 20:00

Contribution: 2020-06-28 20:01

Contribution: 2020-06-28 20:02

Contribution: 2020-06-29 20:00

Contribution: 2020-06-29 20:01

Contribution: 2020-07-02 20:00

Contribution: 2020-07-03 20:00

Contribution: 2020-07-04 20:00

Contribution: 2020-07-04 20:01

Contribution: 2020-07-04 20:02

Contribution: 2020-07-05 20:00

Contribution: 2020-07-05 20:01

Contribution: 2020-07-05 20:02

Contribution: 2020-07-06 20:00

Contribution: 2020-07-06 20:01

Contribution: 2020-07-06 20:02

Contribution: 2020-07-09 20:00

Contribution: 2020-07-09 20:01

Contribution: 2020-07-11 20:00

Contribution: 2020-07-16 20:00

Contribution: 2020-07-16 20:01

Contribution: 2020-07-16 20:02

Contribution: 2020-07-18 20:00

Contribution: 2020-07-18 20:01

Contribution: 2020-07-18 20:02

Contribution: 2020-07-21 20:00

Contribution: 2020-07-21 20:01

Contribution: 2020-07-21 20:02

Contribution: 2020-07-25 20:00

Contribution: 2020-07-25 20:01

Contribution: 2020-07-25 20:02

Contribution: 2020-07-26 20:00

Contribution: 2020-07-26 20:01

Contribution: 2020-07-27 20:00

Contribution: 2020-07-27 20:01

Contribution: 2020-07-27 20:02

Contribution: 2020-07-29 20:00

Contribution: 2020-07-29 20:01

Contribution: 2020-07-29 20:02

Contribution: 2020-07-30 20:00

Contribution: 2020-07-30 20:01

Contribution: 2020-07-30 20:02

Contribution: 2020-07-31 20:00

Contribution: 2020-07-31 20:01

Contribution: 2020-07-31 20:02

Contribution: 2020-08-03 20:00

Contribution: 2020-08-03 20:01

Contribution: 2020-08-03 20:02

Contribution: 2020-08-04 20:00

Contribution: 2020-08-06 20:00

Contribution: 2020-08-06 20:01

Contribution: 2020-08-06 20:02

Contribution: 2020-08-07 20:00

Contribution: 2020-08-08 20:00

Contribution: 2020-08-09 20:00

Contribution: 2020-08-10 20:00

Contribution: 2020-08-10 20:01

Contribution: 2020-08-12 20:00

Contribution: 2020-08-12 20:01

Contribution: 2020-08-12 20:02

Contribution: 2020-08-13 20:00

Contribution: 2020-08-13 20:01

Contribution: 2020-08-13 20:02

Contribution: 2020-08-14 20:00

Contribution: 2020-08-15 20:00

Contribution: 2020-08-15 20:01

Contribution: 2020-08-16 20:00

Contribution: 2020-08-16 20:01

Contribution: 2020-08-17 20:00

Contribution: 2020-08-17 20:01

Contribution: 2020-08-18 20:00

Contribution: 2020-08-19 20:00

Contribution: 2020-08-23 20:00

Contribution: 2020-08-23 20:01

Contribution: 2020-08-24 20:00

Contribution: 2020-08-27 20:00

Contribution: 2020-08-28 20:00

Contribution: 2020-08-28 20:01

Contribution: 2020-08-28 20:02

Contribution: 2020-09-02 20:00

Contribution: 2020-09-02 20:01

Contribution: 2020-09-05 20:00

Contribution: 2020-09-05 20:01

Contribution: 2020-09-05 20:02

Contribution: 2020-09-08 20:00

Contribution: 2020-09-08 20:01

Contribution: 2020-09-08 20:02

Contribution: 2020-09-10 20:00

Contribution: 2020-09-10 20:01

Contribution: 2020-09-12 20:00

Contribution: 2020-09-12 20:01

Contribution: 2020-09-12 20:02

Contribution: 2020-09-15 20:00

Contribution: 2020-09-17 20:00

Contribution: 2020-09-17 20:01

Contribution: 2020-09-17 20:02

Contribution: 2020-09-22 20:00

Contribution: 2020-09-22 20:01

Contribution: 2020-09-22 20:02

Contribution: 2020-09-23 20:00

Contribution: 2020-09-24 20:00

Contribution: 2020-09-24 20:01

Contribution: 2020-09-25 20:00

Contribution: 2020-09-25 20:01

Contribution: 2020-09-28 20:00

Contribution: 2020-09-28 20:01

Contribution: 2020-10-03 20:00

Contribution: 2020-10-08 20:00

Contribution: 2020-10-11 20:00

Contribution: 2020-10-11 20:01

Contribution: 2020-10-12 20:00

Contribution: 2020-10-13 20:00

Contribution: 2020-10-13 20:01

Contribution: 2020-10-15 20:00

Contribution: 2020-10-15 20:01

Contribution: 2020-10-15 20:02

Contribution: 2020-10-18 20:00

Contribution: 2020-10-18 20:01

Contribution: 2020-10-18 20:02

Contribution: 2020-10-19 20:00

Contribution: 2020-10-19 20:01

Contribution: 2020-10-19 20:02

Contribution: 2020-10-21 20:00

Contribution: 2020-10-23 20:00

Contribution: 2020-10-23 20:01

Contribution: 2020-10-25 20:00

Contribution: 2020-10-25 20:01

Contribution: 2020-10-25 20:02

Contribution: 2020-10-26 20:00

Contribution: 2020-10-27 20:00

Contribution: 2020-10-28 20:00

Contribution: 2020-10-30 20:00

Contribution: 2020-10-31 20:00

Contribution: 2020-10-31 20:01

Contribution: 2020-10-31 20:02

Contribution: 2020-11-02 20:00

Contribution: 2020-11-02 20:01

Contribution: 2020-11-04 20:00

Contribution: 2020-11-04 20:01

Contribution: 2020-11-05 20:00

Contribution: 2020-11-05 20:01

Contribution: 2020-11-07 20:00

Contribution: 2020-11-07 20:01

Contribution: 2020-11-07 20:02

Contribution: 2020-11-08 20:00

Contribution: 2020-11-09 20:00

Contribution: 2020-11-09 20:01

Contribution: 2020-11-09 20:02

Contribution: 2020-11-11 20:00

Contribution: 2020-11-11 20:01

Contribution: 2020-11-11 20:02

Contribution: 2020-11-12 20:00

Contribution: 2020-11-17 20:00

Contribution: 2020-11-18 20:00

Contribution: 2020-11-20 20:00

Contribution: 2020-11-20 20:01

Contribution: 2020-11-20 20:02

Contribution: 2020-11-24 20:00

Contribution: 2020-11-27 20:00

Contribution: 2020-11-27 20:01

Contribution: 2020-11-29 20:00

Contribution: 2020-11-30 20:00

Contribution: 2020-11-30 20:01

Contribution: 2020-12-03 20:00

Contribution: 2020-12-05 20:00

Contribution: 2020-12-05 20:01

Contribution: 2020-12-05 20:02

Contribution: 2020-12-08 20:00

Contribution: 2020-12-10 20:00

Contribution: 2020-12-10 20:01

Contribution: 2020-12-10 20:02

Contribution: 2020-12-14 20:00

Contribution: 2020-12-17 20:00

Contribution: 2020-12-17 20:01

Contribution: 2020-12-20 20:00

Contribution: 2020-12-20 20:01

Contribution: 2020-12-20 20:02

Contribution: 2020-12-21 20:00

Contribution: 2020-12-26 20:00

Contribution: 2020-12-27 20:00

Contribution: 2021-01-01 20:00

Contribution: 2021-01-01 20:01

Contribution: 2021-01-01 20:02

Contribution: 2021-01-02 20:00

Contribution: 2021-01-03 20:00

Contribution: 2021-01-03 20:01

Contribution: 2021-01-05 20:00

Contribution: 2021-01-08 20:00

Contribution: 2021-01-08 20:01

Contribution: 2021-01-08 20:02

Contribution: 2021-01-09 20:00

Contribution: 2021-01-10 20:00

Contribution: 2021-01-10 20:01

Contribution: 2021-01-10 20:02

Contribution: 2021-01-11 20:00

Contribution: 2021-01-11 20:01

Contribution: 2021-01-13 20:00

Contribution: 2021-01-13 20:01

Contribution: 2021-01-14 20:00

Contribution: 2021-01-14 20:01

Contribution: 2021-01-19 20:00

Contribution: 2021-01-19 20:01

Contribution: 2021-01-19 20:02

Contribution: 2021-01-21 20:00

Contribution: 2021-01-21 20:01

Contribution: 2021-01-23 20:00

Contribution: 2021-01-23 20:01

Contribution: 2021-01-24 20:00

Contribution: 2021-01-24 20:01

Contribution: 2021-01-24 20:02

Contribution: 2021-01-25 20:00

Contribution: 2021-01-26 20:00

Contribution: 2021-01-26 20:01

Contribution: 2021-01-26 20:02

Contribution: 2021-01-28 20:00

Contribution: 2021-01-28 20:01

Contribution: 2021-01-28 20:02

Contribution: 2021-01-31 20:00

Contribution: 2021-01-31 20:01

Contribution: 2021-01-31 20:02

Contribution: 2021-02-02 20:00

Contribution: 2021-02-02 20:01

Contribution: 2021-02-02 20:02

Contribution: 2021-02-03 20:00

Contribution: 2021-02-03 20:01

Contribution: 2021-02-03 20:02

Contribution: 2021-02-04 20:00

Contribution: 2021-02-04 20:01

Contribution: 2021-02-04 20:02

Contribution: 2021-02-09 20:00

Contribution: 2021-02-09 20:01

Contribution: 2021-02-13 20:00

Contribution: 2021-02-13 20:01

Contribution: 2021-02-14 20:00

Contribution: 2021-02-15 20:00

Contribution: 2021-02-15 20:01

Contribution: 2021-02-15 20:02

Contribution: 2021-02-17 20:00

Contribution: 2021-02-17 20:01

Contribution: 2021-02-17 20:02

Contribution: 2021-02-18 20:00

Contribution: 2021-02-18 20:01

Contribution: 2021-02-18 20:02

Contribution: 2021-02-19 20:00

Contribution: 2021-02-19 20:01

Contribution: 2021-02-19 20:02

Contribution: 2021-02-23 20:00

Contribution: 2021-02-23 20:01

Contribution: 2021-02-23 20:02

Contribution: 2021-02-27 20:00

Contribution: 2021-02-27 20:01

Contribution: 2021-02-27 20:02

Contribution: 2021-02-28 20:00

Contribution: 2021-02-28 20:01

Contribution: 2021-02-28 20:02

Contribution: 2021-03-01 20:00

Contribution: 2021-03-02 20:00

Contribution: 2021-03-03 20:00

Contribution: 2021-03-03 20:01

Contribution: 2021-03-03 20:02

Contribution: 2021-03-05 20:00

Contribution: 2021-03-05 20:01

Contribution: 2021-03-07 20:00

Contribution: 2021-03-07 20:01

Contribution: 2021-03-10 20:00

Contribution: 2021-03-10 20:01

Contribution: 2021-03-10 20:02

Contribution: 2021-03-11 20:00

Contribution: 2021-03-11 20:01

Contribution: 2021-03-13 20:00

Contribution: 2021-03-14 20:00

Contribution: 2021-03-14 20:01

Contribution: 2021-03-14 20:02

Contribution: 2021-03-15 20:00

Contribution: 2021-03-15 20:01

Contribution: 2021-03-16 20:00

Contribution: 2021-03-24 20:00

Contribution: 2020-04-15 20:00

Contribution: 2020-04-15 20:01

Contribution: 2020-04-15 20:02

Contribution: 2020-04-21 20:00

Contribution: 2020-04-26 20:00

Contribution: 2020-04-26 20:01

Contribution: 2020-05-05 20:00

Contribution: 2020-05-05 20:01

Contribution: 2020-05-05 20:02

Contribution: 2020-05-07 20:00

Contribution: 2020-05-12 20:00

Contribution: 2020-05-12 20:01

Contribution: 2020-05-12 20:02

Contribution: 2020-05-15 20:00

Contribution: 2020-05-15 20:01

Contribution: 2020-05-15 20:02

Contribution: 2020-05-16 20:00

Contribution: 2020-05-17 20:00

Contribution: 2020-05-17 20:01

Contribution: 2020-05-17 20:02

Contribution: 2020-05-27 20:00

Contribution: 2020-06-07 20:00

Contribution: 2020-06-07 20:01

Contribution: 2020-06-07 20:02

Contribution: 2020-06-09 20:00

Contribution: 2020-06-09 20:01

Contribution: 2020-06-09 20:02

Contribution: 2020-06-11 20:00

Contribution: 2020-06-11 20:01

Contribution: 2020-06-12 20:00

Contribution: 2020-06-12 20:01

Contribution: 2020-06-12 20:02

Contribution: 2020-06-17 20:00

Contribution: 2020-06-17 20:01

Contribution: 2020-06-17 20:02

Contribution: 2020-06-19 20:00

Contribution: 2020-06-26 20:00

Contribution: 2020-06-26 20:01

Contribution: 2020-06-28 20:00

Contribution: 2020-06-28 20:01

Contribution: 2020-06-28 20:02

Contribution: 2020-06-29 20:00

Contribution: 2020-06-29 20:01

Contribution: 2020-06-29 20:02

Contribution: 2020-07-01 20:00

Contribution: 2020-07-01 20:01

Contribution: 2020-07-01 20:02

Contribution: 2020-07-08 20:00

Contribution: 2020-07-11 20:00

Contribution: 2020-07-11 20:01

Contribution: 2020-07-12 20:00

Contribution: 2020-07-12 20:01

Contribution: 2020-07-12 20:02

Contribution: 2020-07-14 20:00

Contribution: 2020-07-15 20:00

Contribution: 2020-07-15 20:01

Contribution: 2020-07-18 20:00

Contribution: 2020-07-18 20:01

Contribution: 2020-07-18 20:02

Contribution: 2020-07-19 20:00

Contribution: 2020-07-19 20:01

Contribution: 2020-07-21 20:00

Contribution: 2020-07-24 20:00

Contribution: 2020-07-24 20:01

Contribution: 2020-07-26 20:00

Contribution: 2020-07-26 20:01

Contribution: 2020-07-29 20:00

Contribution: 2020-07-29 20:01

Contribution: 2020-07-29 20:02

Contribution: 2020-08-05 20:00

Contribution: 2020-08-06 20:00

Contribution: 2020-08-20 20:00

Contribution: 2020-08-20 20:01

Contribution: 2020-08-20 20:02

Contribution: 2020-08-31 20:00

Contribution: 2020-09-14 20:00

Contribution: 2020-09-15 20:00

Contribution: 2020-09-15 20:01

Contribution: 2020-09-18 20:00

Contribution: 2020-09-19 20:00

Contribution: 2020-09-20 20:00

Contribution: 2020-09-20 20:01

Contribution: 2020-09-25 20:00

Contribution: 2020-09-25 20:01

Contribution: 2020-09-27 20:00

Contribution: 2020-09-27 20:01

Contribution: 2020-09-27 20:02

Contribution: 2020-10-05 20:00

Contribution: 2020-10-05 20:01

Contribution: 2020-10-08 20:00

Contribution: 2020-10-21 20:00

Contribution: 2020-10-21 20:01

Contribution: 2020-10-28 20:00

Contribution: 2020-10-28 20:01

Contribution: 2020-10-28 20:02

Contribution: 2020-10-30 20:00

Contribution: 2020-10-30 20:01

Contribution: 2020-10-30 20:02

Contribution: 2020-11-01 20:00

Contribution: 2020-11-01 20:01

Contribution: 2020-11-01 20:02

Contribution: 2020-11-06 20:00

Contribution: 2020-11-06 20:01

Contribution: 2020-11-09 20:00

Contribution: 2020-11-16 20:00

Contribution: 2020-11-16 20:01

Contribution: 2020-11-16 20:02

Contribution: 2020-11-17 20:00

Contribution: 2020-11-19 20:00

Contribution: 2020-11-19 20:01

Contribution: 2020-11-22 20:00

Contribution: 2020-11-22 20:01

Contribution: 2020-11-26 20:00

Contribution: 2020-11-26 20:01

Contribution: 2020-12-01 20:00

Contribution: 2020-12-01 20:01

Contribution: 2020-12-01 20:02

Contribution: 2020-12-04 20:00

Contribution: 2020-12-04 20:01

Contribution: 2020-12-04 20:02

Contribution: 2020-12-10 20:00

