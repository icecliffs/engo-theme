# 该项目重构中...

## Engo Theme
 ✨适用于企业及政府门户网站的**Emlog**模板

**该项目源于2019年末为某甲方爸爸而编写，后来因为甲方爸爸撕毁合约后索性开源**

**原先仅适用于 5.3.1 博客系统，现在有时间了写了个全版本适配的**

**Enjoying :)**

## 测试环境
 - System: Ubuntu 20.04 LTS ()
 - PHP 8.1.4 (fpm_gd_...)
 - Nginx (1.20.1)

## 预览

## 使用方法

1. 将本项目 clone 到你主题下
2. 开启伪静态 (可选)
```php
location / {
    index index.php index.html;
    if (!-e $request_filename){
        rewrite ^/(.*)$ /index.php last;
    }
}
```

## 功能
 - 