# Lista Przypadków Użycia

*autor: Wojciech Szade*

1. **Synchronizacja**
2. **Powiadomienia**
3. **Wielojęzyczność**
4. **Posty**
5. **Recenzja**
6. **Polubienia**
7. **Zbieranie statystyk**
8. **Kredyty**
9. **Subskrypcje konta usługodawcy**
10. **Główna strona użytkownika**
11. **Wyszukiwanie**
12. **Zamówienia**
13. **Historia**
14. **Płatności**
15. **Konto premium**
16. **Status zamówienia**
17. **Konta**
18. **Subskrypcja diety**

### Opis Przypadków Użycia

#### Synchronizacja

**Przypadek użycia: Synchronizacja danych między stroną internetową a aplikacją mobilną**

**Aktorzy:** Użytkownik, Aplikacja mobilna, Strona internetowa

**Warunki początkowe:** Użytkownik jest zalogowany zarówno na stronie internetowej, jak i w aplikacji mobilnej.

**Opis:**
1. Użytkownik dokonuje zmiany danych na stronie internetowej lub w aplikacji mobilnej.
2. System automatycznie synchronizuje dane między obiema platformami.
3. Użytkownik może kontynuować pracę na dowolnej z platform, mając pewność, że jego dane są aktualne na obu.

**Warunki końcowe:** Dane użytkownika są zsynchronizowane między aplikacją mobilną a stroną internetową.

#### Powiadomienia

**Przypadek użycia: Zarządzanie powiadomieniami**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik zalogowany na swoim koncie.

**Opis:**
1. Użytkownik przechodzi do ustawień powiadomień.
2. Może zaznaczyć preferowane rodzaje powiadomień, które chce otrzymywać.
3. Użytkownik może również wyłączyć powiadomienia, jeśli nie chce ich otrzymywać.

**Warunki końcowe:** Użytkownik ma skonfigurowane powiadomienia zgodnie z własnymi preferencjami.

#### Wielojęzyczność

**Przypadek użycia: Wybór języka interfejsu**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik otwiera interfejs aplikacji.

**Opis:**
1. Użytkownik przechodzi do ustawień języka.
2. Wybiera preferowany język spośród dostępnych opcji: polski, angielski, ukraiński.
3. Interfejs aplikacji automatycznie zmienia się na wybrany język.

**Warunki końcowe:** Interfejs aplikacji jest wyświetlany w wybranym przez użytkownika języku.

#### Posty

**Przypadek użycia: Dodawanie posta przez usługodawcę**

**Aktorzy:** Usługodawca

**Warunki początkowe:** Usługodawca jest zalogowany na swoje konto.

**Opis:**
1. Usługodawca przechodzi do opcji dodawania nowego posta na swoim profilu.
2. Wpisuje treść posta oraz dodaje zdjęcia i hasztagi.
3. Potwierdza dodanie posta.

**Warunki końcowe:** Nowy post usługodawcy jest widoczny na jego profilu dla użytkowników.

#### Recenzja

**Przypadek użycia: Dodawanie recenzji przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i posiada zakupiony produkt.

**Opis:**
1. Użytkownik przechodzi do opcji wystaw

iania recenzji danego produktu.
2. Wpisuje treść recenzji oraz przyznaje ocenę produktowi.
3. Potwierdza dodanie recenzji.

**Warunki końcowe:** Recenzja użytkownika jest widoczna na stronie produktu dla innych użytkowników.

#### Polubienia

**Przypadek użycia: Polubienie posta przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przegląda posty innych użytkowników.
2. Klikając na przycisk "polubienia", potwierdza swoje zainteresowanie postem.

**Warunki końcowe:** Post otrzymuje nowe polubienie od użytkownika.

#### Zbieranie statystyk

**Przypadek użycia: Zbieranie statystyk dotyczących aktywności użytkowników**

**Aktorzy:** Administrator systemu

**Warunki początkowe:** System działa i użytkownicy wykonują różne czynności.

**Opis:**
1. System monitoruje aktywność użytkowników, taką jak liczba logowań, dodanych postów, recenzji, zakupów itp.
2. Zbierane są dane dotyczące aktywności w określonym przedziale czasowym.
3. Dane te są przechowywane i mogą być wykorzystane do analizy i raportowania.

**Warunki końcowe:** Administrator ma dostęp do statystyk dotyczących aktywności użytkowników.

#### Kredyty

**Przypadek użycia: Zakup kredytów przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do opcji zakupu kredytów.
2. Wybiera pakiet kredytów, który chce zakupić.
3. Realizuje płatność za pomocą wybranej metody płatności.

