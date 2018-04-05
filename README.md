# NET.S.2018.Dementey.10
Tenth day .NET EPAM

### Задание 1

1. Для объектов класса Book (ISBN, автор, название, издательство, год издания, количество страниц, цена) (домашнее задание 8-ого дня)
- реализовать возможность строкового представления различного вида.

Например, для объекта со значениями ISBN = 978-0- 7356-6745- 7, AuthorName = Jeffrey Richter, Title = CLR via C#, Publisher = Microsoft Press, Year = 2012, NumberOPpages = 826, Price = 59.99$, могут быть следующие варианты:
- Jeffrey Richter, CLR via C#
- Jeffrey Richter, CLR via C#, Microsoft Press, 2012
- ISBN 13: 978-0- 7356-6745- 7, Jeffrey Richter, CLR via C#, Microsoft Press,2012, P. 826.
- Jeffrey Richter, CLR via C#, &quot;Microsoft Press&quot;, 2012
- ISBN 13: 978-0- 7356-6745- 7, Jeffrey Richter, CLR via C#, Microsoft Press, 2012, P. 826., $59.99.

<a href="https://github.com/Suorness/NET.S.2018.Dementey.08/tree/master/NET.S.2018.Dementey.08.BookLibrary/BooksLibrary/Models">
Смотреть 
</a>

### Задание 2

**Не изменяя класс Book**, добавить для объектов данного класса дополнительную возможность форматирования, изначально не предусмотренную классом.

<a href="https://github.com/Suorness/NET.S.2018.Dementey.08/tree/master/NET.S.2018.Dementey.08.BookLibrary/BooksLibrary/Formatters">
Смотреть 
</a>

### Задание 3

Для реализованных в пп. 1, 2 функциональностей разработать модульные тесты.

<a href="https://github.com/Suorness/NET.S.2018.Dementey.08/tree/master/NET.S.2018.Dementey.08.BookLibrary/BookLibrary.Tests">
Смотреть 
</a>

### Задание 4

Выполнить рефакторинг класса (с целью сокращения повторного кода) в алгоритмах Евклида (для рефакторинга использовать делегаты, рефакторинг возможен только в случае, когда все метод находятся в одном классе!). Интерфейс класса измениться не должен.

<a href="https://github.com/Suorness/NET.S.2018.Dementey.03-04/tree/master/GCDAlgorithm">
Смотреть 
</a>

### Задание 5

В класс с алгоритмом сортировки не прямоугольной матрицы, принимающим как компаратор интерфейс IComparer<int[]> добавить метод, принимающий как параметр делегат-компаратор, инкапсулирующий логику сравнения строк матрицы. Протестировать работу разработанного метода на примере сортировки матрицы, используя прежние критерии сравнения. Класс реализовать двумя способами, «замкнув» в первом варианте реализацию метода сортировки с делегатом на метод с интерфейсом, во втором – наоборот.

<a href="https://github.com/Suorness/NET.S.2018.Dementey.05/tree/master/SortingAlgorithm">
Смотреть 
</a>
