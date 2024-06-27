# goit-js-hw-02

## Zadanie 1

Napisz funkcję ``calculateRectangleArea``, która będzie obliczała pole prostokąta na podstawie długości i szerokości, przekazanych jako argumenty funkcji. Następnie przetestuj tę funkcję, używając testów jednostkowych w Jasmine lub innym narzędziu do testowania JavaScript.

```// calculate.js
function calculateRectangleArea(length, width) {
  return length * width;
}

module.exports = calculateRectangleArea;

```
## Zadanie 2

Napisz funkcję ``isAdult``, która będzie sprawdzała, czy osoba jest pełnoletnia, na podstawie przekazanego wieku. Funkcja powinna zwracać wartość logiczną (``true`` lub ``false``). Następnie przetestuj tę funkcję dla różnych przypadków.

```// checkAge.js
function isAdult(age) {
  return age >= 18;
}

module.exports = isAdult;

```

Po napisaniu funkcji i odpowiednich testów, uruchom je, aby sprawdzić poprawność działania. Upewnij się, że testy przechodzą, a funkcje zachowują się zgodnie z oczekiwaniami.

# Instrukcja 

Oto kroki do wykonania zadania domowego:

## Kroki do wykonania zadania z operacjami matematycznymi:

Stwórz nowy plik JavaScript o nazwie ``calculate.js``.
W pliku ``calculate.js``, zdefiniuj funkcję ``calculateRectangleArea``, która będzie przyjmować długość i szerokość prostokąta jako argumenty i zwracać ich pole.

```// calculate.js
function calculateRectangleArea(length, width) {
  return length * width;
}

module.exports = calculateRectangleArea;

```
Stwórz nowy plik testowy JavaScript o nazwie ``calculate.test.js``.
W pliku ``calculate.test.js``, użyj funkcji test z biblioteki testowej (np. ``Jest``), aby napisać testy dla funkcji ``calculateRectangleArea``.


Uruchom testy, aby sprawdzić, czy funkcja ``calculateRectangleArea`` działa poprawnie.

## Kroki do wykonania zadania z operatorem porównania:

Stwórz nowy plik JavaScript o nazwie ``checkAge.js``.
W pliku ``checkAge.js``, zdefiniuj funkcję ``isAdult``, która będzie sprawdzała, czy osoba jest pełnoletnia na podstawie wieku.

```// checkAge.js
function isAdult(age) {
  return age >= 18;
}

module.exports = isAdult;
```
Uruchom testy, aby sprawdzić, czy funkcja ``isAdult`` działa poprawnie.
Po wykonaniu powyższych kroków, sprawdź czy testy przechodzą, a funkcje zachowują się zgodnie z oczekiwaniami.
