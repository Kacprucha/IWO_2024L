# Sposób testowania przypadków użycia

*autor: Szymon Ochnio*

### **13. Historia**
**Opis testu:** Test przeglądania historii zamówień przez użytkownika.

- **Kroki:**
  1. Użytkownik loguje się na swoje konto na platformie sklepu.
  2. Użytkownik przechodzi do ustawień konta.
  3. Użytkownik wybiera opcję "historia zamówień".
  4. Użytkownik przegląda listę wcześniej złożonych zamówień.
  5. Użytkownik wybiera dowolne zamówienie.
  6. Użytkownik sprawdza szczegóły zamówienia, w tym status dostawy.
- **Miara testu:**
  - **Pozytywny wynik:** Lista złożonych zamówień jest widoczna. Szczegóły każdego zamówienia, w tym status dostawy, są dostępne po wybraniu odpowiedniej pozycji na liście.
  - **Negatywny wynik:** Historia zamówień jest niewidoczna, niekompletna lub szczegółowe informacje o poszczególnych zamówieniach nie są dostępne.

### **14. Płatności**
**Opis testu:** Test realizacji płatności za zamówienie przez użytkownika

- **Kroki:**
  1. Użytkownik loguje się na swoje konto.
  2. Przechodzi do koszyka z wybranymi produktami.
  3. Wybiera opcję realizacji płatności.
  4. Wybiera metodę płatności i wprowadza niezbędne dane.
  5. Potwierdza płatność przez kliknięcie przycisku "Zapłać".
- **Miara testu:**
  - **Pozytywny wynik:** Płatność zostaje zrealizowana, a użytkownik otrzymuje potwierdzenie transakcji.
  - **Negatywny wynik:** Płatność nie zostaje zrealizowana, użytkownik nie otrzymuje potwierdzenia transakcji.

### **15. Konto premium**
**Opis testu:** Test zakupu kontem premium przez użytkownika

- **Kroki:**
  1. Użytkownik loguje się na swoje konto.
  2. Przechodzi do ustawień konta.
  3. Wybiera opcję zakupu konta premium.
  4. Dokonuje tranzakcji.
  5. Użytkownik ma dostęp do nowych funkcjonalności.
- **Miara testu:**
  - **Pozytywny wynik:** Użytkownik widzi zmiany w strukturze aplikacji i posiada dostęp do wcześniej nie dostępnych funkcjonalności.
  - **Negatywny wynik:** Użytkownik nie ma dostępu do funkcjonalności premium lub tranzakcja nie zostaje wykonana.

### **16. Status zamówienia**
**Opis testu:** Test sprawdzania statusu zamówienia przez użytkownika

- **Kroki:**
  1. Użytkownik loguje się do systemu.
  2. Użytkownik przechodzi do historii swoich zamówień.
  3. Użytkownik wybiera zamówienie, którego status chce sprawdzić.
  4. Użytkownik sprawdza status wybranego zamówienia.
- **Miara testu:**
  - **Pozytywny wynik:** Informacja o statusie zamówienia jest zgodna z aktualnym stanem i jest dla użytkownika zrozumiała.
  - **Negatywny wynik:** Informacja o statusie zamówienia jest niezgodna z aktualnym stanem lub nie jest dla użytkownika zrozumiała.

### **17. Zarządzanie kontami użytkowników przez administratora**
**Opis testu:** Test zarządzania kontami użytkowników przez administratora

- **Kroki:**
  1. Administrator loguje się do panelu administracyjnego.
  2. Administrator przechodzi do sekcji zarządzania kontami użytkowników.
  3. Administrator przegląda listę wszystkich kont użytkowników.
  4. Administrator dodaje, edytuje lub usuwa wybrane konta.
- **Miara testu:**
  - **Pozytywny wynik:** Administracja kontami użytkowników przebiega zgodnie z oczekiwaniami, wszystkie zmiany są poprawnie zapisywane w systemie.
  - **Negatywny wynik:** Administracja kontami użytkowników napotyka na problemy, zmiany nie są zapisywane lub są zapisywane niepoprawnie.

### **18. Subskrypcja diety**
**Opis testu:** Test złożenie przez użytkownika subksrypcji na dietę

- **Kroki:**
  1. Użytkownik loguje się do systemu.
  2. Użytkownik przechodzi do zakupu diety.
  3. Użytkownik wybiera okres na jaki chce zakupić deitę.
  4. Użytkownik wybiera formę płatności i jej dokonuje
  5. Użytkownik dostaje komunikat o dokonaniu subksrypcji i jest ją w stanie zobaczyć w liście swoich subksrypcji
- **Miara testu:**
  - **Pozytywny wynik:** Użtkownik widzi informacje o dokonanej subskrypcji a odpowiedni usługodawcy również dostali powaidamenie o jej dokonaniu.
  - **Negatywny wynik:** Użytkownik nie jest w stanie sprawdzić swoich subskrypcji lub informacja o subskrypcji nie doszła do usługodawców.