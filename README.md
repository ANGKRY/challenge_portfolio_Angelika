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

2.2. Po zalogowaniu wyświetla się **Strona główna**, na samej górze w rzędzie widoczne są przyciski z aktualizowanymi na bieżąco wartościami (**ilość graczy, ilość meczy, ilość raportów, ilość akcji**), które nie są aktywne, po ich naciśnięciu nie można wejść w szczegóły wyświetlanych danych.



2.3.	W części centralnej **Strony głównej** wyświetlane są również przyciski:
* **Scouts Panel** (panel zarządzania graczami, meczami i do tworzenia raportów), który powinien dawać możliwość tworzenia raportów oraz administrowanie danych graczy i ich meczów;
* **Linki pomocnicze** (dodaj gracza), daje możliwość dodania nowego zawodnika;
* **Aktywność**, pokazuje aktualną aktywność na stronie, tj.:
     * ostatnio stworzony gracz;
     * ostatnio zaktualizowany gracz;
     * ostatnio stworzony mecz;
     * ostatnio zaktualizowany mecz;
     * ostatnio zaktualizowany raport.

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
* **English**, przycisk zmienia język na angielski;
*	**Wyloguj**, powoduje wylogowanie z aplikacji.

W wersji mobilnej na telefon, po zmianie rozdzielczości ekranu, powyższe informacje wyświetlają się po kliknięciu w ikonę w lewym górnym rogu. 

2.4.1.	Tabele z danymi **Graczy** można przy użyciu ikon w prawym górnym rogu:
* pobrać do pliku Excel;
* wydrukować;
* porównać wybierając dowolne wskaźniki;
* wyszukać dane przy zastosowaniu określonych filtrów.

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
     * Dodania meczu.

2.5.2. **Raporty** zawierają takie dane jak:
* Drużyna zawodnika;
* Zdobyte gole;
* Stracone gole;
* Drużyna przeciwna;
* Data;
* Ostatnia modyfikacja;
* Autor;
* Akcje, dają możliwość:
     * Edycji.

Po wejściu na ikonę **Mecze** jak i **Raporty** istnieje możliwość dodania nowego dokumentu.


### 2. Funkcjonalność



Przycisk dający możliwość dodawania zawodników (**Linki pomocnicze**), powinien zostać inaczej zatytułowany, żeby jasno określał swój cel, tj. dodawanie nowych zawodników.

**Scouts Panel** nie spełnia opisanej funkcji zarządzania graczami, meczami tworzenia raportów. Błędnie kieruje do kontaktu z programistami. Zarządzanie graczami, meczami i tworzenie raportów jest możliwe dopiero po wejściu na konto jednego z **Graczy**.

Podczas wpisywania danych nowego zawodnika, aplikacja informuje, że nie może wprowadzić do systemu nowego **Gracza**, natomiast nie informuje z jakiego powodu, tak się dzieje, które dane należy poprawić, żeby tak się stało.

### 3.	Interfejs (wygląd)

Po zmianie rozdzielczości ekranu na wersje mobilną, interfejs aplikacji zyskuje na wyglądzie. Wersja na komputer zdecydowanie mi się nie podoba.

Interfejs aplikacji jest bardzo prosty, skromny, mało zachęcający do użytkowania. Proponowałabym inny układ strony. Dodanie na pierwszej stronie rankingu najlepszych 10 graczy. Wyświetlanie krótkich filmów z udziałem graczy z najlepszymi momentami z meczów. Zmiane tłą. Dodanie dźwięku.

Dodatkowo w aplikacji jest dużo literówek oraz błędów, w polskiej wersji językowej nie wszystkie słowa zostały przetłumaczone na język polski.

### 4.	Bugi oraz propozycje zmian 

4.1.	Na **Stronie głównej**:

* Przyciski na stronie głównej (**ilość graczy, ilość meczy, ilość raportów, ilość akcji**) nie są aktywne, po ich naciśnięciu nie przechodzi się do wyświetlanych wartości i ich szczegółów. Warto dodać taką możliwość.
* Przycisk **Scouts Panel** opisany został jako Panel zarządzania graczami, meczami i do tworzenia raportów, natomiast ostatecznie pełni on funkcje kontaktu z programistami. Dodatkowo po zmianie na języka polski, nazwa nie zostaje przetłumaczona.
* Przycisk **Aktywność** jest błędnie zapisany (Aktywnosć), dodatkowo słowa: "zaktualizowany" również posiada dodatkowe „a”.
* Ikona zmiany języka powinna zawierać na przykład flagę z językiem do wyboru, a nie niezrozumiałe znaczki.

4.2.	Na stronie z **Graczami**;

* Podczas ściągania pliku, dane eksportowane są do Excela. Niestety wszystkie dane trafiają do jednej kolumny. Powinny trafiać do poszczególnych kolumn. 
* Dane widoczne do druku wyświetlają się w innej formie, niż widoczna na ekranie monitora komputera, mniej czytelnej.
* Nie ma możliwości segregowania danych alfabetycznie lub od najmniejszego do najwyższego wartości i odwrotnie. Nie można również ustawić ilości wyświetlanych danych na stronie.
* Aplikacja nie weryfikuje czy dane gracza nie są zdublowane.
* Podczas próby wydruku tabeli z danymi, na podglądzie do wydruku widoczni są jedynie zawodnicy z pierwszej strony raportu (pierwszych 10).
* W polskiej wersji językowej ikony ściągania, drukowania, widoku kolumny i filtrowanie wyświetlane są w języku angielskim. Dodatkowo po wejściu na opcje filtrowania również w wersji językowej polskie wyświetlają się frazy w języku angielskim (filters, reset, age, rate)

4.3.	Błędy zweryfikowane podczas wpisywania nowego zawodnika:

* Podczas wpisywania imienia i nazwiska można używać symboli i cyfr, oraz nie ma ograniczenia co do ich długości.
* Wpisując dane nowego gracza w rubryce telefon można wpisać nie tylko cyfry, a symbole i litery. Dla ułatwienia powinna być możliwość wyboru numeru kierunkowego danego kraju oraz wprowadzone ograniczenie co do ilości wpisywanych cyfr.
* W rubryce wzrost i waga można wpisać ujemne wartości.
* W polskiej wersji językowej, w lewym dolnym roku są przyciski w języku angielskim (submit i clear).
* Wprowadzając datę urodzenia gracza można wpisać czas przyszły. Zawodnik zapisany w aplikacji może mieć również nieograniczoną ilość lat. Proponuje wykluczyć możliwość zapisu daty urodzenia przyszłej i wprowadzić maksymalny i minimalny wiek.

 4.4.	**Raporty** i **Mecze**:

* Podczas edycji meczu w polskiej wersji językowej wyświetlają się angielskojęzyczne wskaźniki:
     * Web match
     * General 

### 5.	Według Raportu Lighthouse wydajność aplikacji wynosi 56 %, w celu jej poprawy należy:

* wyeliminować zasoby blokujące renderowanie;
* zminimalizuj pracę głównego wątku;
* skróć czas poświęcany na analizowanie, kompilowanie i wykonywanie Java Script.

