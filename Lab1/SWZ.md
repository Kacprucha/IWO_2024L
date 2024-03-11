## Specyfikacja Wymagań Zamawiającego

### I. Wprowadzenie

  #### 1.1 Cel dokumentu
  Dokument ten będzie podstawą do dalszej pracy nad projektem, zawierając szczegółowy opis problemu biznesowego, wizję systemu, modele procesów biznesowych, listę przypadków użycia oraz wymagania jakościowe.

  #### 1.2 Zakres projektu
  System integrujący dostawców cateringu. Planowany system powinien umożliwiać integrację usług wielu takich dostawców w jednym miejscu. Dzięki temu możliwe będzie zamawianie posiłków od wielu dostawców w obrębie jednego zamówienia. W szczególności, dotyczy to możliwości łączenia posiłków od różnych dostawców w ramach diet dziennych, tygodniowych, miesięcznych itp.

  #### 1.3 Podział pracy na sekcje
  - Analitycy Biznesowi:
    - Jakub Wysocki *- 3.1 Ogólne wymagania funkcjonalne, 3.2 Szczegółowe funkcjonalności systemu*
    - Szymon Ochnio *- 3.3 Wymagania dotyczące wydajności, 3.4 Wymagania dotyczące bezpieczeństwa*
    - Mateusz Sobol *- II Opis Problemu Biznesowego i Celu Projektu*
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

  Przy każdej osobie zostało zaznaczone za jakie sekcje dokumentu była odpowiedzialna. **Specjaliści od Dokumentacji** mieli wspólne zadanie **nadzorowania tworzenia dokumentów innych członków** zespołu oraz **utworzenie wspólnego dokumentu** łączącego całość pracy zespołu. Dodatkowo słownik dziedziny powstawał wspólnie przez każdego z członków zespołu.

### II. Opis Problemu Biznesowego i Celu Projektu

  #### 2.1 Opis aktualnej sytuacji biznesowej
  Aktualnie na rynku znajduje się wiele usług kateringowych. Każda z nich posiada własną stronę internetową, wymagającą utworzenia konta. Stron z recenzjami jest wiele, ale często nie posiadają wszystkich dostępnych na rynku ofert.  Osoby poszukujące usług kateringowych, poświęcają dużo czasu na przeglądanie różnych stron internetowych oraz analizowanie recenzji. Nawet jak znajdą interesującą ich ofertę, często nie zadowala ich w pełni i są zmuszeni do korzystania z wielu usług kateringowych.

  #### 2.2 Problemy i wyzwania
  Największym wyzwaniem będzie zapewnienie jak największej dostępności systemu. System musi być wielojęzyczny, wieloplatformowy oraz niezawodny, aby dotrzeć do jak największej liczby klientów. Ponadto, dużym wyzwaniem stanowić będzie komunikacja z usługami kateringowymi.

  #### 2.3 Cel projektu
  Celem jest utworzenie systemu informatycznego, który zbierałby oferty kateringowe w jednym miejscu i umożliwiał użytkownikowi szybkie i łatwe odnalezienie ofert. Ponadto, użytkownik mógłby zamawiać różne dania z różnych firm w formie jednego posiłku oraz zamawiać spersonalizowane diety. System ma być też platformą dla producentów, gdzie mogą się reklamować w formie postów publikowanych w ramach profilu producenta oraz zdobyć dostęp do większej ilości klientów.

  #### 2.4 Korzyści płynące z realizacji projektu
  Firmy kateringowe otrzymują możliwość łatwego i bezpiecznego publikowania swoich ofert oraz przeglądania swoich statystyk. Ponadto, mają możliwość reklamowania swoich ofert i zdobycia dostępu do większej ilości klientów. 
  Dla użytkowników główną korzyścią jest zwiększenie wygody.Mogą oni w łatwy sposób odnaleźć usługi kateringowe, mieszać ich oferty oraz sprawdzać recenzje. Otrzymują łatwy system śledzenia promocji, a dodatkowo otrzymują rekomendację na podstawie historii zamówień, co pozwala im na odkrywanie nowych dań.

### III. Lista Kluczowych Funkcjonalności i Wymagań Biznesowych

  #### 3.1 Ogólne wymagania funkcjonalne
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

  #### 3.2 Szczegółowe funkcjonalności systemu 
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

  #### 3.3 Wymagania dotyczące wydajności 

  #### 3.4 Wymagania dotyczące bezpieczeństwa 

