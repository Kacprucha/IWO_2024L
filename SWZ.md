# Specyfikacja Wymagań Zamawiającego

## I. Wprowadzenie

### 1.1 Cel dokumentu
Dokument ten będzie podstawą do dalszej pracy nad projektem, zawierając szczegółowy opis problemu biznesowego, wizję systemu, modele procesów biznesowych, listę przypadków użycia oraz wymagania jakościowe.

### 1.2 Zakres projektu
System integrujący dostawców cateringu. Planowany system powinien umożliwiać integrację usług wielu takich dostawców w jednym miejscu. Dzięki temu możliwe będzie zamawianie posiłków od wielu dostawców w obrębie jednego zamówienia. W szczególności, dotyczy to możliwości łączenia posiłków od różnych dostawców w ramach diet dziennych, tygodniowych, miesięcznych itp.

### 1.3 Podział pracy na sekcje
Przy każdej osobie zostało zaznaczone za jakie sekcje dokumentu była odpowiedzialna.
- Analitycy Biznesowi:
  - Jakub Wysocki *- 3.1 Ogólne wymagania funkcjonalne, 3.2 Szczegółowe funkcjonalności systemu, 8.1 Identyfikacaj procesów biznesowych*
  - Szymon Ochnio *- 3.3 Wymagania dotyczące wydajności, 3.4 Wymagania dotyczące bezpieczeństwa*
  - Mateusz Sobol *- II Opis Problemu Biznesowego i Celu Projektu, 6.4 Opisy przypadków użycia*
  - Angelina Sudenkova *- 8.1 Identyfikacaj procesów biznesowych*
  - Mateusz Czarnecki
  - Szymon Kopańko *- 6.4 Opisy przypadków użycia*
  - Tymoteusz Gryszkalis *- 6.5 Implementacja przypadków użycia w procesach biznesowych*
- Analitycy Systemowi:
  - Krzysztof Jurkowski *- 5.1 Wizja systemu, 5.2 Lista cech systemu*
  - Mateusz Czarnecki *- 5.2 Lista cech systemu, 5.3 Wymagania dotyczące wydajności*
  - Filip Sosnowski *- 5.3 Wymagania dotyczące wydajności, 5.4 Wymagania dotyczące bezpieczeństwa*
  - Karol Zalewski *- 5.4 Wymagania dotyczące bezpieczeństwa, 5.5 Wymagania dotyczące niezawodności*
  - Sebastian Pawlińsk *- 5.5 Wymagania dotyczące niezawodności, 5.6 Ograniczenia środowiskowe*
- Specjaliści od Przypadków Użycia:
  - Tymoteusz Gryszkalis *- 6.1 Zrozumienie wymagań, 6.2 Identyfikacja aktorów*
  - Szymon Kopańko *- 6.3 Lista przypadków użycia, 6.4 Opis przypadków użycia*
  - Wojtek Szade *- 6.3 Lista przypadków użycia, 6.4 Opis przypadków użycia*
- Specjalista od Dokumentacji:
  - Angelina Sudenkova
  - Szymon Rogoziński
  - Igor Kędzierawski
  - Julia Owczarczyk

**Specjaliści od Dokumentacji** mieli wspólne zadanie **nadzorowania tworzenia dokumentów innych członków** zespołu oraz **utworzenie wspólnego dokumentu** łączącego całość pracy zespołu. 

- Analityk Systemowy i Specjalista od Przypadków Użycia
  - Sebastian Pawliński
  - Igor Kędzierewski
  - Wojtek Szade
  - Jakub Wysocki
  - Angelina Sudenkova
  - Karol Zalewski
  - Julia Owczarek
  - Krzysztof Jurkowski
- Projektant UI
  - Karol Zalewski *- 9.1 Ustalenia dotyczące wyglądu UI*
  - Krzysztof Jurkowski
  - Filip Sosnowski
  - Szymon Rogodziński
  - Julia Owczarczyk
- Deweloper
 	- Tymoteusz Gryszkalis
 	- Mateusz Sobol
 	- Szymon Ochnio

**Deweloprzey** pełnili role akceptacujną oraz konsulantacyjną odpowiednio **Tymoteusz Gryszkalis** do identyfikcji procesów biznesowych, **Mateusz Sobol** do realizacji diagramów BPMN procesów biznesowych i **Szymon Ochnio** do realizacji widoków systemowych. <br>
**Analitycy Systemowi i Specjaliści od Przypadków Użycia** mieli za zadanie wykonać diagramów BPMN zamieszczonych w odzielnej dokumentacji. <br>
**Projektancji UI** mieli za zdanie wykonać projekty widoków umiesczone w Figmie oraz w odzielnej dokumentacji.

- Tester
  - Igor Kędzierewski *- 7.1 Przypadków użycia*
  - Mateusz Czarnecki *- 7.1 Przypadków użycia*
  - Szymon Ochnio *- 7.1 Przypadków użycia*

Dodatkowo słownik dziedziny powstawał wspólnie przez każdego z członków zespołu.

## II. Opis Problemu Biznesowego i Celu Projektu

### 2.1 Opis aktualnej sytuacji biznesowej
Aktualnie na rynku znajduje się wiele usług kateringowych. Każda z nich posiada własną stronę internetową, wymagającą utworzenia konta. Stron z recenzjami jest wiele, ale często nie posiadają wszystkich dostępnych na rynku ofert.  Osoby poszukujące usług kateringowych, poświęcają dużo czasu na przeglądanie różnych stron internetowych oraz analizowanie recenzji. Nawet jak znajdą interesującą ich ofertę, często nie zadowala ich w pełni i są zmuszeni do korzystania z wielu usług kateringowych.

### 2.2 Problemy i wyzwania
Największym wyzwaniem będzie zapewnienie jak największej dostępności systemu. System musi być wielojęzyczny, wieloplatformowy oraz niezawodny, aby dotrzeć do jak największej liczby klientów. Ponadto, dużym wyzwaniem stanowić będzie komunikacja z usługami kateringowymi.

### 2.3 Cel projektu
Celem jest utworzenie systemu informatycznego, który zbierałby oferty kateringowe w jednym miejscu i umożliwiał użytkownikowi szybkie i łatwe odnalezienie ofert. Ponadto, użytkownik mógłby zamawiać różne dania z różnych firm w formie jednego posiłku oraz zamawiać spersonalizowane diety. System ma być też platformą dla producentów, gdzie mogą się reklamować w formie postów publikowanych w ramach profilu producenta oraz zdobyć dostęp do większej ilości klientów.

### 2.4 Korzyści płynące z realizacji projektu
Firmy kateringowe otrzymują możliwość łatwego i bezpiecznego publikowania swoich ofert oraz przeglądania swoich statystyk. Ponadto, mają możliwość reklamowania swoich ofert i zdobycia dostępu do większej ilości klientów. 
Dla użytkowników główną korzyścią jest zwiększenie wygody.Mogą oni w łatwy sposób odnaleźć usługi kateringowe, mieszać ich oferty oraz sprawdzać recenzje. Otrzymują łatwy system śledzenia promocji, a dodatkowo otrzymują rekomendację na podstawie historii zamówień, co pozwala im na odkrywanie nowych dań.

## III. Lista Kluczowych Funkcjonalności i Wymagań Biznesowych

### 3.1 Ogólne wymagania funkcjonalne
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

### 3.2 Szczegółowe funkcjonalności systemu 
- **Synchronizacja** : Interfej użytkownika składający się z  strony internetowej i aplikacji mobilnej ma mieć zapewnioną synchronizacją danych między nimi.
- **Powiadomienia** : Automatyczne powiadomienia dla użytkownika, które mają dotyczyć promocji,nowych ofert,statusu dostawy, zmiany regulaminu. Powiadomienia promocyjne i ofertowe możliwe do wyłączenia.
- **Wielojęzyczność** : Obecnie działamy tylko na rynku polskim, ale Interfejs ma być wielojęzyczny z dostępnymi językami: Polski, Angielski, Ukraiński.
- **Posty** : Usługodawcy mają możliwość wstawiania postów na swoje profile. Posty składają się z tekstu, zdjęcia i hasztagów, użytkownicy mogą reagować z postami poprzez dawanie polubień.
- **Recenzja** : Recenzje mogą wystawiać użytkownicy pod konkretnymi daniami, dietami usługodawcy oraz samym usługodawcą. Recenzja może zostać wystawiona po odebraniu danie/dieta lub pod konkretnym usługodawcą. Recenzje składają się z tekstu i oceny w skali 5 gwiazdek. Inni użytkownicy mogą reagować na recenzję lajkami.
- **Polubienia** : Użytkownik może zostawiać polubienia pod postami, daniami co wpływa na jego przyszłe rekomendacje.
- **Zbieranie statystyk** : Usługodawcy mogą zobaczyć statystyki swoich postów, dań i diet takie jak polubienia, recenzje, ilość zakupów, mapę z podziałem na regiony z ilością zakupów z danego regionu.
- **Kredyty** : Kredyty są przyznawane jako rekompensata w wyniku problemów z dostawą bądź z dostarczonym produktem. Odpowiadają one bezpośrednio pieniądzom, można za nie kupić inne produkty, jeśli problem był po stronie usługodawcy, uzyskane kredyty można użyć tylko do zakupu jego produktów, jeśli problem nie był po stronie usługodawcy kredyty można wykorzystać do zakupu dowolnego produktu.
- **Subskrypcje** : Użytkownik ma możliwość subskrybowania danego usługodawcy co sprawi, że jego posty są częściej polecane dla niego.
- **Główna strona użytkownika** : Główna strona wyświetla rekomendacje dla użytkownika na podstawie ostatnich zakupów i subskrypcji.
- **Wyszukiwanie** : Użytkownicy mają dostęp do wyszukiwarki usługodawców i wyszukiwarki dań/diet. W wyszukiwarce można ustawić filtry i sortować wyszukiwanie po takich parametrach jak nazwa, cena, zawartość składników.
- **Zamówienia** : Użytkownicy mogą dodać do koszyka zamówień różne dania od różnych usługodawców i będą one dostarczone do niego razem w ramach jednego zamówienia. Może także wykupić subskrypcję konkretnej diety usługodawcy, która będzie będzie automatycznie ściągać pieniądze z konta użytkownika. Subskrypcję przyjmują postać dziennych, tygodniowych lub miesięcznych. Po zakupie subskrypcji na dietę, odpowiednie dania będą dostarczane do użytkownika o określonych porach dnia.
- **Historia** : Użytkownik ma możliwość zobaczenia historii zamówień oraz listę subskrypcji, która ma opłacone.  Zamówienia, które mają zostać dostarczone w czasie większym niż 24 godziny, mogą zostać anulowane.
- **Pobieranie produktów** : konkretne danie/diety, które są sprzedawane w aplikacji są pobierane bezpośrednio ze strony usługodawcy. Gdy użytkownik zamawia danie może wybrać godzinę dostarczenia lub w przypadku dietu, która jest w modelu subskrypcyjnym wyiera okres subskrypcji na dzień, tydzień lub miesiąc. Użytkownik może tylko zakupić daną subskrypcje, nie może nic w niej zmieniać. Każde danie, które jest dostarczane, też te w ramach diety, ma opisaną zawartość poprzez składniki.
- **Płatności** : Użytkownik może dokonywać płatności za pomocą blika, kraty, kredytu.
- **Konto premium** : Użytkownik może zakupić konto premium dające mu darmowe dostawy.
- **Status zamówienia** : Użytkownik może podejrzeć status zamówień mówiący na jakim etapie dostarczania jest zamówienie.
- **Konta** : Występują 3 rodzaje kont: usługodawca, użytkownik, admin.
- **Różne tryby aplikacji** : aplikacja ma być dostępna w dwóch trybach jasnym i ciemnym.

