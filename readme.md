# 入门总结

> 目前本人尚未入门

原理相对比较难以理解不是那么直观
http://laravelacademy.org/docs/laravel-5_4
要充分实践，找到好的教程

https://github.com/YanlongMa/laravel-curd

Laravel Framework 5.4.28

1、composer install
2、配置.env
3、
2.2 手动执行以下 SQL 创建数据表

DROP TABLE IF EXISTS students;

CREATE TABLE IF NOT EXISTS students(

    `id` INT AUTO_INCREMENT PRIMARY KEY ,
    `name` VARCHAR(255) NOT NULL DEFAULT '' COMMENT '姓名',
    `age` TINYINT UNSIGNED NOT NULL DEFAULT 0 COMMENT '年龄',
    `sex` TINYINT UNSIGNED NOT NULL DEFAULT 10 COMMENT '性别',    /* 10.未知 20.男 30.女 */

    `created_at` INT NOT NULL DEFAULT 0 COMMENT '新增时间',
    `updated_at` INT NOT NULL DEFAULT 0 COMMENT '修改时间'

)ENGINE=InnoDB DEFAULT CHARSET=UTF8 COMMENT='学生表';

```
warning: CRLF will be replaced by LF in .tags_sorted_by_file
```
>
git config --global core.autocrlf false

# 入门流程

1、安装搭建laravel，学习路由+控制器+视图（blade）
> [视图变量传递和Blade](https://www.codecasts.com/blog/post/programming-with-laravel-5-blade-views-with-var)
