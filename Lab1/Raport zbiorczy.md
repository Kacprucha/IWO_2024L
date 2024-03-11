# Raport zbiorczy
*Sprawdzili: Angelina Sudenkova, Szymon Rogoziński, Igor Kędzierawski, Julia Owczarczyk.*

## Treść dokumentu
  #### II. Opis Problemu Biznesowego i Celu Projektu
-   ##### 2.1 [Opis aktualnej sytuacji biznesowej](#21-opis-aktualnej-sytuacji-biznesowej)
-   ##### 2.2 [Problemy i wyzwania](#22-problemy-i-wyzwania)
-   ##### 2.3 [Cel projektu](#23-cel-projektu)
-   ##### 2.4 [Korzyści płynące z realizacji projektu](#24-korzyści-płynące-z-realizacji-projektu)
  #### III. Lista Kluczowych Funkcjonalności i Wymagań Biznesowych
-   ##### 3.1 [Ogólne wymagania funkcjonalne](#31-ogólne-wymagania-funkcjonalne)
-   ##### 3.2 [Szczegółowe funkcjonalności systemu](#32-szczegc3b3c582owe-funkcjonalnoc59bci-systemu-1)
-   ##### 3.3 [Wymagania dotyczące wydajności](#33-wymagania-dotyczc485ce-wydajnoc59bci-1) 
-   ##### 3.4 [Wymagania dotyczące bezpieczeństwa](#34-wymagania-dotyczc485ce-bezpieczec584stwa-1) 
  #### IV. Identyfikacja Interesariuszy Projektu
-   ##### 4.1 [Definicja interesariuszy](#41-definicja-interesarius)
-   ##### 4.2 [Opis roli każdego interesariusza](#42-opis-roli-kac5bcdego-interesarius-1)
-   ##### 4.3 [Oczekiwania i potrzeby interesariuszy](#43-oczekiwania-i-potrzeby-interesarius)
-   ##### 4.4 [Potencjalne konflikty interesów](#44-potencjalne-konflikty-interes)
 #### V. Wymagania Jakościowe i Ograniczenia
-   ##### 5.1 [Wizja systemu](#51-wizja-systemu) 
-   ##### 5.2 [Lista cech systemu](#52-lista-cech-systemu)
-   ##### 5.3 [Wymagania dotyczące wydajności](#53-wymagania-dotyczc485ce-wydajnoc59bci-1)
-   ##### 5.4 [Wymagania dotyczące bezpieczeństwa](#54-wymagania-dotyczc485ce-bezpieczec584stwa-1) 
-   ##### 5.5 [Wymagania dotyczące niezawodności](#55-wymagania-dotyczc485ce-niezawodnoc59bci-1)
-   ##### 5.6 [Ograniczenia środowiskowe](#56-ograniczenia-c59brodowiskowe-1) 
 #### VI. Opracowanie i dokumentowanie przypadków użycia
-   ##### 6.1 [Zrozumienie wymagań](#61-zrozumienie-wymagac584-1)
-   ##### 6.2 [Identyfikacja aktorów](#62-identyfikacja-aktorów) 
-   ##### 6.3 [Lista przypadków użycia](#63-lista-przypadkc3b3w-uc5bcycia-1)
-   ##### 6.4 [Opisy przypadków użycia](#64-opisy-przypadkc3b3w-uc5bcycia-1)
 ### VII. Słownik Dziedziny
-   ##### 7.1 [Terminologia biznesowa](#71-terminologia-biznesowa)
-   ##### 7.2 [Terminologia techniczna](#72-terminologia-techniczna)
-   ##### 7.3 [Terminologia użytkownicza](#73-terminologia-uc5bcytkownicza-1)

## II. Opis Problemu Biznesowego i Celu Projektu

-   ### 2.1 Opis aktualnej sytuacji biznesowej{#21-opis-aktualnej-sytuacji-biznesowej}

    Aktualnie na rynku znajduje się wiele usług cateringowych, które są rozproszone. A osoby chcącę spersjonalizować swoją dietę muszą korzystać z wielu systemów aby zamówić posiłki z firm, których je interesują.

    _Mateusz Sobol_

    Aktualnie na rynku znajduje się wiele usług kateringowych. Każda z nich posiada własną stronę internetową, wymagającą utworzenia konta. Stron z recenzjami jest wiele, ale często nie posiadają wszystkich dostępnych na rynku ofert. Osoby poszukujące usług kateringowych, poświęcają dużo czasu na przeglądanie różnych stron internetowych oraz analizowanie recenzji. Nawet jak znajdą interesującą ich ofertę, często nie zadowala ich w pełni i są zmuszeni do korzystania z wielu usług kateringowych.

-   ### 2.2 Problemy i wyzwania{#22-problemy-i-wyzwania}

    Problemem jest właśnie rozporszony stan usług. Wyzwaniem może być przyciągnięcie firm do zewnętrznego systemu oraz ujednolicić ofery kateringowe aby aplikacja była spójna.

    _Mateusz Sobol_

    Największym wyzwaniem będzie zapewnienie jak największej dostępności systemu. System musi być wielojęzyczny, wieloplatformowy oraz niezawodny, aby dotrzeć do jak największej liczby klientów. Ponadto, dużym wyzwaniem stanowić będzie komunikacja z usługami kateringowymi.

-   ### 2.3 Cel projektu{#23-cel-projektu}

    Celem jest utworzenie systemu informatycznego, który zbierał by oferty kateringowe w jednym miejscu u umozliwiał by użytkownikowi zamawianie róznych dań z różnych firm w formie jednego posiłku oraz zamawianie spersonalizowanych diet. System ma być też platformą dla producentów gdzie mogą się reklamować w formie postów publikowanych w ramach profilu producenta.

    _Mateusz Sobol_

    Celem jest utworzenie systemu informatycznego, który zbierałby oferty kateringowe w jednym miejscu i umożliwiał użytkownikowi szybkie i łatwe odnalezienie ofert. Ponadto, użytkownik mógłby zamawiać różne dania z różnych firm w formie jednego posiłku oraz zamawiać spersonalizowane diety. System ma być też platformą dla producentów, gdzie mogą się reklamować w formie postów publikowanych w ramach profilu producenta oraz zdobyć dostęp do większej ilości klientów.

