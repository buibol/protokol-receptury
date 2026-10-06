# Protokół Receptury 1.0.10

## Zmiany

### Obsługa korekt receptury
- Dodano rozpoznawanie korekt sprzedaży leków recepturowych.
- W oknie **„Leki z dnia”** pozycje są teraz oznaczane jako:
  - **SPRZEDAŻ**
  - **KOREKTA**
- Korekty są dodatkowo wyróżnione kolorem, aby łatwo odróżnić je od zwykłej sprzedaży.
- Po wybraniu korekty program pyta, czy otworzyć sprzedaż pierwotną.
- Po potwierdzeniu program automatycznie przechodzi do pierwotnej realizacji receptury i pobiera z niej właściwe dane oraz dodatnie ilości składników.
- Do powiązania korekty ze sprzedażą pierwotną wykorzystywane jest w pierwszej kolejności bezpośrednie odwołanie zapisane w bazie KS-AOW, a w razie potrzeby mechanizm awaryjny oparty na danych recepty.

### Poprawki interfejsu
- Dodano pionowe przewijanie głównego formularza.
- Poprawiono obsługę programu na komputerach z mniejszą rozdzielczością ekranu.
- Przyciski **„Koniec”** i **„Generuj PDF”** pozostają dostępne również przy ograniczonej wysokości okna.

## Zgodność
- Brak zmian w strukturze bazy danych.
- Zachowana zgodność z dotychczasową konfiguracją programu i licencjami.
- Aktualizacja może być instalowana bez usuwania poprzedniej wersji.

## Wersja
**1.0.10**
