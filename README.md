# Условие Тестового Задания

## Цель

Разработать компонент Vue.js с использованием виртуальной прокрутки для оптимизации отображения большого количества данных. Компонент должен отображать строки, содержащие несколько квадратов, с различными значениями для `border-radius`, и реализовать изменение размера квадрата при наведении на него курсора.

## Требования

### Генерация Данных

- Создать компонент, который генерирует данные для 100000 строк.
- Каждая строка должна содержать от 10 до 20 квадратов.
- Каждый квадрат должен иметь случайное значение `border-radius` (от 0 до 50 пикселей) и случайное число внутри (от 0 до 100).

### Виртуальная Прокрутка

- Реализовать виртуальную прокрутку для оптимизации отображения большого количества данных.
- Компонент должен отображать только видимые строки, а не все 100000 строк одновременно.

### Интерактивность

- При наведении на квадрат, он должен уменьшаться до 80% от своего исходного размера.
- При убирании курсора с квадрата, он должен возвращаться к своему исходному размеру.

### Стиль и Вёрстка

- Строки должны быть расположены вертикально, а квадраты в строках — горизонтально.
- Размер каждого квадрата должен быть 50x50 пикселей.
- Между квадратами должно быть расстояние в 5 пикселей.

## Критерии Оценки

### Корректность

- Компонент правильно генерирует и отображает 100000 строк данных.
- Виртуальная прокрутка работает корректно, и компонент отображает только видимые строки.

### Производительность

- Компонент должен работать без заметных задержек и торможений при прокрутке.

### Интерактивность

- Квадраты корректно уменьшаются при наведении и возвращаются к исходному размеру при убирании курсора.

### Читаемость и Поддерживаемость Кода

- Код должен быть хорошо организован, читаем и документирован.
- Компонент должен быть легко поддерживаемым и расширяемым.

### Стиль и Вёрстка

- Квадраты и строки должны быть правильно выровнены.
- Стили должны быть написаны аккуратно и соответствовать требованиям.

### Реализация Виртуальной Прокрутки

- Виртуальная прокрутка должна быть реализована с использованием правильных методов Vue.js.
- Компонент должен правильно вычислять видимые строки в зависимости от положения прокрутки.
