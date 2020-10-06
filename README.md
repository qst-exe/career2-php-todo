# 職業実践Ⅱ(PHP)サンプルアプリケーション2

TODアプリです。

## 動作環境

- PHP 7.2以上

## 環境構築

clone
```
$ git clone git@github.com:qst-exe/career2-php-todo.git
```

composer install
```
$ composer install
```

.envに設定を入力
```
$ cp .env.sample .env
```

migrate
```
$ vendor/bin/phpmig migrate 
```

起動
```
$ php -S localhost:3000 -t . 
```

---

[職業実践Ⅱ(PHP)](https://github.com/qst-exe/carrier2-php)