### 3.3 Wymagania dotyczące wydajności 
- **Zapewnienie użytkownikom szybkiego dostępu do aplikacji**
  - **Cel:** Chcemy, aby nasi użytkownicy mogli łatwo i szybko korzystać z naszej aplikacji webowej i mobilnej, minimalizując czas ładowania aplikacji.
  - **Oczekiwane rezultaty:** Jak najkrótszy czas ładowania aplikacji.
- **Dostarczenie szybkich odpowiedzi na zapytania użytkowników**
  - **Cel:** Chcemy reagować na zapytania naszych użytkowników w sposób jak najszybszy.
  - **Oczekiwane rezultaty:** Jak najkrótszy czas odpowiedzi na zapytania użytkowników.
- **Zapewnienie skalowalności systemu**
  - **Cel:** Chcemy, aby nasz system był zdolny do obsługi wzrostu liczby użytkowników i dostawców bez utraty wydajności.
  - **Oczekiwane rezultaty:** Skalowalność i stabilność pomimo wzrostu liczby użytkowników.
- **Szybkie przetwarzanie płatności za zamówienia**
  - **Cel:** Chcemy, aby proces płatności za zamówienia był jak najbardziej płynny i szybki dla naszych użytkowników.
  - **Oczekiwane rezultaty:** Jak najkrótszy czas przetwarzania płatności.
- **Dostarczanie natychmiastowych powiadomień**
  - **Cel:** Chcemy, aby nasze powiadomienia docierały do użytkowników niemal natychmiast po ich wygenerowaniu.
  - **Oczekiwane rezultaty:** Jak najkrótszy czas dostarczania powiadomień.

### 3.4 Wymagania dotyczące bezpieczeństwa
- **Silna ochrona danych osobowych**
  - **Cel:** Naszym priorytetem jest zapewnienie bezpieczeństwa danych naszych użytkowników. Dążymy do tego, by były one nie tylko odpowiednio zabezpieczone, ale także transmitowane w bezpieczny sposób.
  - **Oczekiwane rezultaty:** Spełnienie standardów bezpieczeństwa dotyczących przechowywania danych.
- **Silne uwierzytelnianie i autoryzacja użytkowników**
  - **Cel:** Wszystkie procesy uwierzytelniania i autoryzacji w systemie powinny być zabezpieczone silnymi, niezawodnymi mechanizmami, zgodnymi z obowiązującymi standardami bezpieczeństwa.
  - **Oczekiwane rezultaty:** Bezpieczne i skuteczne procesy autoryzacji i autentykacji użytkowników.
- **Określone role dostępu**
  - **Cel:** Chcemy zapewnić, że każda kategoria użytkowników (od użytkowników indywidualnych, poprzez dostawców, aż do administratorów) ma odpowiednio zdefiniowane role i uprawnienia w systemie.
  - **Oczekiwane rezultaty:** Skuteczne zarządzanie uprawnieniami użytkowników.
- **Odporność na ataki internetowe**
  - **Cel:** Naszym celem jest wprowadzenie skutecznych mechanizmów obronnych, które minimalizują ryzyko wszelkiego rodzaju ataków internetowych.
  - **Oczekiwane rezultaty:** Odporność na ataki hakerskie.
- **Monitorowanie aktywności**
  - **Cel:** Chcemy skutecznie monitorować działania w naszym systemie, aby szybko wykrywać wszelkie nieprawidłowości i podejrzane działania.
  - **Oczekiwane rezultaty:** Monitorowanie i zapisywanie istotnych zdarzeń w systemie.

## IV. Identyfikacja Interesariuszy Projektu 

### 4.1 Definicja interesariuszy
Interesariuszami w projekcie są firmy kateringowe, osoby kupujace usługi kateringowe, firma zamawiająca system.

### 4.2 Opis roli każdego interesariusza
Firma kateringowa pełni rolę udostępniającego usługi kateringowe dla aplikacji. <br>
Osoby kupujące usługi kateringowe to użytkownicy aplikacji bez nich aplikacji nie istnieje. Są grupą docelową projektu. <br>
Firma zamawiająca ma kierować działaniami projektu, pnieważ to oni stoją za jego wizją.

### 4.3 Oczekiwania i potrzeby interesariuszy
Firmy katerignowe oczekują platformy, która zwiększy sprzedaż ich usług i zarazem przestrzeni do reklamy poprzez publikowanie postów. <br>
Osoby kupujące chcą mieć łatwy dostęp do szerokiej oferty kateringowej i personalizować w dowolny sposób plan jedzeniowy. <br>
Firma zamawiająca chce zarobić na aplikacji za pomocą programów premium dla użytkowników aplikacji.

### 4.4 Potencjalne konflikty interesów
Potęcjalne konflikty mogą powstać na linii firm kateringowych i firm zamawiajacych, ponieważ firmy kateringowe nie bedą chciały być przedstawiane w jednym miejscu z innymi konkurentami lub uznają że zysk z wzięcia udziału w takim przedsięwzieciu nie będzie wart spełnienia wymagań firmy zamawiającej aplikacjie. Konflikt interesów może też powstać na linie firma zamawiająca użytkownicy gdy właścicele waplikacji zarządają zbyt duzych cen za plany premium bez odpowiednich benefitów. W takim wypadku użytkownicy nie będą ich kupować, a właścicle nie zarobi zamierzonej kwoty.

## V. Wymagania Jakościowe i Ograniczenia

### 5.1 Wizja systemu 
System będzie wykonany w formie aplikacji PWA komunikującej się z serwerem i bazą danych poprzez web api. Pozwoli to na zapewnienie poprawnego działania i takiego samego user experience niezależnie od urządzenia z którego korzysta użytkownik (przeglądarka, telefon, tablet itp.).
  
Dane użytkowników będą przechowywane w bezpieczny sposób w centralnej bazie danych. Niektóre dane dotyczące np. preferencji użytkownika mogą być również przechowywane lokalnie np. w ciastkach lub w pamięci przeglądarki. 
  
Płatności będą obsługiwane przez zewnętrznego dostawcę, co zapewni niezawodność i jak najlepsze doświadczenie użytkownika, będzie mógł wybrać najczęściej używane formy płatność jak blik lub płatność kartą debetową/kredytową, a sama płatność będzie przeprowadzana sprawnie.
  
Skalowalość i niezawodność systemu zapewni dostawca usług chmurowych dzięki zastosowaniu rozwiązań serverless. Dzięki temu zarówno baza danych jak i web api będą elastyczne i będą mogły odpowiednio dostosowywać moc obliczeniową systemu do obciążenia, co pozwoli na poprawne działanie systemu w przypadku np. nagłego zwiększenia odwiedzeń strony. Za pośrednictwem dostawcy usług chmurowych administrator systemu będzie również miał dostęp do wszelakich danych telemetrycznych pozwalających na szybkie i skuteczne diagnozowanie usterek.
  
### 5.2 Lista cech systemu
* System składa się z 3 części: aplikacji PWA, web api i bazy danych.
* System zapewnia takie same funkcjonalności niezależnie od platformy (web/mobilna).
* System jest dostępny 24/7. Zastrzegamy sobie jako firma 20 dni w roku na naprawy serwisowe, w których aplikacja może być nie aktywan.
* System jest skalowalny, nie przestaje działać nawet przy skokowym wzroście odwiedzeń strony.
* System jest dostępny w wielu językach oraz pamięta preferencje językowe użytkownika.
* System oferuje wysyłanie powiadomień do użytkownika o dostawach, promocjach, zmianach w regulaminie czy o informacjach w zmianach funcjonowaniu oprogramowania.
* System umożliwia wyłączenie niektórych powiadomień.
* System bezpiecznie przechowuje wrażliwe dane użytkowników.
* System pozwala użytkownikowi na usunięcie swoich danych zgodnie z RODO.
* System obsługuje płatności blikiem i kartą kredytową/debetową lub za pomocą kredytów. 

