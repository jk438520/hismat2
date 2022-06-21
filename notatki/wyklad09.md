# Wykład 09: 27.04.22 - Problemy Hilberta

Tagi: problemy Hilberta, Hilbert, hipoteza Riemanna, hipoteza Keplera z anegdotką


## David Hilbert
Urodził się w Królewcu, robił tam doktorat (1885) u Lindemanna, który udowodnił przestępność liczby pi. Przez większość życia zawodowego był (1895 - 1930) profesorem w Getyndze (za jego życia najważniejszy ośrodek matematyczny świata). Jest znany (oprócz przestrzeni Hilberta) z wykładu, który wygłosił 8 sierpnia 1900 na Międzynarodowym Kongresie Matematyków w Paryżu (23 problemu; 10 omówił). Obok **Poincarego**, jeden z ostatnich ludzi mających przegląd całej matematyki, w ciągu swojego życia często zmieniał zainteresowania matematyczne od algebry po podstawy matematyki do fizyki matematycznej. Miał wielu uczniów, m. in. **Hugo Steinhausa**. Hilbert powinien się kojarzyć każdemu z formalizmem matematycznym.

 1. Uważa że nauka rozwija się w sposób ciągły, każda epoka ma problemy, które uważa za szczególnie ważne, po czym przychodzi następna epoka i albo rozwiązuje problemy, albo zastępuje stare pytania nowymi - aby przewidzieć rozwój matematyki, trzeba sprawdzić na nierozwiązane pytania i określić, które są ważne.
 2. Problemy matematyczne muszą być przedstawiane jasno i w sposób łatwy do zrozumienia.
 3. Matematyka rozwija się dwoma drogami - **droga wewnętrzna**, umysł ludzi uświadamia sobie swoją niezależność, rozwija nowe problemy i pojawia się wtedy jako **prawdziwy pytający**, tak powstał problem liczb pierwszych i teoria równań Galois - lub **droga zewnętrzna**, świat zewnętrzny pokazuje nowe rzeczy i narzuca nowe pytania wynikające z **rzeczywistego doświadczenia** (według prof. Strzeleckiego - nawiązanie do fizyki). W tym przeplataniu się dwóch dróg, rozwija się harmonia.
 4.  Jeśli nie da się rozwiązać jakiegoś problemu, to często przyczyna leży w nieumiejętności zobaczenia bardziej ogólnego punktu widzenia. Po znalezieniu problem staje się bardziej dostępny dla rozważań, a jednocześnie pojawia się metoda rozwiązywania problemów pokrewnych. Najbardziej praktyczny sposób szukania metod ogólnych, gdyż “**kto szuka metod, nie mając na myśli konkretnego problemu, zwykle szuka na próżno**”.
 5. Uważał, że “**każdy problem matematyczny musi dać się dokładnie rozwiązać**”.
 6. Przekonanie o rozwiązywalności problemów to największa motywacja do pracy w dziedzinie matematyki - “**musimy wiedzieć, będziemy wiedzieć**”.
 7. Różne teorie matematyczne wymagają aksjomatyzacji oraz ufundować na pewnych podstawach.
 
 ## Problemy Hilberta
 8. **Hipoteza continuum** - pytanie, czy są zbiory nieskończone istotnie większe niż liczby naturalne oraz istotnie mniejsze niż liczby rzeczywiste (niezależne od aksjomatów teorii mnogości).
 9. **Niesprzeczność aksjomatów arytmetyki** - w obrębie systemu formalnego, który zawiera aksjomaty Peano, nie da się udowodnić sprzeczności w obrębie jego samego, w każdym systemie istnieją zdania, które są niedowodliwe.
 10.  **Równoważność wielościanów przez podział skończony** - czy można podzielić jeden wielościan na cegiełki tak, aby złożyć z niego drugi o takiej samej objętości.
 11. **Problem linii prostej jako najkrótszego połączenia punktów.**
 12. **Grupy Liego** - problem, który może występować w dwóch wariantach, jeden z nich do dzisiaj jest nierozwiązany.
 13.  **Matematyczne podejście do aksjomatów fizyki** - formalne teoretyczne i aksjomatyczne podstawy do jak największych partii fizyki, w tym szczególnie dla rachunku prawdopodobieństwa.
 14. Czy a^b jest liczbą przestępną dla a i b algebraicznych niewymiernych? - TAK
 15. **Hipoteza Riemanna**
 16. Pytanie o algorytm, czy dane równanie wielomianowe diofantyczne o współczynnikach całkowitych ma rozwiązanie, wywarło ogromny wpływ na rozwój logiki i informatyki teoretycznej - NIE MA
 17. //** ZAAWANSOWANE PYTANIA Z ALGEBRY I GEOMETRII **//
 18. Rozwiązać równanie 7.go stopnia za pomocą złożeń skończonej liczby funkcji algebraicznych (wariant: funkcji ciągłych) dwóch zmiennych - związek z **nomografią**. Dla funkcji algebraicznych do dzisiaj brak rozwiązania, dla funkcji ciągłych jest odpowiedź twierdząca.
 19. Określić liczbę i opisać położenie różnych **owali**, powstających jako składowe krzywych lub powierzchni algebraicznych, lub jako cykle graniczne wielomianowych pól wektorowych.
 20. Grupy krystalograficzne, wypełnienia przestrzeni wielościanami foremnymi i najgęstsze upakowania kul (**hipoteza Keplera**).
 21.  //** PYTANIA O ISTNIENIE I REGULARNOŚĆ ROZWIĄZAŃ W RACHUNKU WARIACYJNYM **//
 22. //** RÓWNANIA RÓŻNICZKOWE&lt; GRUPY MONODROMII, ANALIZA ZESPOLONA **//