-   ### 2.4 Korzyści płynące z realizacji projektu{#24-korzyści-płynące-z-realizacji-projektu}

    Znaczącą korzyścią jest scenatralizowanie firm kateringowych w jedynym systemie dzięki czemu użytkownicy mogą szysbciej znaleść interesującą ich ofertę oraz przedewszystkim zamawiać dania z jednego miejsca na raz. Ponadto firmy kateringowe dostają platformę do reklamy własnych usług oraz do dotarcia do osób, które są zainteresowane ich działalnością.

    _Mateusz Sobol_

    Firmy kateringowe otrzymują możliwość łatwego i bezpiecznego publikowania swoich ofert oraz przeglądania swoich statystyk. Ponadto, mają możliwość reklamowania swoich ofert i zdobycia dostępu do większej ilości klientów.
    Dla użytkowników główną korzyścią jest zwiększenie wygody. Mogą oni w łatwy sposób odnaleźć usługi kateringowe, mieszać ich oferty oraz sprawdzić recenzje. Otrzymują łatwy system śledzenia promocji, a dodatkowo otrzymują rekomendację na podstawie historii zamówień, co pozwala im na odkrywanie nowych dań.

## III. Lista Kluczowych Funkcjonalności i Wymagań Biznesowych

-   ### 3.1 & 3.2 Wymagania funkcjonalne{#31-ogólne-wymagania-funkcjonalne}

    _Jakub Wysocki_

    -   **Synchronizacja**: Interfejs użytkownika, składający się z strony internetowej i aplikacji mobilnej,
        powinien zapewniać synchronizację danych między nimi.

    -   **Powiadomienia**: Automatyczne powiadomienia dla użytkownika, dotyczące promocji, nowych ofert, statusu
        dostawy, zmiany regulaminu, powiadomienia promocyjne i ofertowe, możliwe do wyłączenia.

    -   **Wielojęzyczność**: Obecnie działamy tylko na rynku polskim, ale interfejs ma być wielojęzyczny z
        dostępnymi językami Polskim, Angielskim, Ukraińskim.

    -   **Posty**: Usługodawcy mają możliwość dodawania postów na swoje profile. Posty składają się z tekstu,
        zdjęć i hashtagów. Użytkownicy mogą reagować na posty poprzez udzielanie polubień.

    -   **Recenzje**: Użytkownicy mogą wystawiać recenzje pod konkretnymi daniami i dietami usługodawcy,
        jeśli zostały one zakupione. Recenzje zawierają tekst i ocenę w skali 5 gwiazdek. Inni użytkownicy
        mogą reagować na recenzję lajkami.

    -   **Polubienia**: Użytkownicy mogą zostawiać polubienia pod postami, daniami, co wpływa na przyszłe
        rekomendacje dla nich.

    -   **Zbieranie statystyk**: Usługodawcy mogą przeglądać statystyki swoich postów, dań i diet, takie jak
        polubienia, recenzje, ilość zakupów oraz mapę z podziałem na regiony i ilością zakupów z danego regionu.

    -   **Kredyty**: Kredyty są przyznawane jako rekompensata za problemy z dostawą lub dostarczonym produktem.
        Są one równoznaczne z pieniędzmi i można za nie kupić inne produkty. Jeśli problem leży po stronie usługodawcy,
        kredyty można użyć tylko do zakupu jego produktów. W przeciwnym razie można je wykorzystać do zakupu dowolnego produktu.

    -   **Subskrypcje**: Użytkownik może subskrybować danego usługodawcę, co sprawia, że jego posty są częściej polecane.

    -   **Główna strona użytkownika**: Rekomendacje dla użytkownika oparte na ostatnich zakupach i subskrypcjach.

    -   **Wyszukiwanie**: Użytkownicy mają dostęp do wyszukiwarki usługodawców oraz wyszukiwarki dań/diet. Wyszukiwarka pozwala
        ustawić filtry i sortować wyniki po takich parametrach jak nazwa, cena, zawartość składników.

    -   **Zamówienia**: Użytkownicy mogą dodawać różne dania od różnych usługodawców do koszyka. Dostarczane są one razem
        w ramach jednego zamówienia. Istnieje także możliwość wykupienia subskrypcji konkretnej diety, która automatycznie
        pobiera opłatę z konta użytkownika.

    -   **Historia**: Użytkownik ma dostęp do historii zamówień oraz listy opłaconych subskrypcji.
        Zamówienia dostarczane w czasie dłuższym niż 24 godziny mogą zostać anulowane.

    -   **Wystawianie produktów**: Usługodawca może wystawić do sprzedaży konkretne danie lub dietę.
        Możliwe jest dostarczanie w wybranej przez użytkownika porze dnia. Opis zawartości składników jest dostępny dla każdego dania.

    -   **Płatności**: Użytkownik może dokonywać płatności za pomocą Blika, karty, lub kredytu.

    -   **Konto premium**: Użytkownik może zakupić konto premium, umożliwiające darmowe dostawy.

    -   **Status zamówienia**: Użytkownik może sprawdzić status zamówienia, informujący na jakim etapie dostarczania się znajduje.

    -   **Konta**: Występują trzy rodzaje kont: usługodawca, użytkownik, admin.

-   ### 3.3 Wymagania dotyczące wydajności{#33-wymagania-dotyczc485ce-wydajnoc59bci-1}

    _Szymon Ochnio_

    -   **Zapewnienie użytkownikom szybkiego dostępu do aplikacji**

        -   **Cel:** Chcemy, aby nasi użytkownicy mogli łatwo i szybko korzystać z naszej aplikacji webowej
            i mobilnej, minimalizując czas ładowania aplikacji.
        -   **Oczekiwane rezultaty:** Jak najkrótszy czas ładowania aplikacji.

    -   **Dostarczenie szybkich odpowiedzi na zapytania użytkowników**

        -   **Cel:** Chcemy reagować na zapytania naszych użytkowników w sposób jak najszybszy.
        -   **Oczekiwane rezultaty:** Jak najkrótszy czas odpowiedzi na zapytania użytkowników.

    -   **Zapewnienie skalowalności systemu**

        -   **Cel:** Chcemy, aby nasz system był zdolny do obsługi wzrostu liczby użytkowników i dostawców bez utraty wydajności.
        -   **Oczekiwane rezultaty:** Skalowalność i stabilność pomimo wzrostu liczby użytkowników.

    -   **Szybkie przetwarzanie płatności za zamówienia**

        -   **Cel:** Chcemy, aby proces płatności za zamówienia był jak najbardziej płynny i szybki dla naszych użytkowników.
        -   **Oczekiwane rezultaty:** Jak najkrótszy czas przetwarzania płatności.

    -   **Dostarczanie natychmiastowych powiadomień**
        -   **Cel:** Chcemy, aby nasze powiadomienia docierały do użytkowników niemal natychmiast po ich wygenerowaniu.
        -   **Oczekiwane rezultaty:** Jak najkrótszy czas dostarczania powiadomień.

