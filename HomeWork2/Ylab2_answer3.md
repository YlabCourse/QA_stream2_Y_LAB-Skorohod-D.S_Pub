﻿Вопрос 3.

1 Приведите пример - ui-элемента из категории Input Controls — Текстовые поля

При разработке пользовательских интерфейсов у нас есть несколько элементов, которые мы постоянно используем. 

Элементы управления — это интерактивные элементы пользовательского интерфейса приложения, которые принимают ввод данных.

Они имеют разные типы и назначения, и разные тестовые случаи.

Самими распространёнными элементами ввода являются:

- Кнопки;
- Флажки;
- Радиокнопки;
- Переключает;
- Текстовые поля;
- Выпадающие списки;
- Списки;
- Кнопки раскрывающегося списка;
- Слайдеры.

Из всех данных элементов самым объемным являются текстовые поля, так как они могут принимать самые разные значения, комбинация этих значений приводит к разным результатам и, кроме этого, они часто имеют дополнительные функции такие как вставка шаблонов или скрытие/раскрытие пароля, пример текстового поля показан на рисунке 1.

![alt text](https://github.com/denistornado/Y_LAB-Skorohod-D.S/blob/main/HomeWork2/YlaB2_img3_1.jpg?raw=true)

Рисунок – 1 Текстовое поле

Это приводит к тому, что порой нам нужно использовать сразу несколько техник тест-дизайна

- Классы эквивалентности и граничные значение для проверки одного поля.
- Попарное тестирование для комбинации значений полей.
- Матрицу принятий решений для логики работы с результирующими данными.

Таким образом мы разделяем работу программы на несколько уровней:

1. Первый уровень – проверка элементов системы.
1. Второй уровень – проверка логики работы системы при комбинации данных.
1. Третий уровень – проверка бизнес-логики.

2 Является ли командная строка частью GUI? — Нет

Интерфейс командной строки (CLI) и графический интерфейс пользователя (GUI) — это два разных метода взаимодействия с компьютерными системами и программным обеспечением. CLI позволяет пользователям выполнять команды, вводя их в терминал или консоль, обеспечивая точный контроль и эффективность, но требуя знания синтаксиса команд. графический интерфейс предлагает визуальный интерфейс с такими элементами, как окна, значки и кнопки, что делает его более интуитивным и удобным для пользователя

Нужно понимать что несмотря на то что кажется что графический интерфейс лучше во всем, это не так, ибо бывают случай когда он избыточен и мешает путем потребления большего количества ресурсов системы и более медленным выполнение команд, кроме этого командная строка во многих системах (Linux как пример) позволяет создавать собственные многосложные команды (Alias как пример) для того чтобы сократить время, чаще всего с системами и программами у которых только консоль работают опытные пользователи, хотя и для новичков порог вхождение может быть высоким.