## Problem numer 8, Hipoteza Riemanna
Pytanie “ile jest liczb pierwszych?”, głupie pytanie! Od 2300 lat wiadomo, że nieskończenie wiele. Znany dowód Euklidesa jednak nie mówi, **jaki** jest rozkład liczb pierwszych wśród innych liczb naturalnych. Hipoteza Riemanna to wyraz popartych poszlakami przeświadczeń, że rozkład liczb pierwszych jest bliski losowemu, ale można go wiernie opisać.

## Funkcja dzeta Riemanna
Istnieje tylko jedna funkcja dzeta zmiennej zespolonej, różnej od jeden, taka że:

 - jest równa dzeta Riemanna dla liczb rzeczywistych większych od jeden.
 - ma pochodną (zespoloną) w każdym punkcie dziedziny.
 
 Hipoteza (**Riemann, 1859**). Jeśli dzeta(z) = 0, Re(z) > 0, to z = ½ + it \
    Funkcja ładna i kolorowa!
    Dlaczego funkcja ta ma związek z liczbami pierwszymi? **Euler** pokazał, że odwrotność funkcji dzeta to nieskończony iloczyn (1 - 1/p) gdzie p jest liczbą pierwszą. **Gauss** wysunął przypuszczenie, że liczba liczb pierwszych mniejszych bądź równych N jest w przybliżeniu równa logarytmowi całkowemu od N. Gauss znał liczby pierwsze od 2 do 3 000 000, zauważył, że liczby pierwsze pojawiają się na wpół losowo wśród innych liczb, dzięki temu na podstawie szacowaniu prawdopodobieństwa tego, że liczba jest pierwsza, wysnuł to porównanie.
## Inne informacje na temat Hipotezy
Praca Riemanna podaje jak bardzo logarytm całkowy różni się od liczb pierwszych mniejszych bądź równych N, kawałek opisujący błąd wyraża się również za pomocą logarytmu całkowego i **zer funkcji dzeta**. Zera funkcji dzeta są **ułożone** tak, aby **losowa** część błędu była możliwie najmniejsza. Hipoteza Riemanna ma również inne dwie równoważne wersje: **hipotezę von Kocha** (1901) oraz **hipotezę Lagariasa** (2000).
Hipoteza Riemanna dla dzieci: liczby dzielimy na trzy klasy, **czerwone**, **czarne** i **szare**. **Szare** to liczby, które dzielą się przez jakiś pełny kwadrat. **Czarne** to te, które są iloczynem parzystej liczby różnych czynników pierwszych. **Czerwone** to te, które są iloczynem nieparzystej liczby różnych czynników pierwszych. Dla przedziału {2,...,k}, dla dużych k, różnica |liczby czarne - liczby czerwone| ma, z grubsza, dwa razy mniej cyfr niż k.
## Aktualne poszlaki na temat hipotezy
 - **Hardy** (1914): na prostej krytycznej Re(z) = ½ jest nieskończenie wiel zer funkcji dzeta.
 - **Levinson** (1974): na prostej krytycznej jest “co najmniej ⅓” nietrywialnych zer.
 - Znamy (XXIw., projekt ZetaGrid) wartości 10^14 zer nietrywialnych, **wszystkie** są na prostej krytycznej.
 
