# Raport z doprecyzowania przypadków uzycia

*autor: Szymon Kopańko*

#### Główna strona użytkownika

**Przypadek użycia: Przeglądanie głównej strony użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do głównej strony swojego profilu.
2. System wyświetla spersonalizowany widok z informacjami o aktywnościach użytkownika, takimi jak posty, recenzje, statystyki.
3. Użytkownik może wchodzić w interakcje z elementami strony, takimi jak kliknięcie w post, przeczytanie recenzji, czy sprawdzenie statystyk.

**Warunki końcowe:** Użytkownik ma przegląd swojej aktywności i interakcji w serwisie na swojej głównej stronie profilu.

#### Wyszukiwanie

**Przypadek użycia: Wyszukiwanie produktów w aplikacji**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik wprowadza kryteria wyszukiwania w pole wyszukiwania.
2. System przetwarza zapytanie i wyświetla listę wyników pasujących do kryteriów wyszukiwania.
3. Użytkownik ma możliwość filtrowania i sortowania wyników wyszukiwania.

**Warunki końcowe:** Użytkownik znajduje produkty lub usługi zgodnie z wprowadzonymi kryteriami wyszukiwania.

#### Zamówienia

**Przypadek użycia: Składanie zamówienia przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma wybrany produkt.

**Opis:**
1. Użytkownik dodaje wybrane produkty do koszyka.
2. Użytkownik Przechodzi do podsumowania koszyka i weryfikuje wybrane produkty.
3. Użytkownik Wybiera opcję zamówienia i wypełnia formularz z danymi do wysyłki i płatności.
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie.
4. Jeżeli płatność się udała, system przetwarza zamówienie i wysyła potwierdzenie na adres email użytkownika.

**Warunki końcowe:** Zamówienie jest złożone i użytkownik oczekuje na dostawę.

#### Historia

**Przypadek użycia: Przeglądanie historii zamówień**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do sekcji historii zamówień.
2. System wyświetla listę zamówień wraz z ich szczegółami: datą zamówienia, status, kwotą i opcją szczegółów.
3. Użytkownik może przeglądać szczegóły każdego zamówienia, w tym status wysyłki i historię płatności.

**Warunki końcowe:** Użytkownik ma dostęp do pełnej historii swoich zamówień.

#### Płatności

**Przypadek użycia: Realizacja płatności za zamówienie**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik ma w koszyku produkty do zakupu.

**Opis:**
1. Użytkownik przechodzi do procesu płatności.
2. Wybiera preferowaną metodę płatności spośród dostępnych opcji (karta kredytowa, przelew bankowy, płatność mobilna).
3. Wprowadza niezbędne dane do realizacji płatności.
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie.
4. Jeżeli płatność się udała, system potwierdza płatność i czeka na autoryzację transakcji.
5. Po pomyślnej autoryzacji, system wysyła użytkownikowi potwierdzenie transakcji i aktualizuje status zamówienia.

**Warunki końcowe:** Płatność zostaje zrealizowana, a zamówienie jest przetwarzane do wysyłki. Użytkownik otrzymuje potwierdzenie płatności.

#### Konto premium

**Przypadek użycia: Zarządzanie kontem premium przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik posiada konto premium.

**Opis:**
1. Użytkownik wchodzi w ustawienia konta premium w swoim profilu.
2. Przegląda aktualny status subskrypcji, datę następnego odnowienia i dostępne plany.
3. Może wybrać opcję zmiany planu subskrypcji, przedłużenia aktualnej lub anulowania subskrypcji.
4. Po dokonaniu wyboru, użytkownik potwierdza zmiany.
5. System aktualizuje status subskrypcji i informuje użytkownika o zmianach.

**Warunki końcowe:** Użytkownik ma zaktualizowane ustawienia dotyczące konta premium zgodnie ze swoimi preferencjami.

#### Status zamówienia

**Przypadek użycia: Sprawdzanie statusu zamówienia przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik posiada co najmniej jedno aktywne zamówienie.

**Opis:**
1. Użytkownik wchodzi w sekcję historii zamówień na swoim koncie.
2. Wybiera zamówienie, którego status chce sprawdzić.
3. System wyświetla szczegółowe informacje o zamówieniu, w tym aktualny status, przewidywaną datę dostawy i historię zmian statusu.
4. Użytkownik może również zobaczyć informacje o śledzeniu przesyłki, jeśli są dostępne.

**Warunki końcowe:** Użytkownik jest poinformowany o aktualnym statusie swojego zamówienia.

#### Konta

**Przypadek użycia: Zarządzanie kontami użytkowników przez administratora**

**Aktorzy:** Administrator systemu

**Warunki początkowe:** Administrator ma dostęp do panelu administracyjnego.

**Opis:**
1. Administrator loguje się do panelu administracyjnego.
2. Przegląda listę kont użytkowników, może wyszukiwać konkretnych użytkowników po nazwie, emailu lub innym kryterium.
3. Może tworzyć nowe konta, edytować istniejące profile użytkowników lub dezaktywować konta.
4. Przy edycji, może zmieniać role użytkowników, resetować hasła lub aktualizować informacje profilowe.
5. Po dokonaniu zmian, system zapisuje aktualizacje.

**Warunki końcowe:** Administrator zarządza kontami użytkowników, zapewniając prawidłowe funkcjonowanie serwisu.

#### Subskrypcja diety

**Przypadek użycia: Założenie przez użytkownika subskrypcji na dietę**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zainteresowany dietą i zalogowany na swoje konto.

**Opis:**
1. Użytkownik wybiera opcję subskrypcji diety z dostępnych ofert.
2. System prezentuje formularz subskrypcji, gdzie użytkownik wybiera preferowany rodzaj diety, okres subskrypcji i szczegóły dotyczące dostawy.
3. Użytkownik przechodzi do płatności, wybierając preferowaną metodę i wprowadzając niezbędne dane.
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie.
4. Jeżeli płatność się udała, system przetwarza zamówienie i aktywuje subskrypcję.
5. Użytkownik otrzymuje potwierdzenie założenia subskrypcji diety oraz szczegóły dotyczące planu dostaw na podany adres.
6. System umożliwia użytkownikowi dostęp do sekcji z indywidualnym planem diety, poradami żywieniowymi i możliwością śledzenia postępów.

**Warunki końcowe:** Użytkownik posiada aktywną subskrypcję diety, z dostępem do zindywidualizowanych materiałów i wsparcia online.