* System umożliwia firmie kateringowej publikować aktualizacje i reklamy w formie postów - 5 dziennie.
* System umożliwia firmie kateringowej przeglądanie statystyk (reakcje użytkowników na posty, wyświetlenia, przychód z aplikacji) .
* System umożliwia użytkownikowi przeglądanie oferty wielu firm kateringowych.
* System umożliwia użytkownikowi przeglądanie i reagowanie na posty usługodawców (firm kateringowych).
* System umożliwia użytkownikowi składanie zamówień.
* System umożliwia użytkownikowi opłacanie zamówień poprzez kredyt, blik oraz kartę debetową/kredytową.
* System umożliwia użytkownikowi doładowanie kredytu użytkowniak w ramach rekompensaty za nie dostarczone produkty (kredyt na dowolnego usługodawcę) lub odwołane zamówienie (kredyt na konkretnego usługodawcę).
* System umożliwia użytkownikowi anulowanie swojego zamówienia do 24 godzin przed planowanym dostarczeniem.
* System proponuje użytkownikowi rekomendowane oferty na podstawie jego poprzednich zamówień oraz zasubskrybowanych firmach kateringowych.
* System pozwala użytkownikowi wyszukiwać oferty po:
  * dostawcy
  * nazwie dania
  * składnikach
  * nazwie diety
* System pozwala użytkownikowi sortować oferty po:
  * ocenie użytkowników
  * cenie
* System pozwala użytkownikowi filtrować oferty po:
  * diecie
  * alergenach
* System pozwala użytkownikowi na dodawanie dań do ulubionych.
* System pozwala użytkownikowi na wystawienie recenzji nt. dania i usługi lub usługodawcę do miesiąca po wykonaniu zamówienia.
* System pozwala użytkownikowi na przeglądanie recenzji produktów i reagowanie na nie.
* System umożliwia użytkownikowi przeglądanie historii swoich zamówień.
* System umożliwia użytkownikowi na przeglądanie statusu dzisiejszych zamówień.
  
### 5.3 Wymagania dotyczące wydajności
- **System powinien osiągać minimalny czas ładowania aplikacji webowej i mobilnej**
  - **Opis:** Średni czas ładowania aplikacji webowej i mobilnej nie powinien przekroczyć 2 sekund, maksymalnie może wynosić 3 sekundy.
  - **Sposób pomiaru:** Pomiar czasu ładowania aplikacji. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
  - **Możliwy wynik pomiaru:** Czas mierzymy z dokładnością do 0.1 sekundy od 0.1 sekundy do 3 sekund (powyżej 3 sekund uznaje się, że system nie załadował aplikacji wystarczająco szybko).
  - **Oczekiwane wartości:** Czas ładowania aplikacji webowej i mobilnej nie przekraczający 2 sekund.
- **System powinien zapewniać jak najmniejszy czas odpowiedzi na zapytania użytkowników**
  - **Opis:** System powinien odpowiadać na zapytania użytkowników w czasie nie przekraczającym 0.5 sekundy, maksymalnie może wynosić 1 sekundę.
  - **Sposób pomiaru:** Pomiar czasu odpowiedzi na zapytanie użytkownika. Mierzymy czas dla 1000 prób i wyliczamy średnią z pomiarów. 
  - **Możliwy wynik pomiaru:** Czas mierzymy z dokładnością 0.01 sekundy od 0.01 sekundy do 1 sekundy (powyżej 1 sekundy uznaje się, że użytkownik nie otrzymał odpowiedzi od systemu wystarczająco szybko)  
  - **Oczekiwane wartości:** Średni czas odpowiedzi na zapytanie użytkownika nie przekracza 0.5 sekundy, najgorszy czas wynosi poniżej 1 sekundy.
- **System powinien być skalowalny**
  - **Opis:** System powinien sprawnie dostosowywać się do zmian w liczbie użytkowników i dostawców, utrzymując podobną wydajność. W przypadku wzrostu liczby użytkowników i dostawców o 100-krotność, system powinien efektywnie obsługiwać wszystkie operacje.
  - **Sposób pomiaru:** Ocena zdolności systemu do obsługi rosnącej liczby użytkowników. Testy wydajnościowe przeprowadzane w warunkach zbliżonych do produkcyjnych, mierzące czas odpowiedzi na operacje w zależności od liczby użytkowników korzystająych z aplikacji w tym samym momencie. 
  - **Możliwy wynik pomiaru:** System obsługuje wzrost liczby użytkowników i dostawców o 100-krotność, utrzymując stabilność oraz akceptowalne czasy odpowiedzi na zapytania (opisane wyżej).  
  - **Oczekiwane wartości:** Skuteczna skalowalność systemu przy wzroście do 100-krotności obecnej liczby użytkowników. System powinien utrzymywać średni czas odpowiedzi poniżej 0.5 sekundy oraz poniżej 1 sekundy przy maksymalnym obciążeniu.
- **System powinien szybko przetwarzać płatności za zamówienia**
  - **Opis:** Średni czas przetwarzania płatności, od chwili zatwierdzenia transakcji do uzyskania potwierdzenia, nie powinien przekraczać 5 sekund. Maksymalnie może być dwa razy dłuższy.
  - **Sposób pomiaru:** Pomiar czasu przetwarzania płatności online. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
  - **Możliwy wynik pomiaru:** Czas mierzony z dokładnością do 0.1 sekundy od zatwierdzenia do potwierdzenia, w przedziale od 0.1 sekundy do 10 sekund (powyżej 10 sekund uznaje się, że przetwarzanie płatności było zbyt długie).
  - **Oczekiwane wartości:** Czas przetwarzania płatności online nie przekraczający 5 sekund, w najgorszym przypadku w czasie mniejszym niż 10 sekund.
- **System powinien obsługiwać natychmiastowe powiadomienia**
  - **Opis:** Powiadomienia powinny być dostarczane użytkownikom w czasie nie przekraczającym 2 sekund po ich wygenerowaniu, maksymalnie w czasie dwa razy dłuższym.
  - **Sposób pomiaru:** Pomiar czasu dostarczania powiadomień do użytkowników. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
  - **Możliwy wynik pomiaru:** Czas dostarczania powiadomień mierzony z dokładnością do 0.1 sekundy, w przedziale od 0.1 do 2 sekund (powyżej 2 sekund uznaje się za opóźnienie w dostarczeniu powiadomienia).
  - **Oczekiwane wartości:** Czas dostarczenia powiadomień do użytkowników nie przekraczający 2 sekund, w najgorszym przypadku w czasie mniejszym niż 4 sekundy.

### 5.4 Wymagania dotyczące bezpieczeństwa 
- **System musi silnie szyfrować i bezpiecznie przechowywać dane osobowe użytkowników**
  - **Opis:** Dane osobowe klientów muszą być bezpiecznie przechowywane i przesyłane.
  - **Sposób pomiaru:** Audyty bezpieczeństwa, które mają na celu weryfikację skuteczności mechanizmów stosowanych do szyfrowania danych w systemie.
  - **Możliwy wynik pomiaru:** Ocena i potwierdzenie bezpieczeństwa danych osobowych użytkowników w systemie.
  - **Oczekiwane wartości:** Dane osobowe w systemie są szyfrowane oraz bezpiecznie przechowywane i przesyłane.
- **System musi wymagać silnego i bezpiecznego uwierzytelniania oraz autoryzacji**
  - **Opis:** Procesy uwierzytelniania i autoryzacji w systemie muszą być oparte na silnych i bezpiecznych mechanizmach.
  - **Sposób pomiaru:** Testy penetracyjne oceniające skuteczność procesów uwierzytelniania i autoryzacji w systemie. Skuteczność procesów uwierzytelniania i autoryzacji, mierzona jako procent poprawnych uwierzytelnień w stosunku do wszystkich prób.
  - **Możliwy wynik pomiaru:** Skuteczność mechanizmów obronnych powinna być blisko maksymalej wartości (minimum 99%). Potwierdzenie, że system w pełni stosuje bezpieczne i niezawodne uwierzytelnianie i autoryzację użytkowników.
  - **Oczekiwane wartości:** Autoryzacja i uwierzytelnienie w systemie są w pełni bezpieczne, oparte na silnych mechanizmach i zgodne z obowiązującymi standardami bezpieczeństwa.
- **System musi mieć zdefiniowane role dostępu**
  - **Opis:** W systemie muszą być zdefiniowane klarowne role dostępu, przypisane do różnych kategorii użytkowników (użytkownik, usługodawcy, administrator), z odpowiednimi uprawnieniami dostępu (Access Management). Interakcje z zasobami systemu muszą być ściśle kontrolowane w zależności od przypisanych uprawnień i ról.
  - **Sposób pomiaru:** Testy w ramach różnych zasobów, które sprawdzą skuteczność mechanizmów zarządzania dostępem w kontekście różnych ról użytkowników. 
  - **Możliwy wynik pomiaru:**  Osiągnięcie 100% udanych prób dostępu do zasobów zgodnych z przydzielonymi uprawnieniami oraz 100% nieudanych prób, kiedy użytkownik nie ma wymaganych uprawnień.
  - **Oczekiwane wartości:** System zapewnia skuteczne zarządzanie dostępem, eliminując dostęp do zasobów dla użytkowników bez wymaganych uprawnień.
