# infa2 

**4 ПАРАГРАФ**

**ВОПРОСЫ**

1) **Структурировать информацию** - значит привести ее в порядок для удобного решения задачи, а точнее, распределить по определенным группам и установить между ними логическую связь. Оно нужно для упрощения понимания основных элементов , из которых состоит весь массив информации, а также логики взаимосвязанности этих элементов.
2) **Алфавитный порядок** – это способ упорядочивания слов по первым буквам в соответствии с алфавитом. Если начальные символы совпали, то сравнивают эти символы до тех пор, пока не будет найдено обоснование. Если одно слово начинается с другого (например, «кот» и «котенок»), то более короткое слово будет стоять раньше.
3) **Оглавление** – это список разделов и разделов книги с указанием страниц, что позволяет быстро перейти к основному содержанию.
**Словарь** – это список терминов с их определениями. Употребляется для поиска результатов слов и понятий.
**Индекс** – это алфавитный список тем, имен, мест и др. с заглавными страницами, где они упоминаются. Помогает в быстром результате поиска упомянутых упоминаний. Эти средства соответствуют своей функции: оглавление помогает ориентироваться в книгах, словарь терминов, **индекс** позволяет быстро искать информацию на страницах.
4) **Перечислением**: {1, 2, 3}
**По правилам**: {x | x > 0} (все положительные числа). **Пустое множество** – это множество, не содержащее никаких элементов, обозначается как ∅ или {}.
5) **примеры множества**: числа, завод
6) Далее не допускается повторение элементов и не имеет порядка, в то время как линейный список упорядочен, и может сохранять повторяющиеся элементы.
7) **Матрица** - это математический термин, описывающий упорядоченный набер чисел или элементов, организованных в виде прямоугольной таблицы.
8) Табличные данные можно преобразовать в список вида «каждая строка — отдельный элемент»:
Первая строка: элемент1, элемент2, элемент3.
Вторая строка: элемент4, элемент5, элемент6.
9) **Иерархия** - структура, в которой одни элементы 'подчиняются' другим. Например, директор->главный инженер->Петров и т.д
10) Классификация организмов в биологии (планетарное дерево жизни).
Систематика минералов в геологии.
Классификация литературных жанров.
11) В информатике иерархическую культуру называют **деревом**
12) **Корень** - Самый первый узел, расположенный на верхнем уровне. **Лист** - Конечный узел, из которого не выходит ни одна дуга. **Родитель** - Два связанных узла, которые находятся на более высоком уровне. **Сын** - дочерняя вершина, унаследованная от родителя. **Предок** - Это узел, из которого можно перейти по стрелкам от узла-предка. **Потомок** - это узел, в который можно перейти по стрелкам от узла-предка.
13) A
/|\
BCDE
В этом дереве 5 вершин (A, B, C, D, E).
14) **Ребро** используется в двадцати неориентированных графах и соединяет две вершины, в то время как **дуга** используется в ориентированных графах и соединяет две вершины с указанием направления.
15) **Дерево** – это специальный вид графа, который является связным и не содержит циклов. Граф же может сохранять циклы и не обязательно быть связанным.
16) **Связный граф** – это граф, в котором существует путь между каждой парой вершин.
17) **Компонента связности** – это подграф, который является связным, и не удаётся добавить в него ещё одну вершину, не нарушив связность.
18) **Петля** – это ребро, соединяющее вершину самого с собой. В матрице соответствующие наличие петеля определяются по диагональным элементам: если диагональный элемент i-ой строки и i-ого столбца больше нуля, то в графе есть петля, связанная с вершиной i.
19) **Орграф** - дерево у которого стоят стрелки от верхних уровней к нижним. Он может служить моделью системы дорог с одностороним движением.
20) Б 

**ЗАДАНИЯ**

1) a) a -(b+c)*d
   б) a - (b-(c-d))
   в) (a-b) * (c-d)
   
2) а) ![image](https://github.com/user-attachments/assets/b77bfb37-478a-4a9c-b3e6-97831b321e9a)
   б) ![image](https://github.com/user-attachments/assets/a878b91c-b57a-46d0-b7cd-39ca2a8adc52) + * - * 2 a * 3 d c * 2 b,        2 a * 3 d * - c * 2 b * +
   в) ![image](https://github.com/user-attachments/assets/a8d2f589-68f6-4bce-ae18-6632dc80c814) * + + a b * 2 c d, a b + 2 c * + d *
   г) ![image](https://github.com/user-attachments/assets/6252de75-8b23-4360-af96-d4296cd61e16) - * 3 a * + * 2 b c d, 3 a * 2 b * c + d * -

3) a) 66, (12+6) * (7-3-1) + 12, + * + 12 6 - - 7 3 1 12
   б) 34, ((12-10) * (5+7)-7) * 2, * - * - 12 10 + 5 7 7 2
   в) 9, 5- (6+ (7- (8+9))), - 5 + 6 - 7 + 8 9
   г) 3, 5-(4-(3-(2-1))), - 5 - 4 - 3 - 2 1
   Дерево, соответствующее каждому заданному выражению, единственно. Оно определяется порядком вычисления значения выражения (порядком обхода узлов 'левый - правый - корень')


