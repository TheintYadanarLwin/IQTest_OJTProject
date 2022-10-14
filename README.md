
# IQTEST_OJTProject
Nuxt-app using Vuex Store with Backend Laravel using Closure Table

## Getting Start

**git clone this repo link in your folder**

1.`git clone https://github.com/TheintYadanarLwin/IQTEST_OJTProject.git`

2.`cd IQTEST_OJTProject`

**Setup installation for Backend laravel**

1.`cd backend`

2.`composer install` 

if you have some error 
 use `composer update`

3.*connect your database and copy paste these two sentenses in .env file*

`SESSION_DOMAIN=localhost`

`SANCTUM_STATEFUL_DOMAINS=localhost:3000`

4.*creating tables in database* 
`php artisan migrate`

5.*inserting data into tables*
`php artisan db:seed`

6.run 
`php artisan serve`

**Setup installation for frontend NUXTJS**

1.`cd frontend`

2.`npm install` or `npm install --force`

3.` npm run dev`

*Hope you Enjoy it!👍*
