# MatrixClass
Класс созданный для работы с матрицами
## Содержит следующие функции для работы с матрицами:
### Инициалиазиция:
1) Matrix A({{...}, {...}, ...}) с помощью двойного вектора
2) fromstream >> A с помоьщью файла
3) eye A(n) единичная матрица n x n
4) diagonal, upper, lower - матрицы созданные из уже сущесвующей матрицы А

### Операции над матрицами:
1) сложение A+B
2) вычитание A-B
3) умножение матриц A*B
4) вывод матрицы std::cout << A
5) адамарово произведение adamar(A,B)
6) A.T() - транспонирование
7) A.inv() обратная к А матрица
8) A.rank() - ранк матрицы
9) A.fbnorm() - норма фасбендера
10) A.det() - определитель матрицы
11) A.trace() - след матрицы
12) A.issquare() - проверка на квадратность
13) A/b - деление матрицы на число
14) A*b - умножение матрицы на число