- **System musi być zabezpieczony przed atakami internetowymi**
  - **Opis:** System powinien posiadać skuteczne mechanizmy obronne, aby minimalizować ryzyko ataków internetowych (między innymi SQL injection, XSS, CSRF, DDoS, Brute Force).
  - **Sposób pomiaru:** Regularne testy bezpieczeństwa każdej kategorii, które mają na celu wykrycie podatności związanych z atakami. Wynik pomiaru stanowi procent udanych zatrzymanych ataków w stosunku do wszystkich prób.
  - **Możliwy wynik pomiaru:**  Skuteczność mechanizmów obronnych powinna być blisko maksymalej wartości (minimum 99%) dla każdej z kategorii badanych ataków.
  - **Oczekiwane wartości:** Skuteczna obrona przed atakami każdej kategorii, która wykazuje jak największą możliwą odporność na ataki internetowe.
- **System musi umożliwiać monitorowanie aktywności**
  - **Opis:** System musi skutecznie monitorować aktywność, co pozwoli na identyfikację nieprawidłowości i podejrzanej aktywności. Każda istotna operacja i zdarzenie w systemie powinny być rejestrowane w celu późniejszej analizy.
  - **Sposób pomiaru:** Mierzona jest liczba zdarzeń monitorowanych w logach systemowych. Wynikiem jest procent zarejestrowanych istotnych zdarzeń w systemie do ich spodziewanej liczby.
  - **Możliwy wynik pomiaru:**  System powinien rejestrować co najmniej 99% istotnych zdarzeń systemowych.
  - **Oczekiwane wartości:** Skuteczne monitorowanie aktywności zgodne z praktykami bezpieczeństwa. System rejestruje istotne wydarzenia w systemie oraz wykrywa istotne nieprawidłowości i działania podejrzane.

### 5.5 Wymagania dotyczące niezawodności 
- System powinien być w stanie szybko i efektywnie przywracać się do poprawnego stanu po wystąpieniu awarii:
  - Opis: System powinien posiadać skuteczne mechanizmy przywracania po awarii, zapewniające szybkie i efektywne przywrócenie funkcji systemu do poprawnego stanu.
  - Sposób pomiaru: Testy awaryjne, w trakcie których oceniana jest skuteczność procesów przywracania po różnych rodzajach awarii.
  - Możliwy wynik pomiaru: Czas przywrócenia systemu do pełnej funkcjonalności na poziomie minimalnym.
  - Oczekiwane wartości: Skuteczne mechanizmy przywracania, minimalizujące czas niedostępności systemu po wystąpieniu awarii.
- System powinien być skalowalny, aby dostosowywać się do zmieniającego się obciążenia:
  - Opis: System powinien być zdolny do dynamicznego dostosowywania swojej infrastruktury w zależności od zmieniającego się obciążenia, zapewniając elastyczność i skalowalność.
  - Sposób pomiaru: Testy wydajnościowe i skalowalności, oceniające zdolność systemu do obsługi rosnącej liczby użytkowników lub zwiększonego obciążenia.
  - Możliwy wynik pomiaru: Skuteczne dostosowywanie się systemu do zmieniającego się obciążenia bez utraty wydajności.
  - Oczekiwane wartości: Elastyczny i skalowalny system, dostosowujący się do rosnących wymagań użytkowników.
- System powinien regularnie przechodzić testy odpornościowe pod obciążeniem i w warunkach ekstremalnych:
  - Opis: System powinien być regularnie testowany pod kątem odporności na obciążenie oraz w warunkach ekstremalnych, aby zweryfikować jego stabilność i wydajność.
  - Sposób pomiaru: Testy obciążeniowe i warunków ekstremalnych, oceniające zachowanie systemu w sytuacjach skrajnych.
  - Możliwy wynik pomiaru: Stabilność systemu w warunkach ekstremalnych na poziomie akceptowalnym.
  - Oczekiwane wartości: System odporny na obciążenie i warunki ekstremalne, zapewniający stabilność działania nawet w trudnych sytuacjach.
- System powinien oferować skuteczne mechanizmy monitorowania aktywności oraz raportowania wszelkich nieprawidłowości:
  - Opis: System powinien być wyposażony w mechanizmy monitorowania aktywności, umożliwiające szybką identyfikację i reakcję na wszelkie nieprawidłowości.
  - Sposób pomiaru: Analiza raportów monitorowania aktywności oraz czas reakcji na wykryte nieprawidłowości.
  - Możliwy wynik pomiaru: Szybka identyfikacja i reakcja na wszelkie nieprawidłowości.
  - Oczekiwane wartości: Skuteczne monitorowanie aktywności, minimalizujące czas reakcji na ewentualne problemy.
- System powinien zapewniać skuteczne mechanizmy backupowania danych oraz przywracania ich w przypadku utraty:
  - Opis: System powinien regularnie tworzyć kopie zapasowe danych oraz umożliwiać ich szybkie przywrócenie w przypadku utraty lub uszkodzenia.
  - Sposób pomiaru: Testy awaryjne, oceniające skuteczność procesów backupowania i przywracania danych.
  - Możliwy wynik pomiaru: Skuteczne przywracanie danych po utracie na poziomie minimalnym.
  - Oczekiwane wartości: Regularne i skuteczne procesy backupowania oraz przywracania danych, minimalizujące ryzyko utraty informacji.
- System powinien być wyposażony w skuteczny system zarządzania błędami, który umożliwia szybkie wykrywanie, raportowanie i naprawę błędów:
  - Opis: System powinien posiadać system zarządzania błędami, który umożliwia szybkie wykrywanie, raportowanie i naprawę wszelkich błędów w funkcjonowaniu systemu.
  - Sposób pomiaru: Analiza czasu reakcji na wykryte błędy oraz skuteczność ich naprawy.
  - Możliwy wynik pomiaru: Szybkie wykrywanie, raportowanie i naprawa błędów na poziomie akceptowalnym.
  - Oczekiwane wartości: Skuteczny system zarządzania błędami, minimalizujący wpływ błędów na działanie systemu oraz informowanie użytkowników o ewentualnych problemach.
- System powinien posiadać dokumentowany plan awaryjny, który określa kroki do podjęcia w przypadku poważnych awarii:
  - Opis: System powinien mieć dokumentowany plan awaryjny, precyzyjnie określający kroki do podjęcia w przypadku poważnych awarii, takich jak utrata dostępu do zasobów czy zniszczenie danych.
  - Sposób pomiaru: Regularne testy planu awaryjnego, sprawdzające skuteczność procedur oraz czas reakcji na poważne awarie.
  - Możliwy wynik pomiaru: Skuteczność planu awaryjnego na poziomie co najmniej 95%.
  - Oczekiwane wartości: Skuteczny i aktualny plan awaryjny, minimalizujący czas reakcji w przypadku poważnych awarii.

### 5.6 Ograniczenia środowiskowe
Ograniczenia dzielimy według typu aplikacji:
- Aplikacja webowa:
Aplikacja ma oferować te same funkcjonalności oraz wyglądać identycznie w podanych przeglądarkach:
  - Google Chrome
  - Firefox
  - Opera
  - Safari
  - Edge
- Aplikacja mobilna:
Aplikacja musi działać w systemach Android od wersji 10 (81,3% urządzeń na rynku) oraz w systemie IOS od wersji 11 (99% urządzeń na rynku).
Niezależnie od typu aplikacji zestaw funkcjonalności musi być identyczny dla każdych z platform.

## VI. Opracowanie i dokumentowanie przypadków użycia

### 6.1 Zrozumienie wymagań
#### Elementy systemu
- **Aplikacja kliencka (front-end)**: Ta strona będzie interfejsem użytkownika, z którym będą wchodzić w interakcję użytkownicy końcowi. Może to być aplikacja webowa dostępna przez przeglądarkę internetową lub aplikacja mobilna na urządzeniach Android lub iOS.
- **Serwer aplikacji (back-end)**: To serwer, który obsługuje logikę biznesową i przetwarza żądania użytkowników. Zarządza on komunikacją między aplikacją kliencką a bazą danych oraz innymi zewnętrznymi systemami, jeśli to konieczne.
- **Baza danych**: W systemie będzie potrzebna baza danych do przechowywania danych użytkowników, produktów, zamówień itp. Serwer aplikacyjny będzie komunikował się z bazą danych w celu pobierania i aktualizowania danych.
- **Systemy zewnętrzne**: Jeśli aplikacja wymaga integracji z zewnętrznymi systemami, takimi jak systemy płatności online lub systemy monitorowania, będą one komunikować się z serwerem aplikacyjnym poprzez odpowiednie interfejsy API.

#### Komunikacja elementów systemu:
- Aplikacja klienta - Serwer aplikacji:
  - Aplikacja klienta wysyła zapytania do serwera aplikacji w celu pobierania danych oraz przetwarzania operacji, takie jak składanie zamówień czy przeglądanie produktów.
  - Serwer aplikacji odpowiada na zapytania klienta, przetwarzając żądania i dostarczając odpowiednie dane.
- Serwer aplikacji - Baza danych:
  - Serwer aplikacji komunikuje się z bazą danych w celu pobierania, aktualizowania i przechowywania danych użytkowników, produktów, zamówień itp.
  - Baza danych odpowiada na zapytania serwera aplikacji, dostarczając lub aktualizując potrzebne dane.

