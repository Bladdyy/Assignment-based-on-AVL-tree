
## Assignment

W związku ze zmianami na szczytach władzy, Bajtazar został niedawno dyrektorem Bajtockich Linii Kolejowych (BKL). Aktualnie Bajtocja jest w ruinie i nie ma tam żadnych linii kolejowych. Bajtazar chciałby
zbudować pierwszą linię, służącą do przewozu towarów. Została zgłoszona pierwsza propozycja przebiegu trasy
i aby ocenić jej jakość, Bajtazar postanowił przeprowadzić pewną symulację. Bajtockie firmy zostały poproszone o zadeklarowanie skąd, dokąd i w jakim terminie chciałyby przesłać towar proponowaną linią kolejową.
Każde takie żądanie jest trójką liczb naturalnych (a, b, t). Ponadto, Bajtazar ustalił pewną liczbę k, służącą
do określania czy dwa punkty czasowe są sobie bliskie. Mówimy, że dwa żądania (a1, b1, t1) oraz (a2, b2, t2)
kolidują ze sobą, gdy przedziały [a1, b1] oraz [a2, b2] mają niepuste przecięcie, oraz gdy |t1 − t2| ≤ k.
Mając daną listę żądań oraz liczbę k, Bajtazar chciałby wiedzieć ile par żądań koliduje ze sobą. Pomóż
Bajtazarowi i napisz program, który realizuje to zadanie.

### Wejście
W pierwszym wierszu wejścia podane są dwie liczby całkowite: n, k (1 ≤ n ≤ 2 · 105, 1 ≤ k ≤ 109), gdzie njest liczbą żądań.
W każdym z kolejnych n wierszy znajduje trójka liczb naturalnych postaci ai, bi, ti oddzielonych spacjami,
oznaczająca i-te żądanie (1 ≤ ai, bi, ti ≤ 109, ai < bi). Może się zdarzyć, że pojawi się wiele identycznychżądań.
### Wyjście
Twój program powinien wypisać na wyjście jedną liczbę całkowitą równą liczbie par żądań, które kolidują ze
sobą.
### Przykład
Dla danych wejściowych:
4 2
1 5 1
4 8 3
10 15 6
3 7 4
poprawnym wynikiem jest:
2


### Self implemented AVL tree 
