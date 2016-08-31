# Ruby on Rails sample application

This is the sample application for Rails 5.0.0.

Functions of the application:
- Static pages
- Sign up/Log in
- Authorization
- Microposts
- Following User

Technologies:

- Use cloud9 to develop the application, deployed to heroku
- TDD/MVC/REST
- Active Record/Action Mailer/Migration/ApplicationController
- Scaffold/ERb/validations/before filter/strong parameters/asset pipeline
- integration test/fixtures
- HTML5/CSS/Bootstrap/JavaScript
- Security/SSL
- Puma
- flash/cookies/session
- database index
- Pagination
- Use Gravatars to display images
- Use Faker to seed the database
- minitest-reporters/automated tests with Guard
- Send email in production using SendGrid
- Store images to Amazon.com's Simple Storage Service (S3)

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

On Cloud9, this command should be

```
$ rails server -b $IP -p $PORT
```

instead.
