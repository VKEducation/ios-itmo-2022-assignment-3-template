# Assignment #3
## Задача:
Реализовать список фильмов для Assignment #2

## Требования:
Модифицируйте проект из предыдущего задания.
Первым экраном в приложении должен стать экран `UITableView` который содержит список фильмов. Ячейка списка должна содержать  название фильма, режиссера, год выпуска  и проставленную отметку (в виде звездочек). Секцией в таблице должен служить год выпуска фильма и они должны быть отсортированы по секциям. На этом экране так же должна быть кнопка «Добавить», которая пушит в навигационный стек экран из предыдущего задания.  Кнопка «Сохранить» должна добавлять на предыдущий экран фильм и попать экран из навигационного стека. К таблице добавить `UISwipeAction` красного цвета с надписью «Удалить», который будет удалять эту ячейку.

## Бонусные задания 
- На экран со списком необходимо реализовать изменение оценки путем нажатия на нужную отметку в звездочках.
-Добавить индекс для быстрого поиска по году (https://developer.apple.com/documentation/uikit/uitableviewdatasource/1614857-sectionindextitles https://developer.apple.com/documentation/uikit/uitableviewdatasource/1614933-tableview)

## За что могут сниматься баллы
- `Warnings` в проекте, которые можно исправить. 
- `Force Unwrap` где не надо
- Только визуальные изменения без изменения `datasource`
- Отсутствие переиспользования ячеек
