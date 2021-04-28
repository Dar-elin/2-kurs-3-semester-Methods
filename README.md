# Методы программирования 
2 курс 3 семестр 

ЛБ 1 
Разработать классы для описанных ниже объектов. Включить в класс методы set (…), get (…), show (…). Определить другие методы.
Student: Фамилия, Имя, Отчество, Дата рождения, Адрес, Теле-фон, Факультет, Курс. Создать массив объектов. Вывести:
а) список студентов заданного факультета;
б) списки студентов для каждого факультета и курса;
в) список студентов, родившихся после заданного года.

ЛБ 2
Разработать перечисленные ниже классы. При разработке каждого класса возможны два варианта решения: а) данные-члены класса пред-ставляют собой переменные и массивы фиксированной размерности; б) память для данных-членов класса выделяется динамически.
«Комплексное число» – Complex. Класс должен содержать не-сколько конструкторов и операции для сложения, вычитания, умноже-ния, деления, присваивания. Создать два вектора размерности   из комплексных координат. Передать их в функцию, которая выполняет сложение комплексных векторов. 

ЛБ 3
При решении задач необходимо описать класс, который использу-ется для представления элементов динамической структуры данных. Затем разрабатывается класс для работы с используемой динамической структурой данных, которая при тестировании класса может быть по-строена путем ввода данных: a) с клавиатуры; б) из файла. Возможны два варианта решения:
а) динамическая структура данных постоянно хранится в памяти;
б) динамическая структура данных хранится в файле.
Создать класс для работы со стеком. Элемент стека – действи-тельное число. Применить класс для вывода возрастающих серий по-следовательности действительных чисел: a) в обратном порядке; б) в том же порядке (серия – упорядоченная последовательность макси-мальной длины).

ЛБ 4
Для разработки шаблонов классов можно использовать результаты выполнения лабораторных работ № 2 и № 3. При тестировании со-зданных шаблонов классов необходимо создавать объекты с различ-ными допустимыми значениями параметров шаблона (например, ком-поненты вектора могут быть целыми, действительными или комплекс-ными числами).
Создать шаблон класса для работы со стеком. Применить его для решения задач № 1 – 4 (лаб. работа № 3).

ЛБ 5
При выполнении данной работы необходимо определить базовый класс и производные от него классы. Предусмотреть передачу аргу-ментов конструкторам базового класса; использование виртуальных и перегруженных функций; обработку исключительных ситуаций.

Вариант А
В следующих заданиях требуется создать базовый класс (как вари-ант абстрактный базовый класс) и определить общие методы show ( ), get ( ), set ( ) и другие, специфические для данного класса. Создать производные классы, в которые добавить свойства и методы.
Часть методов переопределить. Создать массив объектов базового класса и заполнить объектами производных классов. Объекты произ-водных классов идентифицировать конструктором по имени или иден-тификационному номеру.
Вызвать метод show ( ) базового класса и просмотреть массив объ-ектов.
Использовать объекты для моделирования реальных ситуаций.
Создать базовый класс «Транспортное средство» и производные классы «Автомобиль», «Велосипед», «Повозка». Подсчитать время и стоимость пере¬возки пассажиров и грузов каждым транспортным средством.

Вариант Б
Создать класс Item (единица хранения в библиотеке), содержа-щий данные-члены: invNumber – инвентарный номер и taken – взято на руки или имеется в наличии, а также методы:
virtual void Show(); //показать  информацию о единице хранения
bool isAvailable(); // есть ли единица хранения в наличии ?
int GetinvNumber(); //возвращает инвентарный номер
void Take(); //  операция «взять»
void Return(); //  операция «вернуть»
Построить производные классы Book и Magazin. Класс Book со-держит данные-члены: author, title, publisher, year и методы: Author(); 
Title(); Publisher(); YearOf Publishing(); Show().
Класс Magazin включает данные-члены: volume; number; year; title и методы: Volume();  Title(); Number(); Year(); Show().

Задачи на 4-6

Задано множество точек. Провести окружность так, чтобы количе-ство точек внутри и вне круга различалось наименьшим образом.

Создать классы Point и Line. Объявить массив из   объектов класса Point. Создать функцию, определяющую, какие из объектов Point лежат по одну сторону от прямой и какие по разные. Реализовать для вводимых данных.
