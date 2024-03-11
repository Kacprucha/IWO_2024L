# Raport dot. Wizji Systemu
*autor: Filip Sosnowski*

#### 5.3 Wymagania dotyczące wydajności
- **System powinien osiągać minimalny czas ładowania aplikacji webowej i mobilnej**
    - **Opis:** Średni czas ładowania aplikacji webowej i mobilnej nie powinien przekroczyć 2 sekund, maksymalnie może wynosić 3 sekundy.
    - **Sposób pomiaru:** Pomiar czasu ładowania aplikacji. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
    - **Możliwy wynik pomiaru:** Czas mierzymy z dokładnością do 0.1 sekundy od 0.1 sekundy do 3 sekund (powyżej 3 sekund uznaje się, że system nie załadował aplikacji wystarczająco szybko).
    - **Oczekiwane wartości:** Czas ładowania aplikacji webowej i mobilnej nie przekraczający 2 sekund.
- **System powinien zapewniać jak najmniejszy czas odpowiedzi na zapytania użytkowników**
    - **Opis:** System powinien odpowiadać na zapytania użytkowników w czasie nie przekraczającym 0.5 sekundy, maksymalnie może wynosić 1 sekundę.
    - **Sposób pomiaru:** Pomiar czasu odpowiedzi na zapytanie użytkownika. Mierzymy czas dla 1000 prób i wyliczamy średnią z pomiarów. 
    - **Możliwy wynik pomiaru:** Czas mierzymy z dokładnością 0.01 sekundy od 0.01 sekundy do 1 sekundy (powyżej 1 sekundy uznaje się, że użytkownik nie otrzymał odpowiedzi od systemu wystarczająco szybko)  
    - **Oczekiwane wartości:** Średni czas odpowiedzi na zapytanie użytkownika nie przekracza 0.5 sekundy, najgorszy czas wynosi poniżej 1 sekundy.
- **System powinien być skalowalny**
    - **Opis:** System powinien sprawnie dostosowywać się do zmian w liczbie użytkowników i dostawców, utrzymując podobną wydajność. W przypadku wzrostu liczby użytkowników i dostawców o 100-krotność, system powinien efektywnie obsługiwać wszystkie operacje.
    - **Sposób pomiaru:** Ocena zdolności systemu do obsługi rosnącej liczby użytkowników. Testy wydajnościowe przeprowadzane w warunkach zbliżonych do produkcyjnych, mierzące czas odpowiedzi na operacje w zależności od liczby użytkowników korzystająych z aplikacji w tym samym momencie. 
    - **Możliwy wynik pomiaru:** System obsługuje wzrost liczby użytkowników i dostawców o 100-krotność, utrzymując stabilność oraz akceptowalne czasy odpowiedzi na zapytania (opisane wyżej).  
    - **Oczekiwane wartości:** Skuteczna skalowalność systemu przy wzroście do 100-krotności obecnej liczby użytkowników. System powinien utrzymywać średni czas odpowiedzi poniżej 0.5 sekundy oraz poniżej 1 sekundy przy maksymalnym obciążeniu.
- **System powinien szybko przetwarzać płatności za zamówienia**
    - **Opis:** Średni czas przetwarzania płatności, od chwili zatwierdzenia transakcji do uzyskania potwierdzenia, nie powinien przekraczać 5 sekund. Maksymalnie może być dwa razy dłuższy.
    - **Sposób pomiaru:** Pomiar czasu przetwarzania płatności online. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
    - **Możliwy wynik pomiaru:** Czas mierzony z dokładnością do 0.1 sekundy od zatwierdzenia do potwierdzenia, w przedziale od 0.1 sekundy do 10 sekund (powyżej 10 sekund uznaje się, że przetwarzanie płatności było zbyt długie).
    - **Oczekiwane wartości:** Czas przetwarzania płatności online nie przekraczający 5 sekund, w najgorszym przypadku w czasie mniejszym niż 10 sekund.
- **System powinien obsługiwać natychmiastowe powiadomienia**
    - **Opis:** Powiadomienia powinny być dostarczane użytkownikom w czasie nie przekraczającym 2 sekund po ich wygenerowaniu, maksymalnie w czasie dwa razy dłuższym.
    - **Sposób pomiaru:** Pomiar czasu dostarczania powiadomień do użytkowników. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
    - **Możliwy wynik pomiaru:** Czas dostarczania powiadomień mierzony z dokładnością do 0.1 sekundy, w przedziale od 0.1 do 2 sekund (powyżej 2 sekund uznaje się za opóźnienie w dostarczeniu powiadomienia).
    - **Oczekiwane wartości:** Czas dostarczenia powiadomień do użytkowników nie przekraczający 2 sekund, w najgorszym przypadku w czasie mniejszym niż 4 sekundy.

