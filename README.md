# Testowanie systemów wbudowanych

Celem przedmiotu jest przygotowanie studentów do projektowania oraz
implementacji scenariuszy testowych dla systemów wbudowanych ze
szczególnym zaakcentowaniem podejścia *Internet of Things*
(*IoT*, Internet przedmiotów/rzeczy; http://www.intel.com/content/www/us/en/internet-of-things/overview.html).

Studenci, w ramach wykładów oraz zajęć laboratoryjnych prowadzonych
przez pracowników UG oraz doświadczonych inżynierów firmy Intel, będą
mieli okazję w praktyczny sposób nauczyć się procesu tworzenia
scenariuszy testowych, ich implementacji, automatyzacji oraz
raportowania wyników dla systemów wbudowanych. Ćwiczenia praktyczne
zaznajomią dodatkowo uczestników z procesem debugowania, poprawiania
błędów w oprogramowaniu oraz integracją wprowadzonych poprawek z kodem
głównyqm.

Proponowany przedmiot stanowi uzupełnienie wiedzy zdobytej przez
studentów informatyki w ramach innych przedmiotów podczas
studiów. Osoby, które ukończą ten przedmiot będą posiadały wiedzę i
umiejętności pozwalające na podjęcie stażu/pracy w firmie Intel na
stanowisku Software Validation Test Engineer.

**Wymagania:**

1. Język angielski na poziomie umożliwiającym czytanie dokumentacji technicznej.
2. Podstawy programowania w C.
3. Podstawy obsługi systemów Windows/Linux.


## Wykłady

1.  Co to są systemy wbudowane.
2.  Architektury systemów wbudowanych.
3.  Cykl rozwoju systemu wbudowanego.
4.  Technologia *Agile* dla systemów wbudowanych.
5.  Specyfikacja wymagań.
6.  Scenariusze testowe.
7.  Metryki jakości oprogramowania.
8.  Przygotowywanie dokumentacji.
9.  Tworzenie testów.
10. Automatyzacja procesu testowego.
11. Bezpieczeństwo w systemach wbudowanych.
12. Wprowadzanie zmian.


## Laboratoria

1. Intel Galileo Workshop.
2. Opracowywanie przypadków testowych.
  - Zapoznanie się z dokumentacją dostarczonego projektu.
  - Specyfikacja wymagań na podstawie dokumentacji technicznej.
  - Przygotowanie scenariuszy testowych
  - Przygotowanie środowiska i uruchomienie projektu na podstawie
    dostarczonej dokumentacji (brak dostępu do kodu).
3. Implementacja środowiska testowego.
  - Przygotowanie środowiska testowego.
  - Napisanie prostych testów pokrywających wymagania (implementacja
    specyfikacji testowej).
  - Dodanie testów do repozytorium z kodem.
  - Uruchamianie testów.
  - Analiza wyników testów.
  - Raportowanie defektów do bazy danych.
4. Automatyzacja testów.
  - Przygotowanie skryptów automatyzujących testowanie.
  - Automatyzacja analizy wyników testowych.
  - Dodawanie testów do repozytorium z kodem.
5. Raportowanie i ocena wyników testów.
  - Raportowanie znalezionych błędów do bazy *BugZilla*.
  - Metryki jakości oprogramowania.
  - Metryki pokrycia scenariuszy testowych.
  - Priorytetyzacja znalezionych problemów z punktu widzenia klienta.
  - Warunkiem wypuszczenia produktu (testowanego systemu) na rynek jest
    spełnienie kryteriów jakościowych. Grupa powinna
    zaproponować plan w jaki sposób je osiągnąć (np. jakie defekty
    usunąć). Plan będzie realizowany w czasie kolejnych laboratoriów.
6. Statyczna analiza kodu.
  - Statyczna analiza kodu testowanego projektu.
  - Analiza fragmentów związanych z obszarami w których znaleziono problemy.
7. Debugowanie i usuwanie defektów.
  - Bugscrub – analiza defektów zgłoszonych przez wszystkie zespoły.
    W czasie bugscrub’a identyfikujemy duplikaty defektów i rozdzielamy
    je na poszczególne grupy.
  - Reprodukcja znalezionych problemów na podstawie opisu z Bugzilla.
  - Debugowanie problemów.
  - Usuwanie znalezionych problemów.
  - Scalanie (*merging*) zmian wykonanych w kodzie do jednego repozytorium
    (integracja wprowadzonych zmian).
8. Zarządzanie zmianami w kodzie (*change management*) – dodawanie nowej funkcjonalności.
  - Wprowadzenie wymagań na nową funkcjonalność.
  - Określenie nowych przypadków testowych.
  - Dodane nowych testów.
  - Funkcjonalność wprowadzana w oparciu o *Agile* powinna być
    zaimplementowana w jakości produkcyjnej. Odbiór przez *Product Ownera*.
  - Implementacja
9. Testowanie regresji (laboratorium zdalne).
  - Automatyczne testy regresji (laboratorium 3).
  - Testowanie nowej funkcjonalności (laboratorium 7).
  - Tworzenie prostych *Release Notes*.
