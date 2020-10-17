## Zadanie 1
Napisz funkcję 
```go 
func suma(a, b int) int
```
Funkcja ma zwrócić sumę dwóch liczb.

## Zadanie 2

Napisz funkcję
```go 
func concatenate(s1,s2 []int]) []int
```
Funkcja ma zwrócić slice zawierający elementy z s1 i s2

## Zadanie 3
Napisz funkcję 
```go 
func is18(age int) bool
```
Funkcja ma zwrócić prawdę jeżeli age >= 18 false w przeciwnym wypadku

## Zadanie 4
Napisz funkcję
```go 
func printDividedBy4(n int)
```
Funkcja ma wypisać do konsoli wszystkie liczby od 1 do n podzielne przez 4

## Zadanie 5
Napisz funkcję
```go 
func filterEven(age []int) []int
```

Funkcja ma zwrócić  slice z liczbami nieparzystymi

## Zadanie 6
Utwórz structa *User* takich parametrach 
 * name -> string
 * lastName -> string
 * age -> int
 * isAdult -> bool

Napisz funkcję 
```go 
func NewUser(name, lastName string, age int) *User
```
Funkcja ma tworzyć nowy struct User, pole isAdult powinno być uzupełnione

## Zadanie 7
Do structa z zadania 6 dopisz nastepujące funkcje(tak aby były przypisane do structa)

```go 
func (u *User) ToString() string
```
Funkcja ma wypisać w jakimś sensownym formacie parametry danego Usera

==============

```go 
func (u *User) ChangeAge(newAge int)
```
Funkcja ma ustawić User.age na podaną wartość, ale dana wartość ma zawierać się w przedziale (0,120)