-   ### 3.4 Wymagania dotyczące bezpieczeństwa{#34-wymagania-dotyczc485ce-bezpieczec584stwa-1}

    _Szymon Ochnio_

    -   **Silna ochrona danych osobowych**

        -   **Cel:** Naszym priorytetem jest zapewnienie bezpieczeństwa danych naszych użytkowników.
            Dążymy do tego, by były one nie tylko odpowiednio zabezpieczone, ale także transmitowane w bezpieczny sposób.
        -   **Oczekiwane rezultaty:** Spełnienie standardów bezpieczeństwa dotyczących przechowywania danych.

    -   **Silne uwierzytelnianie i autoryzacja użytkowników**

        -   **Cel:** Wszystkie procesy uwierzytelniania i autoryzacji w systemie powinny być zabezpieczone silnymi,
            niezawodnymi mechanizmami, zgodnymi z obowiązującymi standardami bezpieczeństwa.
        -   **Oczekiwane rezultaty:** Bezpieczne i skuteczne procesy autoryzacji i autentykacji użytkowników.

    -   **Określone role dostępu**

        -   **Cel:** Chcemy zapewnić, że każda kategoria użytkowników (od użytkowników indywidualnych, poprzez dostawców,
            aż do administratorów) ma odpowiednio zdefiniowane role i uprawnienia w systemie.
        -   **Oczekiwane rezultaty:** Skuteczne zarządzanie uprawnieniami użytkowników.

    -   **Odporność na ataki internetowe**

        -   **Cel:** Naszym celem jest wprowadzenie skutecznych mechanizmów obronnych, które minimalizują ryzyko wszelkiego
            rodzaju ataków internetowych.
        -   **Oczekiwane rezultaty:** Odporność na ataki hakerskie.

    -   **Monitorowanie aktywności**

        -   **Cel:** Chcemy skutecznie monitorować działania w naszym systemie, aby szybko wykrywać wszelkie nieprawidłowości
            i podejrzane działania.
        -   **Oczekiwane rezultaty:** Monitorowanie i zapisywanie istotnych zdarzeń w systemie.

## IV. Identyfikacja Interesariuszy Projektu

-   ### 4.1 Definicja interesariuszy{#41-definicja-interesarius}

    Interesariuszami w projekcie są firmy kateringowe, osoby kupujace usługi kateringowe, firma zamawiająca system.

-   ### 4.2 Opis roli każdego interesariusza{#42-opis-roli-kac5bcdego-interesarius-1}

    Firma kateringowa pełni rolę udostępniającego usługi kateringowe dla aplikacji. <br>
    Osoby kupujące usługi kateringowe to użytkownicy aplikacji bez nich aplikacji nie istnieje. Są grupą docelową projektu. <br>
    Firma zamawiająca ma kierować działaniami projektu, pnieważ to oni stoją za jego wizją.

-   ### 4.3 Oczekiwania i potrzeby interesariuszy{#43-oczekiwania-i-potrzeby-interesarius}

    Firmy katerignowe oczekują platformy, która zwiększy sprzedaż ich usług i zarazem przestrzeni do reklamy poprzez publikowanie postów. <br>
    Osoby kupujące chcą mieć łatwy dostęp do szerokiej oferty kateringowej i personalizować w dowolny sposób plan jedzeniowy. <br>
    Firma zamawiająca chce zarobić na aplikacji za pomocą programów premium dla użytkowników aplikacji.

-   ### 4.4 Potencjalne konflikty interesów{#44-potencjalne-konflikty-interes}

    Potencjalne konflikty mogą powstać na linii firm kateringowych i firm zamawiajacych, ponieważ firmy kateringowe nie bedą chciały być przedstawiane w jednym miejscu z innymi konkurentami lub uznają że zysk z wzięcia udziału w takim przedsięwzieciu nie będzie wart spełnienia wymagań firmy zamawiającej aplikacjie. Konflikt interesów może też powstać na linie firma zamawiająca użytkownicy gdy właścicele waplikacji zarządają zbyt duzych cen za plany premium bez odpowiednich benefitów. W takim wypadku użytkownicy nie będą ich kupować, a właścicle nie zarobi zamierzonej kwoty.

## V. Wymagania Jakościowe i Ograniczenia

-   ### 5.1 Wizja systemu{#51-wizja-systemu}

    _Krzysztof Jurkowski_

    System będzie wykonany w formie aplikacji PWA komunikującej się z serwerem i bazą danych poprzez web api.
    Pozwoli to na zapewnienie poprawnego działania i takiego samego user experience niezależnie od urządzenia
    z którego korzysta użytkownik (przeglądarka, telefon, tablet itp.).

    Dane użytkowników będą przechowywane w bezpieczny sposób w centralnej bazie danych. Niektóre dane dotyczące
    np. preferencji użytkownika mogą być również przechowywane lokalnie np. w ciastkach lub w pamięci przeglądarki.

    Płatności będą obsługiwane przez zewnętrznego dostawcę, co zapewni niezawodność i jak najlepsze doświadczenie
    użytkownika, będzie mógł wybrać najczęściej używane formy płatność jak blik lub płatność kartą debetową/kredytową,
    a sama płatność będzie przeprowadzana sprawnie.

    Skalowalość i niezawodność systemu zapewni dostawca usług chmurowych dzięki zastosowaniu rozwiązań serverless.
    Dzięki temu zarówno baza danych jak i web api będą elastyczne i będą mogły odpowiednio dostosowywać moc obliczeniową
    systemu do obciążenia, co pozwoli na poprawne działanie systemu w przypadku np. nagłego zwiększenia odwiedzeń strony.
    Za pośrednictwem dostawcy usług chmurowych administrator systemu będzie również miał dostęp do

-   ### 5.2 Lista cech systemu{#52-lista-cech-systemu}

    _Krzysztof Jurkowski_ i _Mateusz Czarnecki_

    -   #### Architektura Systemu

        -   System składa się z 3 części: aplikacji PWA, web API i bazy danych.
        -   Skalowalność i elastyczność z wykorzystaniem rozwiązań chmurowych.

    -   #### Dostępność i Bezpieczeństwo

        -   System jest dostępny 24/7.
        -   Silne szyfrowanie i bezpieczne przechowywanie danych użytkowników.
        -   Wsparcie dla wielu dostawców z systemem ocen i rekomendacji.

    -   #### Wielojęzyczność i Personalizacja

        -   System zapewnia takie same funkcjonalności niezależnie od platformy (web/mobilna).
        -   System jest dostępny w wielu językach.
        -   System pamięta preferencje językowe użytkownika.
        -   Możliwość zarządzania subskrypcjami i preferencjami użytkowników.

    -   #### Powiadomienia

        -   System oferuje wysyłanie powiadomień do użytkownika zarówno o dostawach jak i promocyjnych.
        -   System umożliwia wyłączenie powiadomień.
        -   Zintegrowane powiadomienia z możliwością zarządzania przez użytkownika.

    -   #### Zarządzanie Ofertą i Statystykami

        -   System umożliwia firmie kateringowej zarządzać swoją ofertą.
        -   System umożliwia firmie kateringowej publikować aktualizacje w formie postów.
        -   System umożliwia firmie kateringowej przeglądanie statystyk (reakcje użytkowników na posty, wyświetlenia, przychód z aplikacji).

    -   #### Interakcja Użytkownika z Ofertami

        -   System umożliwia użytkownikowi przeglądanie oferty wielu firm kateringowych.
        -   System umożliwia użytkownikowi przeglądanie i reagowanie na posty usługodawców.
        -   System umożliwia użytkownikowi składanie zamówień.
        -   System umożliwia użytkownikowi opłacanie zamówień poprzez kredyt, blik oraz kartę debetową/kredytową.
        -   System umożliwia użytkownikowi doładowanie swojego kredytu poprzez blik lub kartę debetową/kredytową.
        -   System umożliwia użytkownikowi anulowanie swojego zamówienia do 24 godzin przed planowanym dostarczeniem.
        -   System proponuje użytkownikowi rekomendowane oferty na podstawie jego poprzednich zamówień.

    -   #### Wyszukiwanie, Sortowanie i Filtrowanie Ofert

        -   System pozwala użytkownikowi wyszukiwać oferty po:
            -   dostawcy
            -   nazwie dania
            -   składnikach
            -   nazwie diety
        -   System pozwala użytkownikowi sortować oferty po:
            -   ocenie użytkowników
            -   cenie
        -   System pozwala użytkownikowi filtrować oferty po:
            -   diecie
            -   alergenach.

    -   #### Interakcje z Produktami

        -   System pozwala użytkownikowi na dodawanie dań do ulubionych.
        -   System pozwala użytkownikowi na wystawienie recenzji nt. dania i usługi do miesiąca po wykonaniu zamówienia.
        -   System pozwala użytkownikowi na przeglądanie recenzji produktów i reagowanie na nie.
        -   System umożliwia użytkownikowi przeglądanie historii swoich zamówień.
        -   System umożliwia użytkownikowi na przeglądanie statusu dzisiejszych zamówień.

    -   #### Integracje i Synchronizacja

        -   Obsługa różnych form płatności (blik, karty debetowe/kredytowe).
        -   Automatyczna synchronizacja danych między aplikacją webową a mobilną.
        -   Integracja z zewnętrznymi systemami dostaw i płatności dla optymalizacji procesów.

-   ### 5.3 Wymagania dotyczące wydajności{#53-wymagania-dotyczc485ce-wydajnoc59bci-1}

    _Filip Sosnowski_ i _Mateusz Czarnecki_

    -   #### System powinien osiągać minimalny czas ładowania aplikacji webowej i mobilnej

        -   **Opis:** Średni czas ładowania aplikacji webowej i mobilnej nie powinien przekroczyć 2 sekund, maksymalnie może wynosić 3 sekundy.
        -   **Sposób pomiaru:** Pomiar czasu ładowania aplikacji. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
        -   **Możliwy wynik pomiaru:** Czas mierzymy z dokładnością do 0.1 sekundy do 3 sekund (powyżej 3 sekund uznaje się, że system nie załadował aplikacji wystarczająco szybko).
        -   **Oczekiwane wartości:** Czas ładowania aplikacji webowej i mobilnej nie przekraczający 2 sekund.

    -   #### System powinien zapewniać jak najmniejszy czas odpowiedzi na zapytania użytkowników

        -   **Opis:** System powinien odpowiadać na zapytania użytkowników w czasie nie przekraczającym 0.5 sekundy, maksymalnie może wynosić 1 sekundę.
        -   **Sposób pomiaru:** Pomiar czasu odpowiedzi na zapytanie użytkownika. Mierzymy czas dla 1000 prób i wyliczamy średnią z pomiarów.
        -   **Możliwy wynik pomiaru:** Czas mierzony z dokładnością 0.01 sekundy od 0.01 sekundy do 1 sekundy (powyżej 1 sekundy uznaje się, że użytkownik nie otrzymał odpowiedzi od systemu wystarczająco szybko)
        -   **Oczekiwane wartości:** Średni czas odpowiedzi na zapytanie użytkownika nie przekracza 0.5 sekundy, najgorszy czas wynosi poniżej 1 sekundy.

    -   #### System powinien być skalowalny

        -   **Opis:** System powinien sprawnie dostosowywać się do zmian w liczbie użytkowników i dostawców, utrzymując podobną wydajność. W przypadku wzrostu liczby użytkowników i dostawców o 100-krotność, system powinien efektywnie obsługiwać wszystkie operacje.
        -   **Sposób pomiaru:** Ocena zdolności systemu do obsługi rosnącej liczby użytkowników. Testy wydajnościowe przeprowadzane w warunkach zbliżonych do produkcyjnych, mierzące czas odpowiedzi na operacje w zależności od liczby użytkowników korzystających z aplikacji w tym samym momencie.
        -   **Możliwy wynik pomiaru:** System obsługuje wzrost liczby użytkowników i dostawców o 100-krotność, utrzymując stabilność oraz akceptowalne czasy odpowiedzi na zapytania.
        -   **Oczekiwane wartości:** Skuteczna skalowalność systemu przy wzroście do 100-krotności obecnej liczby użytkowników. System powinien utrzymywać średni czas odpowiedzi poniżej 0.5 sekundy oraz poniżej 1 sekundy przy maksymalnym obciążeniu.

    -   #### System powinien szybko przetwarzać płatności za zamówienia

        -   **Opis:** Średni czas przetwarzania płatności, od chwili zatwierdzenia transakcji do uzyskania potwierdzenia, nie powinien przekraczać 5 sekund. Maksymalnie może być dwa razy dłuższy.
        -   **Sposób pomiaru:** Pomiar czasu przetwarzania płatności online. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
        -   **Możliwy wynik pomiaru:** Czas mierzony z dokładnością do 0.1 sekundy od zatwierdzenia do potwierdzenia, w przedziale od 0.1 sekundy do 10 sekund (powyżej 10 sekund uznaje się, że przetwarzanie płatności było zbyt długie).
        -   **Oczekiwane wartości:** Czas przetwarzania płatności online nie przekraczający 5 sekund, w najgorszym przypadku w czasie mniejszym niż 10 sekund.

    -   #### System powinien obsługiwać natychmiastowe powiadomienia
        -   **Opis:** Powiadomienia powinny być dostarczane użytkownikom w czasie nie przekraczającym 2 sekund po ich wygenerowaniu, maksymalnie w czasie dwa razy dłuższym.
        -   **Sposób pomiaru:** Pomiar czasu dostarczania powiadomień do użytkowników. Wyniki mierzymy dla 100 prób i wyliczamy średnią z pomiarów.
        -   **Możliwy wynik pomiaru:** Czas dostarczania powiadomień mierzony z dokładnością do 0.1 sekundy, w przedziale od 0.1 sekundy do maksymalnie 2 sekund (powyżej 2 sekund uznaje się za opóźnienie w dostarczeniu powiadomienia).
        -   **Oczekiwane wartości:** Czas dostarczenia powiadomień do użytkowników nie przekraczający 2 sekund, w najgorszym przypadku w czasie mniejszym niż 4 sekundy.

