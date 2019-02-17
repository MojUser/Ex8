##Zadania Projektowe
1. Napisz funkcję, która przyjmie dwie mapy a następnie wypisze:
    1. Wszystkie klucze z pierwszej mapy, których nie ma w drugiej
    2. Wszystkie klucze z pierwszej mapy dla których w drugiej mapie są inne wartości.
2. Napisz metodę która w `TreeMap` wyszuka następny klucz niższy od podanego jako argument
3. Napisz własną klasę `Option<T>`, która opakowywała obiekt typu `T`. Wykorzystaj typy generyczne. Klasa option pozwala na unikanie stosowania wartości null.
    1. Klasa powinna mieć metody `get()`, `set()`, `isEmpty()` oraz konstruktor pozwalający na stworzenie opcji z danego obiektu a także domyślny konstruktor tworzący pustą opcję.
    2. Metoda `get()` powinna zwrocic obiekt, który opakowuje opcja, jeśli jest opcja jest pusta to powinien zostać rzucony wyjątek.
 4. Napisz aplikację, która będzie tworzyła listę bez podania typu generycznego.
    1. Dodaj do klasy kilka Stringów.
    2. Dodaj do klasy kilka liczb całkowitych.

2. Napisz prostą klasę  Kalkulator, która pozwoli na wykonanie wszystkich czterech podstawowych operacji matematycznych na liczbach i zwrócenie wyniku tych operacji. UWAGA! Aplikacja powinna zadziałać na wszystkich typach liczbowych w tym także tych z pakietu `java.util.concurrent.atomic`!