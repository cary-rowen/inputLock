# Input Lock #

* Autor: Jose Manuel Delicado
* NVDA compatibility: 2021.3 and beyond
* Pobierz [wersja stabilna][1]

## Opis

Masz w domu zwierzęta lub małe dzieci? Czy Twój kot uwielbia wspinać się na
Twoje biurko i spacerować po klawiaturze komputera? Czy korzystając z
laptopa, zdarza Ci się przesuwać kursor myszy w przypadkowe miejsca na
ekranie? Jeśli tak, to Input Lock jest właśnie dla Ciebie! Teraz możesz
pozostawić włączony komputer bez żadnego ryzyka.

Za pomocą tego dodatku możesz zablokować klawiaturę, ekran dotykowy (jeśli
Twój laptop taki posiada), mysz i monitor brajlowski.

## Jak używać

Input Lock dodaje do NVDA dwa nowe polecenia. Domyślnie są one
nieprzypisane, więc trzeba je skonfigurować w oknie dialogowym Zdarzenia
wejścia. Więcej informacji znajdziesz w Podręczniku Użytkownika NVDA.

Kiedy naciśniesz polecenie ustawione dla Przełączania urządzeń wejścia, NVDA
powie"Urządzenia wejścia zablokowane". Urządzenia wejścia będą zablokowane,
aż do ponownego naciśnięcia tego samego polecenia. NVDA powie wtedy
"Urządzenia wejścia odblokowane" i wszystko zacznie działać tak jak zawsze.

Kiedy naciśniesz polecenie ustawione dla przełączania blokady myszy, mysz
zostanie zablokowana. Aby ją odblokować, naciśnij ponownie to samo
polecenie. Przy włączonej blokadzie myszy nadal można używać poleceń NVDA
służących do przemieszczania myszy i klikania lewym i prawym
przyciskiem. Nie da się jednak używać samej myszy. Kliknięcia myszy można
też wyłączyć w kategorii ustawień Input Lock w menu ustawień NVDA (NVDA
2018.2 i nowsze) lub w dialogu ustawień dodatków, który znajduje się w menu
Ustawienia, w starszych wersjach NVDA. Dodatkowo, w tych ustawieniach możesz
określić, czy mysz ma być automatycznie blokowana po starcie NVDa, czy nie.

Uwaga! Jeśli kliknięcia myszy są zablokowane, polecenia NVDA dotyczące myszy
również nie działają.

## Limitations and known problems

Input Lock has the following known problems:

* The shortcuts control+alt+del and windows+l can be used even when the
  keyboard is locked.
* On some laptops, the touchpad still accepts user input after mouse is
  blocked.

## Lista zmian

### Version 1.10

* Updated compatibility flags for recent NVDA versions.
* Updated translations.
* Updated documentation.
* Now, minimum supported version is 2021.3.
* The input will remain blocked after waking up from standby mode. Thanks to
  Javi Dominguez.

### Version 1.9

* Updated compatibility flags for recent NVDA versions.
* Updated translations.
* Updated documentation.

### Version 1.8

* Updated compatibility flags for recent NVDA versions.
* Updated translations.

### Version 1.7

* Updated compatibility flags for recent NVDA versions.
* Updated translations.

### Version 1.6

* Now, settings are removed only when the add-on is
  uninstalled. Configuration is nolonger reset when upgrading.
* New and updated translations.

### Wersja 1.5

* Dodana zgodność z ostatnimi wersjami NVDA.
* Nowe tłumaczenia.

### Wersja 1.4

* Polecenia dodatku są domyślnie nieprzypisane.

### Wersja 1.3

* Dodano panel ustawień w oknie dialogowym ustawień NVDA, jak również
  element menu i okno dialogowe dla starszych wersji NVDA.
* Dodano możliwość blokowania myszy przy starcie NVDA.
* Dodano możliwość blokowania kliknięć myszy, kiedy sama mysz jest już
  zablokowana.
* Naprawiono pewne niewielkie błędy. Poprawiono optymalizację kodu
  źródłowego oraz usunięto zdublowane fragmenty tłumaczenia.

### Wersja 1.2

* Od teraz zablokować można również mysz.
* Nowe polecenie służące do blokowania i odblokowywania wyłącznie myszy.

### Wersja 1.1

* Jeżeli inny dodatek już wcześniej dodał funkcję przechwytywania do
  menedżera urządzeń wejścia, zostanie ona wznowiona gdy urządzenia wejścia
  zostaną odblokowane.

### Wersja 1.0

* Wersja pierwotna

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=inputlock
