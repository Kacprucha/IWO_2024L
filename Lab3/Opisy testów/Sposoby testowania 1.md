# Sposób testowania przypadków użycia

*autor: Mateusz Czarnecki*

### **1. Synchronizacja**

**Opis testu:** Weryfikacja automatycznej synchronizacji danych między stroną internetową a aplikacją mobilną po dokonaniu zmian w jednej z platform.

- **Kroki:**
    1. Zaloguj się na stronie internetowej i w aplikacji mobilnej.
    2. Dokonaj zmiany danych na stronie internetowej.
    3. Sprawdź, czy dane zostały zaktualizowane w aplikacji mobilnej.
    4. Dokonaj zmiany danych w aplikacji mobilnej.
    5. Sprawdź, czy dane zostały zaktualizowane na stronie internetowej.
- **Miara testu:**
    - **Pozytywny wynik:** Dane są automatycznie i bezbłędnie synchronizowane między obiema platformami niezależnie od miejsca wprowadzenia zmian.
    - **Negatywny wynik:** Dane nie są synchronizowane lub są synchronizowane z opóźnieniem/ błędami.
    

### **2. Powiadomienia**

**Opis testu:** Sprawdzenie możliwości konfiguracji preferencji powiadomień przez użytkownika.

- **Kroki:**
    1. Zaloguj się na konto użytkownika.
    2. Przejdź do ustawień powiadomień.
    3. Zaznacz preferowane typy powiadomień i zapisz ustawienia.
    4. Wyłącz wszystkie powiadomienia i zapisz ustawienia.
    5. Sprawdź, czy system przestrzega zapisanych preferencji.
- **Miara testu:**
    - **Pozytywny wynik:** Użytkownik otrzymuje tylko wybrane powiadomienia lub żadne, jeśli wszystkie zostały wyłączone.
    - **Negatywny wynik:** Użytkownik otrzymuje niepożądane powiadomienia lub nie otrzymuje wybranych powiadomień.

### **3. Wielojęzyczność**

**Opis testu:** Weryfikacja zmiany języka interfejsu aplikacji na wybrany przez użytkownika.

- **Kroki:**
    1. Otwórz aplikację i przejdź do ustawień języka.
    2. Wybierz każdy z dostępnych języków i zaakceptuj zmianę.
    3. Sprawdź, czy cały interfejs aplikacji zmienia się na wybrany język.
- **Miara testu:**
    - **Pozytywny wynik:** Interfejs aplikacji poprawnie wyświetla się w każdym z wybranych języków.
    - **Negatywny wynik:** Części interfejsu nie zmieniają języka lub pojawiają się błędy w wyświetlaniu.

### **4. Posty**

**Opis testu:** Testowanie dodawania nowego posta przez usługodawcę.

- **Kroki:**
    1. Zaloguj się jako usługodawca.
    2. Dodaj nowy post, wprowadzając tekst, zdjęcia i hasztagi.
    3. Sprawdź, czy post jest widoczny na profilu usługodawcy.
- **Miara testu:**
    - **Pozytywny wynik:** Post jest poprawnie dodany i widoczny dla użytkowników.
    - **Negatywny wynik:** Post nie jest widoczny lub pojawiają się błędy podczas dodawania.

### **5. Recenzja**

**Opis testu:** Sprawdzenie procesu dodawania recenzji i oceny produktu/usługodawcy przez użytkownika.

- **Kroki:**
    1. Zaloguj się jako użytkownik, który posiada zakupiony produkt.
    2. Przejdź do opcji wystawienia recenzji dla zakupionego produktu/usługodawcy.
    3. Wpisz tekst recenzji oraz ocenę produktu/usługodawcy w skali 5 gwiazdek.
    4. Potwierdź dodanie recenzji.
    5. Sprawdź, czy recenzja jest widoczna na profilu produktu/usługodawcy.
- **Miara testu:**
    - **Pozytywny wynik:** Post jest poprawnie oznaczony jako polubiony przez użytkownika, a liczba polubień posta zwiększa się o 1.
    - **Negatywny wynik:** Polubienie nie jest rejestrowane, post nie jest oznaczony jako polubiony lub liczba polubień się nie zmienia.

### **6. Polubienia**

**Opis testu:** Weryfikacja funkcjonalności polubienia posta przez użytkownika.

- **Kroki:**
    1. Zaloguj się jako użytkownik.
    2. Przeglądaj posty na platformie.
    3. Kliknij przycisk "polubienia" pod wybranym postem.
    4. Sprawdź, czy system zarejestrował polubienie i czy post jest oznaczony jako polubiony.
- **Miara testu:**
    - **Pozytywny wynik:** Post jest poprawnie oznaczony jako polubiony przez użytkownika, a liczba polubień posta zwiększa się o 1.
    - **Negatywny wynik:** Polubienie nie jest rejestrowane, post nie jest oznaczony jako polubiony lub liczba polubień się nie zmienia.