Jest to proste GUI oparte na socketach, które symuluje zachowanie się zadanej płytki ewaluacyjnej.

Schemat uruchomienia:
javac Board.java
javac Host.java
java Board
java Host

Projekt został zrealizowany jako praca grupowa:

Paweł Śliwa: 
-opracowanie GUI płytki ewaluacyjnej wraz z obsługą zdarzeń
-opracowanie mechanizmu komunikacji opartego na socketach
-stworzenie schematow i opisów
-spięcie wszystkiego w jedną całość

Wiktor Sokół, M. Szot:
-wyświetlanie aktualnego poziomu wyjścia audio hosta na ośmiu diodach LED panelu

Maciek Szybecki, Łukasz Stolarz:
-kontrolowanie poziomu wyjścia audio hosta za pomocą potencjometru na panelu

Jakub Stawowy,Grzegorz Szydło:
-Wyświetlanie obciążenia systemu hosta, użycia pamięci hosta i  temperatury procesora hosta na wyświetlaczu LCD

Paweł Sikora,Mateusz Sitek:
-Klawisze skrótu S1… S8 uruchamiające dowolną akcję na hoście 

Paweł Szydło, Bartosz Szlęzak:
-Wyświetlanie opisów/pomocy klawiszy skrótów na wyświetlaczu LCD

Jakub Medalion,Mateusz Rychlik:
-Wyświetlanie na diodzie RGB panelu bieżącego uśrednionego koloru strumienia video odtwarzanego na hoście
					
Uwaga:
Użyte komendy linuksowe służące do pobierania wartości obciążenia hosta, użycia pamięci hosta oraz temperatury procesora, mogą działać inaczej dla różnych hostów. Aby program działał poprawnie, należy upewnić się, czy następujące komendy wyświetlają w konsoli odpowiednie wartości liczbowe:
