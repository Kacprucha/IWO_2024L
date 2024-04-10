# Raport zbiorczy

## Dokumentacja nawigacji aplikacji

*autorzy: Igor Kędzierawski, Tymoteusz Gryszkalis*

### Strona logowania:

-   **Widok:** Formularz logowania.
-   **Przejścia:** Możliwość przejścia do strony rejestracji użytkownika lub dostawcy [1].
-   **Błędy:** Błąd logowania przy nieprawidłowych danych, komunikat o nieudanej rejestracji użytkownika.
-   **Kluczowe elementy:** Pole do wprowadzenia nazwy użytkownika i hasła, opcja zapomnianego hasła.

![strona_logowania.png](/Lab4/Opis%20nawigacji%20systemu/pics/strona_logowania.png)

### Strona rejestracji użytkownika:

-   **Widok:** Formularz rejestracji dla użytkowników.
-   **Przejścia:** Możliwość przejścia do strony logowania [1].
-   **Błędy:** Komunikat o błędnie wypełnionych polach, informacja o niepowodzeniu rejestracji.
-   **Kluczowe elementy:** Pola do wprowadzenia danych osobowych, opcja wyboru typu konta.

![strona_rejestracji_uzytkownika.png](/Lab4/Opis%20nawigacji%20systemu/pics/strona_rejestracji_uzytkownika.png)

### Strona rejestracji dostawcy:

-   **Widok:** Formularz rejestracji dla dostawców.
-   **Przejścia:** Możliwość przejścia do strony logowania [1].
-   **Błędy:** Komunikat o błędnie wypełnionych polach, informacja o niepowodzeniu rejestracji.
-   **Kluczowe elementy:** Pola do wprowadzenia danych firmy, opcja wyboru typu konta.

![strona_rejestracji_dostawcy.png](/Lab4/Opis%20nawigacji%20systemu/pics/strona_rejestracji_dostawcy.png)

### Panel powitalny (dla użytkownika i dostawcy):

-   **Widok:** Personalizowany panel powitalny po zalogowaniu.
-   **Przejścia:** Możliwość przejścia do strony logowania i strony rejestracji [1].
-   **Kluczowe elementy:** Powitanie użytkownika lub dostawcy, menu nawigacyjne.

![panel_powitalny.png](/Lab4/Opis%20nawigacji%20systemu/pics/panel_powitalny.png)

### Główny widok usługodawcy:

-   **Widok:** Panel zarządzania usługami lub produktami.
-   **Przejścia:** Możliwość przejścia do widoku zamówień, ofert, opini, postów, statystyk i ustawień [1-6]. Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [7,9,10]. Możliwość użycia opcji szukaj [8]. Możliwośc przejścia do strony głównej [11]
-   **Kluczowe elementy:** Lista usług lub produktów, opcje edycji i dodawania.

![glowny_widok_uslugodawcy.png](/Lab4/Opis%20nawigacji%20systemu/pics/glowny_widok_uslugodawcy.png)

### Widok postów sprzedawcy/usługodawcy:

-   **Widok:** Lista postów sprzedawcy/usługodawcy.
-   **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwośc przejścia do strony głównej [5]
-   **Kluczowe elementy:** Lista postów.

![widok_postow_uslugodawcy.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_postow_uslugodawcy.png)

### Widok płatności (subskrypcja):

-   **Widok:** Formularz płatności dla subskrypcji.
-   **Przejścia:**  Możliwości z topbara. Możliwość przejścia na stronę zapłaty [4]
-   **Kluczowe elementy:** Możliwość zatwierdzenia płatności [1]. Możliwość wyboru sposobu płatności [2]. Możliwość szybkiego poglądu koszyka [3].

![widok_platnosci_subskrybcja.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_platnosci_subskrybcja.png)

### Widok płatności (plan Premium):

-   **Widok:** Formularz płatności dla planu Premium.
-   **Przejścia:** Możliwość wyboru sposobu płatności [1]. Możliwość zatwierdzenia płatności [2].
-   **Kluczowe elementy:** Formularz sposobu płatności.