#### 5.4 Wymagania dotyczące bezpieczeństwa
- **System musi silnie szyfrować i bezpiecznie przechowywać dane osobowe użytkowników**
    - **Opis:** Dane osobowe klientów muszą być bezpiecznie przechowywane i przesyłane.
    - **Sposób pomiaru:** Audyty bezpieczeństwa, które mają na celu weryfikację skuteczności mechanizmów stosowanych do szyfrowania danych w systemie.
    - **Możliwy wynik pomiaru:** Ocena i potwierdzenie bezpieczeństwa danych osobowych użytkowników w systemie.
    - **Oczekiwane wartości:** Dane osobowe w systemie są szyfrowane oraz bezpiecznie przechowywane i przesyłane.
- **System musi wymagać silnego i bezpiecznego uwierzytelniania oraz autoryzacji**
    - **Opis:** Procesy uwierzytelniania i autoryzacji w systemie muszą być oparte na silnych i bezpiecznych mechanizmach.
    - **Sposób pomiaru:** Testy penetracyjne oceniające skuteczność procesów uwierzytelniania i autoryzacji w systemie. Skuteczność procesów uwierzytelniania i autoryzacji, mierzona jako procent poprawnych uwierzytelnień w stosunku do wszystkich prób.
    - **Możliwy wynik pomiaru:** Skuteczność mechanizmów obronnych powinna być blisko maksymalej wartości (minimum 99%). Potwierdzenie, że system w pełni stosuje bezpieczne i niezawodne uwierzytelnianie i autoryzację użytkowników.
    - **Oczekiwane wartości:** Autoryzacja i uwierzytelnienie w systemie są w pełni bezpieczne, oparte na silnych mechanizmach i zgodne z obowiązującymi standardami bezpieczeństwa.
- **System musi mieć zdefiniowane role dostępu**
    - **Opis:** W systemie muszą być zdefiniowane klarowne role dostępu, przypisane do różnych kategorii użytkowników (użytkownik, dostawca, administrator), z odpowiednimi uprawnieniami dostępu. Interakcje z zasobami systemu muszą być ściśle kontrolowane w zależności od przypisanych uprawnień i ról.
    - **Sposób pomiaru:** Testy w ramach różnych zasobów, które sprawdzą skuteczność mechanizmów zarządzania dostępem w kontekście różnych ról użytkowników. 
    - **Możliwy wynik pomiaru:**  Osiągnięcie 100% udanych prób dostępu do zasobów zgodnych z przydzielonymi uprawnieniami oraz 100% nieudanych prób, kiedy użytkownik nie ma wymaganych uprawnień.
    - **Oczekiwane wartości:** System zapewnia skuteczne zarządzanie dostępem, eliminując dostęp do zasobów dla użytkowników bez wymaganych uprawnień.
- **System musi być zabezpieczony przed atakami internetowymi**
    - **Opis:** System powinien posiadać skuteczne mechanizmy obronne, aby minimalizować ryzyko ataków internetowych (między innymi SQL injection, XSS, CSRF, DDoS, Brute Force).
    - **Sposób pomiaru:** Regularne testy bezpieczeństwa każdej kategorii, które mają na celu wykrycie podatności związanych z atakami. Wynik pomiaru stanowi procent udanych zatrzymanych ataków w stosunku do wszystkich prób.
    - **Możliwy wynik pomiaru:**  Skuteczność mechanizmów obronnych powinna być blisko maksymalej wartości (minimum 99%) dla każdej z kategorii badanych ataków.
    - **Oczekiwane wartości:** Skuteczna obrona przed atakami każdej kategorii, która wykazuje jak największą możliwą odporność na ataki internetowe.
- **System musi umożliwiać monitorowanie aktywności**
    - **Opis:** System musi skutecznie monitorować aktywność, co pozwoli na identyfikację nieprawidłowości i podejrzanej aktywności. Każda istotna operacja i zdarzenie w systemie powinny być rejestrowane w celu późniejszej analizy.
    - **Sposób pomiaru:** Mierzona jest liczba zdarzeń monitorowanych w logach systemowych. Wynikiem jest procent zarejestrowanych istotnych zdarzeń w systemie do ich spodziewanej liczby.
    - **Możliwy wynik pomiaru:**  System powinien rejestrować co najmniej 99% istotnych zdarzeń systemowych.
    - **Oczekiwane wartości:** Skuteczne monitorowanie aktywności zgodne z praktykami bezpieczeństwa. System rejestruje istotne wydarzenia w systemie oraz wykrywa istotne nieprawidłowości i działania podejrzane.