# Raport dot. Przypadków Użycia w Systemie
*autor: Tymoteusz Gryszkalis*

### 6.1 Zrozumienie wymagań
#### Elementy systemu

- **Aplikacja kliencka (front-end)**: Ta strona będzie interfejsem użytkownika, z którym będą wchodzić w interakcję użytkownicy końcowi. Może to być aplikacja webowa dostępna przez przeglądarkę internetową lub aplikacja mobilna na urządzeniach Android lub iOS.

- **Serwer aplikacji (back-end)**: To serwer, który obsługuje logikę biznesową i przetwarza żądania użytkowników. Zarządza on komunikacją między aplikacją kliencką a bazą danych oraz innymi zewnętrznymi systemami, jeśli to konieczne.

- **Baza danych**: W systemie będzie potrzebna baza danych do przechowywania danych użytkowników, produktów, zamówień itp. Serwer aplikacyjny będzie komunikował się z bazą danych w celu pobierania i aktualizowania danych.

- **Systemy zewnętrzne**: Jeśli aplikacja wymaga integracji z zewnętrznymi systemami, takimi jak systemy płatności online lub systemy monitorowania, będą one komunikować się z serwerem aplikacyjnym poprzez odpowiednie interfejsy API.

#### Komunikacja elementów systemu:

- Aplikacja klienta - Serwer aplikacji:
  - Aplikacja klienta wysyła zapytania do serwera aplikacji w celu pobierania danych oraz przetwarzania operacji, takie jak składanie zamówień czy przeglądanie produktów.
  - Serwer aplikacji odpowiada na zapytania klienta, przetwarzając żądania i dostarczając odpowiednie dane.
- Serwer aplikacji - Baza danych:
  - Serwer aplikacji komunikuje się z bazą danych w celu pobierania, aktualizowania i przechowywania danych użytkowników, produktów, zamówień itp.
  - Baza danych odpowiada na zapytania serwera aplikacji, dostarczając lub aktualizując potrzebne dane.

### 6.2 Identyfikacja głównych aktorów
- **Użytkownicy aplikacji webowej i mobilnej**: Użytkownicy są zainteresowani minimalnym czasem ładowania aplikacji oraz otrzymywaniem szybkich odpowiedzi na swoje zapytania. Są również zainteresowani otrzymywaniem natychmiastowych powiadomień. Oczekują, że system będzie szyfrował wszystkie dane przesyłane przez niego i przechowywane w nim, aby ich dane osobowe były bezpieczne. Oczekują także, że system będzie w stanie szybko i efektywnie przywracać się do poprawnego stanu po wystąpieniu awarii, oraz zapewniał skuteczne mechanizmy monitorowania aktywności oraz raportowania wszelkich nieprawidłowości. Muszą być informowani o przerwach serwisowych z odpowiednim wyprzedzeniem. Muszą też być świadomi, że w przypadku awarii systemu, aplikacja automatycznie przechodzi na backupowe środowisko, aby minimalizować przestoje. Oczekują, że aplikacja będzie działać zgodnie z tą specyfikacją, zapewniając spójne doświadczenie użytkownika na wszystkich platformach.
- **Dostawcy**: Dostawcy korzystają z systemu w celu dostarczania usług lub towarów. Są zainteresowani skalowalnością systemu oraz szybkim przetwarzaniem płatności za zamówienia.
- **Administratorzy systemu**: Administratorzy mają dostęp do zaawansowanych funkcji systemowych i są odpowiedzialni za zarządzanie rolami dostępu, monitorowanie aktywności, oraz zapewnianie bezpieczeństwa systemu. Administratorzy muszą skutecznie monitorować aktywność, rejestrując istotne operacje i zdarzenia w systemie. Ponadto muszą zarządzać mechanizmami zapobiegającymi utracie danych, takimi jak regularne backupy i przywracanie danych, oraz definiować klarowne i skuteczne zarządzanie dostępem do zasobów, oparte na zdefiniowanych rolach i uprawnieniach. Administratorzy muszą zaplanować przerwy serwisowe, które muszą być komunikowane użytkownikom z trzydniowym wyprzedzeniem. Ponadto, w przypadku awarii systemu, administratorzy muszą zapewnić automatyczne przejście aplikacji na backupowe środowisko w celu minimalizacji przestojów.
- **Potencjalni atakujący**: Aktorzy ci mogą próbować atakować system w celu uzyskania nieautoryzowanego dostępu do danych lub uszkodzenia systemu. System musi być zaprojektowany w taki sposób, aby skutecznie się bronić przed różnymi rodzajami ataków internetowych. Wymagane są skuteczne mechanizmy obronne, takie jak firewall, filtrowanie ruchu czy detekcja anomalii, aby chronić system przed różnorodnymi atakami, takimi jak próby ataków brute force, SQL injection, Cross-Site Request Forgery (CSRF) czy Cross-Site Scripting (XSS).
- **Zespół ds. obsługi technicznej**: Wymagane jest, aby zespół ds. obsługi technicznej monitorował i zarządzał przerwami serwisowymi oraz awariami systemu, zapewniając minimalizację przestojów i zapewniając, że procedury planowane są zgodnie z wymaganiami. Wymagane jest, aby system posiadał skuteczny system zarządzania błędami, który umożliwia szybkie wykrywanie, raportowanie i naprawę błędów. Ponadto, zespół ds. obsługi technicznej musi mieć dokumentowany plan awaryjny, który określa kroki do podjęcia w przypadku poważnych awarii, oraz regularnie przechodzić testy odpornościowe pod obciążeniem i w warunkach ekstremalnych.