![widok_platnosci_plan_premium.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_platnosci_plan_premium.png)

### Widok płatności (danie):

-   **Widok:** Formularz płatności za danie.
-   **Przejścia:** Możliwości z topbara. Możliwość przejścia na stronę zapłaty [4]
-   **Kluczowe elementy:** Możliwość wprowadzenia danych dostawy [1]. Komunikat o darmowej dostawie (Premium) [2]. Wybór sposobu płatności [3]. Zatwierdzenie zamówienia [4]. Możliwość szybkiego poglądu koszyka [5]. Komuniakat o zaoszędzonej kwocie za dostawe (Premium) [6]. Łączna kwota [7]

![widok_platnosci_danie_i_premium.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_platnosci_danie_i_premium.png)

### Widok płatności - błąd (plan Premium):

-   **Widok:** Komunikat o błędzie płatności dla planu Premium.
-   **Przejścia:** Możliwości z topbara. Możliwość przejścia do widoku płatności[1].
-   **Kluczowe elementy:** Komunikat o błędzie, opcja powrotu.

![widok_platnosci_blad.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_platnosci_blad.png)

### Widok popupów z błędami:

-   **Widok:** Wyświetlenie popupów z komunikatami błędów.
-   **Przejścia:** Brak, po zamknięciu [1,2] popupa pozostanie na aktualnej stronie.
-   **Kluczowe elementy:** Przyciski do zamykania popupa [1,2]. Tytuł błędu [4]. Treść błędu [3]

![blad_popup.png](/Lab4/Opis%20nawigacji%20systemu/pics/blad_popup.png)

### Widok podglądu koszyka:

-   **Widok:** Podgląd zawartości koszyka przed dokonaniem zakupu.
-   **Przejścia:** Możliwości z topbara. Możliwość przejścia do widoków zapłaty [3]
-   **Kluczowe elementy:** Lista produktów w koszyku [1]. Wartość koszyka [2]. Przycisk przejścia do kasy [3]

![widok_podgladu_koszyka.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_podgladu_koszyka.png)

### Strona zamówienia:

-   **Widok:** Podląd zamówień, ich statusu, subskrybcji i historii.
-   **Przejścia:** Możliwości z topbara. Możliwości stronicowania zamówień [4]. Możliwość przejścia do opcji subskrybcji [3].
-   **Kluczowe elementy:** Komponent z statusem zamówienia [1]. Komponent z aktywnymi subskrybcjami [2]. Komponent z listą zamówień [4]. Przycisk opcji subskrybcji [3]. Przyciski zarządzania zamówieniami [6]. Przycisk anulowania zamówienia [5]. Przyciski do stronicowania zamówień [7]

![widok_zamowien.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_zamowien.png)

### Widok dodawania recenzji:

-   **Widok:** Formularz dodawania recenzji.
-   **Przejścia:** Przejście do poprzedniej strony [5]. Przejście do opublikowanej opini [6].
-   **Kluczowe elementy:** Nazwa dania [1]. Ocena zbiorcza [2] i oceny cząstkowe [3]. Pole do wpisania opini [4]. Przycisk anulowania zostawiania opini [5]. Przycisk publikujący opinię [6] 

![widok_zamowien.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_dodawania_recenzji.png)

### Widok dodawania postów przez usługodawcę:

-   **Widok:** Formularz dodawania postów.
-   **Przejścia:** Możliwości z topbara. Możliwość przejścia do strony z dodanym postem [3]
-   **Kluczowe elementy:** Pole do załączania plików [1]. Pole do wpisywania treści posta [2]. Przycisk do publickacji posta [3].

![widok_dodania_posta.png](/Lab4/Opis%20nawigacji%20systemu/pics/widok_dodania_posta.png)

### Statystyki podstawowe:

- **Widok:** Okno statystyk podstawowych.
- **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwość przejścia do
  strony głównej [5].