-   ### 5.4 Wymagania dotyczące bezpieczeństwa{#54-wymagania-dotyczc485ce-bezpieczec584stwa-1}

    _Filip Sosnowski_ i _Karol Zalewski_

    -   #### System bezpieczeństwa

        -   **System musi silnie szyfrować i bezpiecznie przechowywać dane osobowe użytkowników**

            -   **Opis:** Dane osobowe klientów muszą być bezpiecznie przechowywane i przesyłane.
            -   **Sposób pomiaru:** Audyty bezpieczeństwa, które mają na celu weryfikację skuteczności mechanizmów stosowanych do szyfrowania danych w systemie.
            -   **Możliwy wynik pomiaru:** Ocena i potwierdzenie bezpieczeństwa danych osobowych użytkowników w systemie.
            -   **Oczekiwane wartości:** Dane osobowe w systemie są szyfrowane oraz bezpiecznie przechowywane i przesyłane.

        -   **System musi wymagać silnego i bezpiecznego uwierzytelniania oraz autoryzacji**

            -   **Opis:** Procesy uwierzytelniania i autoryzacji w systemie muszą być oparte na silnych i bezpiecznych mechanizmach.
            -   **Sposób pomiaru:** Testy penetracyjne oceniające skuteczność procesów uwierzytelniania i autoryzacji w systemie. Skuteczność procesów uwierzytelniania i autoryzacji, mierzona jako procent poprawnych uwierzytelnień w stosunku do wszystkich prób.
            -   **Możliwy wynik pomiaru:** Potwierdzenie, że system w pełni stosuje bezpieczne i niezawodne uwierzytelnianie i autoryzację użytkowników.
            -   **Oczekiwane wartości:** Autoryzacja i uwierzytelnienie w systemie są w pełni bezpieczne, oparte na silnych mechanizmach i zgodne z obowiązującymi standardami bezpieczeństwa.

        -   **System musi mieć zdefiniowane role dostępu**

            -   **Opis:** W systemie muszą być zdefiniowane klarowne role dostępu, przypisane do różnych kategorii użytkowników (użytkownik, dostawca, administrator), z odpowiednimi uprawnieniami dostępu. Interakcje z zasobami systemu muszą być ściśle kontrolowane w zależności od przypisanych uprawnień i ról.
            -   **Sposób pomiaru:** Testy w ramach różnych zasobów, które sprawdzą skuteczność mechanizmów zarządzania dostępem w kontekście różnych ról użytkowników.
            -   **Możliwy wynik pomiaru:** Osiągnięcie 100% udanych prób dostępu do zasobów zgodnych z przydzielonymi uprawnieniami oraz 100% nieudanych prób, kiedy użytkownik nie ma wymaganych uprawnień.
            -   **Oczekiwane wartości:** System zapewnia skuteczne zarządzanie dostępem, eliminując dostęp do zasobów dla użytkowników bez wymaganych uprawnień.

        -   **System musi być zabezpieczony przed atakami internetowymi**

            -   **Opis:** System powinien posiadać skuteczne mechanizmy obronne, aby minimalizować ryzyko ataków internetowych (między innymi SQLi, XSS, CSRF, DDoS, Brute Force).
            -   **Sposób pomiaru:** Regularne testy bezpieczeństwa każdej kategorii, które mają na celu wykrycie podatności związanych z atakami. Wynik pomiaru stanowi procent udanych zatrzymanych ataków w stosunku do wszystkich prób.
            -   **Możliwy wynik pomiaru:** Skuteczność mechanizmów obronnych powinna być blisko maksymalej wartości dla każdej z kategorii badanych ataków.
            -   **Oczekiwane wartości:** Skuteczna obrona przed atakami każdej kategorii, która wykazuje jak największą możliwą odporność na ataki internetowe.

        -   **System musi umożliwiać monitorowanie aktywności**
            -   **Opis:** System musi skutecznie monitorować aktywność, co pozwala na identyfikację nieprawidłowości i podejrzanej aktywności. Każda istotna operacja i zdarzenie w systemie powinny być rejestrowane w celu późniejszej analizy.
            -   **Sposób pomiaru:** Mierzona jest liczba zdarzeń monitorowanych w logach systemowych. Wynikiem jest procent zarejestrowanych istotnych zdarzeń w systemie do ich spodziewanej liczby.
            -   **Możliwy wynik pomiaru:** System powinien rejestrować co najmniej 99% istotnych zdarzeń systemowych.
            -   **Oczekiwane wartości:** Skuteczne monitorowanie aktywności zgodne z praktykami bezpieczeństwa. System rejestruje istotne wydarzenia w systemie oraz wykrywa istotne nieprawidłowości i działania podejrzane.

    -   #### Dodatkowe wymagania bezpieczeństwa

        -   System powinien być zabezpieczony przed różnorodnymi atakami, takimi jak próby ataków brute force, SQL injection, Cross-Site Request Forgery (CSRF) czy Cross-Site Scripting (XSS):
            -   Wymagane są skuteczne mechanizmy obronne takie jak firewall, filtrowanie ruchu czy detekcja anomalii.
        -   System powinien skutecznie monitorować aktywność, rejestrując istotne operacje i zdarzenia:
            -   Zalogowane informacje powinny być dostępne do analizy w celu identyfikacji potencjalnych nieprawidłowości.
        -   System powinien szyfrować wszystkie dane przesyłane przez niego i przechowywane w nim.
        -   System powinien być wyposażony w mechanizmy zapobiegające utracie danych, takie jak regularne backupy i przywracanie danych:
            -   Ochrona