### 6.2 Identyfikacja aktorów
- **Użytkownicy aplikacji webowej i mobilnej**: Użytkownicy są zainteresowani minimalnym czasem ładowania aplikacji oraz otrzymywaniem szybkich odpowiedzi na swoje zapytania. Są również zainteresowani otrzymywaniem natychmiastowych powiadomień. Oczekują, że system będzie szyfrował wszystkie dane przesyłane przez niego i przechowywane w nim, aby ich dane osobowe były bezpieczne. Oczekują także, że system będzie w stanie szybko i efektywnie przywracać się do poprawnego stanu po wystąpieniu awarii, oraz zapewniał skuteczne mechanizmy monitorowania aktywności oraz raportowania wszelkich nieprawidłowości. Muszą być informowani o przerwach serwisowych z odpowiednim wyprzedzeniem. Muszą też być świadomi, że w przypadku awarii systemu, aplikacja automatycznie przechodzi na backupowe środowisko, aby minimalizować przestoje. Oczekują, że aplikacja będzie działać zgodnie z tą specyfikacją, zapewniając spójne doświadczenie użytkownika na wszystkich platformach.
- **Usługodawcy**: Usługodawcy korzystają z systemu w celu dostarczania usług lub towarów. Są zainteresowani skalowalnością systemu oraz szybkim przetwarzaniem płatności za zamówienia.
- **Administratorzy systemu**: Administratorzy mają dostęp do zaawansowanych funkcji systemowych i są odpowiedzialni za zarządzanie rolami dostępu, monitorowanie aktywności, oraz zapewnianie bezpieczeństwa systemu. Administratorzy muszą skutecznie monitorować aktywność, rejestrując istotne operacje i zdarzenia w systemie. Ponadto muszą zarządzać mechanizmami zapobiegającymi utracie danych, takimi jak regularne backupy i przywracanie danych, oraz definiować klarowne i skuteczne zarządzanie dostępem do zasobów, oparte na zdefiniowanych rolach i uprawnieniach. Administratorzy muszą zaplanować przerwy serwisowe, które muszą być komunikowane użytkownikom z trzydniowym wyprzedzeniem. Ponadto, w przypadku awarii systemu, administratorzy muszą zapewnić automatyczne przejście aplikacji na backupowe środowisko w celu minimalizacji przestojów.
- **Potencjalni atakujący**: Aktorzy ci mogą próbować atakować system w celu uzyskania nieautoryzowanego dostępu do danych lub uszkodzenia systemu. System musi być zaprojektowany w taki sposób, aby skutecznie się bronić przed różnymi rodzajami ataków internetowych. Wymagane są skuteczne mechanizmy obronne, takie jak firewall, filtrowanie ruchu czy detekcja anomalii, aby chronić system przed różnorodnymi atakami, takimi jak próby ataków brute force, SQL injection, Cross-Site Request Forgery (CSRF) czy Cross-Site Scripting (XSS).
- **Zespół ds. obsługi technicznej**: Wymagane jest, aby zespół ds. obsługi technicznej monitorował i zarządzał przerwami serwisowymi oraz awariami systemu, zapewniając minimalizację przestojów i zapewniając, że procedury planowane są zgodnie z wymaganiami. Wymagane jest, aby system posiadał skuteczny system zarządzania błędami, który umożliwia szybkie wykrywanie, raportowanie i naprawę błędów. Ponadto, zespół ds. obsługi technicznej musi mieć dokumentowany plan awaryjny, który określa kroki do podjęcia w przypadku poważnych awarii, oraz regularnie przechodzić symulacje awarii pod presją czasu i w warunkach ekstremalnych.

### 6.3 Lista przypadków użycia
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

### 6.4 Opisy przypadków użycia 
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
  4. Jeżeli dodanie posta się udało system wyświetla nowy post i zapisuje ją do bazy danych. 
    1. Jeżeli dodanie posta się nie udało system wyświetla komunikat o błędzie.
  5. System wysyła powiadomienia o nowym poście odpowiednim użytkownikom.

**Warunki końcowe:** Nowy post usługodawcy jest widoczny na jego profilu dla użytkowników.

#### Recenzja

**Przypadek użycia: Dodawanie recenzji przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i posiada zakupiony produkt.

**Opis:**
  1. Użytkownik przechodzi do opcji wystawiania recenzji danego produktu.
  2. System wyświetla odpowiednie pole do wpisania recenzji
  3. Uzytkownik wpisuje treść recenzji oraz przyznaje ocenę produktowi.
  4. Użytownik potwierdza dodanie recenzji. 
    1. Jeżeli dodanie recenzji się nie udało system wyświetla komunikat o błędzie.
  5. Jeżeli dodanie recenzji się udało system wyświetla nową recenzje i zapisuje ją do bazy danych.

**Warunki końcowe:** Recenzja użytkownika jest widoczna na stronie produktu dla innych użytkowników..

#### Polubienia

**Przypadek użycia: Polubienie posta przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik przegląda posty na platformie.

**Opis:**
  1. Użytkownik przegląda posty innych użytkowników.
  2. Użytkownik klikając na przycisk "polubienia", potwierdza swoje zainteresowanie postem.
  3. System wyświetla odpowiednią zmianę na interfejsie

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

**Przypadek użycia: Wykorzystanie kredytów ogólnych przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik posiada kredyty ogólne na swoim koncie.

**Opis:**
  1. Użytkownik dokonuje zakupu produktu/usługi.
  2. Wybiera opcję zapłaty za pomocą kredytów.
  3. System potwierdza dokonanie płatności i odlicza odpowiednią ilość kredytów z konta użytkownika.

**Warunki końcowe:** Produkt/usługa zostaje opłacona za pomocą kredytów.

#### Subskrypcje konta usługodawcy

**Przypadek użycia: Subskrybowanie usługodawcy przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
  1. Użytkownik przechodzi do opcji subskrypcji usługi premium.
  2. Użytkownik wybiera plan subskrypcji, który najlepiej odpowiada jego potrzebom.
  3. Użytkownik wybiera jedną z możliwych płatnośći: Blik, Karta
  4. System wyswietla okno płatności.
  5. Użytkownik realizuje płatność za pomocą wybranej metody płatności. 
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie 
  6. Jeżeli płatność się udała system aktualizuje informacje o użytkowniku i wyświetla komunikat o sukcesie.

**Warunki końcowe:** Użytkownik uzyskuje dostęp do funkcji premium po zakończeniu transakcji.

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
  3. Użytkownik Przechodzi do podsumowania koszyka i weryfikuje wybrane produkty.
  4. Użytkownik Wybiera opcję zamówienia i wypełnia formularz z danymi do wysyłki i płatności.
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie.
  5. Jeżeli płatność się udała, system przetwarza zamówienie i wysyła potwierdzenie na adres email użytkownika.

**Warunki końcowe:** Zamówienie zostaje złożone i przekazane do realizacji.

#### Historia

**Przypadek użycia: Przeglądanie historii zamówień przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
  1. Użytkownik przechodzi do sekcji historii zamówień.
  2. System wyświetla listę zamówień lub subskrypcji wraz z ich szczegółami: datą zamówienia, status, kwotą i opcją szczegółów.
  3. Użytkownik może przeglądać szczegóły każdego zamówienia, w tym status wysyłki i historię płatności.
  4. Ma możliwość anulowania zamówienia, jeśli jego dostarczenie opóźniło się więcej niż 24 godziny.

**Warunki końcowe:** Użytkownik ma dostęp do historii swoich zamówień oraz subskrypcji.

#### Płatności

**Przypadek użycia: Dokonywanie płatności przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma produkty w koszyku.

**Opis:**
  1. Użytkownik przechodzi do opcji płatności.
  2. Wybiera preferowany sposób płatności: blikiem, kartą.
  3. Wprowadza niezbędne dane do realizacji płatności.
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie
  4. Jeżeli płatność się udała, system potwierdza płatność i czeka na autoryzację transakcji.
  5. Po pomyślnej autoryzacji, system wysyła użytkownikowi potwierdzenie transakcji i aktualizuje status zamówienia.

**Warunki końcowe:** Płatność zostaje zrealizowana, a zamówienie jest przetwarzane do wysyłki. Użytkownik otrzymuje potwierdzenie płatności.

#### Konto premium

**Przypadek użycia: Zakup konta premium przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
  1. Użytkownik przechodzi ustawień konta.
  2. Użytkownik wybiera opcję zakupu konta premium.
  3. Wybiera preferowany plan konta premium.
  4. Użytkownik wybiera forme płatności i ją realizuje.
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie.
  5. Użytkownik otrzymuje komunikat o nadaniu nowych uprawnień.
  6. System odblokowuje nowe funcjonalności dla użytkownika.

**Warunki końcowe:** Użytkownik ma aktywowane konto premium i ma dostęp do jego dodatkowych funkcji.

#### Status zamówienia

**Przypadek użycia: Sprawdzanie statusu zamówienia przez użytkownika**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma złożone zamówienie.

**Opis:**
  1. Użytkownik wchodzi w sekcję historii zamówień na swoim koncie.
  2. Wybiera zamówienie, którego status chce sprawdzić.
  3. System wyświetla szczegółowe informacje o zamówieniu, w tym aktualny status, przewidywaną datę dostawy i historię zmian statusu.
  4. Użytkownik może również zobaczyć informacje o śledzeniu przesyłki, jeśli są dostępne.

**Warunki końcowe:** Użytkownik ma aktualną informację o statusie swojego zamówienia.

#### Konta

**Przypadek użycia: Zarządzanie kontami**

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

**Przypadek użycia: Złożenie przez użytkownika subksrypcji na dietę**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

**Opis:**
  1. Użytkownik wybiera opcję subskrypcji diety z dostępnych ofert.
  2. System prezentuje formularz subskrypcji, gdzie użytkownik wybiera preferowany rodzaj diety, okres subskrypcji i szczegóły dotyczące dostawy.
  3. Użytkownik przechodzi do płatności, wybierając preferowaną metodę i wprowadzając niezbędne dane.
    1. Jeżeli płatność się nie udała system wyświetla komunikat o błędzie.
  4. Jeżeli płatność się udała, system przetwarza zamówienie i aktywuje subskrypcję.
  5. Użytkownik otrzymuje potwierdzenie założenia subskrypcji diety oraz szczegóły dotyczące planu dostaw na podany adres.
  6. System umożliwia użytkownikowi dostęp do sekcji z indywidualnym planem diety, poradami żywieniowymi i możliwością śledzenia postępów.

