# Raport z doprecyzowania przypadków uzycia

*autor: Mateusz Sobol*

#### Synchronizacja

**Przypadek użycia: Synchronizacja danych między stroną internetową a aplikacją mobilną**

**Aktorzy:** Użytkownik, Aplikacja mobilna, Strona internetowa

**Warunki początkowe:** Użytkownik jest zalogowany zarówno na stronie internetowej, jak i w aplikacji mobilnej.

**Opis:**
1. Użytkownik dokonuje zmiany danych na stronie internetowej lub w aplikacji mobilnej.
2. System aktualizuje dane w bazie danych.
3. System wysyła zauktualizowane dane do wszystkich zalogowanych urządzeń powiązanych z tą zmianą.

**Warunki końcowe:** Dane użytkownika są zsynchronizowane między aplikacją mobilną a stroną internetową.

#### Powiadomienia

**Przypadek użycia: Zarządzanie powiadomieniami**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik zalogowany na swoim koncie.

**Opis:**
1. Użytkownik przechodzi do ustawień powiadomień.
2. System wyświetla okno ustawięń powiadomień.
3. Użytkownik ,oże zaznaczyć preferowane rodzaje powiadomień, które chce otrzymywać.
4. Użytkownik może również wyłączyć powiadomienia, jeśli nie chce ich otrzymywać.
5. Użytkownik po dokonaniu zmian może je zapisać.
6. System aktualizuje informacje o użytkowniku.

**Warunki końcowe:** Użytkownik ma skonfigurowane powiadomienia zgodnie z własnymi preferencjami.

#### Wielojęzyczność

**Przypadek użycia: Wybór języka interfejsu**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik otwiera interfejs aplikacji.

**Opis:**
1. Użytkownik przechodzi do ustawień języka.
2. System wyświetla okno ustawień języka
3. Użytkownik wybiera preferowany język spośród dostępnych opcji: polski, angielski, ukraiński.
4. Interfejs aplikacji zmienia się na wybrany język.

**Warunki końcowe:** Interfejs aplikacji jest wyświetlany w wybranym przez użytkownika języku.

#### Posty

**Przypadek użycia: Dodawanie posta przez usługodawcę**

**Aktorzy:** Usługodawca

**Warunki początkowe:** Usługodawca jest zalogowany na swoje konto.

**Opis:**
1. Usługodawca przechodzi do opcji dodawania nowego posta na swoim profilu.
2. Wpisuje treść posta oraz dodaje zdjęcia i hasztagi.
3. Potwierdza dodanie posta.
4.1 Jeżeli dodanie posta się udało system wyświetla nowy post i zapisuje ją do bazy danych.
5.1 System wysyła powiadomienia o nowym poście odpowiednim użytkownikom.
4.2 Jeżeli dodanie posta się nie udało system wyświetla komunikat o błędzie.

**Warunki końcowe:** Nowy post usługodawcy jest widoczny na jego profilu dla użytkowników.

#### Recenzja

**Przypadek użycia: Dodawanie recenzji przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i posiada zakupiony produkt.

**Opis:**
1. Użytkownik przechodzi do opcji wystawiania recenzji danego produktu.
2. System wyświetla odpowiednie pole do wpisania recenzji
2. Uzytkownik wpisuje treść recenzji oraz przyznaje ocenę produktowi.
3. Użytownik potwierdza dodanie recenzji.
4.1 Jeżeli dodanie recenzji się udało system wyświetla nową recenzje i zapisuje ją do bazy danych.
4.2 Jeżeli dodanie recenzji się nie udało system wyświetla komunikat o błędzie.

**Warunki końcowe:** Recenzja użytkownika jest widoczna na stronie produktu dla innych użytkowników.

#### Polubienia

**Przypadek użycia: Polubienie posta przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przegląda posty innych użytkowników.
2. Użytkownik klikając na przycisk "polubienia", potwierdza swoje zainteresowanie postem.
3. System wyświetla odpowiednią zmianę na interfejsie.

**Warunki końcowe:** Post otrzymuje nowe polubienie od użytkownika.

#### Zbieranie statystyk

**Przypadek użycia: Zbieranie statystyk dotyczących aktywności użytkowników**

**Aktorzy:** Administrator systemu

**Warunki początkowe:** System działa i użytkownicy wykonują różne czynności.

**Opis:**
1. System monitoruje aktywność użytkowników, taką jak liczba logowań, dodanych postów, recenzji, zakupów itp. i zapisuje je do bazy danych.
2. System regularnie usuwa przestarzałe dane.
3. Zalogowany użytkownik przechodzi do okna statystyk, 
4. System wyświetla statystyki dostępne dla użytkownika.

**Warunki końcowe:** Administrator ma dostęp do statystyk dotyczących aktywności użytkowników.

#### Kredyty

**Przypadek użycia: Zakup kredytów przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do opcji zakupu kredytów.
2. Użytkownik Wwybiera pakiet kredytów, który chce zakupić.
3. Użytkownik wybiera jedną z możliwych opcji płatnośći: Blik, Karta.
4. System wyswietla okno płatności.
5. Uzytkownik realizuje płatność za pomocą wybranej metody płatności.
5.2 Jeżeli płatność się nie udała system wyświetla komunikat o błędzie
5.1 Jeżeli się udała system przypisuje odpowiednią ilość kredytów do użytkownika i wyświetla komunikat o sukcesie.
6.1 System wyświetla nową ilość kredytów.

**Warunki końcowe:** Kredyty są dodane do konta użytkownika po zakończeniu transakcji.

#### Subskrypcje

**Przypadek użycia: Subskrypcja usługi premium przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do opcji subskrypcji usługi premium.
2. Użytkownik wybiera plan subskrypcji, który najlepiej odpowiada jego potrzebom.
3. Użytkownik wybiera jedną z możliwych płatnośći: Blik, Karta
4. System wyswietla okno płatności.
5. Użytkownik realizuje płatność za pomocą wybranej metody płatności.
6.2 Jeżeli płatność się nie udała system wyświetla komunikat o błędzie
6.1 Jeżeli płatność się udała system aktualizuje informacje o użytkowniku i wyświetla komunikat o sukcesie.

**Warunki końcowe:** Użytkownik uzyskuje dostęp do funkcji premium po zakończeniu transakcji.