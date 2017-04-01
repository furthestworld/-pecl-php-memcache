memcached module for PHP
------------------------
This module requires zlib library, used for on-the-fly data (de)compression.
Also, you'll need memcached to use it =)

The memcached website is here:
    http://www.danga.com/memcached/

You will probably need libevent to install memcached:
You can download it here: http://www.monkey.org/~provos/libevent/

How to run tests:
1. sh tests/memcache.sh
2. TEST_PHP_EXECUTABLE=/usr/local/bin/php php -dextension=modules/memcache.so run-tests.php -d extension=modules/memcache.so

Maintainers:
Herman J. Radtke III	hradtke at php dot net


--------
## 用官方[memcache扩展](https://git.php.net/repository/pecl/caching/memcache.git)代码为例子，研究下PHP扩展开发的一些常规套路

> 有兴趣的童鞋一起哈~

* 参考书籍
    * [PHP扩展开发及内核应用](http://www.cunmou.com/phpbook/index.md)
    请自行阅读一百遍~ :)