## About

Simple WebSockets using

1. beyondcode/laravel-websockets
2. laravel/echo
3. laravel-mix/laravel-mix

### Workflow

1. Run 

    npx mix 

    when changing files inside resources/js

2. Run 

    php artisan websockets:serve 

    to start websockets

3. Run

    event (new \App\Events\NewTrade('test'))

    to trigger NewTrade event with text 'test'

    or run go to http://localhost/laravel-websockets and run event via dashboard, Data string needs to be a valid JSON, for example

    {"trade": "test"}