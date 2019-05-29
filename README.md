# AzureLogAnalytics1CMonitor
Мониторинг 1С с использованием Azure Monitor

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fability-group%2FAzureLogAnalytics1CMonitor%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

## Обзор

Конструктивно сервис строится на аналитике событий, которые формирует 1С и систем, на которых 1С базируется. Azure Monitor позволяет отображать аналитическую информацию на заранее настроенных дашбордах. 

Решение состоит из двух модулей:
* Разворачивающаяся из шаблона область Azure Monitor на базе Log Analytics с преднастроенными дашбордами
* Модуль мониторинга 1С на базе модуля внешней обработки 1С

## Порядок установки

Для развертывания решения необходимо выполнить следующие шаги:

1. Нажмите кнопку «Deploy to Azure» для вызова процедуры развертывания шаблона

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fability-group%2FAzureLogAnalytics1CMonitor%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

2. Заполните необходимые параметры



3. После завершения установки сохраните атрибуты для настройки модуля обработки 1С



4. Скачайте и откройте в Конфигураторе 1С модуль 

Детальная информация по работе с модулями внешней обработки: http://v8.1c.ru/overview/Term_000000601.htm 



5. Укажите параметры соединения с развернутым шаблоном



6. Задайте расписание выполнения внешней обработки




## Дополнительная информация

Для просмотра подробной информации перейдите по ссылке:  
https://abilitygroup.ru/solutions/monitoring-sostoyaniya-servera-1s/ 

<a href="https://abilitygroup.ru" target="_blank">
    <img src="https://abilitygroup.ru/local/templates/main/images/ability_logo_footer.png"/>
</a>