**Warunki końcowe:** Użytkownik posiada aktywną subskrypcję diety, z dostępem do zindywidualizowanych materiałów i wsparcia online.

#### Anulowanie zamówienia

**Przypadek użycia: Użytkownik chce anulować złożone wcześniej zamówienie**

**Aktorzy:** Użytkownik

**Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma aktywne zamówienie poniżej 24h do realizacji.

**Opis:**
  1. Użytkownik wybiera okno historię złożonych zmówień.
  2. System wyświetla okno pokazując zbliżającą się realizację zamówienia
    1. W przypadku zamówienia, które będzie w przeciągu 24h system uniemozliwia anulowanie zamówienia.
  3. W przypadku zamówienia, które będzie realizowane dłużej niż 24h system wyświetla przyciska anulowania zamówienia. 
  4. Użytkownik wciska przycisk anulownia.
  5. System wyświetla pop-up z potwierdzeniem anulowania zamówienia.
  6. Użytkownik potwierdza anulowanie.
  7. System wyświetla, krótką ankietę dlaczego uzytkownik chce anulować zamówienia.
    1. Użytkownik wypełnia ankietę.
  8. Użytkownik wysyła ankietę.
  9. System zapisuje ankietę i wysyła ją do uługodawcy anulowanego produktu.
  10. System wysyła komunikat o anulowaniu zamówienia do systemu usługodawcy.
  11. System nadaje użytkwnikowi odpowiednią ilość kredytów do wykorzystania u danego usługodawcy.
  12. System wysyła komunikat do użytkownika o anulowaniu zamówienia oraz nadaniu kredytów.

**Warunki końcowe:** Zamówienie użtkownika zostało anulowane i użytkownik otrzymał kredyty w ramach rekompensaty.

### 6.5 Implementacja przypadków użycia w procesach biznesowych

Po dokładnej analizie zaproponowanych opisów procesów biznesowych stwierdzam, że wszystkie przypadki użycia zostaną odpowiednio zaimplementowane.

## VII. Opis testowania
### 7.1 Przypadków użycia
#### **1. Synchronizacja**
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
    

#### **2. Powiadomienia**
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

#### **3. Wielojęzyczność**
**Opis testu:** Weryfikacja zmiany języka interfejsu aplikacji na wybrany przez użytkownika.

- **Kroki:**
  1. Otwórz aplikację i przejdź do ustawień języka.
  2. Wybierz każdy z dostępnych języków i zaakceptuj zmianę.
  3. Sprawdź, czy cały interfejs aplikacji zmienia się na wybrany język.
- **Miara testu:**
  - **Pozytywny wynik:** Interfejs aplikacji poprawnie wyświetla się w każdym z wybranych języków.
  - **Negatywny wynik:** Części interfejsu nie zmieniają języka lub pojawiają się błędy w wyświetlaniu.

#### **4. Posty**
**Opis testu:** Testowanie dodawania nowego posta przez usługodawcę.

- **Kroki:**
  1. Zaloguj się jako usługodawca.
  2. Dodaj nowy post, wprowadzając tekst, zdjęcia i hasztagi.
  3. Sprawdź, czy post jest widoczny na profilu usługodawcy.
- **Miara testu:**
  - **Pozytywny wynik:** Post jest poprawnie dodany i widoczny dla użytkowników.
  - **Negatywny wynik:** Post nie jest widoczny lub pojawiają się błędy podczas dodawania.

#### **5. Recenzja**
**Opis testu:** Sprawdzenie procesu dodawania recenzji i oceny produktu/usługodawcy przez użytkownika.

- **Kroki:**
  1. Zaloguj się jako użytkownik, który posiada zakupiony produkt.
  2. Przejdź do opcji wystawienia recenzji dla zakupionego produktu/usługodawcy.
  3. Wpisz tekst recenzji oraz ocenę produktu/usługodawcy w skali 5 gwiazdek.
  4. Potwierdź dodanie recenzji.
  5. Sprawdź, czy recenzja jest widoczna na profilu produktu/usługodawcy.
- **Miara testu:**
  - **Pozytywny wynik:** Rezencja jest poprawnie wystawione widać opis oraz poprawną ilość gwiazdek, która została zaznaczona.
  - **Negatywny wynik:** Recenzja nie jest wystaionw czy opis nie jest dodany, czy liczba gwiazdek nie jest zgodna z wyznaczoną.

#### **6. Polubienia**
**Opis testu:** Weryfikacja funkcjonalności polubienia posta przez użytkownika.

- **Kroki:**
  1. Zaloguj się jako użytkownik.
  2. Przeglądaj posty na platformie.
  3. Kliknij przycisk "polubienia" pod wybranym postem.
  4. Sprawdź, czy system zarejestrował polubienie i czy post jest oznaczony jako polubiony.
- **Miara testu:**
  - **Pozytywny wynik:** Post jest poprawnie oznaczony jako polubiony przez użytkownika, a liczba polubień posta zwiększa się o 1.
  - **Negatywny wynik:** Polubienie nie jest rejestrowane, post nie jest oznaczony jako polubiony lub liczba polubień się nie zmienia.

#### **7. Zbieranie statystyk**
**Opis testu:** Weryfikacja poprawności zbierania danych dotyczących aktywności użytkowników przez system.

- **Kroki:**
  1. Sprawdź, czy system monitoruje aktywność użytkowników poprzez zapisywanie odpowiednich zdarzeń.
  2. Wykonaj różne czynności jako użytkownicy, takie jak logowanie, dodawanie postów, wystawianie recenzji, dokonywanie zakupów.
  3. Po upływie określonego czasu, sprawdź, czy system prawidłowo zbiera dane dotyczące tych aktywności.
  4. Zweryfikuj, czy zebrane dane są przechowywane w systemie.
  5. Upewnij się, że administrator ma dostęp do zebranych statystyk dotyczących aktywności użytkowników.

- **Miara testu:**
  - **Pozytywny wynik:** System poprawnie monitoruje aktywność użytkowników i zbiera dane, a administrator może uzyskać dostęp do zebranych statystyk.
  - **Negatywny wynik:** System nie rejestruje wszystkich aktywności użytkowników lub dane nie są poprawnie zbierane i przechowywane, co uniemożliwia administratorowi uzyskanie dostępu do statystyk.

#### **8. Kredyty**
**Opis testu:** Weryfikacja wykorzystanie kredytów ogólnych przez użytkownika.

- **Kroki:**
  1. Użytkownik loguje się na swoje konto.
  2. Użytkownik przechodzi do dowolnej ofrty w aplikacji.
  3. Użytkownik wybiera formę płatności jako kredyty ogólne lub specjalnie nadane do danego usługodawcy.
  4. Użytkownik realizuje płatność.

- **Miara testu:**
  - **Pozytywny wynik:** Po zakończeniu transakcji kredyty są usuwane z konta użytkownika, ofrta trafia do realizacji.
  - **Negatywny wynik:** Transakcja nie zostaje zrealizowana lub kredyty nie są poprawnie usuwane z konta użytkownika.

#### **9. Subskrypcje**
**Opis testu:** Weryfikacja procesu subskrypcji usługi premium przez użytkownika.

- **Kroki:**
  1. Użytkownik/usługodawca przechodzi do opcji subskrypcji usługi premium.
  2. Wybiera plan subskrypcji, który najlepiej odpowiada jego potrzebom.
  3. Realizuje płatność za pomocą wybranej metody płatności.

- **Miara testu:**
  - **Pozytywny wynik:** Użytkownik/usługodawca uzyskuje dostęp do funkcji premium po zakończeniu transakcji.
  - **Negatywny wynik:** Użytkownik/usługodawca nie uzyskuje dostępu do funkcji premium po zakończeniu transakcji lub proces subskrypcji kończy się błędem.

#### **10. Główna strona użytkownika**
**Opis testu:** Weryfikacja funkcji wyświetlania rekomendacji dla użytkownika.

- **Kroki:**
  1. Zaloguj się na swoje konto użytkownika.
  2. Sprawdź, czy są wyświetlane posty, proponowae dania pokrywają się z subskrybowanymi usługodawcami czy ostatnio dokonywanami zakupami.

- **Miara testu:**
  - **Pozytywny wynik:** System prawidłowo proponuje uzytkownikowi treści w zależności od jego ostatnicj aktywności. Miarą testów będzie 60% zgodności treści z historią oraz subskrypcjiami użytkownika przy założeniu, że użytkownik ma w historii przynajmniej 15 zamówień.
  - **Negatywny wynik:** Brak wyświetlanych informacji lub propozycje nie są skorelowane z ostatnimi aktywnosciami użytkownika.

#### **11. Wyszukiwanie**
**Opis testu:** Weryfikacja funkcjonalności wyszukiwania produktów w aplikacji.

- **Kroki:**
  1. Użytkownik zalogowuje się na swoje konto.
  2. Użytkownik wprowadza kryteria wyszukiwania w pole wyszukiwania.
  3. Użytkownik naciska przycisk lub klawisz "Szukaj".
  4. System przetwarza zapytanie i wyświetla wyniki pasujące do podanych kryteriów.

- **Miara testu:**
  - **Pozytywny wynik:** System wyświetla poprawne wyniki wyszukiwania zgodne z podanymi kryteriami.
  - **Negatywny wynik:** System nie wyświetla żadnych wyników, wyświetla błędne wyniki lub aplikacja zawiesza się podczas wyszukiwania.