-   ### 5.5 Wymagania dotyczące niezawodności{#55-wymagania-dotyczc485ce-niezawodnoc59bci-1}

    _Sebastian Pawliński_

    -   Aplikacja powinna działać cały czas z wyjątkiem przerw serwisowych.

    -   Przerwy serwisowe:
        -   Muszą być planowane na godziny z najmniejszą liczbą zamówień - w przypadku braku danych powinny być wybierane godziny od 00:00 do 6:00,
        -   Nie mogą zaburzać dostępności systemu, tzn. mogą występować maksymalnie 3 razy w miesiącu i nie mogą trwać dłużej niż godzinę,
        -   Muszą być komunikowane użytkownikom z trzydniowym wyprzedzeniem.

    _Karol Zalewski_

    -   System powinien być w stanie szybko i efektywnie przywracać się do poprawnego stanu po wystąpieniu awarii:

        -   Mechanizmy przywracania muszą być regularnie testowane i aktualizowane.

    -   System powinien być skalowalny, aby dostosowywać się do zmieniającego się obciążenia.

    -   System powinien regularnie przechodzić testy odpornościowe pod obciążeniem i w warunkach ekstremalnych:

        -   Testy te powinny obejmować zarówno obszar wydajności, jak i stabilności systemu.

    -   System powinien oferować skuteczne mechanizmy monitorowania aktywności oraz raportowania wszelkich nieprawidłowości.

    -   System powinien zapewniać skuteczne mechanizmy backupowania danych oraz przywracania ich w przypadku utraty:

        -   Należy wykonywać testy awaryjne, które potwierdzają skuteczność tych mechanizmów.

    -   System powinien być wyposażony w skuteczny system zarządzania błędami, który umożliwia szybkie wykrywanie, raportowanie i naprawę błędów:

        -   Wymaga się, aby użytkownicy byli informowani o ewentualnych problemach i dostawane były jasne komunikaty dotyczące błędów.

    -   System powinien posiadać dokumentowany plan awaryjny, który określa kroki do podjęcia w przypadku poważnych awarii:
        -   Plan ten powinien być regularnie testowany i aktualizowany.

-   ### 5.6 Ograniczenia środowiskowe{#56-ograniczenia-c59brodowiskowe-1}

    _Sebastian Pawliński_

    Niezależnie od typu aplikacji zestaw funkcjonalności musi być identyczny dla każdych z platform.

    Ograniczenia dzielimy według typu aplikacji:

    -   #### Aplikacja webowa

        Aplikacja ma oferować te same funkcjonalności oraz wyglądać identycznie w podanych przeglądarkach:

        -   Google Chrome
        -   Firefox
        -   Opera
        -   Safari

    -   #### Aplikacja mobilna

        Aplikacja musi działać w systemach Android od wersji 10 oraz w systemie IOS od wersji 11.

## VI. Opracowanie i dokumentowanie przypadków użycia

-   ### 6.1 Zrozumienie wymagań{#61-zrozumienie-wymagac584-1}

    _Tymoteusz Gryszkalis_

    -   #### Elementy systemu

        -   **Aplikacja kliencka (front-end)** - Ta strona będzie interfejsem użytkownika, z którym będą wchodzić w interakcję użytkownicy końcowi. Może to być aplikacja webowa dostępna przez przeglądarkę internetową lub aplikacja mobilna na urządzeniach Android lub iOS.

        -   **Serwer aplikacji (back-end)** - To serwer, który obsługuje logikę biznesową i przetwarza żądania użytkowników. Zarządza on komunikacją między aplikacją kliencką a bazą danych oraz innymi zewnętrznymi systemami, jeśli to konieczne.

        -   **Baza danych** - W systemie będzie potrzebna baza danych do przechowywania danych użytkowników, produktów, zamówień itp. Serwer aplikacyjny będzie komunikował się z bazą danych w celu pobierania i aktualizowania danych.

        -   **Systemy zewnętrzne** - Jeśli aplikacja wymaga integracji z zewnętrznymi systemami, takimi jak systemy płatności online lub systemy monitorowania, będą one komunikować się z serwerem aplikacyjnym poprzez odpowiednie interfejsy API.

    -   #### Komunikacja elementów systemu:

        -   **Aplikacja klienta - Serwer aplikacji**:
            -   Aplikacja klienta wysyła zapytania do serwera aplikacji w celu pobierania danych oraz przetwarzania
                operacji, takie jak składanie zamówień czy przeglądanie produktów.
            -   Serwer aplikacji odpowiada na zapytania klienta, przetwarzając żądania i dostarczając odpowiednie dane.
        -   **Serwer aplikacji - Baza danych**:
            -   Serwer aplikacji komunikuje się z bazą danych w celu pobierania, aktualizowania i przechowywania
                danych użytkowników, produktów, zamówień itp.
            -   Baza danych odpowiada na zapytania serwera aplikacji, dostarczając lub aktualizując potrzebne dane.

-   ### 6.2 Identyfikacja aktorów{#62-identyfikacja-aktorów}

    _Tymoteusz Gryszkalis_

    #### Użytkownicy aplikacji webowej i mobilnej

    Użytkownicy są zainteresowani minimalnym czasem ładowania aplikacji oraz otrzymywaniem szybkich odpowiedzi
    na swoje zapytania. Są również zainteresowani otrzymywaniem natychmiastowych powiadomień. Oczekują, że
    system będzie szyfrował wszystkie dane przesyłane przez niego i przechowywane w nim, aby ich dane osobowe były bezpieczne.

    Oczekują także, że system będzie w stanie szybko i efektywnie przywracać się do poprawnego stanu po
    wystąpieniu awarii, oraz zapewniał skuteczne mechanizmy monitorowania aktywności oraz raportowania
    wszelkich nieprawidłowości. Muszą być informowani o przerwach serwisowych z odpowiednim wyprzedzeniem.
    Muszą też być świadomi, że w przypadku awarii systemu, aplikacja automatycznie przechodzi na backupowe
    środowisko, aby minimalizować przestoje.

    Oczekują, że aplikacja będzie działać zgodnie z tą specyfikacją, zapewniając spójne doświadczenie
    użytkownika na wszystkich platformach.

    #### Dostawcy

    Dostawcy korzystają z systemu w celu dostarczania usług lub towarów. Są zainteresowani
    skalowalnością systemu oraz szybkim przetwarzaniem płatności za zamówienia.

    #### Administratorzy systemu

    Administratorzy mają dostęp do zaawansowanych funkcji systemowych i są
    odpowiedzialni za zarządzanie rolami dostępu, monitorowanie aktywności, oraz zapewnianie bezpieczeństwa
    systemu. Administratorzy muszą skutecznie monitorować aktywność, rejestrując istotne operacje i zdarzenia
    w systemie.

    Ponadto muszą zarządzać mechanizmami zapobiegającymi utracie danych, takimi jak regularne backupy
    i przywracanie danych, oraz definiować klarowne i skuteczne zarządzanie dostępem do zasobów, oparte na
    zdefiniowanych rolach i uprawnieniach.

    Administratorzy muszą zaplanować przerwy serwisowe, które muszą
    być komunikowane użytkownikom z trzydniowym wyprzedzeniem. Ponadto, w przypadku awarii systemu,
    administratorzy muszą zapewnić automatyczne przejście aplikacji na backupowe środowisko w celu
    minimalizacji przestojów.

    #### Potencjalni atakujący

    Aktorzy ci mogą próbować atakować system w celu uzyskania nieautoryzowanego
    dostępu do danych lub uszkodzenia systemu. System musi być zaprojektowany w taki sposób, aby skutecznie się
    bronić przed różnymi rodzajami ataków internetowych. Wymagane są skuteczne mechanizmy obronne, takie jak
    firewall, filtrowanie ruchu czy detekcja anomalii, aby chronić system przed różnorodnymi atakami, takimi
    jak próby ataków brute force, SQL injection, Cross-Site Request Forgery (CSRF) czy Cross-Site Scripting (XSS).

    #### Zespół ds. obsługi technicznej

    Wymagane jest, aby zespół ds. obsługi technicznej monitorował i
    zarządzał przerwami serwisowymi oraz awariami systemu, zapewniając minimalizację przestojów i zapewniając,
    że procedury planowane są zgodnie z wymaganiami.

    Wymagane jest, aby system posiadał skuteczny system zarządzania błędami, który umożliwia szybkie wykrywanie,
    raportowanie i naprawę błędów. Ponadto, zespół ds. obsługi technicznej musi mieć dokumentowany plan awaryjny,
    który określa kroki do podjęcia w przypadku poważnych awarii, oraz regularnie przechodzić testy odpornościowe
    pod obciążeniem i w warunkach ekstremalnych.

