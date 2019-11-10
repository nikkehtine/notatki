# Notatki C++
[Kurs C++ Pasja Informatyki](https://www.youtube.com/watch?v=ErOzmh3BiXU&list=PLOYHgt8dIdoxx0Y5wzs7CFpmBzb40PaDo "Link do playlisty Mirosława Zelenta o C++")

## Dołączanie biblioteki
`#include <nazwa_biblioteki>`

(np. iostream - biblioteka strumieni wejścia i wyjścia)

## Przestrzeń nazw
`using namespace std;` używa przestrzeni nazw *standard*

## Funkcje
funkcja `main()` to tzw. *funkcja główna*

`return 0` kończy funkcję główną, a więc cały nasz program

## Pisanie po ekranie
`cout << "Napis" << endl`

* `cout` - wyświetla linię w konsoli
* `endl` - kończy linię
* `<<` - output
* `>>` - input
* `cin` - wczytuje znaki z klawiatury

## Zmienne
`int x` rezerwuje w pamięci miejsce na liczbę całkowitą *x*

* `int` - *integer*, liczba całkowita (integralna, niepodzielna)
* `string` - ciąg znaków

`=` - operator przypisania, używany do przypisywania wartości do zmiennej

## Warunki
```cpp
if(/*Warunki*/)
{
    //Instrukcja do wykonania w razie spełnionych warunków
}
else if(/*Warunki*/)
{
    //Instrukcja do wykonania w razie niespełnionych pierwszych warunków
}
else
{
    //Instrukcja do wykonania w razie niespełnionych obu warunków
}
```

## Operatory
### Arytmetyczne
* `+` - dodawanie
* `-` - odejmowanie
* `*` - mnożenie
* `/` - dzielenie
* `%` - reszta z dzielenia dwóch liczb całkowitych

### Relacyjne
* `<` - mniejszy
* `>` - większy
* `==` - równy
* `!=` - różny
* `>=` - większy lub równy
* `<=` - mniejszy lub równy

### Logiczne
* `&&` - **AND** - oba warunki naraz spełnione
* `||` - **OR** - przynajmniej jeden warunek spełniony
* `!` - odwraca wartość z *true* na *false* i odwrotnie
