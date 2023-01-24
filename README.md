# Task 1  


## *Subtask 1*

8 pkt

## *Subtask 3*

Biorę udział w projekcie, ponieważ szukam zmian i wyzwań w moim życiu zawodowym. Jestem otwarta na nowości i gotowa do nauki. Moim celem jest znalezienie właściwej drogi zawodowej. Oczekuje, że to wyzwanie da mi jeszcze większy zapał do dalszej nauki i pewność, że właśnie to jest to co chciałabym robić w przyszłości. 	:smiley:

## *Subtask 4*

### 1. Opis aplikacji

Aplikacja:  https://scouts-test.futbolkolektyw.pl/pl służy do weryfikacji osiągnieć graczy, w dwóch wersjach językowych polskim i angielskim. Daje również możliwość dodawania zawodników, porównania wskaźników, dodawania meczów, tworzenia raportów. Przeznaczona jest dla osób/firmy poszukujących utalentowanych zawodników.

### 2. Funkcjonalność

2.1. Funkcjonalność aplikacji w ramach logowania i wylogowania jest prawidłowa, zmiana języka przy logowaniu działa poprawnie. Istnieje możliwość przesłania maila przypominającego z hasłem w przypadku nie zapamiętania hasła.

2.2. Po zalogowaniu wyświetla się **Strona główna**, na samej górze w rzędzie widoczne są przyciski z aktualizowanymi na bieżąco wartościami (**Ilość graczy, Ilość meczy, Ilość raportów, Ilość akcji**), które niestety nie są aktywne, po ich naciśnięciu nie można wejść w szczegóły wyświetlanych danych.

