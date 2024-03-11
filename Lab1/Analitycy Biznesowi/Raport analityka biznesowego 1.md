# Raport dot. Wymagań Biznesowych
*autor: Jakub Wysocki*

#### 3.1 Wymagania funkcjonalne
- **Synchronizacja** 
- **Powiadomienia** 
- **Wielojęzyczność** 
- **Posty** 
- **Recenzja** 
- **Polubienia** 
- **Zbieranie statystyk** 
- **Kredyty** 
- **Subskrypcje** 
- **Główna strona użytkownika** 
- **Wyszukiwanie** 
- **Zamówienia** 
- **Historia** 
- **Wystawianie produktów** 
- **Płatności** 
- **Konto premium** 
- **Status zamówienia** 
- **Konta** 

##### 3.2 Szczegółowe funkcjonalności systemu
- **Synchronizacja** : Interfej użytkownika składający się z  strony internetowej i aplikacji mobilnej ma mieć zapewnioną synchronizacją danych między nimi.
- **Powiadomienia** : Automatyczne powiadomienia dla użytkownika, które mają dotyczyć promocji,nowych ofert,statusu dostawy, zmiany regulaminu. Powiadomienia promocyjne i ofertowe możliwe do wyłączenia.
- **Wielojęzyczność** : Obecnie działamy tylko na rynku polskim, ale Interfejs ma być wielojęzyczny z dostępnymi językami: Polski, Angielski, Ukraiński.
- **Posty** : Usługodawcy mają możliwość wstawiania postów na swoje profile. Posty składają się z tekstu, zdjęcia i hasztagów, użytkownicy mogą reagować z postami poprzez dawanie polubień.
- **Recenzja** : Recenzje mogą wystawiać użytkownicy pod konkretnymi daniami i dietami usługodawcy, jeśli zostały one zakupione przez nich lub pod konkretnym usługodawcą. Recenzje składają się z tekstu i oceny w skali 5 gwiazdek. Inni użytkownicy mogą reagować na recenzję lajkami.
- **Polubienia** : Użytkownik może zostawiać polubienia pod postami, daniami co wpływa na jego przyszłe rekomendacje.
- **Zbieranie statystyk** : Usługodawcy mogą zobaczyć statystyki swoich postów, dań i diet takie jak polubienia, recenzje, ilość zakupów, mapę z podziałem na regiony z ilością zakupów z danego regionu.
- **Kredyty** : Kredyty są przyznawane jako rekompensata w wyniku problemów z dostawą bądź z dostarczonym produktem. Odpowiadają one bezpośrednio pieniądzom, można za nie kupić inne produkty, jeśli problem był po stronie usługodawcy, uzyskane kredyty można użyć tylko do zakupu jego produktów, jeśli problem nie był po stronie usługodawcy kredyty można wykorzystać do zakupu dowolnego produktu.
- **Subskrypcje** : Użytkownik ma możliwość subskrybowania danego usługodawcy co sprawi, że jego posty są częściej polecane dla niego.
- **Główna strona użytkownika** : Główna strona wyświetla rekomendacje dla użytkownika na podstawie ostatnich zakupów i subskrypcji.
- **Wyszukiwanie** : Użytkownicy mają dostęp do wyszukiwarki usługodawców i wyszukiwarki dań/diet. W wyszukiwarce można ustawić filtry i sortować wyszukiwanie po takich parametrach jak nazwa, cena, zawartość składników.
- **Zamówienia** : Użytkownicy mogą dodać do koszyka zamówień różne dania od różnych usługodawców i będą one dostarczone do niego razem w ramach jednego zamówienia. Może także wykupić subskrypcję konkretnej diety usługodawcy, która będzie będzie automatycznie ściągać pieniądze z konta użytkownika. Subskrypcję przyjmują postać dziennych, tygodniowych lub miesięcznych. Po zakupie subskrypcji na dietę, odpowiednie dania będą dostarczane do użytkownika o określonych porach dnia.
- **Historia** : Użytkownik ma możliwość zobaczenia historii zamówień oraz listę subskrypcji, która ma opłacone.  Zamówienia, które mają zostać dostarczone w czasie większym niż 24 godziny, mogą zostać anulowane.
- **Wystawianie produktów** : Usługodawca może wystawić do sprzedaży konkretne danie, które jest sprzedawane i dostarczane o wybranej przez użytkownika porze dnia lub dietę, która jest w modelu subskrypcyjnym na dzień, tydzień lub miesiąc. Użytkownik może tylko zakupić daną subskrypcje, nie może nic w niej zmieniać. Każde danie, które jest dostarczane, też te w ramach diety, ma opisaną zawartość poprzez składniki.
- **Płatności** : Użytkownik może dokonywać płatności za pomocą blika, kraty, kredytu.
- **Konto premium** : Użytkownik może zakupić konto premium dające mu darmowe dostawy.
- **Status zamówienia** : Użytkownik może podejrzeć status zamówień mówiący na jakim etapie dostarczania jest zamówienie.
- **Konta** : Występują 3 rodzaje kont: usługodawca, użytkownik, admin.


#### Słownik
**statystyki** - zbiór ogólnych reakcji użytkowników na posty, wyświetlania, zarobki z aplikacji.

**recenzja** - opinia użytkownika na temat dania lub usługodawcy.

**rodzaj diety** - wyłącznie nazwa.

**dieta** - pełen plan jedzeniowy na określony czas.

**rodzaj posiłeku** - np. śniadanie, obiad, kolacja.

**posiłek** - składa się z jednego lub więcej dań.

**danie** - składa się ze składników.

**produkt** - to co wystawi usługodawca do sprzedaży, czyli danie lub dieta.