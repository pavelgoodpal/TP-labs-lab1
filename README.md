# Лабораторная работа 1 по дисциплине "Технологии программирования"

## Дешевов Павел Павлович САПР 1.4
## Вариант 4

## Цели работы
1. Познакомиться c распределенной системой контроля версий кода Git и ее функциями;
2. Познакомиться с понятиями «непрерывная интеграция» (CI) и «непрерывное развертывание»
(CD), определить их место в современной разработке программного обеспечения;
3. Получить навыки разработки ООП-программ и написания модульных тестов к ним на
современных языках программирования;
4. Получить навыки работы с системой Git для хранения и управления версиями ПО;
5. Получить навыки управления автоматизированным тестированием программного обеспечения,
расположенного в системе Git, с помощью инструмента GitHub Actions.

## Задачи

1. Выберите для Вашего проекта тип лицензии и добавьте файл с лицензией в проект.
2. Добавьте в проект файл .gitignore и сформируйте его содержимое.
3. Добавьте в проект еще один класс – наследник класса DataReader, который должен
обрабатывать входной файл определенного формата (согласно индивидуальному варианту, см.
таблицу). Составьте модульные тесты для методов этого класса, постарайтесь покрыть тестами
максимально возможный объем кода. Для работы с этим заданием создайте новую ветку кода на основе
главной и фиксируйте в нее весь программный код в процессе разработки. Добейтесь выполнения всех
тестов проекта, после чего объедините текущую ветку кода с главной.
4. Добавьте в проект класс, реализующий расчет определенных характеристик студентов
(согласно индивидуальному варианту, см. таблицу). Составьте модульные тесты для методов этого
класса, постарайтесь покрыть тестами максимально возможный объем кода. Для работы с этим
заданием создайте новую ветку кода на основе главной и фиксируйте в нее весь программный код в
процессе разработки. Добейтесь выполнения всех тестов проекта, после чего объедините текущую
ветку кода с главной.
5. Составьте UML-диаграмму классов итогового проекта.
6. Проанализируйте полученные результаты и сделайте выводы

### Формат ввода: JSON
### Задание
Рассчитать и вывести на экран количество студентов,
имеющих академические задолженности (имеющих балл
< 61 хотя бы по одному предмету).


## UML диаграмма классов
![img.png](img.png)

## Лицензия

MIT

## Выводы:

- Были изучены основные подходы CI/CD 
- Были изучены основы системы контроля версий git
- Было выполнено индивидуальное задание
- Построена UML диаграмма классов проекта
- Выбрана лицензия для проекта. Лицензия: MIT
- Была добавлена реализация класса DataReader - JsonDataReader для работы с JSON форматом
- Создан класс для нахождения академических задолжников, StudyDebtorFinder
- Написаны модульные тесты для новых добавленных классов JsonDataReader и StudyDebtorFinder
- Были получены навыки управления автоматизированным тестированием программного обеспечения,
расположенного в системе Git, с помощью инструмента GitHub Actions