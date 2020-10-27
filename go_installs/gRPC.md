# Instalacja GRPC

## MacOS
* w terminalu odpal: `brew install protobuf`
* wpisz `protoc`, jak uruchomi helpa to działa :)

## Windows
* kliknij tutaj [link](https://github.com/google/protobuf/releases)
* znajdź wersje z zipem pod windowsa np. `protoc-3.13.0-win64.zip` i pobierz
* wypakuj wszystko do `C:\proto3`
* W środku  folderu  *proto3* powinny wkleić się foldery **bin** i **include**
* Otwórz zmienne środowiskowe 
* Znajdź w zmiennych systemowych *Path* i dodaj tam `C:\proto3\bin`
* Odpal konsole i wpisz `protoc` aby zobaczyć czy działa


## Oba systemy

* w VSCode doinstaluj paczkę `vscode-proto3`
* clone repo [link]()
* odpal komendy z pliku `hello-proto/command.sh`
* odpal w jednym terminalu program z folderu `hello_server`
* odpal w kolejnym oknie terminalu program z folderu `hello_client`

## Linki pomocnicze 
[strona gRPC](https://grpc.io/docs/languages/go/)
[protoc install](https://grpc.io/docs/protoc-installation/)
[tutorial](https://tutorialedge.net/golang/go-grpc-beginners-tutorial/#prerequisites)