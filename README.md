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


# Task 3

## Subtask 1 

Formularz do zgłaszania błędów systemu.

https://docs.google.com/spreadsheets/d/1kTWmcChi0hz9Q90Mx5DCk5yTq6h-r8UfxduPLMGh7Do/edit?usp=share_link

## Subtask 2

Testowanie według planów testów i raportowanie błędów

https://docs.google.com/spreadsheets/d/1yk2sd5-TrRxMyD8aUxhAUdKQwpo0XNFtybqBk7czpQc/edit?usp=share_link

## Subtask 3

Raport z wykonanych testów.

https://docs.google.com/document/d/1rf8GIMs0iJKXkLUXEJRQD32iCCK16sKatQEg4F6_hLk/edit?usp=share_link

# Task 4

## Subtask 2

https://docs.google.com/spreadsheets/d/1bAqjko-hBOIW7fudtsWaxG0IGbjl9IARJmoZzjYMw_U/edit#gid=0

## Subtask 3 

1. Aplikacja OLX służy do zamieszczania ogłoszeń z różnych dziedzin. 

2. Użytkownikiem końcowym może być tak naprawdę każdy, zarówno osoba prywatna jak i firma, poszukująca konkretnej usługi / rzeczy wśród ogłoszeń.

3. Moim zdaniem aplikacja OLX powinna popracować nad tym, aby była w 100% przyjazna dla użytkownika.

5. Co zrobić, aby usprawnić aplikacje:

* Należy popracować nad czasem ładowania aplikacji.
* Proponuje aby obrazki przedstawiające kategorie ogłoszeń były bardziej dopracowane.
* Przyciski kategorii ogłoszeń powinny się wyświetlać po cztery w rzędzie na głównej stronie, w celu lepszej wizualizacji i zobaczenie od razu wszystkich kategorii, bez konieczności przewijania w bok.
* Użytkownik powinien również mieć jasny komunikat co w formularzu dotyczącym nowego ogłoszenia zostało wprowadzone błędnie, które wartości należy poprawić, aktualnie tak się nie dzieje.
* Trzeba również popracować nad tym, żeby podczas poszukiwania i skrolowania wyświetlały się wszystkie zdjęcia, a nie czarne plamy.
* Aplikacja nie powinna się również zamykać podczas wprowadzania nowego ogłoszenia oraz kontynuacji wprowadzania ogłoszenia.
* Wskaźniki wprowadzane do ogłoszenia powinny posiadać ograniczenia co do maksymalnej i minimalnej wartości.
* Pole do wypełnienia cyframi powinny zostać wypełnione tylko cyframi.
5.	Różnice pomiędzy testowaniem aplikacji webowych i natywnych:
* Aplikacje natywne można testować offline, do aplikacji webowych potrzebny jest Internet.
* Testowanie aplikacji natywnych wiąże się z instalacja aplikacji na urządzeniu mobilnym, natomiast przy aplikacji webowych nie jest to wymagane.
* Interfejs aplikacji natywnej powinien zostać dostosowany do różnego rodzaju urządzeń mobilnych.
* W aplikacji natywnej nawigacja powinna być intuicyjna i znajdować  się w okolicy kciuka, w aplikacji webowej nawigacja znajduje się zazwyczaj na górze strony.


## Subtask 4

https://challangedareit.atlassian.net/jira/software/projects/CHAL/boards/1

