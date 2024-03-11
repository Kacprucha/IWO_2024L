# Raport dot. Przypadków Użycia w Systemie
*autorzy: Wojciech Szade i Szymon Kopańko*

### 6.3 Lista Przypadków Użycia
1. **Synchronizacja**
2. **Powiadomienia**
3. **Wielojęzyczność**
4. **Posty**
5. **Recenzja**
6. **Polubienia**
7. **Zbieranie statystyk**
8. **Kredyty**
9. **Subskrypcje**
10. **Główna strona użytkownika**
11. **Wyszukiwanie**
12. **Zamówienia**
13. **Historia**
14. **Wystawianie produktów**
15. **Płatności**
16. **Konto premium**
17. **Status zamówienia**
18. **Konta**

### 6.4 Opis Przypadków Użycia
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
1. Użytkownik przechodzi do opcji wystawienia recenzji.
2. Wpisuje tekst recenzji oraz ocenę produktu/usługodawcy w skali 5 gwiazdek.
3. Potwierdza dodanie recenzji.

**Warunki końcowe:** Recenzja użytkownika jest widoczna na profilu produktu/usługodawcy.

#### Polubienia

**Przypadek użycia: Polubienie posta przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik przegląda posty na platformie.

**Opis:**
1. Użytkownik klika na przycisk "polubienia" pod postem.
2. System dodaje polubienie do danego posta.

**Warunki końcowe:** Post jest oznaczony jako polubiony przez użytkownika.

#### Zbieranie statystyk

**Przypadek użycia: Przeglądanie statystyk przez usługodawcę**

**Aktorzy:** Usługodawca

**Warunki początkowe:** Usługodawca jest zalogowany na swoje konto.

**Opis:**
1. Usługodawca przechodzi do sekcji ze statystykami.
2. Przegląda zebrane informacje, takie jak liczba polubień, recenzji, ilość zakupów, mapa z podziałem na regiony.
3. Analizuje zebrane dane w celu lepszego zrozumienia preferencji klientów i efektywniejszej promocji.

**Warunki końcowe:** Usługodawca ma dostęp do zbiorczych statystyk swojej działalności.

#### Kredyty

**Przypadek użycia: Wykorzystanie kredytów przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik posiada kredyty na swoim koncie.

**Opis:**
1. Użytkownik dokonuje zakupu produktu/usługi.
2. Wybiera opcję zapłaty za pomocą kredytów.
3. System potwierdza dokonanie płatności i odlicza odpowiednią ilość kredytów z konta użytkownika.

**Warunki końcowe:** Produkt/usługa zostaje opłacona za pomocą kredytów.

#### Subskrypcje

**Przypadek użycia: Subskrybowanie usługodawcy przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do profilu usługodawcy.
2. Wybiera opcję subskrypcji.
3. Potwierdza subskrypcję usługodawcy.

**Warunki końcowe:** Użytkownik subskrybuje usługodawcę i otrzymuje częstsze polecenia jego postów.

#### Główna strona użytkownika

**Przypadek użycia: Wyświetlanie rekomendacji dla użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. System analizuje ostatnie zakupy i subskrypcje użytkownika.
2. Na podstawie analizy generuje rekomendacje produktów/usług.
3. Użytkownik przegląda rekomendacje na swojej głównej stronie.

**Warunki końcowe:** Użytkownik ma dostęp do spersonalizowanych rekomendacji na swojej głównej stronie.

#### Wyszukiwanie

**Przypadek użycia: Wyszukiwanie usługodawców lub dań/diet**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do wyszukiwarki.
2. Wpisuje nazwę usługodawcy, dania lub diety.
3. Może stosować filtry i sortować wyniki wyszukiwania według różnych parametrów.
4. Przegląda wyniki wyszukiwania i wybiera interesujący produkt/usługodawcę.

**Warunki końcowe:** Użytkownik znajduje poszukiwany produkt/usługodawcę na podstawie wprowadzonych kryteriów.

#### Zamówienia

**Przypadek użycia: Składanie zamówienia przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przegląda dostępne dania od różnych usługodawców.
2. Dodaje wybrane dania do koszyka zamówień.
3. Wybiera opcję dostawy i płatności.
4. Potwierdza zamówienie.

**Warunki końcowe:** Zamówienie zostaje złożone i przekazane do realizacji.

#### Historia

**Przypadek użycia: Przeglądanie historii zamówień przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do sekcji historii zamówień.
2. Przegląda listę swoich poprzednich zamówień oraz subskrypcji.
3. Ma możliwość anulowania zamówienia, jeśli jego dostarczenie opóźniło się więcej niż 24 godziny.

**Warunki końcowe:** Użytkownik ma dostęp do historii swoich zamówień oraz subskrypcji.

#### Wystawianie produktów

**Przypadek użycia: Dodawanie produktu przez usługodawcę**

**Aktorzy:** Usługodawca

**Warunki początkowe:** Usługodawca jest zalogowany na swoje konto.

**Opis:**
1. Usługodawca przechodzi do opcji wystawiania nowego produktu.
2. Wpisuje dane produktu, takie jak nazwa, opis, cena.
3. Potwierdza dodanie produktu.

**Warunki końcowe:** Nowy produkt jest dostępny do zakupu dla użytkowników.

#### Płatności

**Przypadek użycia: Dokonywanie płatności przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma produkty w koszyku.

**Opis:**
1. Użytkownik przechodzi do opcji płatności.
2. Wybiera preferowany sposób płatności: blikiem, kartą, kredytem.
3. Potwierdza dokonanie płatności.

**Warunki końcowe:** Zamówienie jest opłacone, a produkty są przygotowane do dostawy.

#### Konto premium

**Przypadek użycia: Zakup konta premium przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
1. Użytkownik przechodzi do opcji zakupu konta premium.
2. Wybiera preferowany plan konta premium.
3. Potwierdza zakup konta premium.

**Warunki końcowe:** Użytkownik ma aktywowane konto premium i korzysta z jego dodatkowych funkcji.

#### Status zamówienia

**Przypadek użycia: Sprawdzanie statusu zamówienia przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma złożone zamówienie.

**Opis:**
1. Użytkownik przechodzi do sekcji statusu zamówienia.
2. Sprawdza aktualny status swojego zamówienia, czy jest w trakcie realizacji, dostarczania itp.

**Warunki końcowe:** Użytkownik ma aktualną informację o statusie swojego zamówienia.

#### Konta

**Przypadek użycia: Zarządzanie kontami**

**Aktorzy:** Administrator

**Warunki początkowe:** Administrator ma dostęp do panelu administracyjnego.

**Opis:**
1. Administrator może tworzyć, edytować i usuwać konta użytkowników i usługodawców.
2. Zarządza uprawnieniami kont, np. nadaje konto premium, blokuje konto za złamanie regulaminu itp.

**Warunki końcowe:** Administrator skutecznie zarządza kontami na platformie.
