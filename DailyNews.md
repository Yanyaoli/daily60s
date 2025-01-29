ErrorException: Trying to access array offset on value of type null in /www/wwwroot/API/app/service/ocrService.php:33<br />

Stack trace:<br />

#0 /www/wwwroot/API/app/service/ocrService.php(33): support\App::{closure}()<br />

#1 /www/wwwroot/API/app/logic/ApiLogic.php(52): app\service\ocrService->ocr()<br />

#2 /www/wwwroot/API/app/controller/ApiController.php(34): app\logic\ApiLogic->zb()<br />

#3 /www/wwwroot/API/vendor/workerman/webman-framework/src/App.php(319): app