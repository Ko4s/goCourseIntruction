# Goopher haszator plików > 3.10.2020 - 10.10.2020

## Zadanie 

Napisać program który wczyta plik tekstowy i każdą jego linię zahashuje za pomocą sha256.
Funkcja powinna zwrócić slice typu string (`[]string`) gdzie każdy element jest hashem odpowiedniej lini z pliku. Program proszę napisać jako osobny moduł go (Patrz pierwsze zadanie domowe).

**Ustalenia:**
* program powinien mieć funkcję podobną do tej poniżej:
    * `func HashFile(path string) ([]string, error)`

**Wskazówki**
* Wykorzystaj z zajęć
    * funkcję otwierającą plik i zwracającą każdą linie
    * funkcję haszującą podany string 

**Uwaga!**
W przypadku jakiego kolwiek problemu, napisz na discord :)