-   ### 6.3 Lista przypadków użycia{#63-lista-przypadkc3b3w-uc5bcycia-1}

    _Wojciech Szade_ i _Szymon Kopańko_

    -   **Synchronizacja**
    -   **Powiadomienia**
    -   **Wielojęzyczność**
    -   **Posty**
    -   **Recenzja**
    -   **Polubienia**
    -   **Zbieranie statystyk**
    -   **Kredyty**
    -   **Subskrypcje**
    -   **Główna strona użytkownika**
    -   **Wyszukiwanie**
    -   **Zamówienia**
    -   **Historia**
    -   **Wystawianie produktów**
    -   **Płatności**
    -   **Konto premium**
    -   **Status zamówienia**
    -   **Konta**

-   ### 6.4 Opisy przypadków użycia{#64-opisy-przypadkc3b3w-uc5bcycia-1}

    _Wojciech Szade_ i _Szymon Kopańko_

    -   #### Synchronizacja

        **Przypadek użycia**: Synchronizacja danych między stroną internetową a aplikacją mobilną

        **Aktorzy:** Użytkownik, Aplikacja mobilna, Strona internetowa

        **Warunki początkowe:** Użytkownik jest zalogowany zarówno na stronie internetowej, jak i w aplikacji mobilnej.

        **Opis:**

        1. Użytkownik dokonuje zmiany danych na stronie internetowej lub w aplikacji mobilnej.
        2. System automatycznie synchronizuje dane między obiema platformami.
        3. Użytkownik może kontynuować pracę na dowolnej z platform, mając pewność, że jego dane są aktualne na obu.

        **Warunki końcowe:** Dane użytkownika są zsynchronizowane między aplikacją mobilną a stroną internetową.

    -   #### Powiadomienia

        **Przypadek użycia**: Zarządzanie powiadomieniami

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik zalogowany na swoim koncie.

        **Opis:**

        1. Użytkownik przechodzi do ustawień powiadomień.
        2. Może zaznaczyć preferowane rodzaje powiadomień, które chce otrzymywać.
        3. Użytkownik może również wyłączyć powiadomienia, jeśli nie chce ich otrzymywać.

        **Warunki końcowe:** Użytkownik ma skonfigurowane powiadomienia zgodnie z własnymi preferencjami.

    -   #### Wielojęzyczność

        **Przypadek użycia**: Wybór języka interfejsu

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik otwiera interfejs aplikacji.

        **Opis:**

        1. Użytkownik przechodzi do ustawień języka.
        2. Wybiera preferowany język spośród dostępnych opcji: polski, angielski, ukraiński.
        3. Interfejs aplikacji automatycznie zmienia się na wybrany język.

        **Warunki końcowe:** Interfejs aplikacji jest wyświetlany w wybranym przez użytkownika języku.

    -   #### Posty

        **Przypadek użycia**: Dodawanie posta przez usługodawcę

        **Aktorzy:** Usługodawca

        **Warunki początkowe:** Usługodawca jest zalogowany na swoje konto.

        **Opis:**

        1. Usługodawca przechodzi do opcji dodawania nowego posta na swoim profilu.
        2. Wpisuje treść posta oraz dodaje zdjęcia i hasztagi.
        3. Potwierdza dodanie posta.

        **Warunki końcowe:** Nowy post usługodawcy jest widoczny na jego profilu dla użytkowników.

    -   #### Recenzja

        **Przypadek użycia**: Dodawanie recenzji przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i posiada zakupiony produkt.

        **Opis:**

        1. Użytkownik przechodzi do opcji wystawienia recenzji.
        2. Wpisuje tekst recenzji oraz ocenę produktu/usługodawcy w skali 5 gwiazdek.
        3. Potwierdza dodanie recenzji.

        **Warunki końcowe:** Recenzja użytkownika jest widoczna na profilu produktu/usługodawcy.

    -   #### Polubienia

        **Przypadek użycia**: Polubienie posta przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik przegląda posty na platformie.

        **Opis:**

        1. Użytkownik klika na przycisk "polubienia" pod postem.
        2. System dodaje polubienie do danego posta.

        **Warunki końcowe:** Post jest oznaczony jako polubiony przez użytkownika.

    -   #### Zbieranie statystyk

        **Przypadek użycia**: Przeglądanie statystyk przez usługodawcę

        **Aktorzy:** Usługodawca

        **Warunki początkowe:** Usługodawca jest zalogowany na swoje konto.

        **Opis:**

        1. Usługodawca przechodzi do sekcji ze statystykami.
        2. Przegląda zebrane informacje, takie jak liczba polubień, recenzji, ilość zakupów, mapa z podziałem na regiony.
        3. Analizuje zebrane dane w celu lepszego zrozumienia preferencji klientów i efektywniejszej promocji.

        **Warunki końcowe:** Usługodawca ma dostęp do zbiorczych statystyk swojej działalności.

    -   #### Kredyty

        **Przypadek użycia**: Wykorzystanie kredytów przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik posiada kredyty na swoim koncie.

        **Opis:**

        1. Użytkownik dokonuje zakupu produktu/usługi.
        2. Wybiera opcję zapłaty za pomocą kredytów.
        3. System potwierdza dokonanie płatności i odlicza odpowiednią ilość kredytów z konta użytkownika.

        **Warunki końcowe:** Produkt/usługa zostaje opłacona za pomocą kredytów.

    -   #### Subskrypcje

        **Przypadek użycia**: Subskrybowanie usługodawcy przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

        **Opis:**

        1. Użytkownik przechodzi do profilu usługodawcy.
        2. Wybiera opcję subskrypcji.
        3. Potwierdza subskrypcję usługodawcy.

        **Warunki końcowe:** Użytkownik subskrybuje usługodawcę i otrzymuje częstsze polecenia jego postów.

    -   #### Główna strona użytkownika

        **Przypadek użycia**: Wyświetlanie rekomendacji dla użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

        **Opis:**

        1. System analizuje ostatnie zakupy i subskrypcje użytkownika.
        2. Na podstawie analizy generuje rekomendacje produktów/usług.
        3. Użytkownik przegląda rekomendacje na swojej głównej stronie.

        **Warunki końcowe:** Użytkownik ma dostęp do spersonalizowanych rekomendacji na swojej głównej stronie.

    -   #### Wyszukiwanie

        **Przypadek użycia**: Wyszukiwanie usługodawców lub dań/diet

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

        **Opis:**

        1. Użytkownik przechodzi do wyszukiwarki.
        2. Wpisuje nazwę usługodawcy, dania lub diety.
        3. Może stosować filtry i sortować wyniki wyszukiwania według różnych parametrów.
        4. Przegląda wyniki wyszukiwania i wybiera interesujący produkt/usługodawcę.

        **Warunki końcowe:** Użytkownik znajduje poszukiwany produkt/usługodawcę na podstawie wprowadzonych kryteriów.

    -   #### Zamówienia

        **Przypadek użycia**: Składanie zamówienia przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

        **Opis:**

        1. Użytkownik przegląda dostępne dania od różnych usługodawców.
        2. Dodaje wybrane dania do koszyka zamówień.
        3. Wybiera opcję dostawy i płatności.
        4. Potwierdza zamówienie.

        **Warunki końcowe:** Zamówienie zostaje złożone i przekazane do realizacji.

    -   #### Historia

        **Przypadek użycia**: Przeglądanie historii zamówień przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

        **Opis:**

        1. Użytkownik przechodzi do sekcji historii zamówień.
        2. Przegląda listę swoich poprzednich zamówień oraz subskrypcji.
        3. Ma możliwość anulowania zamówienia, jeśli jego dostarczenie opóźniło się więcej niż 24 godziny.

        **Warunki końcowe:** Użytkownik ma dostęp do historii swoich zamówień oraz subskrypcji.

    -   #### Wystawianie produktów

        **Przypadek użycia**: Dodawanie produktu przez usługodawcę

        **Aktorzy:** Usługodawca

        **Warunki początkowe:** Usługodawca jest zalogowany na swoje konto.

        **Opis:**

        1. Usługodawca przechodzi do opcji wystawiania nowego produktu.
        2. Wpisuje dane produktu, takie jak nazwa, opis, cena.
        3. Potwierdza dodanie produktu.

        **Warunki końcowe:** Nowy produkt jest dostępny do zakupu dla użytkowników.

    -   #### Płatności

        **Przypadek użycia**: Dokonywanie płatności przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma produkty w koszyku.

        **Opis:**

        1. Użytkownik przechodzi do opcji płatności.
        2. Wybiera preferowany sposób płatności: blikiem, kartą, kredytem.
        3. Potwierdza dokonanie płatności.

        **Warunki końcowe:** Zamówienie jest opłacone, a produkty są przygotowane do dostawy.

    -   #### Konto premium

        **Przypadek użycia**: Zakup konta premium przez użytkownika

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto.

        **Opis:**

        1. Użytkownik przechodzi do opcji zakupu konta premium.
        2. Wybiera preferowany plan konta premium.
        3. Potwierdza zakup konta premium.

        **Warunki końcowe:** Użytkownik ma aktywowane konto premium i korzysta z jego dodatkowych funkcji.

    -   #### Status zamówienia

        **Przypadek użycia: Sprawdzanie statusu zamówienia przez użytkownika**

        **Aktorzy:** Użytkownik

        **Warunki początkowe:** Użytkownik jest zalogowany na swoje konto i ma złożone zamówienie.

        **Opis:**

        1. Użytkownik przechodzi do sekcji statusu zamówienia.
        2. Sprawdza aktualny status swojego zamówienia, czy jest w trakcie realizacji, dostarczania itp.

        **Warunki końcowe:** Użytkownik ma aktualną informację o statusie swojego zamówienia.

    -   #### Konta

        **Przypadek użycia: Zarządzanie kontami**

        **Aktorzy:** Administrator

        **Warunki początkowe:** Administrator ma dostęp do panelu administracyjnego.

        **Opis:**

        1. Administrator może tworzyć, edytować i usuwać konta użytkowników i usługodawców.
        2. Zarządza uprawnieniami kont, np. nadaje konto premium, blokuje konto za złamanie regulaminu itp.

        **Warunki końcowe:** Administrator skutecznie zarządza kontami na platformie.

