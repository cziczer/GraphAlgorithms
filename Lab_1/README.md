# Lab 1: Rozgrzewka
W ramach laboratorium należy zaimplementować program (lub kilka jego wariantów) rozwiązujący zadanie “przewodnik turystyczny”.

Zadanie
Dany jest graf nieskierowany G = (V,E), funkcja c: E -> N dająca wagi krawędziom, oraz wyróżnione wierzchołki s i t. Należy znaleźć scieżkę z s do t taką, że najmniejsza waga krawędzi na tej ścieżce jest jak największa.

Podejścia algorytmiczne:

wykorzystanie struktury find-union
wyszukiwanie binarne + przegląd grafu metoda BFS/DFS
algorytm a’la Dijkstra
W ramach laboratorium należy zaimplementować jeden, dowolny z tych algorytmów (a jeśli zostanie czas, to także kolejne)

Proponowana kolejność prac
W ramach laboratorium proponujemy realizować zadanie w następujących krokach

napisz skrypt wczytujący przykładowy graf i wypisujący krawędzie
zaimplementuj funkcje find i union realizujące zbiory rozłączne (przetestuj je, np. z poziomu konsoli)
zaimplementuj sortowanie krawędzi grafu malejąco
zaimplementuj rozwiązanie zdania oparte o find-union

zaimplementuj konwersję grafu na listy (zbiory) sąsiedztwa
zaimplementuj algorytm DFS
połącz oba algorytmy w rozwiązanie zadania (najpierw możesz budować grafy osobno dla każdej minimalnej dopuszczalnej wagi, potem zmodyfikuj DFS tak, żeby korzystał tylko z odpowiednich krawędzi, a na końcu zrealizuj wyszukiwanie binarne)
zamień DFS na BFS zrealizuj rozwiązanie oparte o algorytm Dijkstry

[Pełna treść zadania](https://faliszew.github.io/algograf/lab1)
