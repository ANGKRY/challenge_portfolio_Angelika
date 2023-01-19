# Task 1  


## *Subtask 1*

8 pkt

## *Subtask 3*

Biorę udział w projekcie, ponieważ szukam zmian i wyzwań w moim życiu zawodowym. Jestem otwarta na nowości i gotowa do nauki. Moim celem jest znalezienie właściwej drogi zawodowej. Oczekuje, że to wyzwanie da mi jeszcze większy zapał do dalszej nauki i pewność, że właśnie to jest to co chciałabym robić w przyszłości. 	:smiley:

## *Subtask 4*

### 1. Opis aplikacji

Aplikacja:  https://scouts-test.futbolkolektyw.pl/pl służy do weryfikacji osiągnieć graczy w dwóch wersjach językowych polskim i angielskim. Daje również możliwość porównania wskaźników, dodawania meczów, tworzenia raportów i ściągania danych do Excela. Przeznaczona jest dla osób/firmy poszukujących utalentowanych zawodników.

### 2. Funkcjonalność

2.1. Funkcjonalność aplikacji w ramach logowania i wylogowania jest prawidłowa, zmiana języka przy logowaniu działa poprawnie. Istnieje możliwość przesłania maila przypominającego z hasłem w przypadku nie zapamiętania hasła.

2.2. Po zalogowaniu wyświetla się **Strona główna**, na samej górze w rzędzie widoczne są przyciski z aktualizowanymi na bieżąco wartościami (**Ilość graczy, Ilość meczy, Ilość raportów, Ilość akcji**), które niestety nie są aktywne, po ich naciśnięciu nie można wejść w szczegóły wyświetlanych danych.