"Matematyk tym różni się od biologa, czy fizyka doświadczalnego, że mimo poszlak uważa hipotezę Riemanna jako pytanie otwarte".
## Hipoteza Keplera
Sir Walter Raleigh (królewski pirat - brutalne i krwawe piractwo w służbie korony Brytyjskiej) miał asystenta Thomasa Harriota (astronom, matematyk, etnograf), który odbył wraz z pierwszym wyprawę do Ameryki Północnej. Thomas Harriot napisał _Krótki i Prawdziwy Raport o Nowo Znalezionym Kraju Wiginii_, w którym uznał Indian za dobrych ludzi wymagających nawrócenia. W **1591** Raleigh zlecił Harriotowi przyszykowanie tabeli ułożeń kul, podając liczbę kul w stosie w zależności od wysokości, tak aby oszczędnie magazynować kule armatnie. Harriot zaczął badać w tym celu teorię sum kwadratów oraz zestaw możliwych ułożeń cząsteczek w kształcie kul. W czasie korespondencji z Keplerem powstało pytanie: dlaczego promień świetlny, padający na powierzchnię przezroczystego ośrodka częściowo się odbija, a częściowo załamuje? **Harriot**: bo materia ma strukturę atomistyczną. **Kepler**: nie. (ale później się przekonał). W latach 1609-1611 **Kepler** formułuję hipotezę o najgęstszym możliwym ułożeniu kul w przestrzeni trójwymiarowej. Najgęstsze upakowanie (74% przestrzeni):
 - Przestrzeń wypełniona jednakowymi sześcianami.
 - Środki kul w wierzchołkach i w środkach ścian sześcianów.
 - Kule jednakowe, jak największe.

Nie jest to jedynie najgęstsze upakowanie, wszystkich jest nieprzeliczalnie wiele! I do tego nie każde ułożenia są symetryczne. Niektóre ułożenia zyskały swoje nazwy: HCP oraz FCC.

## Hipoteza Keplera jako problem Hilberta

 - 1900 - Hilbert dokłada ją do swoich problemów.
 -  Zbliżony stary problem: mamy kulę o promieniu 1 w przestrzeni; ile rozłącznych jednakowych kul o promieniu 1 może dotykać jej od zewnątrz? **Newton** twierdził, że 12, a jego kolega **Gregory** twierdził że 13. Newton miał rację…
 - 1953: **Fejes Toth** redukuje hipotezę Keplera do skończonego zestawu obliczeń.
 - Kilka błędnych dowodów (**Buckminster Fuller**, **Hsiang**)
 - 1993-1998: **Thomas Hales **i **Sam Ferguson** przedstawiają dowód hipotezy Keplera wspierany komputerowo (powstaje pytanie: czy to jest dowód?) - składa się z teorii optymalizacji, teorii grafów, kombinatoryki.

**Inne pytanie**: jak dzielić przestrzeń na komórki o jednakowej objętości tak, żeby przeciętne pole powierzchni ścian komórki było minimalne?

 -  Lord Kelvin (XIX wiek): brać czternastościany i lekko wyokrąglać ścianki.
 - Phelan, Weaire, 1993: propozycja lepszego rozwiązania, z dwóch rodzajów dwunastościanów (dwóch fizyków - badania piany).
## Koniec życia Hilberta
 Hilbert zmarł w 1943 roku w Getyndze. W 1933 roku wprowadzono w Niemczech obowiązkową służbę wojskową, urzędników państwowych, którzy nie są pochodzenia aryjskiego, przeniesiono w stan spoczynku (profesor był takim urzędnikiem). W 1934 roku w Getyndze Hilbert spotkał się z “ministrem edukacji”, który zadał mu pytanie, czy instytut ucierpiał po usunięciu żydów, na co ten drugi odpowiedział instytut? Tego przecież już wcale nie ma.
