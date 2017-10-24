<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## How to use

sample download project and run following command.

composer dump-autoload -o

composer update --no-scripts

php artisan migrate

php artisan route:list

php artisan make:seeder ArticlesTableSeeder

php artisan db:seed --class=ArticlesTableSeeder

## Configure Postman

POST-  http://localhost/passport/public/oauth/token
goto authentic create folde with any name like login
add header-

(1) Accept  application/json
(2) Content-Type   application/json

Body- select "raw" and write following line

{
"grant_type":"password",
"client_id":"2",
"client_secret":"m3p351DK9RfJuwCJGIBVxQNEktsc6BlNcGMk01kk",
"username":"r@gmail.com",
"password":"123456",
"scope":"*"
}

GOTO manage enveronment

Add your own authentication like that

Add key- authorization
value- 
Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiIsImp0aSI6IjkzNzdjNDE0MDRlMDQ3ODhmNmMzNTA4ODEzNWM1NjEyMzhmMGRjN2I3Njg1ZTc5OWM1N2U2M2EyNTQ5MGY3ZTQwMTI5YzNlODE5NTQ2YjljIn0.eyJhdWQiOiIyIiwianRpIjoiOTM3N2M0MTQwNGUwNDc4OGY2YzM1MDg4MTM1YzU2MTIzOGYwZGM3Yjc2ODVlNzk5YzU3ZTYzYTI1NDkwZjdlNDAxMjljM2U4MTk1NDZiOWMiLCJpYXQiOjE1MDg4Mjg5MDAsIm5iZiI6MTUwODgyODkwMCwiZXhwIjoxNTQwMzY0OTAwLCJzdWIiOiIxIiwic2NvcGVzIjpbIioiXX0.kTs4X7ZYNaTzoQJf75AtO94_xjtZoHTM4JIPii3kbZgHCX5u-fM_Fw9yzCX1NZqJxARivo3umB0gXF6CB3b7PTHE1SjNY44bn9YaxqF134nlNI_e5rFjJbl32lZ0B2p-8qfC1wCjnEJ0jD-fFr8TZo6jJEJ16qeAb0jNSZzjSfRfe5hyfVk6B90vjwUPqaVqS-iAZ2OJB5R5JewSvML-Y-SpHUnO6hmV_RtkGRt5pyTBMAQOhabrrn5UtgrJGXNO6uf9JjtV4LPx24gW_OM1xrMHviaHovqO9EubRXoj3JF3_69KPDuOtSCHtxWM-EUnyVQ7rENIFJUMvbUxopjzXYqL7ADua7142D3vZZRAzEFw-WH1pA89u1oXEBDAb3soFNJIZ7tN_66tEZ3W9j9pzdqFjsEchih_k_EKnB4CI_FfRbXDW4YJjqF2eYlCAEbpPknNtMbtbLEEzeitoA3LmKNnm_8Q_z1iavMxkoaRZzf12WbZP8vg7GjzSvG05PenGkm9TlP-1a210h--6e9eDF59yBQlPHPIl2lD4R_bFjJuprfIRJPucBLpHP3mLVuoLmfI-DmWSFZ3lPR1qEd_7p1rSnoSOhL_fytjUC6abvCwT7RmHa8i6RK-jUUSCbItIqfxw9fhFLdakFaQYSiHu-Pck7jVwgOF5AcLB1gPIec

select yor authentication name

Reference website-  https://www.toptal.com/laravel/restful-laravel-api-tutorial




## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb combination of simplicity, elegance, and innovation give you tools you need to build any application with which you are tasked.

## Learning Laravel

Laravel has the most extensive and thorough documentation and video tutorial library of any modern web application framework. The [Laravel documentation](https://laravel.com/docs) is thorough, complete, and makes it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 900 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for helping fund on-going Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](http://patreon.com/taylorotwell):

- **[Vehikl](http://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[British Software Development](https://www.britishsoftware.co)**
- **[Styde](https://styde.net)**
- [Fragrantica](https://www.fragrantica.com)
- [SOFTonSOFA](https://softonsofa.com/)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell at taylor@laravel.com. All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
