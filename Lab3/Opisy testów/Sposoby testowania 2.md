# Sposób testowania przypadków użycia

*autor: Igor Kędzierewski*

### **7. Zbieranie statystyk**

**Opis testu:** Weryfikacja poprawności zbierania danych dotyczących aktywności użytkowników przez system.

-   **Kroki:**

    1. Sprawdź, czy system monitoruje aktywność użytkowników poprzez zapisywanie odpowiednich zdarzeń.
    2. Wykonaj różne czynności jako użytkownicy, takie jak logowanie, dodawanie postów, wystawianie recenzji, dokonywanie zakupów.
    3. Po upływie określonego czasu, sprawdź, czy system prawidłowo zbiera dane dotyczące tych aktywności.
    4. Zweryfikuj, czy zebrane dane są przechowywane w systemie.
    5. Upewnij się, że administrator ma dostęp do zebranych statystyk dotyczących aktywności użytkowników.

-   **Miara testu:**
    -   **Pozytywny wynik:** System poprawnie monitoruje aktywność użytkowników i zbiera dane, a administrator może uzyskać dostęp do zebranych statystyk.
    -   **Negatywny wynik:** System nie rejestruje wszystkich aktywności użytkowników lub dane nie są poprawnie zbierane i przechowywane, co uniemożliwia administratorowi uzyskanie dostępu do statystyk.

### **8. Kredyty**

**Opis testu:** Weryfikacja procesu zakupu kredytów przez użytkownika.

-   **Kroki:**

    1. Użytkownik loguje się na swoje konto.
    2. Użytkownik przechodzi do opcji zakupu kredytów.
    3. Użytkownik wybiera pakiet kredytów, który chce zakupić.
    4. Użytkownik realizuje płatność za pomocą wybranej metody płatności.

-   **Miara testu:**
    -   **Pozytywny wynik:** Po zakończeniu transakcji kredyty są poprawnie dodane do konta użytkownika.
    -   **Negatywny wynik:** Transakcja nie zostaje zrealizowana lub kredyty nie są poprawnie dodane do konta użytkownika.

### **9. Subskrypcje**

**Opis testu:** Weryfikacja procesu subskrypcji usługi premium przez użytkownika.

-   **Kroki:**

    1. Użytkownik przechodzi do opcji subskrypcji usługi premium.
    2. Wybiera plan subskrypcji, który najlepiej odpowiada jego potrzebom.ji, dokonywanie zakupów.
    3. Realizuje płatność za pomocą wybranej metody płatności.

-   **Miara testu:**
    -   **Pozytywny wynik:** Użytkownik uzyskuje dostęp do funkcji premium po zakończeniu transakcji.
    -   **Negatywny wynik:** Użytkownik nie uzyskuje dostępu do funkcji premium po zakończeniu transakcji lub proces subskrypcji kończy się błędem.

### **10. Główna strona użytkownika**

**Opis testu:** Weryfikacja funkcji przeglądania głównej strony profilu użytkownika.

-   **Kroki:**

    1. Zaloguj się na swoje konto użytkownika.
    2. Przejdź do głównej strony swojego profilu.
    3. Sprawdź, czy są wyświetlane informacje dotyczące aktywności, postów, recenzji itp.

-   **Miara testu:**
    -   **Pozytywny wynik:** Użytkownik ma dostęp do podsumowania swojej aktywności na głównej stronie profilu.
    -   **Negatywny wynik:** Brak wyświetlanych informacji lub problemy z dostępem do głównej strony profilu.

### **11. Wyszukiwanie**

**Opis testu:** Weryfikacja funkcjonalności wyszukiwania produktów w aplikacji.

-   **Kroki:**

    1. Użytkownik zalogowuje się na swoje konto.
    2. Użytkownik wprowadza kryteria wyszukiwania w pole wyszukiwania.
    3. Użytkownik naciska przycisk lub klawisz "Szukaj".
    4. System przetwarza zapytanie i wyświetla wyniki pasujące do podanych kryteriów.

-   **Miara testu:**
    -   **Pozytywny wynik:** System wyświetla poprawne wyniki wyszukiwania zgodne z podanymi kryteriami.
    -   **Negatywny wynik:** System nie wyświetla żadnych wyników, wyświetla błędne wyniki lub aplikacja zawiesza się podczas wyszukiwania.

### **12. Zamówienia**

**Opis testu:** Weryfikacja procesu składania zamówienia przez użytkownika.

-   **Kroki:**
    1. Użytkownik zalogowuje się na swoje konto i znajduje się na stronie produktu.
    2. Użytkownik wybiera produkt, który chce zamówić.
    3. Użytkownik dodaje produkt do koszyka lub przechodzi od razu do procesu zamawiania.
    4. Użytkownik podaje niezbędne dane do zrealizowania zamówienia, takie jak adres dostawy, metoda płatności itp.
    5. Użytkownik potwierdza zamówienie.
-   **Miara testu:**
    -   **Pozytywny wynik:** Zamówienie jest pomyślnie złożone i widoczne w historii zamówień użytkownika.
    -   **Negatywny wynik:** Nie można dokończyć procesu zamówienia z powodu błędów, zamówienie nie jest widoczne w historii zamówień użytkownika lub występują problemy z płatnością.