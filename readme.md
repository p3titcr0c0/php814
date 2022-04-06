# Custom PHP 8.1.4

Base php8.1.4 (17 Mar 2022)

* SQlite3.
* Sqlsrv : a plugin for PDO to connect to an MSSQL Server Instance.

php.ini :
```
[ExtensionList]
extension=php_pdo_sqlsrv_81_ts_x64.dll
extension=php_sqlsrv_81_ts_x64.dll
extension=php_sqlite3.dll

output_buffering = 16384
```