![2023-01-18_17h21_03](https://user-images.githubusercontent.com/122534768/213235825-457766a5-19b2-4481-86bb-c5c4b964f9b2.png)

2.3.	W części centralnej **Strony głównej** wyświetlane są również przyciski:

2.3.1. **Scouts Panel** (panel zarządzania graczami, meczami i do tworzenia raportów) nie spełnia opisanej funkcji zarządzania graczami, meczami tworzenia raportów. Błędnie kieruje do kontaktu z programistami. Zarządzanie graczami, meczami i tworzenie raportów jest możliwe dopiero po wejściu na konto jednego z **Graczy**.

![2023-01-18_20h08_41](https://user-images.githubusercontent.com/122534768/213273420-eef8aeb0-514f-462a-a63b-eb7e78ec81dd.png)

2.3.2. **Linki pomocnicze** (Dodaj Gracza);

* Przycisk dający możliwość dodawania zawodników, powinien zostać inaczej zatytułowany, żeby jasno określał swój cel, tj. dodawanie nowych zawodników.

![2023-01-18_20h20_03](https://user-images.githubusercontent.com/122534768/213274664-373ccb33-4353-4e65-9f9c-0a2f978843ee.png)

* Podczas wpisywania danych nowego zawodnika, aplikacja informuje, że nie może wprowadzić do systemu nowego **Gracza**, natomiast nie informuje z jakiego powodu        tak się dzieje. 

* Podczas wpisywania imienia i nazwiska można używać symboli i cyfr, oraz nie ma ograniczenia co do ich długości.

![2023-01-18_21h48_20](https://user-images.githubusercontent.com/122534768/213291547-da236eb5-7200-4c36-9062-bace55ecdeef.png)

* Wpisując dane nowego gracza w rubryce telefon można wpisać nie tylko cyfry, a symbole i litery. Proponuje aby dla ułatwienia stworzyć możliwość wyboru numeru kierunkowego danego kraju oraz wprowadzić ograniczenie co do ilości wpisywanych cyfr, w zależności od wybranego kraju.

![image](https://user-images.githubusercontent.com/122534768/213292227-6a523131-7970-4f41-a666-336bae2b6ff4.png)

* W rubryce wzrost i waga można wybrać ujemne wartości. Powinno się wprowadzić minimalne i maksymalne wartości.

![2023-01-18_21h59_49](https://user-images.githubusercontent.com/122534768/213293762-2725a082-4280-4f96-bbf7-309a6209100d.png)

* W polskiej wersji językowej, w lewym dolnym roku są przyciski w języku angielskim (submit i clear).

![2023-01-18_22h04_07](https://user-images.githubusercontent.com/122534768/213294307-6ee08930-287d-4ebc-a92a-0683cfc778c0.png)

* Wprowadzając datę urodzenia gracza można wpisać czas przyszły. Zawodnik zapisany w aplikacji może mieć również nieograniczoną liczbę lat. Proponuje wykluczyć            możliwość zapisu daty urodzenia przyszłej i wprowadzić maksymalny i minimalny wiek.

![2023-01-18_22h07_12](https://user-images.githubusercontent.com/122534768/213297787-b75279b8-5235-4bc2-8bbe-d98ab93129d7.png)

 * Aplikacja pozwala wprowadzać tego samego gracza kilkarotnie, co mocno zmniejsza jej funkcjonalność.

![2023-01-18_22h25_59](https://user-images.githubusercontent.com/122534768/213298512-d9c651c9-d1c5-440c-8b14-f1b088c5a8f9.png)

  2.3.3. **Aktywność**, pokazuje aktualną aktywność na stronie, tj.:
     * ostatnio stworzony gracz;
     * ostatnio zaktualizowany gracz;
     * ostatnio stworzony mecz;
     * ostatnio zaktualizowany mecz;
     * ostatnio zaktualizowany raport.
     
* Przycisk **Aktywność** jest błędnie zapisany (Aktywnosć), dodatkowo słowa: "zaktualizowany" również posiada dodatkowe „a”.

![2023-01-18_22h31_04](https://user-images.githubusercontent.com/122534768/213299609-8a69b429-ed84-470e-aaf8-3d934cedd801.png)

2.4.	 W wersji pełno ekranowej z lewej strony znajduje się pasek z następującymi przyciskami:
*	**Strona główna** 
*	**Gracze**, po kliknięciu pojawia się tabela z następującymi danymi:
     *	imię;
     *	nazwisko;
     *	wiek;
     *	pozycja rozgrywająca;
     *	klub;
     *	recenzja;
     *	ilość rozegranych meczy;
     *	raporty.
     
Nie ma możliwości segregowania danych alfabetycznie lub od najmniejszego do najwyższego wartości i odwrotnie. Nie można również ustawić ilości wyświetlanych danych na stronie.
          
* **English** / **Polski**, przycisk zmienia język;

Ikona zmiany języka powinna zawierać na przykład flagę z językiem do wyboru, a nie niezrozumiałe znaczki.

![2023-01-18_20h39_35](https://user-images.githubusercontent.com/122534768/213278898-ad847c88-7c66-4212-8cb5-a328edc1cf6c.png)
![2023-01-18_20h39_57](https://user-images.githubusercontent.com/122534768/213278935-d908492f-93b0-410c-8d02-d45a6cd748ec.png)

*	**Wyloguj**, powoduje wylogowanie z aplikacji.

W wersji mobilnej na telefon, po zmianie rozdzielczości ekranu, powyższe informacje wyświetlają się po kliknięciu w ikonę w lewym górnym rogu. 

2.4.1.	Tabele z danymi **Graczy** można przy użyciu ikon w prawym górnym rogu:
* pobrać do pliku Excel;
     * Dane po pobraniu do Excela trafiają do do pierwszej kolumny, co nie jest funkcjonalne i czytelne.

![2023-01-18_20h54_38](https://user-images.githubusercontent.com/122534768/213282540-c4fc4ac0-ea51-4613-948f-2f0bde39b566.png)

* wydrukować;
     * Podczas próby wydruku tabeli z danymi, na podglądzie do wydruku widoczni są jedynie zawodnicy z pierwszej strony raportu (pierwszych 10).
     * Dane widoczne do druku wyświetlają się w innej formie, niż widoczna na ekranie monitora komputera, mniej czytelnej.

![2023-01-18_21h08_35](https://user-images.githubusercontent.com/122534768/213285230-a94b3343-23a9-4b6d-9200-316450b57e39.png)
![2023-01-18_21h09_57](https://user-images.githubusercontent.com/122534768/213285261-05d363b4-d156-4dda-9d0c-a26c3b5a3663.png)

* porównać wybierając dowolne wskaźniki;
* wyszukać dane przy zastosowaniu określonych filtrów.

W polskiej wersji językowej ikony ściągania, drukowania, widoku kolumny i filtrowanie wyświetlane są w języku angielskim. Dodatkowo po wejściu na opcje filtrowania również w wersji językowej polskie wyświetlają się frazy w języku angielskim (filters, reset, age, rate)

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

Dodatkowo w aplikacji jest dużo literówek oraz błędów, w polskiej wersji językowej nie wszystkie słowa zostały przetłumaczone na język polski.

### 4.	Według Raportu Lighthouse wydajność aplikacji wynosi 58 %, w celu jej poprawy należy:

* wyeliminować zasoby blokujące renderowanie;
* zminimalizuj pracę głównego wątku;
* skróć czas poświęcany na analizowanie, kompilowanie i wykonywanie Java Script.

![image](https://user-images.githubusercontent.com/122534768/213310258-512d270d-1285-4585-afce-0546c74e6bbe.png)

