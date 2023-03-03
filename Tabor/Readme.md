# Zasady i porady dotyczące taboru

Tworząc nową jednostkę taboru można wybrać jeden z dwóch rodzajów prezentacji formularzy: uproszczony (standardowy) i pełny.

![Tryb uproszczony](./Misc/short_create_tabor.png)

![Tryb pełny](./Misc/long_create_tabor.png)

Podczas dodawania zdjęcia korzystanie z pełnego formularza do tworzenia jest mile widziane, ale nie wymagane.
Oficjalne, dodawanie szczegółów do bazy danych jest zadaniem redaktorów. Jedynym problemem jest ich ograniczona liczba i czas.

## Model

Przy wyborze modelu wyposażenia prosimy o zwrócenie uwagi na to, którą pozycję wybieramy z listy, ponieważ czasami nazwy rodzin modeli pokrywają się z nazwami samych modeli.

![Wybor modelu](./Misc/choose_model.png)

Nazwy rodziny modeli należy używać tylko wtedy, gdy nie znasz dokładnej modyfikacji lub gdy ta modyfikacja nie istnieje w bazie danych.

## Zajezdnia

*Zobacz także: [Przedsiębiorstwa](../Przedsi%C4%99biorstwa/Readme.md)*

W przeciwieństwie do Phototransu, nasze pojazdy są przypisane do działającej bazy, a nie do prawnego właściciela.

Weźmy jako przykład firmę Irex/Meteor, która posiada oddziały w całej Polsce. Jeśli autobus został sfotografowany na terenie Lublina, to znaczy, że autobus tworzymy w Lublinie, czyli lubelskim oddziale firmy Irex/Meteor, ponieważ autobus jest przechowywany i serwisowany przez zajezdnię w tym mieście (i nie jeździ co dzień do Świętochlowic iz powrotem😅).

Związanie ze spółką matką następuje, gdy:
- firma posiada jedną zajezdnie (nie dotyczy firm zarejestrowanych w innym miejscu niż zajezdnia)
- nie wiesz na pewno, do której zajezdni należy ten pojazd (w większości przypadków ma to znaczenie, gdy w tym samym mieście jest kilka zajezdni jednego przedsiębiorstwa).

Nie wskazujemy w ewidencji pośrednich właścicieli tymczasowych (sprzedawcy, instytucje finansowe, bazy złomu).

### Przekazania między oddiałamy











## Numer fabryczny i VIN

### Numer fabryczny

#### MAN

W przypadku MANów numer fabryczny jest osbnym znaczeniem które można zobaczyć na tablice fabrycznej lub znaleźć w specjalnym programie (na przykład MANtis). Na stronie internetowej podajemy numer fabryczny bez numeru modelu (262 zamiast 19C0262)

#### Mercedes

W większości przypadków numer fabryczny jest częścią kodu win, a mianowicie jego ostatnich 6 cyfr.

#### Solaris

