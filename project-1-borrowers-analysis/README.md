## Исследование надёжности заёмщиков

Для заказчика — кредитного отдела банка — необходимо выяснить, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. 
Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга.

**Цель исследования:** определить влияние семейного положения и количества детей клиента на факт погашения кредита в срок.

**Используемые данные:** статистика банка о платёжеспособности клиентов.

**Описание данных**

* `children` — количество детей в семье
* `days_employed` — общий трудовой стаж в днях
* `dob_years` — возраст клиента в годах
* `education` — уровень образования клиента
* `education_id` — идентификатор уровня образования
* `family_status` — семейное положение
* `family_status_id` — идентификатор семейного положения
* `gender` — пол клиента
* `income_type` — тип занятости
* `debt` — имел ли задолженность по возврату кредитов
* `total_income` — ежемесячный доход
* `purpose` — цель получения кредита
