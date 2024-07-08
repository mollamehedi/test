<p align="center"><a href="https://www.youtube.com/watch?v=PTE6GHgfh1Q" target="_blank"><img src="https://i9.ytimg.com/vi/PTE6GHgfh1Q/sddefault.jpg?v=668bf9a6&sqp=CMD0r7QG&rs=AOn4CLC8spyTL1dUYKRjF9JSHfiamrAddg" width="400" alt="Laravel Logo"></a></p>

## How to Use Multiple Languages in Laravel
Welcome to the repository for the tutorial video on how to use multiple languages in Laravel! This README provides a summary of the video content and additional resources.
## Video Link

Watch the full tutorial on YouTube: [How to Use Multiple Languages in Laravel](https://www.youtube.com/watch?v=PTE6GHgfh1Q)

## Topics Covered

- Introduction to Laravel Localization and Internationalization (i18n)
- Setting up Language Files and Directories
- Creating Language Keys and Translations
- Switching between Languages Dynamically
- Best Practices for Multi-language Support in Laravel

## Instructions

- 1.Download freash laravel project
- 2.create language folder and assign text inside resoures folder
- 3.create route, controller and assign function
- 4.create language select option and function
- 5.Create middleware

## Step-by-Step Instructions

### 1. Download Fresh Laravel Project

```bash
composer create-project --prefer-dist laravel/laravel multi-language-laravel
cd multi-language-laravel
```

## 2. Create Language Folder and Assign Text Inside Resources Folder
Create a lang folder inside the resources directory. Inside resources/lang, create subdirectories for each language you want to support (e.g., en for English, bn for Bangla, fr for French).
<img src="data:image/png;base64,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" width="400" alt="Laravel Logo">

Open text.php file from each directory and paste bellow code.

resources/lang/bn/conent.php 
```
<?php

return [
    'heading' => 'আমরা দেখব কিভাবে মোল্লা মেহেদীর সাথে লারাভেলের একাধিক ভাষা ব্যবহার করা যায়'
];
```
resources/lang/en/conent.php 
```
<?php

return [
    'heading' => 'We will see how to use multiple languages ​​in Laravel with Molla Mehedi'
];
```
resources/lang/fr/conent.php 
```
<?php

return [
    'heading' => 'Nous verrons comment utiliser plusieurs langues dans Laravel avec Molla Mehedi',
];
```

## 3. Create Route, Controller, and Assign Function
Generate a new controller and define functions for language handling:
```
php artisan make:controller LanguageController
```
Define routes in web.php:
```
Route::get('lang/change', [LangController::class, 'lang_change'])->name('lang.change');

```
 Create Language Select Option and Function
```
<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;
use Illuminate\Support\Facades\App;

class LangController extends Controller
{
    public function lang_change(Request $request)
    {
        App::setLocale($request->lang);
        session()->put('lang_code',$request->lang);
        return redirect()->back();
    }
}
```

## 4 .create language select option and function 
 put the html code  inside views folder  welcome.blade
```
<!DOCTYPE html>
<html>
<head>
    <title> Laravel Multiple Language With Molla Mehedi</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container text-center">
      
        <div class="row">
            <div class="col-md-8 m-auto mt-5">
                <div class="card">
                    <div class="card-header">
                        <img src="{{ asset('logo.jpg') }}" alt="">
                        <h2>Laravel Multiple Language With Molla Mehedi</h2>
                    </div>
               
                <div class="card-body">
                    <strong>Select Language: </strong>
                    <select class="form-control lang-change">
                        <option value="en" {{ session()->get('lang_code')=='en' ? 'selected' : ''}}>English</option>
                        <option value="fr" {{ session()->get('lang_code')=='fr' ? 'selected' : ''}}>French</option>
                        <option value="bn" {{ session()->get('lang_code')=='bn' ? 'selected' : ''}}>Bengali</option>
                    </select>
                <h4 class="mt-5">{{ __('content.heading') }}</h4>
                </div>
                <div class="card-footer">
                    <h4 class="mt-5">Support</h4>
                    <strong>Email : </strong> <a href="mailto:mollameehedi@gmail.com">mollameehedi@gmail.com</a>
                    <br/>
                    <strong>Website : </strong><a href=" mlmehedi.com"> mlmehedi.com</a>
                </div>
            </div>
            </div>
        </div>
     
    </div>
</body>
  
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script type="text/javascript">
 
  var url = "{{ route('lang.change') }}";

    $('.lang-change').change(function(){
     let lang_code = $(this).val();
      window.location.href = url + "?lang="+ lang_code;
    });

</script>
</html>
```

## 5.Create middleware
Create a middleware to handle language switching globally:
```
php artisan make:middleware LangMiddleware
```
Assign Condition
```
<?php

namespace App\Http\Middleware;

use Closure;
use Illuminate\Http\Request;
use Illuminate\Support\Facades\App;
use Symfony\Component\HttpFoundation\Response;

class LangMiddleware
{
    /**
     * Handle an incoming request.
     *
     * @param  \Closure(\Illuminate\Http\Request): (\Symfony\Component\HttpFoundation\Response)  $next
     */
    public function handle(Request $request, Closure $next): Response
    {
        if(session()->has('lang_code')){
            App::setLocale(session()->get('lang_code'));
        }
        return $next($request);
    }
}
```
# Register the middleware in app/Http/Kernel.php:

```
protected $middlewareGroups = [
    'web' => [
        // Other middleware...
        \App\Http\Middleware\LangMiddleware::class,
    ],
];
```

Ok Now run artisan server using the bellow command and test your app.
```
php artisan serve
 
```
Paste this URL in the browser http://127.0.0.1:8000

 

 

Hope this will help you. Thanks