#### **12. Zamówienia**
**Opis testu:** Weryfikacja procesu składania zamówienia przez użytkownika.

- **Kroki:**
  1. Użytkownik zalogowuje się na swoje konto i znajduje się na stronie głównej.
  2. Użytkownik wybiera produkt, który chce zamówić.
  3. Użytkownik dodaje produkt do koszyka lub przechodzi od razu do procesu zamawiania.
  4. Użytkownik podaje niezbędne dane do zrealizowania zamówienia, takie jak adres dostawy, metoda płatności itp.
  5. Użytkownik potwierdza zamówienie.
- **Miara testu:**
  - **Pozytywny wynik:** Zamówienie jest pomyślnie złożone i widoczne w historii zamówień użytkownika.
  - **Negatywny wynik:** Nie można dokończyć procesu zamówienia z powodu błędów, zamówienie nie jest widoczne w historii zamówień użytkownika lub występują problemy z płatnością.

#### **13. Historia**
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

#### **14. Płatności**
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

#### **15. Konto premium**
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

#### **16. Status zamówienia**
**Opis testu:** Test sprawdzania statusu zamówienia przez użytkownika

- **Kroki:**
  1. Użytkownik loguje się do systemu.
  2. Użytkownik przechodzi do historii swoich zamówień.
  3. Użytkownik wybiera zamówienie, którego status chce sprawdzić.
  4. Użytkownik sprawdza status wybranego zamówienia.
- **Miara testu:**
  - **Pozytywny wynik:** Informacja o statusie zamówienia jest zgodna z aktualnym stanem i jest dla użytkownika zrozumiała.
  - **Negatywny wynik:** Informacja o statusie zamówienia jest niezgodna z aktualnym stanem lub nie jest dla użytkownika zrozumiała.

#### **17. Zarządzanie kontami użytkowników przez administratora**
**Opis testu:** Test zarządzania kontami użytkowników przez administratora

- **Kroki:**
  1. Administrator loguje się do panelu administracyjnego.
  2. Administrator przechodzi do sekcji zarządzania kontami użytkowników.
  3. Administrator przegląda listę wszystkich kont użytkowników.
  4. Administrator dodaje, edytuje lub usuwa wybrane konta.
- **Miara testu:**
  - **Pozytywny wynik:** Administracja kontami użytkowników przebiega zgodnie z oczekiwaniami, wszystkie zmiany są poprawnie zapisywane w systemie.
  - **Negatywny wynik:** Administracja kontami użytkowników napotyka na problemy, zmiany nie są zapisywane lub są zapisywane niepoprawnie.

#### **18. Subskrypcja diety**
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

## VIII. Procesy biznesowe
### 8.1 Identyfikacaj procesów biznesowych
- **Synchronizacja danych między stroną internetową a aplikacją mobilną:**
[Użytkownik dokonuje zmiany danych] Użytkownik zmienia dane, takie jak profil użytkownika, preferencje, ustawienia, zawartość, itp., zarówno na stronie internetowej, jak i w aplikacji mobilnej.[System wykrywa zmiany] System stale monitoruje aktywność użytkownika na obu platformach i wykrywa wszelkie zmiany w danych.[Inicjacja procesu synchronizacji] Po wykryciu zmian w danych na jednej z platform, system inicjuje proces synchronizacji, mający na celu zrównanie danych między stroną internetową a aplikacją mobilną.[Analiza różnic w danych] System analizuje różnice w danych między platformami, identyfikując, które dane wymagają synchronizacji.[Synchronizacja danych] Dane, które uległy zmianie na jednej z platform, są synchronizowane z odpowiednią platformą docelową.Proces synchronizacji obejmuje przesyłanie, aktualizację i zapisywanie danych na obu platformach w celu zapewnienia ich zgodności.

- **Aktualizacja produktów usługodawcy przez system** :
System codziennie sprawdza czy po stronie usługodawcy pojawiły się zmiany wśród produktów do sprzedaży, jeśl nie przechodzi do kolejengo usługodawcy tak długo aż sprawdzi wszystkich, jeśli tak to dokonuje aktualizacji produktów danego usługodawcy w systemie w przypadku dodanie nowego produktu zostaje wysłane powiadomienie od użytkowników którzy mają zasubskrybowany profil usługodawcy lub mają dokonaną niedawny zakup od tego usługodawcy oraz nie mają zablokowanych,

- **Dodawanie postów przez usługodawców** :
Usługodawca przechodzi do opcji dodawania nowego posta na swoim profilu.[Tworzenie treści posta]Usługodawca wprowadza treść posta, która może zawierać tekst, multimedia (zdjęcia, widea).[Personalizacja posta] Może   również dodawać hasztagi lub oznaczenia, aby treść była łatwiej odnajdywana przez użytkowników.[Dodawanie dodatkowych informacji] Jeśli to konieczne, usługodawca może dodać dodatkowe informacje, takie jak ceny, szczegóły, itp., w zależności od charakteru posta.[Podgląd i edycja] Przed opublikowaniem, usługodawca może obejrzeć podgląd posta, aby upewnić się, że wygląda on zgodnie z jego oczekiwaniami.W przypadku konieczności, może dokonać edycji treści lub układu posta.[Publikacja posta] Po zakończeniu tworzenia i personalizacji, usługodawca potwierdza publikację posta. Post staje się dostępny dla użytkowników do przeglądania.

- **Dodanie promocji przez usługodawca** :
Usługodawca po analizie sprzedaży sprzedaży decyduje się wystawić promocje przegląda listę swoich produktów wybiera odpowiednie produkty po wybraniu ustawia czas trwania promocji oraz procent zniżki po wybraniu wybiera opcję dodania promocji i system aktualizuje cenę, zostaje wysłane powiadomienie o promocji od użytkowników którzy mają zasubskrybowany profil usługodawcy lub mają dokonaną niedawny zakup od tego usługodawcy oraz nie mają zablokowanych powiadomień o promocjach.

- **Dostawa produktów** :
Powiadomienie firmy kurierskie o specyfikacji zamówienia i usługodawców poszczególnych części zamówienia. Kiedy minie odpowiedni czas kurier zaczyna realizować zamówienie zaczyna od zmiany statusu zamówienia w systemie, następnie kompletuje poszczególne części zamówienia od różnych dostawców/usługodawców jeśli jakiś z usługodawców nie będzie miał możliwości wydania zamówienie kurie zaznacza to w systemie a system wysyła powiadomienie do użytkownika który złożył to zamówienie o braku możliwości złożenia całego zamówienia i udziel mu stosownie kredyty na produkty usługodawcy który zawinił. Jeśli zamówienie zostanie skompletowane przez kuriera (pomijając produkty których nie mógł wystąpić usługodawca) Kurier aktualizuje status zamówienia i dostarcza zamówienie po czym klient odbiera zamówienie a kurie aktualizuje status dostawy. Do użytkownika, jeśli zamówienie nie mogło być dostarczone z powodu kuriera przyznawana jest stosowna rekompensata dla użytkownika na dowolne produkty.

- **Wystawianie recenzji przez użytkowników** :
Użytkownik poszukuję usługodawcę dla którego chce pozostawić recenzję.[Wybór produktu] Użytkownik wybiera konkretny produkt lub danie dla którego chce wystawić recenzję. [Wpisane recenzji] Użytkownik wprowadza tekst recenzji, w którym dzieli się swoją opinią na temat dania, diety lub usługodawcy. [Ocena w skali 5 gwiazdek] Użytkownik przypisuje ocenę produktu/usługodawcy w skali od 1 do 5 gwiazdek. [Potwierdzenie dodania recenzji] Po zakończeniu pisania recenzji i przypisania oceny, użytkownik sprawdza poprwaność swojej recenzji. Jeżeli dane są poprawne użytkownik potwierdza dodanie recenzji.

- **Przyznawanie kredytów jako rekompensata** :
[Zgłoszenie problemu przez użytkownika] Użytkownik informuje usługodawcę o problemie poprzez odpowiednią sekcję w systemie lub poprzez wystawienie recenzji. [Analiza problemu przez obsługę klienta] Zespół obsługi klienta analizuje zgłoszenie użytkownika, aby zrozumieć naturę problemu oraz określić, czy problem był po stronie usługodawcy czy też związany z dostawą.[Określenie przyczyny problemu] W przypadku, gdy problem wynikał z opóźnienia w dostawie lub uszkodzenia produktu, a było to związane z działaniem usługodawcy, przyznawane są kredyty jako rekompensata. Jeśli problem nie wynikał z winy usługodawcy (np. problem z kurierem), analizuje się sytuację, aby ustalić, czy kredyty będą przyznane jako rekompensata. [Pzyznanie kredytów] Jeśli problem był po stronie usługodawcy, kredyty są automatycznie przyznawane użytkownikowi jako rekompensata. Kredyty są dodawane do konta użytkownika i są dostępne do wykorzystania podczas kolejnych zakupów. [Warunki wykorzystania kredytów] Jeśli problem był po stronie usługodawcy, kredyty mogą być wykorzystane wyłącznie do zakupu produktów tego usługodawcy. Jeśli problem nie był po stronie usługodawcy, kredyty mogą być użyte do zakupu dowolnych produktów na platformie.[Powiadomienie użytkownika o przyznaniu kredytów] Użytkownik otrzymuje powiadomienie o przyznaniu kredytów jako rekompensaty za problem związany z dostawą lub produktem. Informacja ta zawiera również instrukcje dotyczące warunków wykorzystania kredytów.