![2023-01-18_17h21_03](https://user-images.githubusercontent.com/122534768/213235825-457766a5-19b2-4481-86bb-c5c4b964f9b2.png)

2.3.	W części centralnej **Strony głównej** wyświetlane są również przyciski:

2.3.1. **Scouts Panel** (Panel zarządzania graczami, meczami i do tworzenia raportów) nie spełnia opisanej funkcji zarządzania graczami, meczami tworzenia raportów. Błędnie kieruje do kontaktu z programistami. Zarządzanie graczami, meczami i tworzenie raportów jest możliwe dopiero po wejściu na konto dowolnego  **Gracza**.

![2023-01-18_20h08_41](https://user-images.githubusercontent.com/122534768/213273420-eef8aeb0-514f-462a-a63b-eb7e78ec81dd.png)

2.3.2. **Linki pomocnicze** (Dodaj Gracza);

* Przycisk dający możliwość dodawania zawodników, powinien zostać inaczej zatytułowany, żeby jasno określał swój cel, tj. dodawanie nowych zawodników.

![2023-01-18_20h20_03](https://user-images.githubusercontent.com/122534768/213274664-373ccb33-4353-4e65-9f9c-0a2f978843ee.png)

* Podczas wpisywania danych nowego zawodnika, aplikacja informuje, że nie może wprowadzić do systemu nowego **Gracza**, natomiast nie informuje z jakiego powodu        tak się dzieje. 

* Podczas wpisywania imienia i nazwiska można używać symboli i cyfr, oraz nie ma ograniczenia co do ich długości.

![2023-01-18_21h48_20](https://user-images.githubusercontent.com/122534768/213291547-da236eb5-7200-4c36-9062-bace55ecdeef.png)

* Wpisując dane nowego gracza w rubryce telefon można wpisać nie tylko cyfry, a symbole i litery. Proponuje aby dla ułatwienia stworzyć możliwość wyboru numeru kierunkowego danego kraju oraz wprowadzić ograniczenie co do ilości wpisywanych cyfr, w zależności od wybranego kraju.

![image](https://user-images.githubusercontent.com/122534768/213292227-6a523131-7970-4f41-a666-336bae2b6ff4.png)

* W rubryce wzrost i waga można wybrać ujemne wartości. W celu polepszenia funkcjonalności należy wprowadzić minimalne i maksymalne wartości oraz wykluczyć wpisywanie ujemnych wartości.

![2023-01-18_21h59_49](https://user-images.githubusercontent.com/122534768/213293762-2725a082-4280-4f96-bbf7-309a6209100d.png)

* W polskiej wersji językowej, w lewym dolnym roku są przyciski w języku angielskim (submit i clear).

![2023-01-19_18h53_37](https://user-images.githubusercontent.com/122534768/213523369-2df2f5da-26bf-4f1c-9bc3-43ce403b47cc.png)

* Wprowadzając datę urodzenia gracza można wpisać czas przyszły. Zawodnik zapisany w aplikacji może mieć również nieograniczoną liczbę lat. Proponuje wykluczyć            możliwość zapisu daty urodzenia przyszłej i wprowadzić maksymalny i minimalny wiek.

![2023-01-18_22h07_12](https://user-images.githubusercontent.com/122534768/213297787-b75279b8-5235-4bc2-8bbe-d98ab93129d7.png)

 * Aplikacja pozwala wprowadzać tego samego gracza kilkarotnie, co mocno zmniejsza jej funkcjonalność. Trzeba wykluczyć możliwość dublowania zawodników.

![2023-01-18_22h25_59](https://user-images.githubusercontent.com/122534768/213298512-d9c651c9-d1c5-440c-8b14-f1b088c5a8f9.png)

  2.3.3. **Aktywność**, pokazuje aktualną aktywność na stronie, tj.:
  * Ostatnio stworzony gracz;
  * Ostatnio zaktualizowany gracz;
  * Ostatnio stworzony mecz;
  * Ostatnio zaktualizowany mecz;
  * Ostatnio zaktualizowany raport.
     
Przycisk **Aktywność** jest błędnie zapisany (Aktywnosć), dodatkowo słowa: "zaktualizowany" również posiada dodatkowe „a”.

![2023-01-18_22h31_04](https://user-images.githubusercontent.com/122534768/213299609-8a69b429-ed84-470e-aaf8-3d934cedd801.png)

2.4.	 W wersji pełno ekranowej z lewej strony znajduje się pasek z następującymi przyciskami:
*	**Strona główna** 
*	**Gracze**, po kliknięciu pojawia się tabela z następującymi danymi:
     *	Imię;
     *	Nazwisko;
     *	Wiek;
     *	Pozycja rozgrywająca;
     *	Klub;
     *	Recenzja;
     *	Ilość rozegranych meczy;
     *	Raporty.
     
Nie ma możliwości segregowania danych alfabetycznie lub od najmniejszego do najwyższego wartości i odwrotnie. Nie można również ustawić ilości wyświetlanych danych na stronie.
          
* **English** / **Polski**, przycisk zmienia język;

Ikona zmiany języka powinna zawierać na przykład flagę z językiem do wyboru, a nie niezrozumiałe znaczki.

![2023-01-18_20h39_35](https://user-images.githubusercontent.com/122534768/213278898-ad847c88-7c66-4212-8cb5-a328edc1cf6c.png)
![2023-01-18_20h39_57](https://user-images.githubusercontent.com/122534768/213278935-d908492f-93b0-410c-8d02-d45a6cd748ec.png)

*	**Wyloguj**, powoduje wylogowanie z aplikacji.

W wersji mobilnej na telefon, po zmianie rozdzielczości ekranu, powyższe informacje wyświetlają się po kliknięciu w ikonę w lewym górnym rogu. 

2.4.1.	Tabele z danymi **Graczy** można przy użyciu ikon w prawym górnym rogu:
* Pobrać do pliku Excel;
     * Wszystkie dane po pobraniu do Excela trafiają do pierwszej kolumny, co nie jest funkcjonalne i czytelne.

![2023-01-18_20h54_38](https://user-images.githubusercontent.com/122534768/213282540-c4fc4ac0-ea51-4613-948f-2f0bde39b566.png)

* Wydrukować;
     * Podczas próby wydruku tabeli z danymi, na podglądzie do wydruku widoczni są jedynie zawodnicy z pierwszej strony raportu (pierwszych 10).
     * Dane widoczne do druku wyświetlają się w innej formie, niż widoczna na ekranie monitora komputera, mniej czytelnej.

![2023-01-18_21h08_35](https://user-images.githubusercontent.com/122534768/213285230-a94b3343-23a9-4b6d-9200-316450b57e39.png)
![2023-01-18_21h09_57](https://user-images.githubusercontent.com/122534768/213285261-05d363b4-d156-4dda-9d0c-a26c3b5a3663.png)

* Porównać wybierając dowolne wskaźniki;
* Wyszukać dane przy zastosowaniu określonych filtrów;
     * W polskiej wersji językowej ikony ściągania, drukowania, widoku kolumny i filtrowanie po najechaniu na nie wyświetlane są w języku angielskim. 
     * Dodatkowo po wejściu na opcje filtrowania również w wersji językowej polskie wyświetlają się frazy w języku angielskim (filters, reset, age, rate).
     
![2023-01-19_19h11_15](https://user-images.githubusercontent.com/122534768/213527119-67c17629-6870-4b6b-81d8-8f19a95ed1b5.png)

2.5.	Po wejściu na dowolne założone konto **Gracza** wyświetlają się:

2.5.1.	**Mecze**, które zawierają następujące dane:
* Drużyna zawodnika;
* Zdobyte gole;
* Stracone gole;
* Drużyna przeciwna;
* Data;
* Czas gry;
* Recenzja;
* Autor;
* Akcje, dają możliwość:
     * Edycji;
     * Dodania raportu;
     * Rozpocznij mecz:
     
Opcja rozpoczęcia meczu jest mało intuicyjna i mało czytelna, brak legendy i informacji w jaki sposób można dodać mecz.

![2023-01-18_22h41_10](https://user-images.githubusercontent.com/122534768/213301434-fa4bbde9-851c-44fb-a568-d6a420390eeb.png)

Dodatkowo podczas edycji meczu, w polskiej wersji językowej, wkradają się angielskojęzyczne słowa.

![2023-01-18_23h20_52](https://user-images.githubusercontent.com/122534768/213309007-2625b2e3-18ef-4ecd-ae15-224f4cff48b2.png)

2.5.2. **Raporty** zawierają takie dane jak:
* Drużyna zawodnika;
* Zdobyte gole;
* Stracone gole;
* Drużyna przeciwna;
* Data;
* Ostatnia modyfikacja;
* Autor;
* Akcje, dają możliwość:
     * Edycji **Raportu**.

### 3.	Interfejs (wygląd)

* Po zmianie rozdzielczości ekranu na wersje mobilną, interfejs aplikacji zyskuje na wyglądzie. Wersja na komputer zdecydowanie mi się nie podoba.

![image](https://user-images.githubusercontent.com/122534768/213310605-1dde6160-9f81-4f7d-a5bf-6ecfcf659883.png)

* Interfejs aplikacji jest bardzo prosty, skromny, mało zachęcający do użytkowania. Proponowałabym inny układ strony. Dodanie na pierwszej stronie rankingu najlepszych 10 graczy. Wyświetlanie krótkich filmów z udziałem graczy z najlepszymi momentami z meczów. Zmiane tłą. Dodanie dźwięku.

* Dodatkowo w aplikacji jest dużo literówek oraz błędów w tłumaczeniu, nie wszystkie słowa zostały przetłumaczone do wybranej wersji językoej.

* Aplikacja jest mało intuicyjna.

### 4.	Według Raportu Lighthouse wydajność aplikacji wynosi 58 %, w celu jej poprawy należy:

* wyeliminować zasoby blokujące renderowanie;
* zminimalizuj pracę głównego wątku;
* skróć czas poświęcany na analizowanie, kompilowanie i wykonywanie Java Script.

![image](https://user-images.githubusercontent.com/122534768/213310258-512d270d-1285-4585-afce-0546c74e6bbe.png)

# Task 2

## Subtask 1

### 1. Writing test cases based on User Story.

https://docs.google.com/spreadsheets/d/1nj29FupjcOu1rnDOw2KjLS-ICXrpnYi3P9NKVSt8oFw/edit?usp=sharing

1.1. US_01 As a Football Scout, I would like to have a login platform to be able to log into the system.

Users need a login page with a Login field, Password field (Login and password are given by the site administrator to avoid bots). The website should also contain a remind password button, a dropdown with the option of choosing the language - English or Polish, as well as a Sing button.

Acceptance Criteria:
* Login field,
* Password field,
* After entering the correct login and password, the user should be able to log into the system (after clicking sign in button),
* After entering an Invalid login or password, the validation "Identifier or password invalid" should be displayed,
* After you try to log into the system without providing your login or password, the validation "Please provide your username or your e-mail." should be displayed,
* After clicking remind password - the user should be redirected to the remind password page,
* Choosing one of the language options, the website should be translated into Polish or English. 

1.2. US_02 As a Football Scout, I would like to add a new player to be able to trade it in the future.
After logging in to the system, the user must have easy access to the form for adding a new player. It will be the "Add player" button on the tile named "Shortcuts".

Design 1:

![2023-01-24_11h01_46](https://user-images.githubusercontent.com/122534768/214263688-0cf84829-9018-4235-82cc-0f5372563010.png)

After clicking the add player button, the user is redirected to the player-adding form.

Design 2:

![2023-01-24_11h02_45](https://user-images.githubusercontent.com/122534768/214266409-a019e157-d5dd-48b8-9dd1-f37ef023adff.png)

Acceptance Criteria:
* Add player button must redirect to the player-adding form,
* The form should contain fields such as E-mail, name, surname, phone, weight (kg), height (cm), age, leg, club, level, main position, second position, district, achievements, Łączy nas piłka, 90 minutes, Facebook.
* The required fields are Name, Surname, Age, and Main position.
* The form should contain buttons such as Add language, add a link to youtube, submit, and clear.
*After clicking Add language - a field should appear with the option to enter the language used by the player. A trash can icon should appear on the right so you can easily delete the item.
* After clicking Add link to youtube - a field should appear with the option to enter the link to youtube. A trash can icon should appear on the right so you can easily delete the item.
* After clicking the Clear button, the entire form should be cleared immediately.
* After clicking the Submit button, the player should be added to the system * as long as all mandatory fields have been filled in.
* If any of the required fields have not been filled in, a bubble should appear with the words "Fill in this field", and after clicking somewhere next, the field should turn red with the validation "required"

## Subtask 2

### Writing test cases based on "own experience".

https://docs.google.com/spreadsheets/d/131yd2nYajoGlCBeDk5eO_olVVewJm-YwyJhoZn56tKs/edit?usp=sharing

## Subtask 3

Test cases are used to document the functionality of the application in a clear way. Tests are performed on their basis. After the tests are completed, test cases are used to create reports on the tests performed. They are also used to create acceptance tests.

## Subtask 4

### Writing test cases based on "own experience".

https://docs.google.com/spreadsheets/d/1syBFhG4C7qPP1Y_xCBwWt0g7E3WA1kY2ih22RPAT3Wo/edit?usp=sharing

