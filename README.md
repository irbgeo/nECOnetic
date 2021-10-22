# nECOnetic

## Разворачивание системы

* Запуск
```
make up
```

## Data-service

maintainers:

- Морочев Георгий morochev.g@gmail.coma

Функционал:
* Хранение и управление списком станций
* Обработка, управление и хранение данных со станций экомониторинга и профилемера
* Управление расчета данных и хранение расчетных данных

Для того чтобы расчитать данные экомониторинга на следующий сутки, необходимо в систему загрузить измерения со станций экомониторинга и профилемера за последние сутки  и отправить запрос на расчет данных, указав за какой период были загружены данные

Документация:
 * [REST API](data-service/docs/API.md)
 * [TODO](data-service/docs/TODO.md)

## !!!WARNING!!!

Для корректной обработке файлов с данными, необходимо чтобы были:
- правильные и единообразные названы параметров измерения концентраци
- дата и время в формате: dd/mm/yyyy hh:mm(:ss - не обязательно)


