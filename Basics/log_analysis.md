# Практическое задание 1

Отработка тем "списки", "словари", "генераторы", "строки", "файлы" под контролем преподавателя.

Анализ журнала (лог-файла).

Формат строки:
`date - module [ type   ] message`

Если строка не удовлетворяет шаблону -- её надо пропустить.

Анализ:

1. Сформировать словарь с ключами -- значениями поля `module` и значениями -- словарями с ключами -- типами сообщений `(DEBUG, INFO, WARNING, ERROR)` и значениями -- количествами сообщений каждого типа.
То есть на выходе должен быть словарь вида:
`{'module1': {'DEBUG': 0, 'INFO': 121, 'WARNING': 1, 'ERROR': 0}, 'module2': {...}}`

2. Найти, сколько раз в логе встречается строка с заданной подстрокой `fun:`.

3. \* Сформировать список количества найденных мод (в строках типа **Found 307 modes ...**)

