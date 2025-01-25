ErrorException: json_decode(): Passing null to parameter #1 ($json) of type string is deprecated in /www/wwwroot/API/app/logic/ApiLogic.php:38<br />

Stack trace:<br />

#0 [internal function]: support\App::{closure}()<br />

#1 /www/wwwroot/API/app/logic/ApiLogic.php(38): json_decode()<br />

#2 /www/wwwroot/API/app/controller/ApiController.php(34): app\logic\ApiLogic->zb()<br />

#3 /www/wwwroot/API/vendor/workerman/webman-framework/src/App.php(319): app