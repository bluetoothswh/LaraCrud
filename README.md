## LaraCrud
<p>一个基于Laravel5.5的crud操作的package </p>
<p>
 网址：
 <a href="https://larashuo.com">larashuo.com</a>
 <p>

## 安装

````php
//安装
composer require larashuo/laracrud

//在config/app.php $providers中添加
//LaraShuo\LaraCrud\LaraCrudServiceProvider::class,
//支持laravel5.5的安装，已经不需要在手工添加$providers数组

// publish
php artisan vendor:publish 

//生成数据表
php artisan migrate

//修改下config/filesystems.php

        'local' => [
            'driver' => 'local',
            'root' => public_path('/'),
        ],

````

<p>最后可以通过 http://domain/goods 来访问</p>