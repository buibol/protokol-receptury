# Protokół leku recepturowego v1.0.5

Wersja 1.0.5 zawiera poprawki obsługi receptur w KS-AOW, przywraca pełną obsługę zdalnego serwera Firebird oraz poprawia wygodę wyboru daty.

## Zmiany

- dodano obsługę receptur, w których składniki są dopisywane później i mają `NRSRC = 0`,
- zachowano obsługę dotychczasowego wariantu, w którym składniki mają `NRSRC` zgodny z numerem receptury,
- przywrócono obsługę zdalnego serwera Firebird,
- aplikacja korzysta z `host`, `database` i danych użytkownika `RAPORTR` zapisanych w `db_credentials.json`,
- aktualizacja zachowuje istniejącą licencję i konfigurację RAPORTR,
- dodano kalendarz przy polu **Data sprzedaży**,
- datę można wybrać myszką,
- dodano przechodzenie między miesiącami oraz przycisk **Dzisiaj**,
- ręczne wpisywanie daty nadal działa,
- kalendarz nie wymaga dodatkowych bibliotek Pythona.

## Aktualizacja

Przy aktualizacji istniejącej instalacji nie ma potrzeby ponownego uruchamiania konfiguratora RAPORTR, jeżeli obecna konfiguracja połączenia jest prawidłowa.

## Pobieranie

Stały link do najnowszej wersji instalatora:

https://github.com/buibol/protokol-receptury/releases/latest/download/ProtokolReceptury_Setup.exe

Plik wersjonowany tego wydania:

`ProtokolReceptury_Setup_1.0.5.exe`
