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
