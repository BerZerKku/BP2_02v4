Блок питания БП2 для аппаратуры АВАНТ.
Версия платы: 02v4.
Дата создания: декабрь 2014.
Среда разработки: OrCAD 16.6-S036.
База: greysql.

Измеренные пороги:
Включение - 22.5 В.
Выключение - 21.9 В. 

Проблемы:
1. Предохранители в держателях стоят слишком свободно, надо где-то на 1.5мм короче.
2. Надо сдвинуть разъем питания где-то на 0.5мм ближе к краю.
3. Проверить на зазоры между элементами платы и креплением/панелью. Нужно отодвинуть С5, т.к. слишком близко к винту заземления. Так же можно сдвинуть схему сравнения.
4. Надо поставить ключ и по 24 В. Сейчас может быть ситуация когда светодиод питания 24 В горит, т.е. есть какое-то напряжение при этом 5 В отсутствует.

Дополнительно:
Плата BP2_02_ctrl сделана для проверки схемы управления, взамен механического реле.