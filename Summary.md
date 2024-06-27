# Podsumowanie zadania

# W trakcie wykonywania zadania trzeba było zmierzyć się z zagadnieniami:

## 1. Własciwa struktura kataloogów i plików:

Po pierwsze należało okreslić gdzie i jakie pliki mają sie znajdować.
Wypracowana struktura poniżej.
```
## goit-js-hw-02/
├── src/
│ ├── calculate.js
│ ├── checkAge.js
│ │
│ ├── support/
│ └── jasmine.json
│
└── spec/
├── calculate.test.js
└── checkAge.test.js
```

 ## 2. Instalacja Jasmine globalnie na komputerze w `VScode`:

Aby zainstalować Jasmine globalnie w terminalu `Node.js` wpisujemy komendę:

`npm install -g jasmine`

Tworzymy projekt, w moim przypadku `myProject` i z poziomu tego katalogu będziemy inicjalizować `Jasmine` w projekcie.

Ale wcześniej trzeba:

 ## 3. Zmiana polityki wykonywania w `Microsoft PowerShell` 
z poziomu administratora komendą `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned`

![](https://github.com/EwaRRPoland/goit-js-hw-02/blob/ffe5fbec1e704b5deb0f00696a6576ad16574641/assets/PowerShell.jpg)

 ## 4. Teraz możemy inicjalizować ``Jasmine`` w projekcie komendą w ``VScode``:

``jasmine init``

## 5. Uruchomienie testów w terminalu w `VScode`
 
Testy uruchamiamy komendą:

``jasmine``

![](https://github.com/EwaRRPoland/goit-js-hw-02/blob/27874097ec2b3829a0d3686a0de621c4ae1993cb/assets/jasmine2.jpg)

## 6. Analiza wyników testów:

Komentarz z wyników testów automatycznych (unit testów) w środowisku Jasmine:

``Randomized with seed 16311``: Oznacza, że testy były uruchamiane w trybie losowym (randomized), a ziarno (seed) użyte do generowania tych losowych wyników to 16311.

``Started``: Informuje, że testy zostały rozpoczęte.

``6 specs, 0 failures``: Oznacza, że przetestowano 6 specyfikacji (testów) i nie wystąpiły żadne błędy (failures).

``Finished in 0.019 seconds``: Czas, w jakim testy zostały zakończone.

``Randomized with seed 16311 (jasmine --random=true --seed=16311)``: To dodatkowe potwierdzenie, że testy były uruchamiane w trybie losowym z użyciem ziarna 16311.