![image](https://user-images.githubusercontent.com/122534768/217265739-5db25c66-24ad-4e02-b72a-0908611b2edf.png)

![image](https://user-images.githubusercontent.com/122534768/217266239-f8b06f96-7605-467b-a07f-097b892c17d0.png)

![image](https://user-images.githubusercontent.com/122534768/217266700-964af885-44ba-4623-bd58-370cebb11bcf.png)

![image](https://user-images.githubusercontent.com/122534768/217266953-4259c4d3-282c-4fd8-b976-41702c6f63dc.png)

# Task 5 

## Subtask 1  

## Operatory / zapytania  ? polecenia w SQL których sią nauczyłam :

### Zapytania i komendy w SQL

* **SELECT** - jest podstawową klauzulą SQL- używaną do wyszukiwania danych. 
* **FROM** - służy do określania tabeli, której dotyczy zapytanie.
* **WHERE** - formułuje warunek, który określa ograniczenia, jakie mają spełniać rekordy, jeżeli rekord spełnia ograniczenia to zostaje dołączony do tabeli wynikowej.

<img width="339" alt="image" src="https://user-images.githubusercontent.com/122534768/218282340-7a323980-14a2-400f-ac80-4b0e25e6e57c.png">

* **CREATE TABLE** - służy do tworzenia tabeli.

<img width="315" alt="image" src="https://user-images.githubusercontent.com/122534768/218283580-8f2c0bfa-122a-4a2b-ba1f-d1bef31a8112.png">

* **AS** - (alias) używany w celu zmiany nazwy według własnej potrzeby.

<img width="239" alt="image" src="https://user-images.githubusercontent.com/122534768/218313553-ec9e05d0-6d2c-4a89-be65-3da6c08ebd76.png">

* **ORDER BY** - służy do sortowania wyników.

     * do sortowania malejącegi używamy **DESC**;
     * do rosnącego sortowania **ASC** - normalnie jest pomijane, ponieważ z założenia sortowane są rosnąco.

<img width="355" alt="image" src="https://user-images.githubusercontent.com/122534768/218313930-4d8b1f09-167f-4270-a0c0-022f4cc8bd90.png">

* **USE** - polecenie jest używane, gdy w SQL istnieje wiele baz danych, a użytkownik lub programista chce konkretnie użyć określonej bazy danych.

* **GO** -  podczas wpisywania komend gdy napotkana zostanie fraza GO, zostania ona uruchomiona.

<img width="391" alt="image" src="https://user-images.githubusercontent.com/122534768/218315753-648c9164-9405-48a8-92e9-09415e356c44.png">

* **GROUP BY** - polega na grupowaniu danych, krok ten, wykonywany jest jako kolejny po filtrowaniu rekordów, zgodnie z warunkami określonymi w **WHERE** (o ile w ogóle cokolwiek filtrujemy), lub bezpośrednio po **FROM** jeśli nie korzystamy z selekcji wierszy.

<img width="308" alt="image" src="https://user-images.githubusercontent.com/122534768/218321130-422590b4-e47f-46f8-aa35-eeeb43d2ad95.png">

* **JOIN** - klauzula pozwala na łączenie ze sobą danych znajdujących się w różnych tabelach.

<img width="789" alt="image" src="https://user-images.githubusercontent.com/122534768/218321787-a062cfc0-5326-4503-b018-3565da189fe7.png">

### Funkcje w SQL

#### 1. Funkcja skalarna to funkcja, która dla każdego zestawu jednego lub większej liczby parametrów skalarnych zwraca pojedynczą wartość skalarną.

* **GETDATE** - zwraca bieżącą datę i czas

<img width="139" alt="image" src="https://user-images.githubusercontent.com/122534768/218317501-7b0e33e5-850a-44ee-8253-7d7182807e84.png">

* **UPPER** - zamienia małe na duże litery.

<img width="284" alt="image" src="https://user-images.githubusercontent.com/122534768/218317685-793ec887-704e-47d6-938c-610d3faae3d9.png">

* **LOWER** - zamienia duże lietry na małe.

<img width="442" alt="image" src="https://user-images.githubusercontent.com/122534768/218317813-bea7406b-64de-465d-be8e-4d1275a4cdfc.png">

* **DATEDIFF** potrafi wyliczać różnice pomiędzy dwoma wartościami takimi jak lata, miesiące, godziny itp.

<img width="471" alt="image" src="https://user-images.githubusercontent.com/122534768/218317264-99d44ca1-9ab2-48e0-ac75-f34f0a88eeea.png">

<img width="366" alt="image" src="https://user-images.githubusercontent.com/122534768/218318028-241a188b-0827-4499-929f-e5ba86f7f80d.png">

#### 2. Funkcje agregujące - funkcje wbudowane w serwer bazodanowy, które są stosowane w odniesieniu do grup danych i bazując na nich zwracają jedną wartość.

* **COUNT** - zwraca liczbę wierszy w określonej tabeli i zachowuje zduplikowane wiersze. Liczy każdy wiersz osobno. Obejmuje to wiersze zawierające wartości null.

<img width="412" alt="image" src="https://user-images.githubusercontent.com/122534768/218318276-4d838a07-1148-47db-b5d2-e5cc7ea218fb.png">

* **SUM** - za pomocą funkcji dodawane są wszystkie wartości rekordów wybranych w zapytaniu i zwracany jest pojedynczy wynik. Obejmuje wyłącznie liczby.

<img width="121" alt="image" src="https://user-images.githubusercontent.com/122534768/218320162-b8e6549c-e6c7-4a3c-9178-d8e11784f0dc.png">

* **MIN** - funkcja służy do znajdowania wartości najmniejszej w zbiorze wartości,  obie funkcje, podobnie jak funkcja COUNT(), mogą być użyte dla różnych typów danych.

<img width="445" alt="image" src="https://user-images.githubusercontent.com/122534768/218320391-91e88b62-feaf-4401-b18d-0a8f33506f4b.png">

* **MAX** - funkcja służy do znajdowania wartości największej w zbiorze wartości,  obie funkcje, podobnie jak funkcja COUNT(), mogą być użyte dla różnych typów danych.

* **AVG** - zwraca średnią wartość.

#### 1. Operatory porównania

* równe **(=)** pokazuje wynik , jeżeli porównane wartości są takie same.

**SELECT** LastName
**FROM**  Person.Person
**WHERE** LastName = 'Adams';

* większe niż **(>)** pokazuje wynik, jeżeli pierwsza wartość jest większa od drugiej

**SELECT** *
**FROM**  Production.Product
**WHERE** ListPrice > 0;

* mniejsze niż **(<)** pokazuje wynik, jeżeli pierwsza wartość jest mniejsza od drugiej

**SELECT** *
**FROM**  Production.Product
**WHERE** ListPrice < 100;

* większy lub równy **(>=)** - wynik wyświetla się jeśli pierwsza wartość jest większa lub równa drugiej

**SELECT** *
**FROM**  Production.Product
**WHERE** ListPrice >= 100

* mniejszy lub równy **(<=)** - wynik wyświetla się jeśli pierwsza wartość jest mniejsza lub równa drugiej

**SELECT** *
**FROM**  Production.Product
**WHERE** ListPrice <= 100

* różny (<>,!=) - wynik wyświetla się, jeśli porównywane wartości są różne

**SELECT** *
**FROM**  Production.Product
**WHERE** ListPrice <> 0;

**SELECT** *
**FROM**  Production.Product
**WHERE** ListPrice != 0;

#### 2. Operatory SQL w klauzuli WHERE:

* **IN** - wyświetla wynik jeśli argument z lewej strony operatora jest równy jednej z wartości po prawej stronie

**SELECT** *
**FROM** Person.Person
**WHERE** LastName  **IN** ( 'Walters', 'Miller')

* **BEETWEN .. AND** – wyświetla wynik, jeżeli argument znajdujący się z lewej strony operatora ma wartość z przedziału podanego po prawej stronie operatora. Końce przedziału są włączone do zakresu.

**SELECT** *
**FROM** Production.Product
**WHERE** ListPrice **BETWEEN** 50 **AND** 200

* **LIKE** - umożliwia przeszukiwanie danych tekstowych pod kątem ich zgodności ze wzorcem
     * symbol procent **(%)** zastępuje dowolny ciąg znaków
     
     **SELECT** *
     **FROM** Person.Person
     **WHERE** LastName **LIKE 'M%'**

     * symbol dolnego podkreślenia **(_)** zastępuje jeden dowolny znak
     
     **SELECT** *
     **FROM** Person.Person
     **WHERE** LastName **LIKE 'M_'** 
     
* **NUL** znacznik, który reprezentuje brakujące dane i jest różny od zera oraz od pustego ciągu znaków. Do znacznika **NULL** można się odnosić jak do braku jakichkolwiek danych w polu. Z powodu występowania znacznika **NULL**, w serwerach bazodanowych obowiązuje logika trójwartościowa a nie dwuwartościowa. Porównanie znacznika **NULL** z dowolną inną wartością daje w wyniku wartość nieznaną, a nie PRAWDĘ lub FAŁSZ.
 
<img width="416" alt="image" src="https://user-images.githubusercontent.com/122534768/218284039-d9bd9a73-0ec3-4140-a33b-8a072cec117b.png">

<img width="424" alt="image" src="https://user-images.githubusercontent.com/122534768/218284145-749d48c3-ca46-4a91-8cb7-f2d3548005a5.png">
    
#### 3. Operatory logiczne, które umożliwiają połączenie kilku warunków w jeden złożony:

* **AND** - (i) wszystkie warunki muszą być prawdziwe, aby całość wyrażenia została wyświetlona

**SELECT** *
**FROM** Person.Person
**WHERE** FirstName = 'David' **AND** LastName = 'Bradley';

* **OR** - (lub) tylko jeden z warunków musi być prawdziwy, aby całość została wyświetlona

**SELECT** *
**FROM** Person.Person
**WHERE** FirstName = 'David' **OR** LastName = 'Bradley';

* **NOT** używany do zaprzeczenia

## SUBTASK 3

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

<img width="213" alt="image" src="https://user-images.githubusercontent.com/122534768/218324798-b39f5776-6c78-402b-8534-8794c8b9e6b3.png">
<img width="190" alt="image" src="https://user-images.githubusercontent.com/122534768/218324895-5ef985e1-f383-418c-a114-725ada73704b.png">

2. Wyświetl film, który powstał w 2019 roku.

<img width="303" alt="image" src="https://user-images.githubusercontent.com/122534768/218326024-5b20d6b4-dfe3-42ba-bbb7-27b26aab50e8.png">
<img width="240" alt="image" src="https://user-images.githubusercontent.com/122534768/218326071-63ce6ce1-964b-4e82-8288-99686144f8d4.png">

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

<img width="382" alt="image" src="https://user-images.githubusercontent.com/122534768/218326664-ae9181ff-5759-41bf-9a63-671175ad1946.png">
<img width="373" alt="image" src="https://user-images.githubusercontent.com/122534768/218326685-9e728f63-885a-42e4-a3a9-4d949ddb744c.png">


4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

<img width="275" alt="image" src="https://user-images.githubusercontent.com/122534768/218328891-e40cd0a5-ade1-48cc-81c2-1569247c9a9b.png">
<img width="225" alt="image" src="https://user-images.githubusercontent.com/122534768/218328913-0b4987b0-4594-4e13-9522-726ff7d36e26.png">

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

<img width="333" alt="image" src="https://user-images.githubusercontent.com/122534768/218329250-0567be1e-b511-4c44-83d4-1a7d3a92cf14.png">
<img width="178" alt="image" src="https://user-images.githubusercontent.com/122534768/218329266-2f16831b-648c-41a5-ab07-87b30ef12084.png">

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

<img width="472" alt="image" src="https://user-images.githubusercontent.com/122534768/218332491-e22d3ef6-ec13-46fd-b128-9d6b21ae081c.png">
<img width="259" alt="image" src="https://user-images.githubusercontent.com/122534768/218332513-1a6dab69-0655-4f17-b33b-84cc79f11e3d.png">

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

<img width="317" alt="image" src="https://user-images.githubusercontent.com/122534768/218583651-2ecacbe8-8c71-43a1-a5df-93af80e875df.png">
<img width="250" alt="image" src="https://user-images.githubusercontent.com/122534768/218583709-0f362c36-7615-43fc-92cd-1165af0f7097.png">
 
8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

<img width="238" alt="image" src="https://user-images.githubusercontent.com/122534768/218584455-82ead9a9-5a05-401b-ad33-fb6d22485574.png">
<img width="160" alt="image" src="https://user-images.githubusercontent.com/122534768/218584509-7cd5f8c9-8441-4f37-ba4d-c56a3dd50506.png">

9. Wyświetl dane klienta, który nie ma podanego adresu email.

<img width="248" alt="image" src="https://user-images.githubusercontent.com/122534768/218585040-d8321254-cbed-4812-adde-655679f2ca07.png">
<img width="215" alt="image" src="https://user-images.githubusercontent.com/122534768/218585099-8dd3b679-c359-4965-8194-370f1184afb4.png">

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

<img width="387" alt="image" src="https://user-images.githubusercontent.com/122534768/218586550-826bbf1e-1439-4e6c-8070-0a03f6b5f6c0.png">
<img width="270" alt="image" src="https://user-images.githubusercontent.com/122534768/218586634-301972e6-0d7a-4781-8e02-bfa974811557.png">

# Task 5

## Subtask 1

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd.

<img width="340" alt="image" src="https://user-images.githubusercontent.com/122534768/219371798-a570fa2b-b0b8-4729-b6fd-3b6da279a537.png">
<img width="265" alt="image" src="https://user-images.githubusercontent.com/122534768/219372212-2d975b73-1336-45a1-af6b-811f1470ebfc.png">

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

<img width="653" alt="image" src="https://user-images.githubusercontent.com/122534768/219452701-52b9ff46-1c24-4d6f-bb5c-cd4d4fbba22e.png">
<img width="92" alt="image" src="https://user-images.githubusercontent.com/122534768/219452869-69ad6f59-17d1-468e-a632-79836c34a8d9.png">

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com

<img width="363" alt="image" src="https://user-images.githubusercontent.com/122534768/219467580-23b28e91-adf4-4739-8dba-c744407437fb.png">
<img width="266" alt="image" src="https://user-images.githubusercontent.com/122534768/219467809-d46e0546-21fc-43a8-ba38-10594261849e.png">

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

<img width="729" alt="image" src="https://user-images.githubusercontent.com/122534768/219642591-d5b821f3-e4ea-4ee9-9339-8aef76223200.png">
<img width="333" alt="image" src="https://user-images.githubusercontent.com/122534768/219642716-d51f40e4-4f03-4d1c-8143-f660f01e04d4.png">

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

<img width="267" alt="image" src="https://user-images.githubusercontent.com/122534768/219663993-df69e61c-53fb-44f9-a750-df4138bceba1.png">
<img width="499" alt="image" src="https://user-images.githubusercontent.com/122534768/219662614-d0bbf7d5-19e7-439e-98e4-03e969d5bc10.png">
<img width="73" alt="image" src="https://user-images.githubusercontent.com/122534768/219662686-c873128e-cc14-4f90-bfa9-6ae7bb818b62.png">

16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

<img width="473" alt="image" src="https://user-images.githubusercontent.com/122534768/219677225-ff26a73f-b45f-4524-bc79-a29d35624723.png">
<img width="178" alt="image" src="https://user-images.githubusercontent.com/122534768/219677298-265a78b0-1f65-48c3-b564-a363fe21d789.png">

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

<img width="514" alt="image" src="https://user-images.githubusercontent.com/122534768/219687576-57f4ca43-4f6a-47d7-889c-0799fd792dd6.png">
<img width="73" alt="image" src="https://user-images.githubusercontent.com/122534768/219687508-f2326a35-1e87-4d7b-a89c-82491bde7822.png">

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

<img width="379" alt="image" src="https://user-images.githubusercontent.com/122534768/219776281-1400b3f3-3c89-4dee-ab85-e2f91c374672.png">
<img width="395" alt="image" src="https://user-images.githubusercontent.com/122534768/219775768-469160c7-d2f0-4296-bc12-9eb1d1b298e8.png">
<img width="382" alt="image" src="https://user-images.githubusercontent.com/122534768/219775909-37d9305e-c522-4a18-80e4-b8a9bcd8e3cb.png">

19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał.

<img width="613" alt="image" src="https://user-images.githubusercontent.com/122534768/219780539-fb88cb3a-c0a8-41e3-99e0-1bbe86d189ca.png">
<img width="157" alt="image" src="https://user-images.githubusercontent.com/122534768/219780779-c24b5ab8-f8ac-4a46-b915-1efede30ba4f.png">

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

<img width="640" alt="image" src="https://user-images.githubusercontent.com/122534768/219794650-bd9735e5-4222-4c1b-9190-6d425e18f28f.png">
<img width="332" alt="image" src="https://user-images.githubusercontent.com/122534768/219794706-f9216074-c887-4c48-abef-47769cf4fd91.png">


