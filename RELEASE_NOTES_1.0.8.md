# Protokół Receptury 1.0.8

## Zmiany

- Rozdzielono ilości składników na dwie niezależne, edytowalne wartości:
  - **Ilość przepisana**
  - **Ilość odważona**
- Obie wartości są na starcie uzupełniane ilością wynikającą z realizacji receptury i mogą zostać ręcznie skorygowane przed utworzeniem PDF.
- W głównej tabeli składników zmieniono opis kolumny z **„Ilość”** na **„Ilość odważona”**.
- W PDF poprawiono nagłówek sekcji:
  - **„Odważnie składników leku”** → **„Odważenie składników leku”**.
- Rozszerzono wybór terminu przydatności do:
  - **7 dni**
  - **14 dni**
  - **30 dni**
  - **45 dni**
  - **90 dni**
- Termin przydatności nadal nie ma wartości domyślnej — użytkownik musi świadomie wybrać okres przed utworzeniem PDF.
- Poprawiono układ formularza ilości składników:
  - kolumny „Ilość przepisana” i „Ilość odważona” są ustawione bliżej siebie,
  - formularz lepiej dopasowuje się do różnych rozdzielczości ekranu.
- Przyciski **„Utwórz PDF”** i **„Anuluj”** są stale widoczne na dole okna, niezależnie od przewijania formularza.
- Okno **„Dane uzupełniające protokół”** jest automatycznie centrowane na ekranie.

## Dystrybucja

W GitHub Release publikowany jest instalator o stałej nazwie:

`ProtokolReceptury_Setup.exe`

Wersjonowany plik:

`ProtokolReceptury_Setup_1.0.8.exe`

pozostaje w lokalnym archiwum wydań.

## Wersja

`1.0.8`
