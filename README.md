Висновки щодо обчислення інтеграла методом Монте-Карло

Завдання та вхідні дані

Задача полягала в обчисленні визначеного інтеграла функції за допомогою методу Монте-Карло. Для порівняння точності результатів використовувалася також бібліотека SciPy, зокрема функція quad для аналітичного обчислення інтеграла.

Обчислення методом Монте-Карло

Для методу Монте-Карло було згенеровано 100,000 випадкових точок в прямокутній області, обмеженій графіком функції та межами інтегрування. Область під кривою була оцінена за допомогою відношення кількості точок, які опинились під кривою, до загальної кількості точок. Отримана площа була помножена на площу прямокутника для обчислення значення інтеграла.

Результати та порівняння

Результат обчислення інтеграла методом Монте-Карло складає 2.665, тоді як використання функції quad дало значення 2.666666666666667 з оцінкою помилки 2.960594732333751e−14. Помилка методу Монте-Карло може залежати від кількості випадкових точок, і, можливо, з додатковим налаштуванням кількості точок можна досягти більшої точності.

Висновки

Метод Монте-Карло надав досить точний результат порівняно з аналітичним обчисленням, але точність може залежати від кількості випадкових точок. За результатами порівняння можна стверджувати, що метод Монте-Карло в даному випадку надає прийнятний результат, особливо з урахуванням його простоти та використання обчислювальних ресурсів.

