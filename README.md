# Group Chat using Laravel and Pusher

This repository demonstrates the process to create a realtime *Group Chat Application* using [Laravel](https://laravel.com/) and [Pusher](https://pusher.com/). Please follow below steps to have a running version of the app in this repo

1. Clone repo
2. Configure your environment variables for Pusher and Laravel by copying the `.env.example` to `.env`
3. Configure pusher Key/Secret key in `.env` 
4. Configure your Pusher key in the `resources/assets/js/bootstrap.js` file
4. Install composer dependencies
5. Run npm install
6. Run php artisan migrate
7. Do not forget to run the queue listener to broadcast the events => php artisan queue:listen