### IV. Identyfikacja Interesariuszy Projektu 

  #### 4.1 Definicja interesariuszy
  Interesariuszami w projekcie są firmy kateringowe, osoby kupujace usługi kateringowe, firma zamawiająca system.

  #### 4.2 Opis roli każdego interesariusza
  Firma kateringowa pełni rolę udostępniającego usługi kateringowe dla aplikacji. <br>
  Osoby kupujące usługi kateringowe to użytkownicy aplikacji bez nich aplikacji nie istnieje. Są grupą docelową projektu. <br>
  Firma zamawiająca ma kierować działaniami projektu, pnieważ to oni stoją za jego wizją.

  #### 4.3 Oczekiwania i potrzeby interesariuszy
  Firmy katerignowe oczekują platformy, która zwiększy sprzedaż ich usług i zarazem przestrzeni do reklamy poprzez publikowanie postów. <br>
  Osoby kupujące chcą mieć łatwy dostęp do szerokiej oferty kateringowej i personalizować w dowolny sposób plan jedzeniowy. <br>
  Firma zamawiająca chce zarobić na aplikacji za pomocą programów premium dla użytkowników aplikacji.

  #### 4.4 Potencjalne konflikty interesów
  Potęcjalne konflikty mogą powstać na linii firm kateringowych i firm zamawiajacych, ponieważ firmy kateringowe nie bedą chciały być przedstawiane w jednym miejscu z innymi konkurentami lub uznają że zysk z wzięcia udziału w takim przedsięwzieciu nie będzie wart spełnienia wymagań firmy zamawiającej aplikacjie. Konflikt interesów może też powstać na linie firma zamawiająca użytkownicy gdy właścicele waplikacji zarządają zbyt duzych cen za plany premium bez odpowiednich benefitów. W takim wypadku użytkownicy nie będą ich kupować, a właścicle nie zarobi zamierzonej kwoty.

### V. Wymagania Jakościowe i Ograniczenia

  #### 5.1 Wizja systemu 
  System będzie wykonany w formie aplikacji PWA komunikującej się z serwerem i bazą danych poprzez web api. Pozwoli to na zapewnienie poprawnego działania i takiego samego user experience niezależnie od urządzenia z którego korzysta użytkownik (przeglądarka, telefon, tablet itp.).
  
  Dane użytkowników będą przechowywane w bezpieczny sposób w centralnej bazie danych. Niektóre dane dotyczące np. preferencji użytkownika mogą być również przechowywane lokalnie np. w ciastkach lub w pamięci przeglądarki. 
  
  Płatności będą obsługiwane przez zewnętrznego dostawcę, co zapewni niezawodność i jak najlepsze doświadczenie użytkownika, będzie mógł wybrać najczęściej używane formy płatność jak blik lub płatność kartą debetową/kredytową, a sama płatność będzie przeprowadzana sprawnie.
  
  Skalowalość i niezawodność systemu zapewni dostawca usług chmurowych dzięki zastosowaniu rozwiązań serverless. Dzięki temu zarówno baza danych jak i web api będą elastyczne i będą mogły odpowiednio dostosowywać moc obliczeniową systemu do obciążenia, co pozwoli na poprawne działanie systemu w przypadku np. nagłego zwiększenia odwiedzeń strony. Za pośrednictwem dostawcy usług chmurowych administrator systemu będzie również miał dostęp do wszelakich danych telemetrycznych pozwalających na szybkie i skuteczne diagnozowanie usterek.
  
  #### 5.2 Lista cech systemu 
  
  #### 5.3 Wymagania dotyczące wydajności

  #### 5.4 Wymagania dotyczące bezpieczeństwa 

  #### 5.5 Wymagania dotyczące niezawodności 

  #### 5.6 Ograniczenia środowiskowe 

### VI. Opracowanie i dokumentowanie przypadków użycia

  #### 6.1 Zrozumienie wymagań 

  #### 6.2 Identyfikacja aktorów 

  #### 6.3 Lista przypadków użycia 

  #### 6.4 Opisy przypadków użycia 

### VII. Słownik Dziedziny 
  #### 7.1 Terminologia biznesowa
  **usługodawca** - firma kateringowa <br>
  **odpowiednie produkty** - produkty sezonowe zbierane lokalnie <br>
  **kredyt** - forma wewnętrzych kuponów rozdawanych w ramacg rekompensata <br>

  #### 7.2 Terminologia techniczna
  **post** - treść, hashy i ewentualne zdjęcie umieszczne przez usługodawcę w formie promocje, infrmacji <br>

  #### 7.3 Terminologia użytkownicza
  **statystyki** - zbiór ogólnych reakcje użytkowników na posty, wyświetlania, zarobki z aplikacji <br>
  **recenzja** - opinia użytkownika na temat dania lub usługodawcy <br>
  **rodzaj diety** - wyłącznie nazwa <br>
  **dieta** - pełen plan jedzeniowy na określony czas <br>
  **rodzaj posiłeku** - np. śniadanie, oboad, kolacja <br>
  **posiłek** - składa się z jednego lub więcej dań <br>
  **danie** - składa się ze składników <br>
