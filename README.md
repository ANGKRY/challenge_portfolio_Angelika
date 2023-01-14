# Task 1


## *Subtask 1*

8 pkt

## *Subtask 3*

Biorę udział w projekcie, ponieważ szukam zmian i wyzwań w moim życiu zawodowym. Jestem otwarta na nowości i gotowa do nauki. Moim celem jest znalezienie właściwej drogi zawodowej. Oczekuje, że to wyzwanie da mi jeszcze większy zapał do dalszej nauki i pewność, że właśnie to jest to co chciałabym robić w przyszłości.

## *Subtask 4*

### 1. Opis i funkcjonalność aplikacji

Aplikacja:  https://scouts-test.futbolkolektyw.pl/pl, służy do weryfikacji osiągnieć graczy. Daje również możliwość porównania wskaźników, tworzenia raportów 
i eksportowania danych do excela. Przeznaczona jest dla osób/firmy poszukujących utalentowanych piłkaży.

Po zalogowaniu wyświetla się Strona główna, na samej górze w rzędzie widoczne są przyciski z aktualizowanymi na bierząco wartościami (ilość graczy, ilość meczy, ilość raportów, ilość akcji).

#### W cześci centralnej Strony głównej wyświetlane są również przyciski:
1. Scouts Panel (panel zarządzania graczami, meczami i do tworzenia raportów);
2. Linki pomocnicze (dodaj gracza);
3. Aktywność.

ad 1. Przycisk "Scouts Panel" powinien dawać możliwość skontaktowania się z zespołem programistów.

ad 2. Kolejny przycisk daje możliwość dodania nowego zawodnika.

ad 3. Ostatni pokazuje aktualną aktywność na stronie, tj.:
  * ostatnio stworzony gracz;
  * ostatnio zaaktualizowany gracz;
  * ostatnio stworzony mecz;
  * ostatnio zaaktualizowany mecz;
  * ostatnio zaaktualizowany raport;

Z lewej strony znajduje się pasek z następującymi przyciskami:
* Strona główna / Main page
* Gracze / Players
* English / Polish
* Wyloguj / Sign out


#### Po przejściu do "Gracze"/"Players" wyświetla się tabela, posiada ona następujące wskaźniki, które można porównać:
  * imię / name;
  * nazwisko / surname;
  * wiek age;
  * pozycja rozgrywająca /;
  * klub;
  * recenzja;
  * ilość rozegranych meczy;
  * raporty.


#### W prawym górnym rogu znajdują się ikony pozwaljące na:
  * ściągnięcie danych;
  * wydrukowanie danych;
  * wybranie wskaźników do porównania;
  * wyszukiwanie danych.
  
Aplikacja jest dwujęzyczna.
Po wejściu na konto gracza z lewej strony wyświetlają się raporty oraz męcze, które można przeglądać, dodawać lub edytować.

### 2. Funkcjonalność i interfejs

Funkcjonalność aplikacji w ramach logowania i wylogowania jest prawidłowa, zmiana języka przy logowaniu działa poprawnie. Istnieje możliwość przesłania maila przypominającego z hasłem w przypadku nie zapamiętania hasła.

Aplikacja wizualnie lepiej wygląda wizualnie wyświetona na ekranie telefonu niż na ekranie komputera.

Interfejs aplikacji jest bardzo prosty, skromny i mało zachęcający do użytkowania. Proponowałam bym inny układ strony. Dodanie na pierwszej stronie rankingu najlepszych 10 graczy. Wyświetlanie krótkich filmów z udziałem graczy z najlepszymi momentami z meczów. 

### 3. Zauważone błędy lub rzeczy do zmiany

#### Na stronie głównej:
1. Przyciski na stronie głównej (ilość graczy, ilość meczy, ilość raportów, ilość akcji) nie są aktywne, po ich naciśnieciu nie przechodzi się do wyświetlanych wartości i ich szczegółów. Warto dodać taką możliwość.
2. Przycisk "Linki pomocnicze" z możliwością dodania nowego gracza powinien być inaczej zatytułowany.
3. Przycisk "Scouts Panel" opisany został jako Panel zarządzania graczami, meczami i do tworzenia raportów, natomiast ostatecznie pełni on funkcje kontaktu z programistami. Dodatkowo po zmianie na języka polski nazwa nie zostaje przetłumaczona.
4. Przycisk "Aktywność" jest błędnie zapisany.
5. Ikona zmiany  języka powinna zawierać na przykład flage z językiem do wyboru, a nie niezrozumiałe znaczki.

####  Po wejściu na Graczy
1. Podczas ściągania pliku, dane eksportowane są do excela. Niestety wszystkie dane trafiają do jednej kolumny. Powiiny trafiać do poszczególnych kolumn. 
2. Dane widoczne do druku wyświetlają się w innej formie niż widoczna na ekranie, mniej czytelnej.
3. Nie ma możliwości segregowania danych alfabetycznie lub od najmniejszego do najwyższego wyniku i odwrotnie. Nie można również ustawić ilości wyświetlanych danych na stronie.
4. Aplikacja nie weryfikuje czy dane gracza nie są zdublowane.
5. Podczas wpisywania imienia i nazwiska można używać symboli i cyfr, oraz nie ma ograniczenia co do ich długości.
6. Wpisując dane nowego gracza w rubryce telefon można wpisać nie tylko cyfry a symbole i litery. Dla ułatwienia powinna być możliwość wyboru numeru kierunkowego danego kraju oraz wprowadzone ograniczenie co do ilości wpisywanych cyfr.
7. W rubryce wzrost i waga można wpisać ujemne wartości.
8. W polskiej wersji językowej podczas wprowadzania danych nowego gracza w lewym dolnym roku są przyciski w języku angielskim (submit i clear).
9. Próbując dodać nowego gracza, nie udało mi sie tego zrobić, pojawił się komunikat: Nie udało się dodać nowego gracza, brak informacji z jakiego powodu.
10. W polskiej wersji językowej ikony ściągania, drukowania, widoku kolumny i filtrowanie wyświetlane są w w języku angielskim. Dodatkowo po wejściu na opcje filtrowania również w wersji językowej polskie wyświetlają się frazy w języku angielskim (filters, reset, age, rate)
11. Wprowadzając datę urodzenia gracza można wpisac czas przyszły. Zawodnik zapisany w aplikacji może mieć rok lub mniej. Trzeba nanieśc ograniczenia wiekowe, od jakiego wieku można zapisywać piłkaży oraz wykluczyć możliwość zapisu daty urodzenia przyszłej. 


#### Devtools - lightools

1. Wydajność – czyli “Performance” 64 %.
2. Ułatwienia dostępu/dostępność – “Accessibility”  100 %.
3. Best Practices 92 %.
4. SEO – to co najważniejsze pod kątem pozycjonowania 91 %.

ad 1.  W celu poprawienia wydajności aplikacji należy:
* zredukować nieużywany JavaScript i odłóżyć ładowanie skryptów, dopóki nie będą wymagane do zmniejszenia liczby bajtów zużywanych przez aktywność sieciową;
* wyeliminować zasoby blokujące renderowanie;
* zminimalizuj pracę głównego wątku;
* skróć czas poświęcany na analizowanie, kompilowanie i wykonywanie Java Script.



