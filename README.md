# restfulapi

## Installation

Clone restfulapi project to web root

cd to the folder

Install the composer and node dependencies

# composer install

# npm install

Ccreare database db_test (or any name)

Copy the environment variable and update it to set the database and other details

# copy .env.example .env

inside the project folder run the following commands

# php artisan key:generate

Create the database tables
# php artisan migrate

Dumping initila data
# php artisan db:seed

Copy attached images to public/img folder

create a virtual host for the project. The project is hosted under the public folder inside the project root folder. You can browse this folder for the apis for the react project

if the virtual host for the public folder of this project is restfulapi.test(The default virtual host given by laragon)

Following is an example APIEndpoint
eg. restfulapi.test/api/users
