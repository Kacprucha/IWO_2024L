# Pomoc w realizacji widoków - uwagi do widoków

*autor: Szymon Ochnio*

Przygotowane widoki pokrywają się z opisami procesów biznesowych, jednak na moment formułowania niniejszych uwag zdają się nie pokrywać we wszystkich procesach biznesowych. Brakuje widoków dla wielu procesów biznesowych (na przykład obsługa płatności za zamówienie, czy wystawianie recenzji).

Pomijając brakujące widoki, te obecnie dodane są bardzo dobrze przygotowane i odzwierciedlają to, co zostało sformułowane w opisach procesów biznesowych. Nie mam do nich technicznych zastrzeżeń. 
Wyzwaniem może być implementacja integracji z zewnętrznymi dostawcami. 
Należy pamiętać o dodaniu walidacji pól na froncie - na projekcie widoku rejestracji widnieje przykład wyświetlenia komunikatu do jednego błędnie wypełnionego pola. 
Widoki są wizualnie spójne i emanują świeżością zachęcając do korzystania z aplikacji zarówno przez usługodawców jak i potencjalnych klientów. Interfejs zdaje się być intuicyjny i nie skrywa żadnych tajemnic przed użytkownikami.

Ogólnie rzecz biorąc, projekt interfejsu jest dobrze przygotowany i wydaje się spełniać wszystkie wymogi biznesowe. 
Można na nim bazować podczas tworzenia specyfikacji technicznej i planowania implementacji. 
Na plus zasługuje fakt, iż został zrealizowany z użyciem Atomic Design, co jest bardzo dobrą praktyką i z pewnością ułatwi, a także przyspieszy implementację poprzez ponowne wykorzystanie elementów interfejsu.