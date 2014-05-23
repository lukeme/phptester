phptester
=========

基于aauto开发的一款在windows下快速解释执行php代码的小工具

支持快捷键操作
F5解释执行
F4清除结果

注：需要在config.ini中配置php-cgi.exe的相关路径，如下：
[php]
;php-cgi绝对路径，不可有空格
dir=d:\xampp\php\php-cgi.exe
;php.ini绝对路径，不可有空格
ini=d:\xampp\php\php.ini
