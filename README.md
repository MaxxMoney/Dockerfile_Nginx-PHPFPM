This is a Dockerfile/image to build a container for nginx, phpfpm and composer.

参考Dockerfile

https://github.com/richarvey/nginx-php-fpm

https://hub.docker.com/r/richarvey/nginx-php-fpm

在此Dockerfile基础上做了部分精简，删除第三方nginx模块、certbot；nginx源码包因网络问题使用COPY替代.
