# officing-com
Projekt WSB - Metody modelowania i analizy systemów informatycznych

## Zadanie 1.
### pkt 1. Wybór systemu
System zarządzania rezerwacją stanowisk w przestrzeni coworkingowej

### pkt 2. Nazwij procesy wspierane przez system
- Rezerwacja miejsca / sprzętu
- nadzór
- zgłoszenia błedu sprzętu, maintenance
- wsparcie planowaniapracy zespołu
- ew. płatności

### pkt 3. Zidentyfikuj interesariuszy (klient i użytkownik)
- Właściciel / dzierżawca lokalu
- manager zespołu (klient - firma)
- użytkownik (klient - freelancer)
- uzytkownik (pracownik firmy)
- HR

### pkt 4. Wskaż problemy rozwiazywane przez system
- optymalizacja procesu wynajmu
- optymalizacja zarządzania zespołem
- optymalizacja zarządzania zasobami firmy

- zagospodarowanie przestrzeni
- opóźnienie reakcji na awarię wynajmowanego sprzętu
- eliminacja overbookingu
- niedostosowanie wyposarzenia do potrzeb uzytkowników (pracowników / freelancerów)
- nieuczciwość pracowników
- nie wypełnianie założeń polityki pracy hybrydowej

### pkt 5. Krótki opis
System optymalizujący zarządzanie przestrzenią biurową i dostępem do sprzętu. Przeznaczony dla osób zarządzających przestrzenią biurową, firm i freelancerów.

### pkt 6.Lista (rejestr) korzysci
- Analiza wykorzystania przestrzeni
- organizacja spotkań
- wdrażanie polityki firmy dotyczącej pracy hybrydowej
- zgłaszanie niedziałającego sprzętu
- udostępnianie niewykorzystanej przestrzeni
- znajdowanie dostępnej przestrzeni biurowej

## SIDENOTE killer app: https://pl.wikipedia.org/wiki/Killer_application
Prowadzący przedstawiał to jako przykuwajacy uwage element, mający być atutem w porównaniu do konkurencji

## Zadanie 2.
### pkt 1. Struktura systemu
- rdzeń apki na serwerze
- baza danych
- moduł dostępnych zasobów
- rezerwacja
- analiza zajętości stanowisk (stany i historia)
- konto klienta
- płatnosci

### pkt 2. Analiza funkcjonalna (max. 30)
- rejestracja
- rezerwacja
- rezerwacja bez konta
- potwierdzenie rezerwacji
- wyszukiwanie wolnych stanowisk
- generowanie raportów
- ustalanie zasad wynajmu
- śledzenie stanu technicznego
- wdrażanie i egzekwowanie polityk pracowniczych
- oferowanie zdjęć stanowiskaocenianie stanowiska (rating)
- powiadomienia (push/sms) o zbliżajacym się końcu czasu
- mapka dotarcia dostanowiska
- system znizek (opcja)
- "powiadom o dostępnosci"
- personalizacja interfejsu
- formularz kontaktu
- czat AI
- możliwość wyłączenia czata AI
- zgłoszenie stanu po obecności poprzedniego użytkownika
- informacja o dostępności dla osób niepełnosprawnych
- LLM odpowiada na maile -> zabezpieczyć przed prompt injection -> llm skraca treść i wysyła z odpowiednim tytułem oraz odpowiada nadawcy zapewniajac o podjęciu działań

### pkt 3. Analiza niefunkcjonalna (cechy)
- ciemny / jasny intefejs
- zabezpieczenie płatności
- centralny rdzeń
- dostęp przez przeglądarkę i apki (desktop i mobile)
- czytelny (nie skomplikowany) interfejs; w tym dla niedowidzących

## Zadanie 3.
### pkt 1. Wyestymuj w skali punktowej (ilość napojów energetycznych, potrzebnych podczas implementacji)
- rejestracja 0,3
- rezerwacja 1,5
- rezerwacja bez konta 2
- potwierdzenie rezerwacji    0,1
- wyszukiwanie wolnych stanowisk  0,1
- generowanie raportów          0,5
- ustalanie zasad wynajmu   1
- śledzenie stanu technicznego  1
- wdrażanie i egzekwowanie polityk pracowniczych  10
- oferowanie zdjęć stanowiskaocenianie stanowiska (rating)  0,3
- powiadomienia (push/sms) o zbliżajacym się końcu czasu  2,5
- mapka dotarcia dostanowiska   0,2
- system znizek (opcja)  0,1
- "powiadom o dostępnosci"  3
- personalizacja interfejsu  3
- formularz kontaktu  0,2
- czat AI  30
- możliwość wyłączenia czata AI  0,1
- zgłoszenie stanu po obecności poprzedniego użytkownika  0,2
- informacja o dostępności dla osób niepełnosprawnych  0,1
- LLM odpowiada na maile -> zabezpieczyć przed prompt injection -> llm skraca treść i wysyła z odpowiednim tytułem oraz odpowiada nadawcy zapewniajac o podjęciu działań  25
  
