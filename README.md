Laravel Jetstream ​
Laravel Jetstream is a beautifully designed application starter kit for Laravel and provides the perfect starting point for your next Laravel application. Jetstream provides the implementation for your application's login, registration, email verification, two-factor authentication, session management, API via Laravel Sanctum, and optional team management features.

Jetstream is designed using Tailwind CSS and offers your choice of Livewire or Inertia scaffolding.

![](https://jetstream.laravel.com/img/preview-3.png)




Available Stacks ​
Laravel Jetstream offers your choice of two frontend stacks: Livewire and Inertia.js. Each stack provides a productive, powerful starting point for building your application; however, the stack you choose will depend on your preferred templating language.

Livewire + Blade ​
Laravel Livewire is a library that makes it simple to build modern, reactive, dynamic interfaces using Laravel Blade as your templating language. This is a great stack to choose if you want to build an application that is dynamic and reactive, and is a great alternative to a full JavaScript framework like Vue.js.

When using Livewire, you may pick and choose which portions of your application will be a Livewire component, while the remainder of your application can be rendered as the traditional Blade templates you are used to.




Installation ​
Installing Jetstream ​
You may use Composer to install Jetstream into your new Laravel project:
```
composer create-project laravel/laravel example-app

cd example-app

composer require laravel/jetstream
```

After installing the Jetstream package, you may execute the jetstream:install Artisan command. This command accepts the name of the stack you prefer (livewire or inertia). In addition, you may use the --teams switch to enable team support.

The jetstream:install command will also install a suite of "feature" tests that provide test coverage for the features provided by Jetstream.

You are highly encouraged to read through the entire documentation of Livewire or Inertia before beginning your Jetstream project.



Install Jetstream With Livewire:

```
php artisan jetstream:install livewire

php artisan jetstream:install livewire --teams
```


The Inertia stack may also be installed with SSR support:
```
php artisan jetstream:install inertia --ssr
```


http://127.0.0.1:8000 make an account and login to your dashboard.
