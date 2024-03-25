# Sposób testowania przypadków użycia

*autor: Szymon Ochnio*

### **13. Historia**

**Opis testu:** Test przeglądania historii zamówień przez użytkownika.

- **Kroki:**
  1.  Użytkownik loguje się na swoje konto na platformie sklepu.
  2.  Użytkownik przechodzi do ustawień konta.
  3.  Użytkownik wybiera opcję "historia zamówień".
  4.  Użytkownik przegląda listę wcześniej złożonych zamówień.
  5.  Użytkownik wybiera dowolne zamówienie.
  6.  Użytkownik sprawdza szczegóły zamówienia, w tym status dostawy.
- **Miara testu:**
  - **Pozytywny wynik:** Lista złożonych zamówień jest widoczna. Szczegóły każdego zamówienia, w tym status dostawy, są dostępne po wybraniu odpowiedniej pozycji na liście.
  - **Negatywny wynik:** Historia zamówień jest niewidoczna, niekompletna lub szczegółowe informacje o poszczególnych zamówieniach nie są dostępne.

### **14. Wystawianie produktu**

**Opis testu:** Test dodawania nowego produktu przez sprzedawcę.

- **Kroki:**
  1.  Sprzedawca loguje się na swoje konto.
  2.  Sprzedawca przechodzi do opcji dodawania nowego produktu.
  3.  Sprzedawca wypełnia wymagane dane produktu, takie jak nazwa, cena, opis, zdjęcia itp.
  4.  Sprzedawca klikuje przycisk, aby dodać produkt do swojego asortymentu.
  5.  Sprzedawca sprawdza, czy nowy produkt jest widoczny w ofercie dla użytkowników.
- **Miara testu:**
  - **Pozytywny wynik:** Nowy produkt został pomyślnie dodany i jest widoczny w ofercie sprzedawcy dla użytkowników.
  - **Negatywny wynik:** Produkt nie został dodany, dane produktu są niekompletne lub produkt nie jest widoczny w ofercie sprzedawcy.

### **15. Płatności**

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

### **16. Konto premium**

**Opis testu:** Test zarządzania kontem premium przez użytkownika

- **Kroki:**
  1. Użytkownik loguje się na swoje konto.
  2. Przechodzi do ustawień konta.
  3. Zarządza opcjami związanymi z subskrypcją premium, takimi jak przedłużenie subskrypcji, zmiana planu itp.
- **Miara testu:**
  - **Pozytywny wynik:** Użytkownik efektywnie zarządza swoją subskrypcją premium.
  - **Negatywny wynik:** Użytkownik nie jest w stanie zarządzać swoją subskrypcją premium.

### **17. Status zamówienia**

**Opis testu:** Test sprawdzania statusu zamówienia przez użytkownika

- **Kroki:**
  1. Użytkownik loguje się do systemu.
  2. Użytkownik przechodzi do historii swoich zamówień.
  3. Użytkownik wybiera zamówienie, którego status chce sprawdzić.
  4. Użytkownik sprawdza status wybranego zamówienia.
- **Miara testu:**
  - **Pozytywny wynik:** Informacja o statusie zamówienia jest zgodna z aktualnym stanem i jest dla użytkownika zrozumiała.
  - **Negatywny wynik:** Informacja o statusie zamówienia jest niezgodna z aktualnym stanem lub nie jest dla użytkownika zrozumiała.

### **18. Zarządzanie kontami użytkowników przez administratora**

**Opis testu:** Test zarządzania kontami użytkowników przez administratora

- **Kroki:**
  1. Administrator loguje się do panelu administracyjnego.
  2. Administrator przechodzi do sekcji zarządzania kontami użytkowników.
  3. Administrator przegląda listę wszystkich kont użytkowników.
  4. Administrator dodaje, edytuje lub usuwa wybrane konta.
- **Miara testu:**
  - **Pozytywny wynik:** Administracja kontami użytkowników przebiega zgodnie z oczekiwaniami, wszystkie zmiany są poprawnie zapisywane w systemie.
  - **Negatywny wynik:** Administracja kontami użytkowników napotyka na problemy, zmiany nie są zapisywane lub są zapisywane niepoprawnie.