- **Wykorzystanie kredytów podczas dokonywania zamówienia** :
[Wybór płatności] Po zakończeniu wyboru produktów, użytkownik przechodzi do procesu płatności. W trakcie tego kroku ma możliwość wyboru sposobu płatności, w tym także opcji wykorzystania posiadanych kredytów.[Użycie kredytów] Jeśli użytkownik posiada wystarczającą liczbę kredytów na koncie, może zdecydować się na ich wykorzystanie jako formy płatności za zamówienie. System automatycznie oblicza wartość kredytów, które można zastosować do zredukowania całkowitej kwoty do zapłaty.[Potwierdzenie płatności] Po wyborze opcji wykorzystania kredytów, użytkownik potwierdza swoją decyzję i dokonuje finalizacji zamówienia.Jeżeli ilość kredytów nie jest wystarczająca do całkowitej zapłaty za zamówienie, użtkownik musi wybrać inną metodę płatności dla pozostałej kwoty. System uwzględnia użyte kredyty podczas obliczania kwoty do zapłaty.[Zakończenie transakcji] Po pomyślnym potwierdzeniu płatności, zamówienie jest składane, a użytkownik otrzymuje potwierdzenie transakcji. Produkty zostają przygotowane do dostawy lub odbioru zgodnie z wybranymi preferencjami dostawy.

- **Dokonanie płatności** :
[PB Zakup produktów przez klienta]. [Przejście do płatności] Po zakończeniu wyboru produktów, użytkownik przechodzi do procesu płatności. W tym momencie może wybrać preferowany sposób płatności spośród dostępnych opcji: blikiem, kartą lub kredytem. [PB Wykorzystanie kredytów podczas dokonywania zamówienia]. W przypdku braku wystarczającej ilości kredytu lub odrzucenia tej opcji następuje [wybór opcji płatności] Użytkownik wybiera jedną z dostępnych opcji płatności:
  - Blik: Jeśli użytkownik wybiera płatność za pomocą blika, wprowadza odpowiedni kod autoryzacyjny wygenerowany przez aplikację bankową na swoim smartfonie.
  - Karta: W przypadku płatności kartą, użytkownik wprowadza dane karty płatniczej, takie jak numer karty, datę ważności i kod CVV.
      
[Potwierdzenie płatności] Po wyborze odpowiedniej opcji płatności, użytkownik potwierdza swoją decyzję. W przypadku płatności blikiem lub kartą, może być dodatkowo wymagane potwierdzenie autoryzacji transakcji za pomocą hasła, kodu SMS lub innej metody autoryzacyjnej. [Finalizacja płatności] Po pomyślnym potwierdzeniu płatności, system przetwarza transakcję. Kwota płatności zostaje obciążona z konta użytkownika, a zamówienie jest składane do realizacji.[Potwierdzenie zamowienia] Użytkownik otrzymuje potwierdzenie dokonania płatności oraz szczegóły zamówienia, w tym datę dostawy oraz podsumowanie zamówionych produktów/usług.

- **Rezygnacja z zakupu** :
Użytkownik przegląda historię zamówień wybiera zamówienie i wybiera zwrot jeśli do realizacji zamówienia jest mniej niż 24 godziny sytem pozwalu my wybrać konkretne produkty które chce zwrócić. Po wybraniu system symen aktualizuje zamówienie i wysyła informacje do usługodawców oraz firmy kurierskiej o zmianach w zamówienie i wypłaca użytkownikowi zwrot pieniędzy na konto.

- **Utrzymywanie systemu** :
System co miesiąc generuje raport związany wydajnościowy Zespół ds. obsługi technicznej analizuje raport i jeśli wynika z niego że jest zauważalny jest spadek wydajności zostają przeprowadzona analiza co jest przyczyną spadku wydajności. Po ustaleniu przyczyna przeprowadzana jest akutalizacja systemu mająca na celu rozwiązać problem

- **Reakcja na ataki/błędy** :
System w czasie monitorowania aktywności wykrywa nieprawidłowość wysyła wiadomośc do Zespół ds. obsługi technicznej. Zespół ds. obsługi technicznej dokonuje analizy zagrożeń dotyczących błędu. Jeśli błąd nie niesie ze sobą zagrożeń przechodzą do naprawy błędu. dokonuje naprawę po czym sprawdzają błąd został wyeliminowany i jeśli naprawa się nie powiodła ponownie dokonują naprawę, jeśli błąd wiąże się z zagrożeniami wycieku danych odpowiednie systemy są blokowane i Zespół ds. obsługi technicznej dokonuje naprawę po czym sprawdzają błąd został wyeliminowany i jeśli naprawa się nie powiodła ponownie dokonują naprawę , jeśli naprawa się powiodła Zespół ds. obsługi technicznej przywraca zablokowane części systemu.

## IX. UI
### 9.1 Ustalenia dotyczące wyglądu UI
Po ustaleniach z klientem ustaliliśmy wstępną wizję odnoszącą się do topoligi projektu wizualnego aplikacji:
- rodzaje czcionek używanych w projekcie
- paleta kolorów używana w projekcie 

Jeśli chodzi ogólny styl i wygląd aplikacji klijent zaproponował inspirować się już istniejącymi aplikacjiami działających w podobnej branży np.: Glovo czy Wolt.
Zatem navbar może zawierać logo, wyszukiwarkę, przyciski logowania/wylogowania, profilu użytkownika, historii zamówień itp.
Na stronie głównej powinno być wyświetlane najpopularniejsze oferty, rodzaje jedzenia, rodzaje dostawców, różne kuchnie.
Na dole strony powinna zawierać się stopka zwierające regulamin, dane kontaktowe itp.
Na razie są to ustalenia wstępne i klijent pozwolił na dowolność zepołowi designerskiemu. Ewntualne uwagi będą już zwracane do konkretnych widoków. 

## X. Słownik Dziedziny 
### 10.1 Terminologia biznesowa
**usługodawca** - firma kateringowa <br>
**użytkownik** - osoba zakupująca posiłki/diety w aplikacji <br>
**odpowiednie produkty** - produkty sezonowe zbierane lokalnie <br>
**kredyt** - forma wewnętrzych kuponów rozdawanych w ramacg rekompensata <br>
**system** - aplikacja która powstaje <br>
**przestażałe dane** - dane użytkowników wykorzystywane w zbieraniu statystyk, które zbierane było do roku temu oraz dane, które zostały zmienione
**powiadomienia niewyłączalne** - powiadomienia związane z zmianami w regulaminie, komunikatach wymuszanych prawnie

### 10.2 Terminologia techniczna
**post** - treść, hashy i ewentualne zdjęcie umieszczne przez usługodawcę w formie promocje, infrmacji <br>
**PWA** - progresywna aplikacja webowa stworzona w technologii, która pozwala uzyskać wrażenie, że tak przygotowana strona internetowa działa jak natywna aplikacja <br>
**hashtag** - służy do oznaczania treści (wpisów, zdjęć), aby łatwiej można je było wyszukiwać <br>
**zapytania użytkownika** - żądanie przesłane przez użytkownika do serwera internetowego w celu uzyskania określonych informacji, treści lub usług <br>
**szyforwanie danych** - zapisywanie danych wykorzystywanych przez system w sposób niejawny, aby wyciek z bazy danych nie spowodował ujawnienia informacji tam zapisanych <br>
**SQL injection** - technika ataku polegająca na wykorzystaniu luk w zabezpieczeniach aplikacji internetowej, które pozwalają na wstrzyknięcie złośliwego kodu SQL (Structured Query Language) do zapytań SQL wysyłanych do bazy danych przez aplikację <br>
**XSS** - Cross-Site Scripting to technika ataku polegająca na wstrzyknięciu złośliwego skryptu (najczęściej JavaScript) do treści strony internetowej lub danych przesyłanych do użytkownika przez aplikację internetową <br>
**CSRF** - Cross-Site Request Forgery to technika ataku, w której atakujący zmusza użytkownika do wykonania niechcianych działań na stronie internetowej, na którą jest zalogowany. Atak ten polega na wykorzystaniu zaufania przeglądarki do wywołania żądania HTTP w imieniu zalogowanego użytkownika, zazwyczaj poprzez przekierowanie go na złośliwą stronę <br>
**DDoS** - Distributed Denial of Service to rodzaj ataku, w którym wielka ilość złośliwego ruchu sieciowego jest kierowana na konkretny serwer, stronę internetową lub usługę online w celu spowodowania niedostępności dla prawidłowych użytkowników <br>
**Brute Force** -  technika ataku, która polega na próbie odgadnięcia hasła, klucza szyfrowania lub innej tajnej wartości poprzez wypróbowanie wszystkich możliwych kombinacji <br>
**testy odpornościowe** - to rodzaj testów oprogramowania, który ma na celu ocenę zdolności systemu informatycznego do radzenia sobie z nieprzewidywalnymi i niespodziewanymi sytuacjami oraz przywrócenia normalnego działania po wystąpieniu awarii lub zakłóceń <br>
**backup** - kopia zapasowych danych wykonywana w celu ich zabezpieczenia przed utratą, uszkodzeniem lub nieautoryzowanym dostępem <br>

### 10.3 Terminologia użytkownicza
**statystyki** - zbiór ogólnych reakcje użytkowników na posty, wyświetlania, zarobki z aplikacji <br>
**recenzja** - opinia użytkownika na temat dania lub usługodawcy <br>
**rodzaj diety** - wyłącznie nazwa <br>
**dieta** - pełen plan jedzeniowy na określony czas <br>
**rodzaj posiłeku** - np. śniadanie, oboad, kolacja <br>
**posiłek** - składa się z jednego lub więcej dań <br>
**danie** - składa się ze składników <br>
**produkt** - to co wystawi usługodawca do sprzedaży, czyli danie lub dieta.<br>
**status dzisiejszych zamówień** - zbiór informacji dotyczących zamówień, realizowanych danego dnia.
