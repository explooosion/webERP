#webERP中文修正
版本：未限制

#說明
```
CentOS、Ubuntu：
測試過沒問題

Winodows：
PHP「;extension=php_gettext.dll」影響，導致語系失效，
因此本次修正為php.ini檔，讓weberp使用該套件的語系設定，
```

#基本語系
首先請先確定，MySQL、PHP皆是utf8。
```
wampserver -> MySQL -> my.ini
wampserver -> PHP -> php.ini
```

#修正php.ini
```
step1. wampserver
step2 .PHP
step3. php.ini
step4. extension=php_gettext.dll (用;註解)
step5. restart wampserver
```

參考資料：
http://job.achi.idv.tw/2009/08/11/windows-weberp-utf-8-%E4%B8%AD%E6%96%87%E5%8C%96/
