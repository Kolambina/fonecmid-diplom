## ИНСТРУКЦИЯ ПО НАЧАЛЬНОЙ НАСТРОЙКЕ
*Все ниже перечисленные справочники, регистры и документы доступны в подсистеме «Добавленные объекты».
### Шаг 1
Первоначально создайте группу и бота в Телеграмм. Они нужны для отправки уведомлений специалистам о созданных документах «Обслуживание клиента». Уведомления создаются при создании нового документа, а так же при изменении даты и ФИО специалиста.

### Шаг 2
Заполните следующие константы: 
«Абоненская плата» - заполняется из справочника «Номенклатура» соответствующим по смыслу наименованием, при необходимости создайте нужную номенклатуру;
«Работы специалиста» - заполняется из справочника «Номенклатура» соответствующим по смыслу наименованием, при необходимости создайте нужную номенклатуру;
«ВКМ токен ТГБот» - заполняется токеном бота телеграмм;
«Идентификатор группы ТГ» - заполняется идентификатором группы телеграмм;

### Шаг 3
Заполните регистр сведений «Условия оплаты сотрудников», укажите процент от продаж у Специалистов и оклады у всех сотрудников.

### Шаг 4
В справочник «Графики работы» заведите необходимый вид графика работы, например пятидневка.
За тем в подсистеме «Сервис» выберите обработку «Заполнение графика работы». 
В поле выбор периода выберите период (год) для заполнения графика. В поле «Выходные дни» через запятую перечислите порядковый номер выходного дня недели. Например: 6,7 (как суббота и воскресенье).
В поле «график работы» выберите ранее созданный элемент справочника «Графики работы».
Нажмите кнопку «Заполнить». Далее в регистре «График работы» проверьте корректность заполнения графика. Будьте внимательны, для расчетов с использованием календарных дней, необходимо отдельно создать и заполнить график «Календарные дни».

### Шаг 5
В справочник «Подписи» подгрузите изображение печати и факсимиле в формате Jpeg, они необходимы для формирования печатной формы «Акт» документа «Реализация товаров и услуг».


### Шаг 6
В справочнике пользователи создайте для каждого сотрудника пользователя. 
Например: Бухгалтер Бухова Н.Н. как пользователь «Бухова». 
На вкладке права доступа назначьте каждому пользователю соответствующий должности профиль группы доступа.
Наименования профиля группы доступа  созданы для вашего удобства интуитивно понятными. Пример: для бухгалтеров профиль группы доступа - «БухгалтерИТФирмы», для кадровика – «Кадровик расчетчик».
Все созданные профили групп доступа являются поставляемыми и не могут быть изменены пользователем самостоятельно. Подробнее с составом ролей профилей групп доступа вы можете ознакомится по следующему пути: «Администрирование» - «Настройки пользователей и прав» - «Профили групп доступа» - папка «ВКМ».

### Шаг 7 
1.Проинструктируйте кадровика о необходимости создать сотрудников в справочнике «Физические лица» и назначить каждому подразделение. Назначить подразделение важно для автоматического заполнения сотрудниками документов «Начисление заработной платы»;

2.Проинструктируйте бухгалтера о возможности автоматического формирования документов по реализации за месяц с помощью обработки «ВКМ массовое создание актов». Период в обработке должен быть выбран предыдущий месяц;

3.Проинструктируйте менеджера о возможности создания договоров вида Абоненское обслуживание. Для них реализовано заполнение дополнительных полей: «дата начала» и «окончания договора», «стоимость часа работы», «Абоненская плата». Эти поля должны быть заполнены для корректного формирования документов реализации;

4.Так же проинформируйте пользователя, что при не заполненных константах «Работы специалиста» и «Абоненская плата» документ заполнен не будет.

