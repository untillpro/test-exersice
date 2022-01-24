### Что нужно сделать

1. Сверстать скрин из файла `design_example.jpg`. Жестко соблюдать размеры и наличие всех элементов не нужно. Например стрелочками в левом сайдбаре можно пренебречь. В файле `design_example_with_marks.jpg` находится тот же макет, но с пометками для лучшей ориентации по заданию.
2. Добавить `splash screen` с логотипом `logo.png` по центру. Можно проявить фантазию.
3. Список Категорий (1) и список позиций (2)  должен генерироваться исходя из тестовых данных из файла `data.json` (сущности "departments" и "articles" соответственно). Связь позиций с категориями происходит по полю `id_departament`
4. При выборе категории из списка (1) должны выводится позиции только выбранной категории в списке (2)
5. При нажатии на позицию , она должна добавляться в список заказа (3) в количестве 1 штуки на нажатие. Так как расчет цены в приложении это достаточно сложный процесс, цену для позиций можно либо генерировать случайно в момент добавления, либо просто каждая позиция будет стоить некое фиксированное значение, например `1`.
6. Все изменения списка позиций должны изменять Total (5) заказа.
7. Для управления состоянием нужно использовать Redux. Вся динамика через глобальное состояние - списки категорий и позиций, текущая категория, список заказа - все должно хранится в State. Переключение категории через Action (Stateful Widget использовать не нужно).
8. Все остальные элементы, которые по вашему мнению, должны нажиматься, сделайте кликабельными, но без callback.
9. Иконки для кнопок находятся в папке `./icons/`.
