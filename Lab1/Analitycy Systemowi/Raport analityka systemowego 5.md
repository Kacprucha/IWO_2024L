# Raport dot. Wizji Systemu
*autor: Sebastian Pawliński*

#### 5.5 Wymagania dotyczące niezawodności
- Aplikacja powinna działać cały czas z wyjątkiem przerw serwisowych. 

- Przerwy serwisowe:
    - muszą być planowane na godziny z najmniejszą liczbą zamówień - w przypadku braku danych powinny być wybierane godziny od 00:00 do 6:00,
	- nie mogą zaburzać dostępności systemu, tzn. mogą występować maksymalnie 3 razy w miesiącu i nie mogą trwać dłużej niż godzinę,
	- muszą być komunikowane użytkownikom z trzydniowym wyprzedzeniem. 		
	
- W przypadku awarii systemu, aplikacja powinna automatycznie przechodzić na backupowe środowisko, aby minimalizować przestój.

#### 5.6 Ograniczenia środowiskowe
Ograniczenia dzielimy według typu aplikacji:
- Aplikacja webowa:
Aplikacja ma oferować te same funkcjonalności oraz wyglądać identycznie w podanych przeglądarkach:
    - Google Chrome
	- Firefox
	- Opera
	- Safari
- Aplikacja mobilna:
Aplikacja musi działać w systemach Android od wersji 10 oraz w systemie IOS od wersji 11.
Niezależnie od typu aplikacji zestaw funkcjonalności musi być identyczny dla każdych z platform.