# Heroku-totp-generator

Deploy nginx docker container to heroku

## Deploy

Click the following button to deploy the repository to heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Manual deployment

To deploy the repository manually, you have to install:

* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Docker](https://docs.docker.com/install/)
* [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

```bash
git clone https://github.com/kiookp/Heroku-totp-generator.git
```

```bash
cd Heroku-totp-generator
```

```bash
heroku login
```

```bash
heroku container:login
```

Change `APP_NAME` with the name of your heroku app.

```bash
heroku container:push web -a APP_NAME
```

```bash
heroku container:release web -a APP_NAME
```