- **Kluczowe elementy:** Lista statystyk podstawowych

![statystyki podsatwowe](/Lab4/Opis%20nawigacji%20systemu/pics/01statpodst.png)

### Statystyki premium:

- **Widok:** Okno statystyk premium.
- **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwość przejścia do
  strony głównej [5].
- **Kluczowe elementy:** Lista wszystkich statystyk.

![statystyki premium](/Lab4/Opis%20nawigacji%20systemu/pics/02statprem.png)

### Zakup konta premium:

- **Widok:** Zakup konta premium.
- **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwość przejścia do
  strony głównej [5]. Możliwość przejścia do strony płatności [6].
- **Kluczowe elementy:** Plany premium do wyboru.

![zakup konta premium](/Lab4/Opis%20nawigacji%20systemu/pics/03zakuppremium.png)

### Płatność za konto premium:

- **Widok:** Widok płatności (plan Premium).
- **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwość przejścia do
  strony głównej [5]. Możliwość zapłaty [6].
- **Kluczowe elementy:** Metody płatności do wyboru.

![płatność za konto premium](/Lab4/Opis%20nawigacji%20systemu/pics/04platnoscpremium.png)

### Udana płatność za konto premium:

- **Widok:** Widok płatności - OK (plan Premium).
- **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwość przejścia do
  strony głównej [5,6].
- **Kluczowe elementy:** Informacja o powodzeniu płatności.

![powodzenie przy płatności](/Lab4/Opis%20nawigacji%20systemu/pics/05platnoscgit.png)

### Nieudana płatność za konto premium:

- **Widok:** Widok płatności - błąd (plan Premium).
- **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwość przejścia do
  strony głównej [5]. Możliwość przejścia do strony płatności [6].
- **Kluczowe elementy:** Informacja o niepowodzeniu płatności.

![niepowodzenie przy płatności](/Lab4/Opis%20nawigacji%20systemu/pics/06platnoscblad.png)

### Wyszukiwanie:

- **Widok:** Panel wyszukiwania 2.
- **Przejścia:** Możliwość zobaczenia koszyka, konta i rozwinięcia sidebara [1,2,3]. Możliwość użycia opcji szukaj [4]. Możliwość przejścia do
  strony głównej [5]. Możliwość przejścia do wybranej pozycji wyszukiwania [6]. Możliwość wyszukania daniej kategorii [7,8,9]
- **Kluczowe elementy:** Wyniki wyszukiwania, kategorie wyszukiwania, narzędzie filtrujące, narzędzie sortujące.

![panel wyszukiwania](/Lab4/Opis%20nawigacji%20systemu/pics/07panelszukania.png)

### Dodawania kredytów

- **Widok:** Okno dodawania kredytów użytkownikowi.
- **Przejścia:** Możliwość dokonania operacji dodania kredytów [1]. Możliwość przejścia do strony głównej [2].
- **Kluczowe elementy:** Formularz do sformalizowania dodania kredytów.

![dodawanie kredytów](/Lab4/Opis%20nawigacji%20systemu/pics/08dodanie%20kredytow.png)

### Jakiegoś przejścia do trybu ciemnego

- **Widok:** Przykładowe okno trybu ciemnego.
- **Przejścia:** Aby zmienić tryb jasności aplikacji należy wejść w rozwijane menu boczne [1], a następnie wybrać opcję trybu ciemnego [2].
- **Kluczowe elementy:** Odpowiadające odpowiedniemu widokowi.

![dodawanie kredytów](/Lab4/Opis%20nawigacji%20systemu/pics/0901panel%20boczny.png) <br>
![dodawanie kredytów](/Lab4/Opis%20nawigacji%20systemu/pics/0902widok%20ciemny.png)

## Zaprojektowane widoki UI

![Widok dodawania recenzji](/Lab4/Widoki%20UI/widok%20dodawania%20recenzji.png) <br>
*autor: Filip Sosonowski* 

