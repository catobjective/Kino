# Kino
Myślę, że nie ma sensu tworzenia pełnego klienta;
Niektóre elementy można pominąć, np:
-zarządzanie bazą pracowników
-zarządzanie salami / miejscami (dodawanie, usuwanie miejsc)

Wymagania funkcjonalne stawiane wobec klienta:
-Logowanie w oparciu o dane z bazy mySQL
-System autoryzacji / uprawnień - przy każdym logowaniu sprawdzana jest rola i na jej podstawie udostępniane są poszczególne moduły klienta
-Usecase:
zarządzania filmami w bazie
zarządzania seansami
sprzedaży/rezerwacji biletów
do sprawdzania biletów 

Myślę, że każdy z tych usecasów które chcemy wprowadzić można umieścić jako osobny panel/okno/frame/

Może byśmy dodali jakiś system generujący bilet dla bajeru? Że jakiś PDF by wyrzucał czy coś. Bajer by był. 

Opis środków technicznych:
-C#
-Moduł współpracy z API IMDb - Metadane filmów będziemy dodawać z IMDb do bazy - ZROBIONE
-Trzeba napisać moduł łączenia z bazą mySQL
-Trzeba uwzględnić system transakcji - w systemie rezerwacji biletów - aby nie sprzedać dwa razy tego samego miejscami




