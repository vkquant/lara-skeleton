### Image processing-service.
#### This service serve RESTFull api backend which used by SPA application.
###### Requirements php7.4, mysql5.7+


#### Install ###
##### 1. Clone the repository. ###
` git clone https://github.com/vkquant/12man.git`
##### 2. Create .env file.  ###
` cp .env.example .env`
##### 3. Download vendors.  ###
`composer install --no-cache`
##### 4. Fetch database migrations.  ###
`php artisan migrate:install` or `php artisan migrate:refresh` to reset database.
######## 5. Test  ####
Run `php artisan test` to validate application state.


## Read more about below: 
- [SETUP](docs/00-setup)
- [CLI](docs/01-cli)
- [API](docs/02-api)
- [TESTING](docs/03-tests)
- [RUN & DEPLOY](docs/04-run)
- [DOCKER](docs/05-docker)
