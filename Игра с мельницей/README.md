## Проект из лабораторных по ООП.
Требовалось разработать на языке С++ иерархию классов фигур (в данном варианте — мельниц), а так же классов дополнительных объектов-препятствий. Реализовать взаимодействие через динамический полиморфизм. Представляет собой консольное приложение с простейшей графикой на основе WinAPI.

Основная фигура (мельница) может изменяться при столкновении с другими объектами: ремонтная станция добавляет или демонтирует ей крышу, а в зоне пруда мельница становится водяной.

Для просмотра усложненной декстопной версии с использованием Qt <a href="https://github.com/Xentention/Uni-projects/tree/main/Mill%20Game%20%D0%BF%D0%BE%D0%B4%20QT">перейдите сюда</a>.

Упрощенная диаграмма иерархии классов:

![uml class simple](https://user-images.githubusercontent.com/96055384/180402849-7cecae76-3e04-42bc-908e-c3b3751186d2.png)

Разбиение по файлам не лучшее, но ввиду обстоятельств было выбрано оно.
