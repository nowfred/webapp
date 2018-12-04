# helloGov

## Config
- ask wcrest for secrets.js file, and put into conf folder
- add a file named env.js in conf folder, with contents of `module.exports = 'dev';`

## Install dependencies
- `brew install node`
- `npm install`
- `sudo gem install sass`

## Provision MongoDB
- [Install Docker](https://docs.docker.com/v17.12/install/)
- `docker-compose up -d mongo`
 - Command starts a mongodb container running in the background, available at localhost
 - Run `docker-compose stop` to stop mongo container (will continue if not explicitly stopped)

## Start app
- `npm run start-dev`

## View app
- `localhost:8080/login`