Informacje o rozkodowaniu VIN można znaleźć na [stronie](https://autobus-vin.fandom.com/pl/wiki/Solaris)

#### Tramwaje

Tramwaje w większości przypadków mają tylko numery fabryczne (pomimo tego, że np. na Phototrans są wpisane w pole VIN). Wyjątkiem może być na przykład Pesa.

### Fabryki i VIN dekoding

#### Volkswagen AG

Kod WMI - WV1

Miejsca montażu są oznaczone 11. znakiem kodu VIN 

WV1________?______

- 6 - Mercedes-Benz Werk Düsseldorf
- 7 - Mercedes-Benz Ludwigsfelde GmbH
- 9 - Zakład Crafter Września

#### NEOPLAN Bus GmbH

Kod WMI - WAG

Miejsca montażu są oznaczone 11. znakiem kodu VIN

WAG_______?______

- S - NEOPLAN Bus GmbH, Stuttgart (do 2003 r.)
- P - NEOPLAN Bus GmbH, Pilsting (do 2003 r.)
- B - NEOPLAN Bus GmbH, Berlin (do 2003 r.)
- N - NEOPLAN Bus GmbH, Plauen (do 2003 r.)
- 3 - NEOPLAN Bus GmbH, Stuttgart (od 2003)
- 4 - NEOPLAN Bus GmbH, Pilsting (od 2003)
- 5 - NEOPLAN Bus GmbH, Plauen (od 2003)
- 6 - Tovarna Vozil Maribor (od 2003)
- B, C, G, H, J, S - MAN Truck & Bus Standort Salzgitter
- R - MAN Bus Sp. z o.o.
- T - MAN Türkiye A.Ş.

#### MAN Truck & Bus SE

Kod WMI - WMA

Miejsca montażu są oznaczone 11. znakiem kodu VIN

WMA_______?______

- B, C, G, H, J, S - MAN Truck & Bus Standort Salzgitter
- F, R - MAN Bus Sp. z o.o.
- T - MAN Türkiye A.Ş.
- 3 - NEOPLAN Bus GmbH, Stuttgart
- 4 - NEOPLAN Bus GmbH, Pilsting
- 5 - NEOPLAN Bus GmbH, Plauen

Dodatkowa informacja na [stronie](http://buspilotin.com/index.php/man/man-vin)

#### Mercedes

##### EvoBus GmbH

Kod WMI - WEB
W przypadku Citaro i Conecto miejsce montażu można określić na podstawie 11. i 12. znaku kodu VIN

WEB_______??_____

- 30xxxxxx - EvoBus GmbH
- 31xxxxxx - EvoBus GmbH
- 32xxxxxx - Mercedes-Benz Türk A.Ş.
- 06xxxxxx - EvoBus France S.A.S.U
- 37xxxxx - EvoBus GmbH

##### Mercedes-Benz Group AG

Kod WMI - WDB

Miejsca montażu są oznaczone 11. znakiem kodu VIN 

WDB________?______

- 5, P, R, S - Mercedes-Benz Werk Düsseldorf
- 9, N - Mercedes-Benz Ludwigsfelde GmbH

#### IVECO France / Irisbus:

Kod WMI - VNE

Miejsca montażu są oznaczone 11. znakiem kodu VIN 

VNE________?______

- 0 - IVECO France SAS
- M - Iveco Czech Republic, a. S.

#### Solaris

Informacje o rozkodowaniu VIN można znaleźć na [stronie](https://autobus-vin.fandom.com/pl/wiki/Solaris)

### Podwozie i nadwozie

Określenie tych parametrów jest charakterystyczne np. dla:
- Skandynawskie podwozia i autobusy
- autobusy na podwoziach samochodów dostawczych (Sprinter, Crafter, TGE) oraz ciężarowych
- inne indywidualne przypadki, w których numer podwozia/nadwozia jest wskazany oddzielnie

## Daty "Od" i "Do"

Dla każdej daty wybieramy najdokładniejszą, zaczynając od pełnej daty (dzień/miesiąc/rok) i przeglądając poniższe listy od góry do dołu. Jeśli nie ma dokładnej daty - wykonujemy ten sam zabieg, ale bez dnia (tylko miesiąc/rok). Jeśli nie ma - to samo, tylko z samym rokiem.

### Od

Tutaj wpisujemy datę:
- przeniesienie transportu do przedsiębiorstwa (poprzez odpowiednie zlecenie/akt przyjęcia-przekazania), lub w przypadku braku:
- rejestracji państwowej, lub:
- oddania do eksploatacji (odpowiedni dokument), albo:
- pierwszego pojawienia się na trasach

### Do

Tutaj wpisujemy datę:
- wykreślenie transportu z przedsiębiorstwa (odpowiednim aktem), lub w przypadku braku:
- wykreślenia z rejestracji państwowej lub:
- wywieźenia pojazdu z terenu firmy na złom, lub:
- jego faktycznego złomowania na złomowisku, lub
- ostatniego pojawienia się na linii

## Status pojazdu

- Nowy - transport jest nowy i nigdy nie był używany przez żadne przedsiębiorstwo (zwykle dotyczy nowego sprzętu, który nie był jeszcze na linii)

- Nieużywany w tym przedsiębiorstwie – używany pojazd, który został przeniesiony z innego działu/przedsiębiorstwa i który jeszcze nie był eksploatowany w tym przedsiębiorstwie

- Nie eksploatowany – transport, który aktualnie nie jest używany, najczęściej z powodu awarii

- Wycofany z eksploatacji - jednostka transportowa, która nie będzie już (jej wykorzystanie nie jest planowane) w eksploatacji w tym przedsiębiorstwie

- Skasowany - jeśli historia pojazdu zakończyła się obecnie w tym przedsiębiorstwie lub jeśli został zezłomowany

- Zniknął - kiedy wiemy na pewno, że zniknął (nieważne jak dziwnie to brzmi😅)

- Modernizacja/zmiana modelu (**WAŻNE!!!** - czytaj: [Modernizacje i profile pojazdów](#modernizacje-i-profile-pojazdów))

- Zmiana miasta lub przedsiębiorstwa - w przypadku przeniesienia pojazdu do innej firmy (ze zmianą miasta lub bez)

- Przekazany w ramach przedsiębiorstwa - transfer z jednej zajezdni (oddziału) do drugiej

- Zmiana danych w ramach oddziału – np. zmiana numeracji w ramach zajezdni, czy zmiana przeznaczenia pojazdu (np. przeróbka na służbowy lub historyczny)

- Nie wiadomo – gdy nie mogłeś znaleźć w Internecie informacji o aktualnym stanie transportu (np. jeśli zdjęcie zostało zrobione w innym kraju o jakim istnieje bardzo niewiele zasobów i źródeł informacji)

### Ceł













## Modernizacje i profile pojazdów