![Widok głównego okna usługodawcy](/Lab4/Widoki%20UI/glowny%20widok%20uslugodawcy.png) <br>
*autor: Filip Sosonowski* 

![Widok dodawania postów](/Lab4/Widoki%20UI/dodawanie%20postów.png) <br>
*autor: Jakub Wysocki* 

![Widok dodawania postów](/Lab4/Widoki%20UI/panel%20boczny.png) <br>
*autor: Jakub Wysocki* 

![Widok trybu ciemnego](/Lab4/Widoki%20UI/widok%20ciemny.png) <br>
*autor: Karol Zalewski* 

![Widok trybu ciemnego](/Lab4/Widoki%20UI/dodawanie%20kredytow.png) <br>
*autor: Karol Zalewski* 

![Widok statystyk](/Lab4/Widoki%20UI/Statystyki.png) <br>
*autor: Krzysztof Jurkowski* 

![Widok statystyk premium](/Lab4/Widoki%20UI/Statystyki%20premium.png) <br>
*autor: Krzysztof Jurkowski* 

![Widok płatności](/Lab4/Widoki%20UI/Widok%20patnosci.png) <br>
*autor: Angelina Sudenkova* 

![Widok płatności z kontem premium](/Lab4/Widoki%20UI/Widok%20patnosci%20premium%20danie.png) <br>
*autor: Angelina Sudenkova* 

![Widok płatności zakończonej pomyślnie](/Lab4/Widoki%20UI/Widok%20patnosci%20OK.png) <br>
*autor: Angelina Sudenkova* 

![Widok płatności zakończonej niepowodzeniem](/Lab4/Widoki%20UI/Widok%20patnosci%20blad.png) <br>
*autor: Angelina Sudenkova* 

![Widok kalendarza do zamawiania subskrypcji](/Lab4/Widoki%20UI/kalendarz.png) <br>
*autor: Szymon Kopańko*

![Widok popapówz z błedami](/Lab4/Widoki%20UI/widok%20popupow%20z%20bledami.png) <br>
*autor: Sebastian Pawliński*

![Widok popapówz z błedami](/Lab4/Widoki%20UI/podglad%20koszyka.png) <br>
*autor: Sebastian Pawliński*

## Raport GUI
*autor: Szymon Rogoziński*

Projekt interfejsu graficznego zachowuję spójność, a poprawki zgłoszone przez klienta zostały wprowadzone.

Prawie wszystkie widoki i panele opisane w dokumentacji zostały zaprojektowane. Brakuję widoku do przeglądania postów, widoku zamawiania potraw i wybierania daty dostawy, widoku anulowania zamówienia, widoku subskrypcji od strony usługodawcy, widoku trybu ciemnego oraz widoku dodawania karty kredytowej.

Opóżnienia te mogą nieznacznie przedłużyć pracę, ale nie powinny one znacznie przeszkodzić projektowi w fazie analizy i projektu.

Zaczęto pracę nad prototypem działającego interfejsu, opisano scenariusze przebiegu interakcji z użytkownikiem dla trzech zadań. Posłużyły one do utworzenia pełnoprawnych prototypów w Figmie.

### Uwagi

- Widoki zostały wpisane w okno aplikacji typu PWA. Miało to na celu ujednolicić widoki oraz ułatwić ocenę przestrzeni widocznej dla użytkownika.
- Niektóre z widoków oferują opcję przewijania, jednak nie zostało to oznaczone w wyraźny sposób. Widoki te to: Panel wyszukiwania i panel postów usługodawcy.
- Wyjątkiem jest widok statystyk, który został rozszerzony, aby pokazać wszystkie komponenty. W kolejnym sprint'cie zostanie dodany widok przycięty, który zostanie zaimplementowany (dostęp do niewidocznych komponentów, będzie poprzez przewijanie strony).

## Prototyp aplikajci
*autorzy: Mateusz Sobol, Szymon Ochnio*

Dostępny w aplikacji Figma.