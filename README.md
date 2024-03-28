# ТЕХНИЧЕСКОЕ ЗАДАНИЕ
Разработать Desktop приложение на основе Windows Forms по предметной области. Все данные должны храниться в формате файла CSV (возможно / допустимо несколько файлов).
В проекте реализовать следующий графический интерфейс (Front-end): 
	Приложение должно иметь адаптивный интерфейс (соответствовать правилам и требованиям проектирования UI/UX дизайна для Windows Forms) и следующие элементы: главное меню, инструментальная панель с кнопками, подсказки к кнопкам и элементам управления, справочные данные по приложению (о программе), краткое руководство пользователя, сетка ввода-вывода данных / поля ввода-вывода данных, элементы для управления функционалом. Возможно несколько окон в приложении. Все окна должны иметь соответствующие надписи в заголовках. 
ПРАВИЛО (СОГЛАШЕНИЕ) НАИМЕНОВАНИЯ ОБЪЕКТОВ В ПРОЕКТЕ:
	Недопустимые названия объектов: Label1, Label2, Button1, Button2, Edit1, Edit2, Form1, Form2 и т.д.

Все объекты в программе: формы, кнопки, метки, поля ввода данных, панели, контейнеры и т.д. ДОЛЖНЫ иметь АССОЦИАТИВНОЕ ИМЯ и в конце имени объекта содержать ваши инициалы.

Пример названия объектов:
	Объект: Button, название buttonDonePrint_PII, buttonSaveResult_PII (ОбъектГлаголСуществительное_ВашиИнициалы)

Объект: TextBox, название textBoxOutPutResult_PII, (ОбъектГлаголСуществительное_ВашиИнициалы)

В проекте реализовать следующий функционал (Back-end): 
- [ ] Ввод
- [ ] Редактирование
- [ ] Поиск
- [ ] Сортировка 
- [ ] Фильтрация
- [ ] Сохранения в файл(ы), чтение из фала(лов) данных. 
- [ ] Реализовать элементы статистики (количество, сумма, среднее, min, max и т.д.).
- [ ] График (гистограмма / функция / диаграмм).

ПРЕДМЕТНАЯ ОБЛАСТЬ: Оптовая база
Возможные характеристики данных (можно добавить свои):
- [ ] код товара, название товара, количество на складе, стоимость единицы товара, примечания - описание товара;
- [ ] номер и ФИО поставщика товара, срок поставки и количество товаров в поставке.
