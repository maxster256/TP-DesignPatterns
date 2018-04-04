# TP-DesignPatterns

List where we've had to implement various design patterns in projects that have already been started.

## Wzorce projektowe
Aby wykonac ́ poniz ̇sze zadania powinienes ́ zaimportowac ́ szkoleniowe projekty J. Pereiry. Dotychczas były one doste ̨pne na repozytorium SVN w serwisie Google Code, który jakis ́ czas temu został wygaszony. Do powyz ̇szego repozytorium SVN odnosza ̨ sie ̨ niektóre instrukcje w zadaniach. Nie wykonuj instrukcji dotycza ̨cych repozytorium, a paczke ̨ ze wszystkimi po- trzebnymi projektami pobierz na tej stronie Google Code Archive1. Po rozpakowaniu paczki projekty znajdziesz w katalogu
source-archive/javatrainings/designpatterns/trunk.

Projekty sa ̨„mavenowe”, w kaz ̇dym projekcie znajdziesz plik pom.xml. Zaimportuj kaz ̇dy z projektów do Eclipse. Moz ̇esz wykorzystac ́ odpowiednie polecenia Maven (mvn eclipse:eclipse) lub Eclipse (np. "File → Import → Maven → Existing Maven Projects"). Naste ̨pnie wykonuj polecenia podane w zadaniach2 - wie ̨kszos ́c ́ sprowadza sie ̨ do niewielkich modyfikacji kodu, które sprawia ̨, z ̇e doła ̨czone testy JUnit be ̨da ̨przechodzic ́.

Uwaga: przy oddawaniu dodatkowo w kaz ̇dym projekcie nalez ̇y dokładnie wskazac ́ wszyst- kie elementy danego wzorca (interfejsy, klasy, metody, pola) oraz wyjas ́nic ́ ich role.

Zadanie 1 — Wykonaj zadaniadotycza ̨cewzorcaSingletonidouble-checkedlocking. Spróbuj równiez ̇ zastosowac ́ implementacje ̨ wzorca Singleton oparta ̨ o typ wyliczeniowy enum. (10 p.)

Zadanie 2 — Wykonaj zadania dotycza ̨ce wzorca Adapter. (10 p.)

Zadanie 3 — Wykonaj zadania dotycza ̨ce wzorca Builder. (10 p.)

Zadanie 4 — Wykonaj zadania dotycza ̨ce wzorca Decorator. Do weryfikacji jaka cze ̨s ́c ́ kodu (i która) jest pokryta testami jednostkowymi zamiast programu Cobertura zainstaluj EclEmma. Uruchamianie: w Eclipse zamiast Run As→JUnit wybierz Coverage As→JUnit , a naste ̨pnie otwórz widok Coverage. (12 p.)

Zadanie 5 — Wykonaj zadania dotycza ̨ce wzorca Composite. (10 p.)

Zadanie 6 — Wykonaj zadania dotycza ̨ce wzorca State. (10 p.)

Zadanie 7 — Wykonaj zadania dotycza ̨ce wzorca Factory Method. (10 p.)

Zadanie 8 — Wykonaj zadania dotycza ̨ce wzorca Abstract Factory. (10 p.)

Zadanie 9 — Wykonaj zadania dotycza ̨ce wzorca Facade. Zadanie wymaga podstawowej zna- jomos ́ci Mockito, o którym be ̨dzie mowa na wykładzie. (12 p.)

Zadanie 10 — Wykonaj zadania dotycza ̨ce wzorca Flyweight. Najnowsza ̨ wersje ̨ JMeter mo- z ̇esz pobrac ́ tutaj. Narze ̨dzie ma stosunkowy łatwy w obsłudze interfejs graficzny − zapoznaj sie ̨ z jego podstawowymi moz ̇liwos ́ciami. Ustawione w testach 10000 wa ̨tków to moz ̇e byc ́ dla niektórych maszyn spore obcia ̨z ̇enie, proponuje ̨ rozpocza ̨c ́ testowanie z mniejsza ̨ liczba ̨. (14 p.)
