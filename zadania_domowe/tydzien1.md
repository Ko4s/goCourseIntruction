# Początki bycia [GoPherem](https://blog.golang.org/gopher)

## Zadanie 1
Zadanie będzie polegało na sprawdzeniu czy dobrze zainstalowało się Go :)

1. Otwórz konsole systemową i wpisz w niej `go version`. Efektem powinno być coś w stylu: *go version go1.15 darwin/amd64*
2. Utwórz sobie na dysku Folder o dowolnej nazwie następnie otwórz go w vscode lub przejdź do niego za pomocą terminala
3. wpisz w terminal komendę: `go mod init tutaj_dowolna_nazwa`
    * przykład `go mod init github/lubieplacki/`
4. Sprawdź czy w twoim folderze powstał plik o nazwie go.mod
5. Utwórz plik `twoja_nazwa.go` i wklej do niego ten kod [link](https://gist.github.com/Ko4s/886172fa2cc0ae662a07d8976278b041)
6. Następnie uruchom ten program pisząc w konsoli `go run twoja_nazwa.go`
7. Zbuduj program komendą `go build twoja_nazwa.go` powinno utworzyć to plik o nazwie *twoja_nazwa*

## Zadanie 2
Na zajęciach omawialiśmy paczkę *flag* z go. Bazując na programie z zajęć zbuduj program który będzie przyjmował flagę typu  **apple** o domyślnej liczbie 0 i z dowolnym komunikatem pomocniczym.
Efektem programu powinno być wypisanie do konsoli napisu *Owca dostała # jabłek`*, gdzie **#** to ilość przekazaną za pomocą utworzonej flagi.
#### Przykład
* `go run main.go -apple=7` => *Owca dostała 7 jabłek*
* `go run main.go -apple=7` => *Owca dostała 1 jabłko*

## Zadanie 3 (opcjonalne)
Przebuduj program z zajęć z folderu class1 aby obsługiwał dzielenie dwóch liczb. Liczby przekaż jako argumenty do programu


## Efekt
* `go run main.go -dziel 5 2` => Wynik : 2.5
* `go run main.go -dziel 7 0` => Mała ch... nie dzielimy przez zero
* `go run main.go -dziel 4 2 1 4 owca` => Wynik: 2