## VII. Słownik Dziedziny

-   ### 7.1 Terminologia biznesowa{#71-terminologia-biznesowa}

    -   **kredyt** - forma wewnętrzych kuponów rozdawanych w ramacg rekompensata

    -   **odpowiednie produkty** - produkty sezonowe zbierane lokalnie

    -   **usługodawca** - firma kateringowa

-   ### 7.2 Terminologia techniczna{#72-terminologia-techniczna}

    -   **post** - treść, hashy i ewentualne zdjęcie umieszczne przez usługodawcę w formie promocje, infrmacji

-   ### 7.3 Terminologia użytkownicza{#73-terminologia-uc5bcytkownicza-1}

    _Jakub Wysocki_ i _Krzysztof Jurkowski_

    -   **danie** - składa się ze składników

    -   **dieta** - pełen plan jedzeniowy na określony czas

    -   **posiłek** - składa się z jednego lub więcej dań

    -   **produkt** - to co wystaw usługodawca do sprzedaży czyli danie lub dieta

    -   **recenzja** - opinia użytkownika na temat dania lub usługodawcy

    -   **rodzaj diety** - wyłącznie nazwa

    -   **rodzaj posiłku** - np. śniadanie, oboad, kolacja

    -   **statystyki** - zbiór ogólnych reakcje użytkowników na posty, wyświetlania, zarobki z aplikacji
