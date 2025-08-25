# Wstęp
## Witajcie!

### Dlaczego Python?
Python to świetny język dla początkujących

- Jest łatwy do nauki
- Ma aktywną i pomocną społeczność
- Oferuje różnorodne możliwości w tworzeniu stron internetowych, grach, naukach o danych
  
CodeHS to najlepsze miejsce do nauki programowania, ponieważ nie ma konieczności konfiguracji - oznacza to, że nie musisz niczego pobierać, ustawiać ani instalować. Całą potrzebną pracę już wykonałeś, bo jesteś tutaj!

Teraz wystarczy, że będziesz podążać za mną, przechodzić do kolejnych etapów tutoriala i po prostu się bawić! No to zaczynamy!

# CodeHS
## Przestrzeń Robocza CodeHS

1. Kliknij na plik `main.py` po lewej stronie. To otworzy plik w głównym oknie kodowania (#2 poniżej), abyśmy mogli zacząć.

### Zróbmy szybką wycieczkę po przestrzeni roboczej CodeHS - czyli co masz teraz na ekranie:

- **Files:** Jeśli potrzebujesz wyświetlić inny plik, po prostu kliknij tutaj. To także miejsce, gdzie możesz przesłać różne zasoby (zdjęcia, gify itp.), aby użyć ich w swoim projekcie.

- **Coding window:** Tutaj będziesz przeprowadzał większość pracy; cały twój kod zostanie dodany tutaj. Możesz także tu wyświetlić pliki.

- **Console:** Pokazuje wynik programu (wszystko, co chcemy pokazać użytkownikom, pojawi się tutaj).

- **Run:** To sprawi, że twój kod... no, wystartuje, uruchomi się.

- **Publish:** Podziel się swoim kodem z naszą społecznością, aby inni mogli zobaczyć i zmodyfikować.

- **Invite:** Pozwól innym osobom na żywo edytować twój kod w trybie wieloosobowym.

# Rozpocznijmy kodowanie!

👉 Wprowadź ten wiersz kodu w `main.py` i kliknij `run`.

```python
print("Hello World")
```

(WSKAZÓWKA: Za każdym razem, gdy zobaczysz 👉, oznacza to, że będziesz kopiować, dodawać lub pisać kod w edytorze kodowania).

Jeśli wszystko działa zgodnie z oczekiwaniami, konsola powinna teraz pokazać ci piękną wiadomość!

<details><summary>💡Wskazówka</summary>Jeśli chcesz poczuć się jak prawdziwy haker, po zakończeniu pisania kodu naciśnij CMD/Windows + Enter, aby uruchomić swój kod!</details>

# Popularne polecenia, które powinien znać każdy programista!

Zaczynajmy od kilku prostych komend, aby uzyskać prosty wynik (informacje, które program przekazuje użytkownikowi).


## Polecenie wypisania (print statement)

Właśnie nauczyłeś się swojej pierwszej komendy: instrukcji `print`. Mówi ona "Wypisz cokolwiek, co znajduje się w moich nawiasach". Instrukcja `print` pozwala programowi wyświetlić wiadomości w konsoli.

![](resources/02-a-print.png)

- Cudzysłowy `""` (cytaty) służą do informowania komendy, że wkładasz tam tekst (dowolny tekst, który chcesz).
- Zbiór tekstu (lub cokolwiek, co umieścisz w cudzysłowach) nazywa się łańcuchem znaków (stringiem).
- 
👉 Użycie ***potrójnego cudzysłowu*** `"""` pozwala na napisanie dużego kawałka tekstu z odstępami lub podziałami linii. Dodaj ten kod do tego, co masz w pliku `main.py` i kliknij `run`.

```python
print("""Anything that starts
with three quotes, and ends
in three quotes can span
many lines and even contain " symbols
within it without freaking anything out!""")
```
## Komenda `input`

Spójrzmy na komendę `input` i jak ona działa. Wprowadzenie danych polega na tym, że użytkownik udziela informacji komputerowi.

![](resources/01-input.png)

To jest bardzo podobne do komendy `print`, z tą różnicą, że spowoduje wyświetlenie wiadomości w konsoli, ***a następnie zaczeka***, aż użytkownik wprowadzi coś do konsoli i naciśnie klawisz Enter. Spróbujmy tego!

&nbsp;

👉 Skopiuj ten kod do edytora kodu w pliku `main.py` i zobacz, co się stanie po kliknięciu `run`:

```python
input("Jak masz na imię?: ")
```
# Jak wykorzystać polecenie input czyli zmienne (Variables)

## Czym jest zmienna?
Komenda `input` pyta o coś, otrzymuje to, ale nie ma gdzie tego umieścić. Możemy to zmienić dzięki zmiennej, która jest wartością, którą możemy użyć, aby nazwać i przechowywać dane.

![](resources/02-variables.png)

## Nazewnictwo zmiennych
- Możesz nadawać zmiennej dowolną nazwę, ale **nie możesz używać spacji**. Możesz używać:
  - podkreślników_między_słowami
  - camelCase, aby ułatwić czytanie

👉 Usuń cały swój kod i skopiuj ten kod do edytora kodu w pliku `main.py`:

```python
myName = input("Jak masz na imię?: ")
myAge = input("Ile masz lat?: ")
print("Wow, to naprawdę DUŻO")
codeCamp = input("Czy lubisz CodeCamp?")
print("OCZYWIŚCIE, ŻE TAK!")
```

- Mamy teraz ***trzy*** zmienne:
  - `myName` przechowuje imię użytkownika
  - `myAge` przechowuje ich wiek
  - `codeCamp` przechowuje ich uczucia wobec CodeCampa 😎.

&nbsp;

# Popularne błędy
*Rozpocznij od usuwania wszelkiego innego kodu z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij "run" i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij "run", aż osiągniesz stan bezbłędny.*

Czasami podczas pisania kodu pojawiają się błędy. Oto najpopularniejsze błędy:

### NameError (Błąd Nazwy)

Będziesz widział ten komunikat błędu, jeśli:
- wpiszesz nazwę funkcji niepoprawnie,
- przeoczyłeś literówkę,
- zrobiłeś błąd w wielkości liter.

&nbsp;

👉 Spróbujmy uruchomić ten kod i zobaczyć, jaki komunikat błędu otrzymamy. Dodaj ten kod do edytora kodu i kliknij `run`.

```python
Print("What could go wrong?")
```

Jak myślisz, co jest źle? Zawsze ważne jest czytanie komunikatów błędów, ponieważ starają się być pomocne.

```
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    Print("Co mogło pójść źle?")
NameError: name 'Print' is not defined
```

Czy zauważyłeś wielką litera `p` w `Print`? Funkcja `print` powinna być pisana tylko małymi literami.

### SyntaxError (Błąd Składni)
Zobaczysz ten komunikat, jeśli:

- kolejność symboli jest nieprawidłowa,
- zapomnisz o () lub " " (cudzysłowach).

&nbsp;

👉 Dostaniemy błąd, kiedy uruchomimy ten kod. Skopiuj ten kod do edytora kodu i kliknij `run`.

```python
print "Hello again"
```
Jak myślisz myślisz, co jest źle?
```  File "main.py", line 1
    print "Hello again"
          ^
SyntaxError: Missing parentheses in call to 'print'. Did you mean print("Hello again")?
```
Tak, zapomniałeś o `()`.

&nbsp;

👉 Co powoduje błąd tutaj? Skopiuj kod i kliknij "run", aby się przekonać.
```python
print(Please work)
```
```
  File "main.py", line 1
    print(Please work)
                 ^
SyntaxError: invalid syntax
```

Potrzebujesz `" "` (cudzysłowów).

&nbsp;

### Nabierzesz wprawy w debugowaniu tylko poprzez praktykę! Będziesz znajdować wiele błędów we własnym kodzie w miarę postępu, więc upewnij się, że ćwiczysz, podejmując się zadań "Popraw mój kod", kiedy tylko się pojawią!

### Teraz, co z tym zrobić?

# Wyświetlanie Zmiennej

Możesz wyświetlić swoją zmienną za pomocą komendy `print` oraz nazwy, którą użyłeś w swojej komendzie `input`. Pamiętasz trzy zmienne, które właśnie stworzyliśmy: `myName`, `myAge` i `codeCamp`?

W swoim kodzie możesz teraz wyświetlić 'imię' za pomocą `print(myName)` lub 'wiek' za pomocą `print(myAge)`.

![](resources/03-printing.png)

&nbsp;

👉 Spróbujmy tego! Dodaj ten kod na koniec tego, co masz, i kliknij `run`:

```python
print()
print("Więc masz na imię")
print(myName)
print("i masz imponujący wiek")
print(myAge)
print("i wyraźnie uważasz, że CodeCamp to")
print(codeCamp)
```
Czy zauważyłeś, co zrobiła komenda `print()`?
  - jeśli wewnątrz `()` znajduje się tekst, to ten tekst jest wypisywany,
  - jeśli wewnątrz `()` nie ma niczego, to dodawana jest pusta linia dla odrobiny przestrzeni.

### Ten kod **wygląda trochę dziwnie** na razie. Zaraz sprawimy, że będzie wyglądać lepiej.

# Powszechne Błędy

*Najpierw usuń wszelki inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij `run` i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij `run`, aż osiągniesz stan bezbłędny. Kliknij na `👀 Odpowiedź`, aby porównać swój kod z poprawnym kodem.*

## Błąd Składni
👉 Co jest nie tak w poniższym kodzie? Skopiuj tylko kod (bez komunikatu o błędzie) i kliknij `run`.
```python
my variable = input("KTO TAM? ")
print(my variable)
```

```
  File "main.py", line 1
    my variable = input("KTO TAM? ")
       ^
SyntaxError: invalid syntax
```

<details>

<summary> 👀 Odpowiedź</summary>
Czy zauważyłeś spację w nazwie zmiennej? Nigdy nie używamy spacji w nazwach zmiennych - to tylko wprowadza zamieszanie w biedny komputer!
</details>

## Błąd Nazwy
👉 Co jest nie tak w tym kodzie? Skopiuj tylko kod i kliknij `run`.
```python
myGrandma = input("Jak się ma Twoja Babcia? 😘 ")
print(mygrandma)
```

Did you get this error message? How can you fix it?
```
Jak się ma Twoja Babcia? 😘 fine
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    print(mygrandma)
NameError: name 'mygrandma' is not defined
```

<details>
  <summary> 👀 Odpowiedź</summary>

- To, co próbujemy wydrukować, *NIE JEST* takie samo jak to, co pierwotnie ustawiliśmy jako zmienną. Różnica polega na **wielkości liter**. `myGrandma` kontra `mygrandma`

- To jest również ważne, gdy próbujesz wydrukować zmienną, której jeszcze nie stworzyłeś. ZAWSZE musisz UTWORZYĆ zmienną PRZED jej wydrukowaniem.
</details>

## To jest po prostu dziwne...
Nie otrzymasz błędu z tego kodu, ale wynik nie będzie miał wiele sensu...

👉 Skopiuj ten kod i kliknij `run`, aby zobaczyć, co się stanie.
```python
myLunch = input("Co jesz na lunch? ")
print("Hmm, wygląda na to, że naprawdę powinieneś to po prostu zamówić")
print("myLunch")
print("najwcześniej jak to możliwe!")
```

```
Co jesz na lunch? Burrito
Hmm, wygląda na to, że naprawdę powinieneś to po prostu zamówić
myLunch
najwcześniej jak to możliwe!
```


<details> <summary> 👀 Odpowiedź</summary>
- Próbujesz wydrukować zmienną, ale dodałeś do tego cudzysłowy!
- Pamiętaj: cudzysłowy dosłownie wydrukują to, co wkleisz do nich.
- W tym przypadku jest wydrukowana nazwa zmiennej zamiast zawartości zmiennej.
-Jeśli chcesz wydrukować zawartość, TO NIE UŻYWASZ CUDZYSŁOWÓW.
</details>

# Popraw Mój Kod
👉 Spróbuj naprawić ten kod, który jest *pełen* błędów.

*Najpierw usuń wszelki inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij `run` i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij `run`, aż osiągniesz stan bezbłędny. Kliknij na `👀 Odpowiedź`, aby porównać swój kod z poprawnym kodem.*

**Proszę zwrócić uwagę: To jest przykład nieszkodliwy. Nigdy nie pisałbyś swojego własnego kodu phishingowego, ale ważne jest wiedzieć, na co zwracać uwagę. Jeśli ktoś prosi cię w internecie o tego rodzaju informacje - pomyśl dwa razy!**

```python
print("Zdecydowanie nie jest to phishingowy scam")
print()
myName = input("Twoje imię: ")
print("Dzięki za zalogowanie")
print(myName)
cardNumber = input("Jaki jest numer twojej karty kredytowej?")
print("Dzięki, z pewnością nie wpiszę")
print("cardNumber")
print("na Amazonie i nie zamówię niczego dziwnego")
print()
print("Obiecuję")
maidenName = input("Jak brzmi nazwisko panieńskie twojej matki? ")
print()
print("To spoko, chciałem tylko wiedzieć, że")
print(maidenName)
print("było nazwiskiem panieńskim twojej mamy. Nie dlatego, że bank o to prosił, oczywiście.")
```

<details><summary> 👀 Odpowiedź </summary>
  
```python
print("Zdecydowanie nie jest to phishingowy scam")
print()
myName = input("Twoje imię: ")
print("Dzięki za zalogowanie się")
print(myName)
cardNumber = input("Jaki jest numer twojej karty kredytowej?")
print("Dziękuję, na pewno nie wpiszę")
print(cardNumber)
print("na Amazonie i nie zamówię niczego dziwnego")
print()
print("Obiecuję")
maidenName = input("Jak brzmi nazwisko panieńskie twojej matki? ")
print()
print("To fajne, chciałem tylko wiedzieć, że")
print(maidenName)
print("było nazwiskiem panieńskim twojej Mamy. Nie dlatego, że bank tego zażądał, oczywiście.")
```
</details>

# Konkatenacja

## Tak, wielkie słowo.
W rzeczywistości oznacza to po prostu **łączenie** tekstu (pamiętaj, tekst to nazywany jest ciągiem znaków) oraz zmiennych w pojedyncze zdania! 😲🤯

Teraz możesz nadać swojemu wejściu i wyjściu piękny wygląd! 🥳

👉 Skopiuj poniższy kod do pliku `main.py` i uruchom go. Zobacz, co się stanie:

```python
myName = input("Jak masz na imię? ")
myLunch = input("Co będziesz jeść na lunch? ")
print(myName, "zaraz zajmie się", myLunch, "bardzo szybko!")
```

Utworzyłeś właśnie pełne zdanie, prawda? Ale jak to działało?

- Okazuje się, że `print` ma supermoc. 
  Możemy mu podać **tyle** różnych rzeczy do wydrukowania, ile chcemy.
  Wszystko, co musimy zrobić, to umieścić przecinek `,` między każdą różną rzeczą w nawiasach `()`.

![](resources/02-concat.png)

&nbsp;

# Instrukcje warunkowe (if)

Te instrukcje są trochę jak zadawanie pytania.
Mówisz komputerowi: **jeśli** coś jest prawdziwe, **to** wykonaj ten konkretny blok kodu.
Podwójny znak równości (`==`) oznacza, że pytamy komputer, czy te dwie rzeczy są ***dokładnie*** takie same.

&nbsp;

W poniższym kodzie pytam, czy zmienna `myName` jest taka sama jak napis `David`.

```python
myName = input("Jak masz na imię?: ")
if myName == "David":
```

## Ale to nic nie drukuje?

Aby stworzyć instrukcję `print` związaną z instrukcją warunkową (`if`), musisz przejść do następnej linii i zrobić wcięcie **raz** tak, aby wszystko to było częścią kodu, który wykonujemy.

👉 Skopiuj ten kod i zobacz, co się stanie.

```python
myName = input("Jak masz na imię?: ")
if myName == "David":
  print("Witaj kolego!")
```

## Co to jest else?

Jeśli warunek nie zostanie spełniony w instrukcji `if`, to chcemy, aby komputer wykonał zamiast tego część z instrukcją `else`.
Podobnie, jeśli warunek **zostanie** spełniony w instrukcji `if`, to część z instrukcją `else` jest pomijana przez komputer.
Instrukcja `else` musi być pierwszą rzeczą **bez wcięcia** po instrukcji `if` i w linii z nią.

👉 Skopiuj ten kod i spróbuj. Zwracaj uwagę na wcięcia!

```python
myName = input("Jak masz na imię?: ")
if myName == "David":
  print("Witaj kolego!")
  print("Jesteś najłysiejszym gościem, jakiego kiedykolwiek widziałem")
else:
  print("Kim do licha jesteś?!")
```

&nbsp;
&nbsp;

# Powszechne Błędy

*Najpierw usuń cały inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego okna z kodem. Następnie kliknij przycisk `run` i zobacz, jakie błędy się pojawią. Popraw błędy i ponownie kliknij przycisk `run`, aż otrzymasz kod bez błędów. Kliknij przycisk `👀 Answer`, aby porównać swój kod z poprawnym kodem.*

## Błąd składni
👉 Co jest nie tak z poniższym kodem?

```python
catsOrDogs = input("Jesteś osobą lubiącą koty? Czy osobą lubiącą psy?: ")
if catsOrDogs = "kot":
  print("Miau")
else:
  print("Hau")
```

<details><summary>Odpowiedź 👀</summary>

- Nasze zdanie `if` musi zawierać `==`, więc powinno być napisane:
- `if catsOrDogs == "kot":`
</details>

## Błąd składni...ponownie

👉 Co jest nie tak z poniższym kodem?

```python
catsOrDogs = input("Jesteś osobą lubiącą koty? Czy osobą lubiącą psy?: ")
if catsOrDogs == "kot"
  print("Miau")
else:
  print("Hau")
```

<details><summary>Odpowiedź 👀</summary>

- Nasze zdanie `if` jest pozbawione dwukropka `:`
</details>

## Błąd wcięcia

👉 Widzisz tutaj błąd?
```python
catsOrDogs = input("Jesteś osobą lubiącą koty? Czy osobą lubiącą psy?: ")
if catsOrDogs == "kot":
  print("Miau")
else:
print("Hau")
```

<details><summary>Odpowiedź 👀</summary>

- Jak tylko zobaczysz dwukropek, następna linia powinna być wcięta **o jedną** w porównaniu do linii powyżej.
</details>

# Fix My Code

👉 Spróbuj naprawić ten kod, który jest *pełen* błędów.

*Najpierw usuń inny kod ze swojego pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając na ikonę kopiowania w prawym górnym rogu każdego pola kodu. Następnie naciśnij `run` i zobacz, jakie błędy występują. Napraw błędy i naciśnij ponownie `run`, aż program będzie działać bez błędów. Kliknij na `👀 Answer`, aby porównać swój kod z prawidłowym kodem.*

```python
drink = input("Wolisz kawę czy herbatę?")
if drink = "kawa"
  print("Herbata jest lepsza.")
else:
  print("Doskonały wybór.")
```

<details> <summary> 👀 Odpowiedź  </summary>
  
```python
drink = input("Czy wolisz kawę czy herbatę?")
if drink == "kawa":
  print("Herbata jest lepsza.")
else:
  print("Doskonały wybór.")
```
</details>

# Czym jest elif?
- Polecenie `elif` (co oznacza 'inaczej mówiąc') pozwala na zadawanie 2, 3, 4 lub nawet 142 pytań przy użyciu tego samego wejścia! To polecenie musi być umieszczone w określonym miejscu. Możesz mieć dowolną ilość instrukcji `elif`, ale **muszą** znajdować się między poleceniem `if`, a `else`, oraz mieć taką samą wcięcie.
  Instrukcje `print` w poleceniu `elif` muszą być wyrównane wcięciem do pozostałych instrukcji `print`.

Gdzie umieścilibyśmy polecenie `elif` w poniższym kodzie?

```python
print("BEZPIECZNY LOGIN")
nazwaUzytkownika = input("Nazwa użytkownika > ")
if nazwaUzytkownika == "mark":
  print("Witaj Marku!")
else:
  print("Odejdź!")
```

<details> <summary> Odpowiedź 👀</summary>

- Instrukcja `elif` zostanie umieszczona pomiędzy instrukcją `if`, a instrukcją `else`.
</details>

&nbsp;

👉 Dodaj poniższą instrukcję `elif` do powyższego kodu. Upewnij się, że prawidłowo wcięto i umieściłeś ją **pomiędzy** instrukcją `if`, a instrukcją `else`!

```python
elif nazwaUzytkownika == "suzanne":
  print("Hejka Suzanne!")
```

&nbsp;

Twój kod powinien wyglądać tak:

<details> <summary> Odpowiedź 👀</summary>
  
```python
print("BEZPIECZNE LOGOWANIE")
nazwaUzytkownika = input("Nazwa użytkownika > ")

if nazwaUżytkownika == "mark":
  print("Witaj Marku!")
elif nazwaUzytkownika == "suzanne":
  print("Hej Suzanne!")
else:
  print("Odejdź!")
```
</details>

### Jak łatwe to było? Wkrótce staniesz się profesjonalistą!

# Dodaj hasło

### Dodajmy trochę więcej wprowadzania danych.

👉 Teraz, gdy mamy wprowadzanie danych zarówno dla nazwy użytkownika, jak i hasła, musimy nieco zmienić nasze instrukcje `if` i `elif`, aby zarówno nazwa użytkownika, jak i hasło musiały pasować, aby Mark i Suzanne mogli się zalogować.
```python
print("BEZPIECZNE LOGOWANIE")
nazwaUżytkownika = input("Nazwa użytkownika > ")
hasło = input("Hasło > ")
```

&nbsp;

👉 W poniższym kodzie zarówno nazwa użytkownika, jak i hasło muszą **obie** być poprawne, aby Mark mógł się zalogować.

 ```python
print("BEZPIECZNE LOGOWANIE")
nazwaUżytkownika = input("Nazwa użytkownika > ")
hasło = input("Hasło > ")

if nazwaUżytkownika == "mark" and hasło == "hasło":
  print("Witaj Marku!")
elif nazwaUżytkownika == "suzanne":
  print("Hej Suzanne!")
else:
  print("Odejdź stąd!")
```

&nbsp;

👉 Hasło Suzanne to 'Su74nne'. Czy możesz dodać je do powyższego kodu? (Wskazówka: Powinno to być *bardzo* podobne do dodawania hasła dla Marka.)

<details><summary> Odpowiedź 👀 </summary>
  
 ```python
print("BEZPIECZNE LOGOWANIE")
nazwaUżytkownika = input("Nazwa użytkownika > ")
hasło = input("Hasło > ")

if nazwaUżytkownika == "mark" and hasło == "hasło":
  print("Witaj Marku!")
elif nazwaUżytkownika == "suzanne" and hasło == "Su74nne":
  print("Hej Suzanne!")
else:
  print("Odejdź stąd!")```
```

</details>

👉 Hasło Suzanne to 'Su74nne'. Czy możesz dodać je do powyższego kodu? (Wskazówka: Powinno to być *bardzo* podobne do dodawania hasła dla Marka.)

<details><summary> Odpowiedź 👀 </summary>
  
 ```python
print("BEZPIECZNE LOGOWANIE")
nazwaUżytkownika = input("Nazwa użytkownika > ")
hasło = input("Hasło > ")

if nazwaUżytkownika == "mark" and hasło == "hasło":
  print("Witaj Marku!")
elif nazwaUżytkownika == "suzanne" and hasło == "Su74nne":
  print("Hej Suzanne!")
else:
  print("Odejdź stąd!")```
```

</details>

# Częste Błędy

*Na początek, usuń wszystkie inne fragmenty kodu z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie naciśnij przycisk `run` i sprawdź, jakie błędy się pojawią. Napraw błędy i naciśnij ponownie `run`, aż kod będzie działać bez błędów. Kliknij `👀 Answer`, aby porównać swój kod z poprawnym kodem.*

## Błąd składni

👉 Co jest nie tak z poniższym kodem?

```python
print("BEZPIECZNE LOGOWANIE")
nazwaUżytkownika = input("Nazwa użytkownika > ")

if nazwaUżytkownika == "mark":
  print("Witaj Marku!")
else:
  print("Odejdź stąd!")
elif nazwaUżytkownika == "suzanne":
  print("Hej Suzanne!")
```

<details>
<summary><strong>👀 Odpowiedź</strong></summary>

Instrukcja `elif` jest umieszczona w niewłaściwym miejscu. **Musisz** umieścić ją między instrukcją `if`, a instrukcją `else`.

```python
print("SECURE LOGIN")
nazwaUżytkownika = input("Nazwa użytkownika > ")

if nazwaUżytkownika == "mark":
  print("Witaj Marku!")
elif nazwaUżytkownika == "suzanne":
  print("Hej Suzanne!")
else:
  print("Odejdź stąd!")
```
</details>


### Brawo, coraz lepiej Ci idzie!

# Napraw mój kod

👉 Spróbuj naprawić ten kod, który jest *pełen* błędów.

*Najpierw usuń inny kod w pliku `main.py`. Skopiuj każdy fragment kodu poniżej do `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola kodu. Następnie kliknij `run` i sprawdź, jakie błędy występują. Napraw błędy i naciśnij `run` ponownie, aż nie będzie już błędów. Kliknij na `👀 Answer`, aby porównać swój kod z poprawnym kodem.*

```python
season = input(Jaki jest twój ulubiony sezon?)
if season = "wiosna"
print("Ah! Ptaki ćwierkają, a kwiaty kwitną.")
elif season == lato:
print("Schwytaj trochę słońca i orzeźw się lemoniadą.")
elif season == jesień
print("Liście zmieniają kolor, a powietrze jest chłodne. Ciesz się tym!)
elif season = zima:
print("Zagrzej się przy ognisku i obserwuj opadający śnieg.")
else:
print("Nie znam tego sezonu. Spróbuj ponownie.")
```

<details><summary>👀 Odpowiedź</summary>

```python
season = input("Jaki jest twoja ulubiona pora roku?")
if season == "wiosna":
  print("Ah! Ptaki ćwierkają, a kwiaty kwitną.")
elif season == "lato":
  print("Schwytaj trochę słońca i orzeźw się lemoniadą.")
elif season == "jesień":
  print("Liście zmieniają kolor, a powietrze jest chłodne. Ciesz się tym!")
elif season == "zima":
  print("Zagrzej się przy ognisku i obserwuj opadający śnieg.")
else: 
  print("Nie znam tej pory roku. Spróbuj ponownie.")
```
</details>

# Zagnieżdżanie
Zagnieżdżanie polega na umieszczeniu instrukcji `if` wewnątrz innej instrukcji `if`, wykorzystując potęgę wcięć. Druga instrukcja `if` wewnątrz pierwszej instrukcji `if` musi być wcięta, a jej instrukcja `print` musi być wcięta jeszcze raz.

Zwróć uwagę na pionowe linie (jak pokazano niebieskimi strzałkami na tym obrazie), aby upewnić się, że wcięcia są poprawnie dopasowane.

![Wcięcia](resources/indentation.png)

&nbsp;

👉 Zauważ drugą instrukcję `if` poniżej dotyczącą zmiennej `faveCharacter` i sposób, w jaki jest wcięta.

```python
tvShow = input("Jakie jest Twoje ulubione show TV? ")
if tvShow == "peppa pig":
  print("Och, dlaczego?")
  faveCharacter = input("Kto jest Twoim ulubionym bohaterem? ")
  if faveCharacter == "daddy pig":
    print("Prawidłowa odpowiedź")
  else:
    print("Nie, Tatusiek Świnka jest najlepszy")
elif tvShow == "paw patrol":
  print("Och, smutne czasy")
else:
  print("Tak, to jest fajne i tak…")
```
### Bardzo wątpliwe, że Twoje ulubione seriale to Peppa Pig i Psi Patrol. Skopiuj powyższy kod i zmień go, aby dopasować się do swoich ulubionych programów telewizyjnych i postaci.

# Typowe Błędy

*Na początek, usuń cały inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego bloku kodu. Następnie naciśnij przycisk `run` i zobacz, jakie błędy występują. Popraw błędy i naciśnij przycisk `run` ponownie, aż do momentu, gdy nie będzie już błędów. Kliknij na `👀 Answer`, aby porównać swój kod z poprawnym kodem.*
## Błąd składni

👉 Co jest nie tak z poniższym kodem?


```python
tvShow = input("Jakie jest Twoje ulubione show TV? ")
if tvShow == "peppa pig":
  print("Och, dlaczego?")
  faveCharacter = input("Kto jest Twoim ulubionym bohaterem? ")
  if faveCharacter == "daddy pig":
    print("Prawidłowa odpowiedź")
else:
  print("Nie, Tatusiek Świnka jest najlepszy")
elif tvShow == "paw patrol":
  print("Och, smutne czasy")
else:
  print("Tak, to jest fajne i tak…")
```

<details><summary> 👀 Odpowiedź  </summary>

```python
else:
  print("Nie, Tatusiek Świnka jest najlepszy")
```
nie jest odpowiednio wcięty.

- To polecenie else odnosi się do zmiennej faveCharacter, dlatego oba powyższe polecenia else i print muszą być wcięte o jeden poziom. Zaznacz je oba i kliknij klawisz 'tab' jeden raz.
</details>

# Napraw mój kod

👉 Spróbuj naprawić ten kod, który jest *pełen* błędów.

*Najpierw usuń inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij przycisk `run` i zobacz, jakie błędy występują. Popraw błędy i naciśnij ponownie przycisk `run`, aż nie będzie już żadnych błędów. Kliknij na `👀 Odpowiedź`, aby porównać swój kod z poprawnym kodem.*

```python
order = input(Co chciałbyś zamówić: pizzę czy hamburgera? ")
if order == "hamburger":
print("Dziękujemy.")
  cheese = input("Czy chcesz ser?")
  if cheese == "tak":
  print("Masz.")
else:
    print("Bez sera.")
elif order == "pizza":
    print("Zamówienie na pizzę w drodze.")
    toppings = input("Czy chcesz dodatek z pepperoni?")
    if toppings == "tak":
        print("Dodamy pepperoni.")
else:
  print("Twoja pizza nie będzie miała pepperoni.")
```

<details> <summary> 👀 Rozwiązanie </summary>

```python
order = input("Co chciałbyś zamówić: pizzę czy hamburgera? ")
if order == "hamburger":
  print("Dziękujemy.")
  cheese = input("Czy chcesz ser?")
  if cheese == "tak":
    print("Masz.")
  else: 
    print("Bez sera.")
elif order == "pizza":
  print("Zamówienie na pizzę w drodze.")
  toppings = input("Czy chcesz dodatek z pepperoni?")
  if toppings == "tak":
    print("Dodamy pepperoni.")
  else:
    print("Twoja pizza nie będzie miała pepperoni.")

```
</details>

# Rzutowanie

Instrukcje warunkowe `if` obsługują więcej niż tylko operator `==`. Wspierają również symbole nierówności. Pamiętasz te znaki <, > i = z matematyki? Wróciły, ale tym razem wyglądają trochę inaczej.

<details>
<summary> Symbole równości i nierówności </summary>

```python
# równość
5 == 5

# nierówność
3 != 5

# większe niż
5 > 3

# większe bądź równe
5 >= 3

# mniejsze niż
3 < 5

# mniejsze bądź równe
3 <= 5
```
</details>

# Rzutowanie (Casting)

To dlatego, że sposób działania funkcji `input` polega na tym, że zawsze zakłada, że to, co wpisujesz, to tekst (lub ciąg znaków) i jest przechowywane jako zmienna w `""`.

*Rzutowanie* to sposób na jasne powiedzenie komputerowi, że to, co wpisujemy, to liczba, a nie litera.

&nbsp;

Poniższy kod oznacza, że każdy wynik większy niż 100 000 to wygrana. W przeciwnym razie, spróbuj ponownie.

👉 Uruchom ten kod w pliku `main.py` i zobacz, co się dzieje:
```python
myScore = input("Twój wynik: ")
if myScore > 100000:
  print("Wygrana!")
else:
  print("Spróbuj ponownie 😭")
```

### Rozwaliliśmy to! Jak powiedzieć komputerowi, "Poczekaj, to jest liczba!"?

# Dodajmy `int`
- Istnieją dwa rodzaje liczb, które komputer rozpoznaje:
  - `int` liczba całkowita (np. 42)
  - `float` dowolna liczba z ułamkiem dziesiętnym (np. 1.81)

## int

Aby zmienić "Twój wynik" na liczbę, musimy dodać `int` przed funkcją `input` i umieścić całe wyrażenie `input` w nawiasach `()`.

```python
myScore = input("Twój wynik: ")
if myScore > 100000:
  print("Wygrana!")
else:
  print("Spróbuj ponownie 😭")
```

👉 Zaktualizuj swój kod, aby wyglądał tak:

```python
myScore = int(input("Twój wynik: "))
if myScore > 100000:
  print("Wygrana!")
else:
  print("Spróbuj ponownie 😭")
```

Czy tym razem zadziałało?

Komputer będzie czytał ten kod, zaczynając od tego, co znajduje się w nawiasach ("twój wynik"). Komputer myśli, że to jest tekst ze względu na `""`. Gdy dodamy `int`, mówimy komputerowi: "To nie jest tekst. Proszę zamień to na liczbę całkowitą." Teraz zmienna `myScore` przechowuje odpowiedź jako liczbę.

### Ale co z liczbami zmiennoprzecinkowymi (float)?

# Dodajmy liczbę zmiennoprzecinkową (float)

Zrobisz dokładnie to samo, tylko użyjesz `float` dla liczb dziesiętnych. W poniższym kodzie chcę znaleźć liczbę π do 3 miejsc dziesiętnych.

👉 Skopiuj ten kod i sprawdź, czy działa!

```python
myPi = float(input("Jakie jest π do 3 miejsc dziesiętnych? "))
if myPi == 3.142:
  print("Dokładnie!")
else:
  print("Spróbuj ponownie 😭")
```
Udało się!

Rzutujemy to wejście jako `float`, co oznacza, że oczekujemy liczby dziesiętnej. Kod nie zatrzyma się w przypadku, gdy wprowadzimy `.` i następnie cyfry po nim, aby oznaczyć liczbę dziesiętną.


# Częste Błędy

*Na początek usuń jakikolwiek inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij przycisk `run` i zobacz, jakie błędy występują. Popraw je i ponownie kliknij `run`, aż nie będzie żadnych błędów. Kliknij* `👀 Answer` *, aby porównać swój kod z poprawnym kodem.*
## Nieprawidłowa Składnia

👉 Jaki jest błąd?

```python
myPi = float(input("Podaj liczbę Pi do 3 miejsc po przecinku: ")
if myPi == 3.142 :
  print("Dokładnie!")
else:
  print("Spróbuj ponownie 😭")
```

<details><summary>👀 Odpowiedź </summary>

Zapomnieliśmy o drugim zamykającym nawiasie `)` na końcu naszego polecenia `input`.
Pamiętaj, że na każdej linii, na której występuje otwarty nawias, musi być także zamykający nawias.

</details>


### Dodatkowe wyzwanie
👉  Jaki jest błąd?

```python
myPi = float input("Podaj liczbę Pi do 3 miejsc po przecinku?")
if myPi == 3.142 :
  print("Dokładnie!)
else:
  print("Spróbuj ponownie 😭")
```

<details><summary>👀 Odpowiedź </summary>

Zapomnieliśmy o pierwszym otwierającym nawiasie `(` przed poleceniem `input`.
Pamiętaj, że przy rzutowaniu na typ float lub int musisz otoczyć to, co chcesz rzutować, nawiasami otwierającym i zamykającym.

Zapomnieliśmy także zakończyć podwójny cudzysłów `"` po `"Dokładnie!`

</details>

# Popraw mój kod

👉 Spróbuj naprawić ten kod, który jest *pełen* błędów.

*Najpierw usuń inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do `main.py`, klikając na ikonę kopiowania w prawym górnym rogu każdego pola kodu. Następnie kliknij przycisk `run` i zobacz, jakie błędy występują. Popraw błędy i ponownie kliknij przycisk `run`, aż nie pojawią się już błędy. Kliknij w odnośnik `👀 Answer`, aby porównać swój kod z poprawnym kodem.*

```python
score = input("Jaki był twój wynik na teście?"))
if score >= 80
  print("Nieźle")
elif score > "70":
  print("Akceptowalne.")
else:
print("Kolego, musisz się więcej uczyć!")
```

<details> <summary> 👀 Odpowiedź </summary>

```python
score = int(input("Jaki był twój wynik na teście? "))
if score >= 80:
  print("Nieźle.")
elif score >= 70:
  print("Akceptowalne.")
else:
  print("Kolego, musisz się więcej uczyć!")
```

</details>

# Trochę matematyki
Dotychczas zapoznaliśmy komputer z dwoma rodzajami liczb:
- `float`: liczby z przecinkiem
- `int`: liczby całkowite

👉 Skopiuj ten kod i spróbuj użyć różnych symboli matematycznych.

```python
dodawanie = 4 + 3
print(dodawanie)

odejmowanie = 8 - 9
print(odejmowanie)

mnożenie = 4 * 32
print(mnożenie)

dzielenie = 50 / 5
print(dzielenie)

# liczba podniesiona do potęgi
# w tym przykładzie podnosimy 5 do potęgi 2
kwadrat = 5**2
print(kwadrat)

# reszta z dzielenia
modulo = 15 % 4
print(modulo)

# dzielenie bez reszty
iloraz = 15 // 2
print(iloraz)
```

# Podzielmy rachunek

Czy dobrze się bawiłeś, bawiąc się tymi matematycznymi symbolami? Teraz wykorzystajmy je w dobry sposób.

Ty i twoi przyjaciele byliście na obiedzie i potrzebujecie podzielić rachunek. Będąc sprytnym przyjacielem, możesz użyć swojego kodu, aby dowiedzieć się, ile każda osoba winna. (Pamiętaj, że `myBill` to liczba zmiennoprzecinkowa (float), ponieważ łączny rachunek prawdopodobnie będzie miał przecinek, a `numberOfPeople` to liczba całkowita (int), ponieważ na obiad nie poszedłeś z 0,7 osoby.)

👉 Skopiuj ten kod i zobacz, co się stanie:

```python
myBill = float(input("Jaka była suma rachunku?: "))
numberOfPeople = int(input("Ilu było osób?: "))
answer = myBill / numberOfPeople
print("Wszyscy jesteście winni", answer)
```

# Zaokrąglanie

Czy otrzymałeś *naprawdę* dziwną liczbę z tak wieloma miejscami po przecinku?

&nbsp;

Możesz wziąć swoją odpowiedź i użyć funkcji `round`. Funkcja `round` ma dwie składowe: "Co chcę zaokrąglić?" i "Do ilu miejsc po przecinku chcę zaokrąglić?".

Dodaj ten fragment kodu po zmiennej `answer` i przed poleceniem `print`. To pokazuje, że zaokrąglasz wartość zmiennej `answer` do 2 miejsc po przecinku.

```python
answer = round(answer, 2)
```

# Wszystko o Pętlach

## Pętla `while`

Pętla `while` pozwala Twojemu kodowi powtarzać się na podstawie warunku, który ustawiasz.

Jest podobna do instrukcji warunkowej `if`, w której zadajesz pytanie, a dopóki odpowiedź jest prawdziwa, komputer będzie wielokrotnie wykonywał kod.

![](resources/while_loop.png)

W poniższym kodzie zmienna nazywa się `counter` i zaczyna się od zera. Pętla `while` ma warunek mówiący "dopóki zmienna counter jest mniejsza niż dziesięć, wykonuj to...".

W tym przypadku wypisz zmienną, a następnie dodaj `+=1` do tej zmiennej. Dopóki zmienna jest mniejsza niż 10, pętla będzie powtarzać kod.


```python
counter = 0
while counter < 10:
  print(counter)
  counter += 1
```

### 👉 Wypróbuj to!

# Nieskończona pętla

Musisz być **naprawdę** ostrożny, żeby przypadkowo nie stworzyć nieskończoną pętlę! To jest sytuacja, w której komputer będzie powtarzał kod aż do końca czasów. Bez przerwy. Na zawsze. 😭

## Naprawa nieskończonej pętli poprzez dodanie:

To po prostu oznacza "licz do 10, dodając 1 za każdym razem" aby pętla zakończyła działanie.

```python
  variable +=1
```

Nie zapomnij, że jeśli twój **warunek** to `>`, to być może będziesz musiał użyć `-=`. To odejmie od zmiennej, zamiast dodawać do niej.

# 👉 Wypróbuj to!

```python
counter = 10
while counter > 0:
  print(counter)
  counter -=1
```

Czy mógłbyś rozbudować ten kod, aby wyświetlał liczby do 100?

<details> <summary> 💡 Podpowiedź </summary>
Pomyśl o warunku w twojej pętli `while`.

</details>

# Częste Błędy

*Najpierw usuń cały inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola kodu. Następnie uruchom go i sprawdź, jakie błędy występują. Napraw błędy i uruchom ponownie, aż nie będzie już błędów. Kliknij na `👀 Answer`, aby porównać swój kod z kodem poprawnym.*

## Pętla Nieskończona

Uruchom ten kod. Co się dzieje?
```python
counter = 0
while counter < 10:
  print(counter)
```

<details>
<summary>👀 Odpowiedź</summary>

Widzisz ciąg nieskończonych zer, które drukują się w kółko. Dlaczego? Stworzyłeś nieskończoną pętlę, ponieważ warunek `counter` zawsze będzie mniejszy niż 10 w tym przypadku. Ręcznie zatrzymaj program i podaj `counter += 1`.


```python
counter = 0
while counter < 10:
  print(counter)
  counter += 1
```
</details>

## Nic się nie dzieje...
Uruchom ten kod. Co jest nie tak?

```python
counter = 0
while counter > 6:
  print(counter)
  counter += 1 
```

<details>
<summary>👀 Odpowiedź</summary>

Problemem jest warunek. Jest ustawiony w złej kolejności. Nierówność mówi, że gdy `counter` jest większy niż 6, dodaj jeden. Jednakże `counter` wynosi 0. Dlatego nie jest większy niż sześć na początek.

Napraw to poprzez poprawienie nierówności na `<`.

</details>

## Wyjście
Możesz również używać pętli `while` z tekstem. W poniższym kodzie warunek mówi "dopóki nie wpiszesz yes, komputer będzie wyświetlać 🥳."

Uruchom ten kod. Co widzisz?

```python
exit = ""
while exit != "yes":
  print("🥳")
exit = input("Exit?: ")
```

<details>
<summary>👀 Odpowiedź</summary>

Poczekaj! Bez względu na to, co wpiszesz, otrzymasz 🥳. Sprawdź wcięcia w kodzie. Zmień zmienną kontrolującą warunek *wewnątrz* samej pętli.


```python
exit = ""
while exit != "yes":
  print("🥳")
  exit = input("Exit?: ")
```

</details>

# Popraw mój kod
### 👉 Spróbuj naprawić ten kod, który jest pełen błędów.

Najpierw usuń inny kod w pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij "Uruchom" i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij "Uruchom", aż osiągniesz stan bezbłędny. Kliknij na 👀 "Odpowiedź", aby porównać swój kod z poprawnym kodem.

```python
counter = 0
while counter < 25:
  print(counter)
  ```

 <details> <summary> 👀 Odpowiedź </summary>

 ```python
counter = 0
while counter < 25:
  print(counter)
  counter +=1
  ```
  
</details>

```python
counter = 0
while counter >= 12:
  print(counter)
  counter += 1
```
<details> <summary> 👀 Odpowiedź</summary>

```python
counter = 0
while counter <= 12:
  print(counter)
  counter += 1
```

</details>

```python
exit = ""
while exit = "yes":
  print("🥳")
exit = input("Exit?: ")
```
<details> <summary> 👀 Odpowiedź </summary>

```python
exit = ""
while exit != "yes":
  print("🥳")
  exit = input("Exit?: ")
  ```

</details>

# Pętla while True

Przed chwilą nauczyliśmy się, jak tworzyć pętlę `while`. Jednak istnieje wiele elementów, które mogą zamienić pętlę `while` w przypadkową pętlę nieskończoną... i koszmar.

## Przedstawiam pętlę while True...

![](resources/while_true_02.png)

### 👉 Wypróbujmy to.
Co myślisz, że robi poniższy kod?

Pamiętaj, że możesz użyć dużego przycisku Stop na górze, jeśli twój program się nie kończy.

```python
while True:
  print("Ten program jest uruchomiony")
print("Och, bawiłem się dobrze 😭")
```

Ten rodzaj pętli ma tylko dwie wartości: `True` i `False`. *Zwróć uwagę na wielkie litery "T" i "F".*

<details> <summary> Ciekawostka </summary>
Pętla logiczna ma dwie wartości: Prawda (True) lub Fałsz (False). Zachwyc swoich znajomych i powiedz im, że wiesz, jak używać pętli logicznej.
</details>

W tej pętli mówię komputerowi:

"Dopóki Prawda jest Prawdą... wykonuj to raz po raz."

### Tak, stworzyliśmy pętlę nieskończoną, ale poczekaj...```

# Zatrzymaj to

Istnieje sposób, aby zatrzymać pętlę za pomocą słowa `break`. To wyjście z pętli i zatrzymuje wszelki kod w tym punkcie. Nawet jeśli po `break` jest napisany inny kod *wewnątrz* pętli.

Po `break` komputer opuszcza pętlę i przechodzi do następnego *nieodsuniętego* wcięcia wiersza kodu.

![](resources/while_true_01.png)

## 👉 Spróbuj tego

Uruchom poniższy kod i zauważ, jak pętla będzie działać, aż do momentu wystąpienia `break`. Następnie zostanie uruchomiona następna *nieodsunięta* linia kodu.

```python
while True:
  print("Ten program jest uruchomiony")
  goAgain = input("Uruchomić ponownie?: ")
  if goAgain == "nie":
    break
print("Ach, świetnie się bawiłem 😭")
```

# Częste błędy

Najpierw usuń inny kod w pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij "Uruchom" i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij "Uruchom", aż osiągniesz stan bezbłędny. Kliknij na 👀 "Odpowiedź", aby porównać swój kod z poprawnym kodem.

## Name Error (Błąd Nazwy)
👉 What is the error here?

```python
counter = 0
while true:
  answer = int(input("Wpisz liczbę: "))
  print("Dodaję ją!")
  counter += answer
  print("Aktualny wynik to", counter)
  addAnother = input("Dodać coś jeszcze? ")
  if addAnother == "nie":
    break
print("Papa!")
```

<details> <summary> 👀 Odpowiedź </summary>

`while true` powinno być zmienione na `while True`.

Zauważ, że gdy zmienisz małe "t" na wielkie "T", kolor słowa zmieni się, ponieważ CodeHS teraz rozpoznaje to jako pętlę logiczną.


</details>

## Błąd składni
👉 Co się dzieje w tym przypadku? Co się stanie, gdy klikniesz przycisk `run`?


```python
counter = 0
while True:
    answer = int(input("Wpisz liczbę: "))
  print("Dodaję ją!")
  counter += answer
  print("Aktualny wynik to", counter)
addAnother = input("Dodać coś jeszcze? ")
if addAnother == "nie":
  break
print("Papa!")
```

<details>
<summary>👀 Odpowiedź</summary>
Zauważ komunikat o błędzie, który mówi "break poza pętlą". Czy zauważasz, że ostatnie trzy linie przed dolnym poleceniem `print` *nie* są częścią pętli, ponieważ nie są poprawnie wcięte (zwróć uwagę na pionowe linie)?

Podświetl te trzy linie kodu i naciśnij klawisz `tab` raz, aby *wcięcie* kodu było *wewnątrz* pętli.
</details>

# Popraw mój kod
### 👉 Spróbuj naprawić ten kod, który jest pełen błędów.

Najpierw usuń inny kod w pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij "Uruchom" i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij "Uruchom", aż osiągniesz stan bezbłędny. Kliknij na 👀 "Odpowiedź", aby porównać swój kod z poprawnym kodem.

```python
while true:
  color = input("Wpisz kolor: ")
  if color = "red":
  break
  else:
    print("Cool color!")
print("Nie przepadam za czerwonym")

```

<details> <summary> 👀 Answer </summary>

```python
while True:
  color = input("Wpisz kolor: ")
  if color == "red":
    break
  else:
    print("Cool color!")
print("Nie przepadam za czerwonym")

```

- Wyraz 'true' powinien być napisany z wielkiej litery w pętli `while True`.
- W instrukcji warunkowej `if` brakuje operatora `==`.
- Istnieje błąd wcięcia przy użyciu `break`.

</details>

# Pętla `for`

Pętla `while` jest doskonała do użycia, gdy **nie wiemy**, ile razy chcemy, aby pętla się powtarzała.

Jeśli mamy jednak z góry określoną liczbę powtórzeń, możemy skorzystać z pętli `for`, aby wykonać kod w dokładnie ten sam sposób, w jaki robi to pętla `while`. 

Jednak w pętli `for` możemy jednocześnie zadeklarować zmienną, warunek kontrolny i inkrementację, wszystko w **JEDNYM** wierszu kodu.

![](resources/for_loop_01.png)

## Porównanie

Oto jak tworzyliśmy licznik przy użyciu pętli `while`:

```python
counter = 0
while counter < 10:
  print(counter)
  counter += 1
```

A tak możemy napisać to samo przy pomocy pętli `for`:

```python
for counter in range(10):
  print(counter)
```

# Zakres (Range)

Funkcja `range` tworzy listę liczb w zakresie, który określisz. Jeśli podasz tylko jedną liczbę, zacznie się od `0` i przesunie w kierunku końcowego stanu, w którym ostatnia liczba jest *o jeden mniejsza* niż liczba w nawiasach kwadratowych. W tym przypadku ostatnia liczba to `9`.

```python
range(10)
```

Uwaga: Zmienna istnieje tylko podczas wykonywania pętli, nie po jej zakończeniu.

<details> <summary> Ciekawostka </summary>
Programiści komputerowi często używają nazw zmiennych `i`, `j` i `k`, gdy korzystają z pętli `for` jako licznika. Nie ma na to naprawdę powodu. To po prostu taki sposób, w jaki zawsze to robiono. Jednak możesz śmiało użyć zmiennej, która ma nieco więcej sensu, jeśli chcesz.

</details>

# Częste Błędy

*Na początek, usuń wszystkie inne fragmenty kodu z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie naciśnij przycisk `run` i sprawdź, jakie błędy się pojawią. Napraw błędy i naciśnij ponownie `run`, aż kod będzie działać bez błędów. Kliknij `👀 Answer`, aby porównać swój kod z poprawnym kodem.*

## Błąd składni (Invalid Syntax)
👉 Ten program będzie dodawał wszystkie liczby od 0 do 99 i ciągle wypisywał sumę. Dlaczego nie działa?

```python
total = 0
for number in range 100:
  total += number
  print(total)
```

<details> <summary> 👀 Odpowiedź </summary> 

Zapomnieliśmy o nawiasach `()` przy funkcji `range`. Nawiasy są ważne, ponieważ `range` jest funkcją (tak jak funkcja wyjścia). To, co robi funkcja `range`, to tworzy listę liczb między 0 a liczbą, którą podajemy w nawiasach. Jeśli nie ma nawiasów `()`, to nie będzie działać.

```python
for number in range (100):
```

</details>

## Błąd nazwy (Name Error)
👉 W tym programie komputer powinien wypisywać dzień + liczby od 1 do 6. Dlaczego pokazuje, że 'day is not defined'?

```python
for days in range(7):
  print("Day", day)
```

<details> <summary> 👀 Odpowiedź </summary> 

Nazwa zmiennej jest nieprawidłowa wewnątrz kodu. Jeśli chcesz odnieść się do stworzonej zmiennej w pętli `for`, musisz pisać ją za każdym razem tak samo.

```python
  print("Day", days)
```

</details>

# Popraw mój kod
### 👉 Spróbuj naprawić ten kod, który jest pełen błędów.

Najpierw usuń inny kod w pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij "Uruchom" i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij "Uruchom", aż osiągniesz stan bezbłędny. Kliknij na 👀 "Odpowiedź", aby porównać swój kod z poprawnym kodem.

```python
total = 10
while counter in range 100:
  total += 10
  print("total")
```

<details> <summary> 👀 Odpowiedź </summary>

```python
total = 10
for counter in range(100):
  total += 10
  print(total)
  ```
</details>`

# Co naprawdę potrafi funkcja range?

Podaj funkcji range jedną liczbę, a ona policzy aż do tej liczby. Jednakże, funkcji range możesz tak naprawdę podać kilka opcji...
- **wartość początkowa:** z jaką liczbą chcesz rozpocząć?
- **wartość końcowa:** liczba *po* liczbie, na której chcesz zakończyć (przykład: jeśli wpiszesz 10 jako wartość końcową, komputer będzie liczyć do 9)
- **krok:** Ile ma się zwiększać za każdym razem, gdy pętla działa? (przykład: Chcesz liczyć co 1, co 5, czy co 10?)

![](resources/range.png)

**Wartość końcowa ma nieujawnione "mniejsze niż". Oznacza to, że komputer zatrzyma się o jedną liczbę wcześniej niż podana liczba końcowa w funkcji range.**

### Spróbujmy kilku przykładów.

# Wypróbujmy to

Pierwsza liczba w tym zakresie, 100, to wartość początkowa. Druga liczba w tym zakresie, 110, to wartość końcowa (Pamiętaj, aby zawsze podać liczbę końcową jako *jedną więcej* niż miejsce, w którym chcesz zakończyć).

👉 Jaką liczbę uruchomi kod jako pierwszą? Jaką liczbę otrzymamy na końcu? Uruchom kod i przekonaj się.

```python
for i in range(100, 110):
  print(i)

```

## 

👉 Co oczekujesz, że zostanie wydrukowane w przypadku poniższego zakresu? Uruchom i przekonaj się.

```python
for i in range(1, 7):
  print("Day", i)
```

Zauważyłeś, że licznik zatrzymał się przy 'Dzień 6'? Zmień wartość końcową, aby była *jedną więcej* niż ostatnia liczba, którą chcesz wyświetlić --- w tym przypadku 8, ponieważ chcemy wyświetlić *7* dni tygodnia.

```python
for i in range(1, 8):
  print("Day", i)
```

## 

👉 Co się dzieje, gdy uruchomisz ten kod?

```python
print("Thirteen Times Table")
for i in range(1, 13):
  print(i, "x 13 =", i * 13)
  ```
  

### Dodajmy teraz kroki do naszego zakresu.

# Kroki

Wiemy, że ten zakres zacznie się od 0 i będzie kontynuowany do 999 999 (co jest liczbą tuż *przed* wartością końcową). Liczba będzie zwiększana o 25 za każdym razem.

👉 Jakie liczby oczekujesz zobaczyć? Kliknij przycisk `run` i przekonaj się.

```python
for i in range (0, 1000000, 25):
  print(i)
  ```

## Liczenie wstecz

W tym przykładzie zaczynamy od 10 i liczymy wstecz do 0 (ponieważ 0 to to, co pojawia się tuż *przed* podaną wartością końcową), z krokiem wstecznym 1 za każdym razem.

👉 Co oczekujesz zobaczyć po kliknięciu przycisku `run`?

```python
for i in range(10, -1, -1):
  print(i)
```

# Częste Błędy

*Na początek, usuń wszystkie inne fragmenty kodu z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie naciśnij przycisk `run` i sprawdź, jakie błędy się pojawią. Napraw błędy i naciśnij ponownie `run`, aż kod będzie działać bez błędów. Kliknij `👀 Answer`, aby porównać swój kod z poprawnym kodem.*

```python
for i in range (10, 0):
  print(i)
```

<details> <summary> 👀 Odpowiedź</summary>
  
Trzecia wartość w funkcji `range`, czyli krok, jest pominięta. Musimy dodać krok -1, aby przejść wstecz. Bez podania kroku, komputer domyślnie dodaje +1.

Bez podanego kroku mówimy komputerowi: "zacznij od 10, idź aż do 0 i dodawaj po jednym za każdym razem". To niemożliwe do wykonania, więc nic się nie wykona, chyba że dodamy krok.

```python
for i in range (10, 0, -1):
```

</details>

# Popraw mój kod
### 👉 Spróbuj naprawić ten kod, który jest pełen błędów.

Najpierw usuń inny kod w pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij "Uruchom" i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij "Uruchom", aż osiągniesz stan bezbłędny. Kliknij na 👀 "Odpowiedź", aby porównać swój kod z poprawnym kodem.

```python
while i in range (20, 40, -1):
  print(i)
```

<details> <summary> 👀 Odpowiedź </summary>

```python
for i in range (20, 40, 1):
  print(i)
  ```

*Uwaga: Możesz zmienić krok na inną liczbę, jeśli chcesz, i liczyć co 2 lub 5, itp.*

</details>

# Biblioteki

Biblioteki to zbiory kodu, które napisali inni ludzie. Gry wideo często korzystają z ogromnych bibliotek (na przykład: [silniki gier](https://en.wikipedia.org/wiki/List_of_game_engines)), aby tworzyć epickie odbicia wody, grafikę 3D, itp.

Zaczniemy trochę mniejszym krokiem, generując po prostu losowe liczby. (W końcu [losowe liczby stanowią podstawę większości gier](https://www.gamedeveloper.com/programming/how-classic-games-make-smart-use-of-random-number-generation)).

## Biblioteka losowa

Możemy korzystać z biblioteki, pisząc `import`, a następnie nazwę biblioteki. 

*To zawsze powinno być jednym z pierwszych wierszy kodu.*

👉 Zaimportujmy bibliotekę, która będzie generować losowe liczby:

```python

import random
```

## Jak działa losowość
W poniższym kodzie stworzyłem zmienną 'myNumber'. Ustalam ją jako losową liczbę wygenerowaną przez bibliotekę `randint` (losowa liczba całkowita). Dodaję najniższą liczbę (1) i najwyższą liczbę (100), które mogą zostać wylosowane, a komputer wygeneruje losową liczbę.

```python
import random
myNumber = random.randint(1,100)
print(myNumber)
```

### 👉 Wypróbuj to!


# Co robić z bibliotekami?

W przeszłości musieliśmy ręcznie programować wartości, których szukali użytkownicy (pamiętasz grę zgadywania wyższej lub niższej...).

### Dzięki funkcji losowej możemy generować liczby, których nawet *my* nie znamy. (Brzmi podobnie do gier, co nie?)

# Częste błędy

*Najpierw usuń wszelki inny kod z pliku `main.py`. Skopiuj każdy fragment kodu poniżej do `main.py`, klikając na ikonę kopiowania w prawym górnym rogu każdego pola kodu. Następnie kliknij przycisk `run` i sprawdź, jakie błędy występują. Popraw błędy i naciśnij ponownie przycisk `run`, aż nie będzie żadnych błędów. Kliknij na przycisk `👀 Answer`, aby porównać swój kod z poprawnym kodem.*

## Błąd nazwy (Name Error)

👉 Dlaczego ten kod wyświetla błąd "name not defined?"

```python
import random

myNumber = randint(1, 100)
print(myNumber)
```

<details> <summary> 👀 Odpowiedź </summary>

Ten błąd występuje z powodu działania bibliotek. Nazwy funkcji i zmiennych w bibliotekach mogą być podobne do nazw, które wybrałem dla moich funkcji i zmiennych. Sposobem na dostęp do funkcji i zmiennych w innych bibliotekach jest dodanie `random.` przed nazwą biblioteki.

![](resources/random.002.png)

Teraz komputer wie, że ma "wejść do biblioteki `random`, znaleźć `randint` i podać mi liczbę między 1 a 100."

```python
import random

myNumber = random.randint(1, 100)
print(myNumber)
```
</details>

## Błąd z losowymi liczbami i pętlami

👉 W przypadku tego kodu chcę, aby zostało wydrukowanych 10 losowych liczb między 1 a 100. Dlaczego zamiast tego drukuje się ta sama liczba dziesięć razy, zamiast dziesięciu *różnych* losowych liczb?

```python
import random

myNumber = random.randint(1, 100)
for i in range(10):
  print(myNumber)

```

<details> <summary> 👀 Odpowiedź </summary>

Problem polega na tym, że generuję losową liczbę *przed* pętlą. Proszę o jedną losową liczbę i zapisuję ją w zmiennej. Następnie mówię, aby `print` wydrukował tę samą liczbę losową 10 razy. W żadnym miejscu w pętli nie proszę o nową liczbę *za każdym* razem. Muszę zmienić kolejność mojego kodu.

```python
import random

for i in range(10):
  myNumber = random.randint(1, 100)
  print(myNumber)

```

Teraz, za każdym razem, gdy pętla się resetuje, będzie generowana nowa losowa liczba. Teraz mogę wygenerować 10 losowych liczb między 1 a 100.
</details>


# Popraw mój kod
### 👉 Spróbuj naprawić ten kod, który jest pełen błędów.

Najpierw usuń inny kod w pliku `main.py`. Skopiuj każdy fragment kodu poniżej do pliku `main.py`, klikając ikonę kopiowania w prawym górnym rogu każdego pola z kodem. Następnie kliknij "Uruchom" i zobacz, jakie błędy występują. Napraw błędy i ponownie kliknij "Uruchom", aż osiągniesz stan bezbłędny. Kliknij na 👀 "Odpowiedź", aby porównać swój kod z poprawnym kodem.

```python
importrandom

myNumber = .randint(1, 10)
for i in range(10):
  print(myNumber)
```

<details> <summary> 👀 Odpowiedź </summary>

```python
import random

for i in range(10):
  myNumber = random.randint(1, 100)
  print(myNumber)
```

</details>

# Tablice

Tablice pozwalają nam na sprawne zarządzanie wieloma jak nie tysiącoma zmiennymi posługując się indeksami (numerkami zmiennych), bardzo pomocne są przy tym pętle, które występowały we wcześniejszych przykładach. Elementy tablicy są **numerowane od 0** . 
 
 ## Listy
 Listy — nie są tablicami, ale działają podobnie i są bardziej elastyczne:
 Mogą przechowywać różne typy danych oraz dynamicznie zmieniają rozmiar.
 
 Definiujemy je następująco:
 ```
  listaZakupow = []
```
 Właśnie stworzyliśmy pustą listę, czas ją wypełnić za pomocą polecenia .append()
 ```
  listaZakupów.append("ser")
  listaZakupów.append("bulki")
  listaZakupów.append("mleko")
 ```
Zobaczmy teraz jak wygląda nasza lista:
```
print(listaZakupow)
```
👉 Oto co otrzymujemy:

```
['ser','bulki','mleko']
```
Listy mogą przechowywać różne typy danych, możemy je mieszać w obrębie jednej listy. Stwórzmy teraz listę zawierającą zarówno string, jak i int:
```
mojaLista = ["kot", "pies", 44, "malpa", 7]
```
I spróbujmy wyświetlić jej element:
```
print(mojaLista[2])
```
Jak myślisz, co otrzymamy?
<details> <summary> 👀 Odpowiedź </summary>
44
*Pamiętaj: Elementy tablicy są numerowane od 0, także gdy prosimy o element o indeksie 2, chodzi nam o 3 element w kolejności!*
</details>

Po elementach listy możemy również iterować z użyciem pętli for
```
zakupy = ["chleb", "mleko", "jajka", "masło", "ser"]

print("Idę do sklepu. Muszę kupić:")
for produkt in zakupy:
    print("-" + produkt)
```
👉 Oto co otrzymujemy:
```
Idę do sklepu. Muszę kupić:
- chleb
- mleko
- jajka
- masło
- ser
```

## Słowniki 

Słownik jest strukturą danych podobną do list z tą różnicą, że słowniki nie pracują w oparciu o indeksy, ale w oparciu o parę: klucz – wartość.

Tworzenie słownika polega na tworzeniu par klucz-wartość za pomocą klamer i dwukropka:
```
slownik = {'klucz1': 'wartosc1', 'klucz2': 'wartosc2'}
```
Słowniki mają tę zaletę, że ich wartości mogą zawierać dowolny typ danych (np. napisy, liczby, listy etc.). Z kluczami jest już inaczej, bo muszą być one zestawami tego samego typu elementów, np. napisy, liczby etc. 

👉 Stwórzmy więc pierwszy słownik:
```
oceny = {
    'matematyka': 5,
    'biologia': 4,
    'historia': 3,
    'angielski': 6
}
```
Jak odwołamy się do elementu naszego słownika?
Za pomocą klucza!
```
ocena_matematyka = oceny['matematyka']
```
Dodajmy teraz nowy element do słownika - wystarczy, że podamy nową parę klucz wartość istniejącemu słownikowi
```
oceny['chemia'] = 1
```
Jak wygląda teraz nasz słownik? Do sprawdzenia użyjmy dobrze znanego print.
👉 print(oceny)
```
{'matematyka': 5, 'biologia': 4, 'historia': 3, 'angielski': 6, 'chemia': 1}
```

Sprawdźmy też, że do słownika możemy dodać nie tylko wartość int, jak było to do tej pory. Spróbujmy z listą:
```
oceny['polski']=[1,2,3]
```
👉 print(oceny)
```
{'matematyka': 5, 'biologia': 4, 'historia': 3, 'angielski': 6, 'chemia': 1, 'polski': [1, 2, 3]}
```

# Funkcje
## Czym są funkcje?
Funkcja to wydzielony fragment kodu, który można wielokrotnie używać w różnych miejscach programu. Tak się składa, że już wykorzystywaliśmy funkcje, a jedną z nich była funkcja xrange. Nie trzeba było jej pisać samodzielnie, bo zrobił to już za ciebie inny programista. Wystarczyło, że wiesz jak ona działa. Bez funkcji praca zespołowa nad nawet średnim programem byłaby prawie niemożliwa. Większość funkcji wymaga informacji z zewnątrz. Są to liczby, tekst i inne obiekty. Większość zwraca również informacje.

Jak napisać funkcję w Pythonie?
W Pythonie bloki kodu (w tym również funkcje) są wyróżniane za pomocą wcięć w następujący sposób: naglowek_kodu:

```python
naglowek_bloku: 
    1. linia bloku 
    2. linia bloku 
    ...
```
Najczęściej nagłówek bloku ma następującą budowę

`slowo_koluczowe_bloku nazwa_bloku(argument1, argument2, ...)`
Słowami kluczowymi, które już znasz są if, for i while, ale one nie wymagały nazwy.

Funkcje są definiowane z użyciem słowa kluczowego def, po którym umieszcza się nazwę funkcji, a potem nawiasy. Jeżeli funkcja nie wymaga informacji z zewnątrz nawiasy pozostawiamy puste.

```python
def przywitanie():
    print "Pozdrowienia z mojej funkcji!"

def przywitanie_imienne(imie, zyczenia):
    print "Witaj" + imie + ". Zycze Tobie " + zyczenia

przywitanie() # Wypisze "Pozdrowienia z mojej funckji!"
przywitanie_imienne("Jacek", "zdrowia") # Wypisze immienne zyczenia
```

Aby przerwać działanie funkcji i zwrócić wartość, musisz użyć słowa return, a za nim umieścić zwracaną wartość. Jeżeli pominiesz wartość, to funkcja tylko zakończy swoje działanie i nic nie zwróci. Przykład:

```python
def dzielenie(dzielna, dzielnik):
    if(dzielnik == 0):
        return # zakoncz funkcje nic nie zwracajac
    else:
        return dzielna / dzielnik

print dzielenie(5, 0)
print "#########################"
print dzielenie(10, 2)
```
