Реализован класс Stack со следующими методами:
isEmpty - проверка стека на пустоту. Метод возвращает True или False.
push - добавляет новый элемент на вершину стека. Метод ничего не возвращает.
pop - удаляет верхний элемент стека. Стек изменяется. Метод возвращает верхний элемент стека
peek - возвращает верхний элемент стека, но не удаляет его. Стек не меняется.
size - возвращает количество элементов в стеке.

Используя стек, написано решиние задачи на проверку сбалансированности скобок. 
Сбалансированность скобок означает, что каждый открывающий символ имеет соответствующий ему закрывающий, и пары скобок правильно вложены друг в друга. 
Сбалансированными последовательности будут следующие скобки:
(((([{}]))))
[([])((([[[]]])))]{()}
{{[()]}} 
Несбалансированными последовательности:
}{}
{{[(])]}}
[[{())}]
Программа ожидает на вход строку со скобками. На выход сообщение "Сбалансированно", если строка корректная и "Небалансированно", если строка составлена не верно.
