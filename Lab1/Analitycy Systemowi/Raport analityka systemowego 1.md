# Raport dot. Wizji Systemu
*autor: Krzysztof Jurkowski*

#### 5.1 Wizja systemu
System będzie wykonany w formie aplikacji PWA komunikującej się z serwerem i bazą danych poprzez web api. Pozwoli to na zapewnienie poprawnego działania i takiego samego user experience niezależnie od urządzenia z którego korzysta użytkownik (przeglądarka, telefon, tablet itp.).

Dane użytkowników będą przechowywane w bezpieczny sposób w centralnej bazie danych. Niektóre dane dotyczące np. preferencji użytkownika mogą być również przechowywane lokalnie np. w ciastkach lub w pamięci przeglądarki. 

Płatności będą obsługiwane przez zewnętrznego dostawcę, co zapewni niezawodność i jak najlepsze doświadczenie użytkownika, będzie mógł wybrać najczęściej używane formy płatność jak blik lub płatność kartą debetową/kredytową, a sama płatność będzie przeprowadzana sprawnie.

Skalowalość i niezawodność systemu zapewni dostawca usług chmurowych dzięki zastosowaniu rozwiązań serverless. Dzięki temu zarówno baza danych jak i web api będą elastyczne i będą mogły odpowiednio dostosowywać moc obliczeniową systemu do obciążenia, co pozwoli na poprawne działanie systemu w przypadku np. nagłego zwiększenia odwiedzeń strony. Za pośrednictwem dostawcy usług chmurowych administrator systemu będzie również miał dostęp do wszelakich danych telemetrycznych pozwalających na szybkie i skuteczne diagnozowanie usterek.

#### 5.2 Lista cech systemu
*// takie bardziej techniczne*
* System składa się z 3 części: aplikacji PWA, web api i bazy danych.
* System zapewnia takie same funkcjonalności niezależnie od platformy (web/mobilna).
* System jest dostępny 24/7.
* System jest skalowalny, nie przestaje działać nawet przy skokowym wzroście odwiedzeń strony.
* System jest dostępny w wielu językach oraz pamięta preferencje językowe użytkownika.
* System oferuje wysyłanie powiadomień do użytkownika zarówno o dostawach jak i promocjach.
* System umożliwia wyłączenie powiadomień.
* System bezpiecznie przechowuje wrażliwe dane użytkowników.
* System pozwala użytkownikowi na usunięcie swoich danych zgodnie z RODO.
* System obsługuje płatności blikiem i kartą kredytową/debetową. 

*// funkcjonalnosci*
* System umożliwia firmie kateringowej zarządzać swoją ofertą.
* System umożliwia firmie kateringowej publikować aktualizacje i reklamy w formie postów.
* System umożliwia firmie kateringowej przeglądanie statystyk (reakcje użytkowników na posty, wyświetlenia, przychód z aplikacji) .
* System umożliwia użytkownikowi przeglądanie oferty wielu firm kateringowych.
* System umożliwia użytkownikowi przeglądanie i reagowanie na posty usługodawców (firm kateringowych).
* System umożliwia użytkownikowi składanie zamówień.
* System umożliwia użytkownikowi opłacanie zamówień poprzez kredyt, blik oraz kartę debetową/kredytową.
* System umożliwia użytkownikowi doładowanie swojego kredytu poprzez blik lub kartę debetową/kredytową.
* System umożliwia użytkownikowi anulowanie swojego zamówienia do 24 godzin przed planowanym dostarczeniem.
* System proponuje użytkownikowi rekomendowane oferty na podstawie jego poprzednich zamówień.
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
* System pozwala użytkownikowi na wystawienie recenzji nt. dania i usługi do miesiąca po wykonaniu zamówienia.
* System pozwala użytkownikowi na przeglądanie recenzji produktów i reagowanie na nie.
* System umożliwia użytkownikowi przeglądanie historii swoich zamówień.
* System umożliwia użytkownikowi na przeglądanie statusu dzisiejszych zamówień.

#### Słownik
**status dzisiejszych zamówień** - zbiór informacji dotyczących zamówień, realizowanych danego dnia.

**danie** - składa się ze składników.

**dieta** - pełen plan jedzeniowy na określony czas.