**Warunki końcowe:** Kredyty są dodane do konta użytkownika po zakończeniu transakcji.

#### Subskrypcje

**Przypadek użycia: Subskrypcja usługi premium przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do opcji subskrypcji usługi premium.
2. Wybiera plan subskrypcji, który najlepiej odpowiada jego potrzebom.
3. Realizuje płatność za pomocą wybranej metody płatności.

**Warunki końcowe:** Użytkownik uzyskuje dostęp do funkcji premium po zakończeniu transakcji.

#### Główna strona użytkownika

**Przypadek użycia: Przeglądanie głównej strony użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do głównej strony swojego profilu.
2. Przegląda informacje o swoich aktywnościach, postach, recenzjach itp.

**Warunki końcowe:** Użytkownik ma dostęp do podsumowania swojej aktywności na głównej stronie profilu.

#### Wyszukiwanie

**Przypadek użycia: Wyszukiwanie produktów w aplikacji**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik wpisuje kryteria wyszukiwania w pole wyszukiwania.
2. System wyświetla wyniki pasujące do podanych kryteriów.

**Warunki końcowe:** Użytkownik widzi wyniki wyszukiwania i może przejść do szczegółów produktów.

#### Zamówienia

**Przypadek użycia: Składanie zamówienia przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i znajduje się na stronie produktu.

**Opis:**
1. Użytkownik wybiera produkt, który chce zamówić.
2. Dodaje produkt do koszyka lub przechodzi od razu do procesu zamawiania.
3. Podaje dane niezbędne do zrealizowania zamówienia.
4. Potwierdza zamówienie.

**Warunki końcowe:** Zamówienie jest złożone i widoczne w historii zamówień użytkownika.

#### Historia

**Przypadek użycia: Przeglądanie historii zamówień**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do historii zamówień w ustawieniach konta.
2. Przegląda listę wcześniej złożonych zamówień.
3. Może sprawdzić szczegóły każdego zamówienia, w tym status dostawy.

**Warunki końcowe:** Użytkownik ma dostęp do historii swoich zamówień.

#### Płatności

**Przypadek użycia: Realizacja płatności za zamówienie**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma produkty w koszyku.

**Opis:**
1. Użytkownik przechodzi do opcji realizacji płatności.
2. Wybiera metodę płatności i wprowadza niezbędne dane.
3. Potwierdza płatność.

**Warunki końcowe:** Płatność za zamówienie zostaje zrealizowana, a użytkownik otrzymuje potwierdzenie transakcji.

#### Konto premium

**Przypadek użycia: Zarządzanie kontem premium przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma aktywną subskrypcję premium.

**Opis:**
1. Użytkownik przechodzi do ustawień konta.
2. Zarządza opcjami związanymi z subskrypcją premium, takimi jak przedłużenie subskrypcji, zmiana planu itp.

**Warunki końcowe:** Użytkownik ma kontrolę nad swoją subskrypcją premium.

#### Status zamówienia

**Przypadek użycia: Sprawdzanie statusu zamówienia przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i posiada złożone zamówienia.

**Opis:**
1. Użytkownik przechodzi do historii zamówień.
2. Wybiera konkretne zamówienie, którego status chce sprawdzić.
3. Przegląda informacje dotyczące statusu zamówienia, np. "w trakcie realizacji", "wysłane", "dostarczone".

**Warunki końcowe:** Użytkownik jest poinformowany o bieżącym statusie swojego zamówienia.

#### Konta

**Przypadek użycia: Zarządzanie kontami użytkowników przez administratora**

**Aktorzy:** Administrator systemu

**Warunki początkowe:** Administrator jest zalogowany do panelu administracyjnego systemu.

**Opis:**
1. Administrator ma możliwość przeglądania listy wszystkich kont użytkowników.
2. Może dodawać nowe konta, edytować istniejące lub usuwać nieaktywne konta.
3. Ma dostęp do danych użytkowników oraz może zarządzać nimi zgodnie z polityką systemu.

**Warunki końcowe:** Administrator ma kontrolę nad kontami użytkowników w systemie.

#### Subskrypcja diety

**Przypadek użycia: Założenie przez użytkownika subksrypcji na dietę**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik wybiera interesującą go ofertę diety.
2. System wyśwetla użytkownikowi formularz subskrypcji.
3. Użytkownik wybiera okres subskrypcji: dzień, tydzień, miesiąc.
4. System przekierowuje użytkownika do formularza płatności
5. Użytkownik wybiera opcję dostawy i płatności.
6. System wyświetla dane subskrypcji.
7. Użytkownik akcpetuje dokonanie subskrypcji.