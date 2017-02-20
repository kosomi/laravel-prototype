<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel<br>
<br>
<br>
https://github.com/apal21/PHP-Laravel-5.4-custom-blog-CMS<br>
<br>
 laravel new custome-blog-CMS<br>
<br>
 php artisan make:auth<br>
<br>
 php artisan make:controller BlogController --resource<br>
 php artisan make:controller CategoryController --resource<br>
 php artisan make:controller CommentsController --resource<br>
 php artisan make:controller PostController --resource <br>
 php artisan make:controller TagController --resource<br>
 php artisan make:controller pagesController --resource<br>
<br>
 php artisan make:migration create_posts_table --create posts <br>
 php artisan make:migration add_slug_to_posts --create posts <br>
 php artisan make:migration add_category_id_to_table --create posts <br>
 php artisan make:migration create_categories_table --create categories <br>
 php artisan make:migration create_tags_table --create tags <br>
 php artisan make:migration create_post_tag_table --create post_tag <br>
 php artisan make:migration create_comments_table --create comments <br>
 php artisan make:migration add_image_col_to_posts --create posts <br>
<br>
 php artisan make:model Category<br>
 php artisan make:model Comment<br>
 php artisan make:model Post<br>
 php artisan make:model Tag <br>
<br>
composer require "laravelcollective/html":"^5.3.0"<br>
Collective\Html\HtmlServiceProvider::class,<br>
'Form' => Collective\Html\FormFacade::class,<br>
'Html' => Collective\Html\HtmlFacade::class,<br>
<br>
composer require mews/purifier<br>
        Mews\Purifier\PurifierServiceProvider::class, <br>
        'Purifier' => Mews\Purifier\Facades\Purifier::class, <br>
<br>
<br>
Intervention\Image\ImageServiceProvider::class   <br>
'Image' => Intervention\Image\Facades\Image::class<br>
<br>
<br>
<br>
composer update<br>
<br>
        "php": ">=5.6.4",<br>
        "guzzlehttp/guzzle": "^6.2",<br>
        "intervention/image": "^2.3",<br>
        "laravel/framework": "5.4.*",<br>
        "laravel/tinker": "~1.0",<br>
        "laravelcollective/html": "^5.4.0",<br>
        "mews/purifier": "^2.0"<br>
<br>
<br>
=================================================================================================<br>
<br>
composer require "laravelcollective/html":"^5.3.0"<br>
composer require mews/purifier<br>
composer require intervention/image<br>
<br>
        Collective\Html\HtmlServiceProvider::class,<br>
        Mews\Purifier\PurifierServiceProvider::class,  <br>
        Intervention\Image\ImageServiceProvider::class,   <br>
<br>
        'Form' => Collective\Html\FormFacade::class,<br>
        'Html' => Collective\Html\HtmlFacade::class,<br>
        'Purifier' => Mews\Purifier\Facades\Purifier::class, <br>
        'Image' => Intervention\Image\Facades\Image::class,<br>
