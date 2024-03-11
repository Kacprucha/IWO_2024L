# Raport dot. Wizji Systemu
*autor: Karol Zalewski*

#### 5.4 Wymagania dotyczące bezpieczeństwa:
- System powinien być zabezpieczony przed różnorodnymi atakami, takimi jak próby ataków brute force, SQL injection, Cross-Site Request Forgery (CSRF) czy Cross-Site Scripting (XSS):
    - Wymagane są skuteczne mechanizmy obronne takie jak firewall, filtrowanie ruchu czy detekcja anomalii.
- System powinien skutecznie monitorować aktywność, rejestrując istotne operacje i zdarzenia:
    - Zalogowane informacje powinny być dostępne do analizy w celu identyfikacji potencjalnych nieprawidłowości.
- System powinien szyfrować wszystkie dane przesyłane przez niego i przechowywane w nim.
- System powinien być wyposażony w mechanizmy zapobiegające utracie danych, takie jak regularne backupy i przywracanie danych:
    - Ochrona musi być zapewniona zarówno przeciwko przypadkowej utracie danych, jak i przed atakami które mogą prowadzić do zniszczenia danych.
- System powinien zapewniać klarowne i skuteczne zarządzanie dostępem do zasobów, oparte na zdefiniowanych rolach i uprawnieniach:
    - Wszelkie próby niezautoryzowanego dostępu powinny być ściśle kontrolowane.
- System powinien mieć zdefiniowany plan reakcji na incydenty bezpieczeństwa, określający kroki do podjęcia w przypadku wykrycia ataku lub naruszenia:
    - Plan powinien być regularnie testowany i aktualizowany.

#### 5.5 Wymagania dotyczące niezawodności:
- System powinien być w stanie szybko i efektywnie przywracać się do poprawnego stanu po wystąpieniu awarii:
    - Mechanizmy przywracania muszą być regularnie testowane i aktualizowane.
- System powinien być skalowalny, aby dostosowywać się do zmieniającego się obciążenia.
- System powinien regularnie przechodzić testy odpornościowe pod obciążeniem i w warunkach ekstremalnych:
    - Testy te powinny obejmować zarówno obszar wydajności, jak i stabilności systemu.
- System powinien oferować skuteczne mechanizmy monitorowania aktywności oraz raportowania wszelkich nieprawidłowości.
- System powinien zapewniać skuteczne mechanizmy backupowania danych oraz przywracania ich w przypadku utraty:
    - Należy wykonywać testy awaryjne, które potwierdzają skuteczność tych mechanizmów.
- System powinien być wyposażony w skuteczny system zarządzania błędami, który umożliwia szybkie wykrywanie, raportowanie i naprawę błędów:
    - Wymaga się, aby użytkownicy byli informowani o ewentualnych problemach i dostawane były jasne komunikaty dotyczące błędów.
- System powinien posiadać dokumentowany plan awaryjny, który określa kroki do podjęcia w przypadku poważnych awarii:
    - Plan ten powinien być regularnie testowany i aktualizowany.