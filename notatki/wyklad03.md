# Wykład 03: 06.03.22 Rozwój algebry w XIX wieku (M. Skałba)

## Przełom XVIII i XIX wieku (Gauss)

### "Disquisitiones Arithmeticae" (Carl Friedrich Gauss, 1801)
Najbardziej wpływowa książka z teorii liczb i algebry napisana przez Gaussa w wieku 21 lat. Ukazała się z kilkuletnim opóźnieniem z powodu trudności odwzrorowania skomplikowanych wzorów na maszynie drukarskiej. Gauss zajmuje się dziedzinami z teorii grup, której jeszcze nie było w matematyce.

Wprowadza pojęcie *kongruencji mod m* w sposób ścisły i ogólny, staje się to ważnym impulsem do rozwoju algebry, ponieważ było przykładem relacji równoważności, które respektują działania arytmetyczne.

Niech $p$ - dowolna liczba naturalna, którą daje się przedstawić jako:
$p = x^2 + 6y^2$, a $n$ niech oznacza liczbę w postaci $n = 2x^2 + 3y^2$.

Następujące tożsamości obowiązują:
$$ (x^2 + 6y^2)(z^2 + 6 t^2) = (xz - 6yt)^2 + 6(xt + yz)^2$$
- Iloczyn dwóch liczb typu $p$ daje liczbę typu $p$.

- Podobnie iloczyn liczby typu $p$ i $n$ daje liczbę typu $n$. 
- A iloczyn $n$ i $n$ daje liczbę $p$. 

Takie proste reguły dają początek teorii grup i nowoczesnej algebrze w XIX wieku, jako nauka o **strukturach algebraicznych** (np. grupach), a nie o rozwiązywaniu równań.

### Prawo wzajemności dla reszt kwadratowych Gaussa

*Das quadratische Reziprozitaetsgesetz* po Niemiecku. Orzeka ono:

*Rozważmy dwie różne liczby nieparzyste $p$, $q$ oraz następujące dwie konkruencje:*
$$ x^2 \equiv q \mod p\qquad x^2 \equiv p \mod q$$
*Wówczas każda z tych kongruencji ma rozwiązanie x albo żadna nie ma rozwiązań,* **chyba, że** $p \equiv q \equiv 3 \mod 4$: *wówczas jedna z nich ma rozwiązanie, a druga nie.* Pierwszy dowód podał Gauss (a potem 5 istotnie innych). Dziś opublikowano >150 różnych dowodów PWRK Gaussa! Dowód jest punktem wyjścia do rozwoju **algebraicznej teorii liczb**.

### Zasadnicze tw. algebry
Każde równanie o współczynnikach zespolonych ma przynajmniej jeden pierwiastek zespolony - Gauss udowondił jako pierwszy w 1799 r.

## Rozwiązywanie równań, czyli teoria Galois

Norweg **Niels Henrik Abel** (1802 - 1829) zrobił pierwszy ważny postęp w rozwiązywaniu równań wielomianowych po renesansowych wyczynach Włochów. Pokazał, że nie ma uniwersalnych wzorów literowych na pierwiastki wielomianów stopnia 5. Pierwszy dowód, że czegoś nie da się zrobić (**Paolo Ruffini** wcześniej uzyskał ten wynik, ale nie został uznany przez środowisko matem.). Ale nie wiadomo, czy nie różnych wzorów w zależności od przypadku.

### Evariste Galois

Udowodnił, że nie da się zapisać pierwiastków równania 5. stopnia z użyciem działań arytmetycznych na współczynnikach i operacji wyciągania pierwiastków, jeśli **grupa Gaolis** wielomianu nie jest *szczególna*. Wykorzystał do tego teorię grup, którą stworzył. Te *szczególne* grupy, kiedy istnieją rozwiązania, nazywa się **grupami rozwiązalnymi**. Skałba poleca książkę *Wybrańcy bogów* Leopolda Infelda o E. Galois.

**Ważne osiągnięcie - pewnych równań nie da się rozwiązać!**

## Dirichlet

P. Lejeune-Dirichlet (1805 - 1859) matematyk niemiecki francuskiego pochodzenia. W swoim dowodzie twierdzenia o liczbach pierwszych w postępie arytmetycznym użył grupy charakterów zredukowanej grupy reszt mod m. Ten dowód to początek analitycznej teorii liczb i teorię reprezentacji grup.

### Charaktery Dirichleta mod 4

Rozważmy funkcję $n: Z \to \{-1,0,1\}$ oraz  $p: Z \to \{-1,0,1\}$:
$$n(4k+1) = 1, \ n(4k+3) = -1,\, n(4k) = n(4k) = 0$$
$$p(4k+1) = 1, \,p(4k+3) = 1,\, n(4k) = n(4k) = 0$$
Funkcja $n$ zachowuje się dobrze przy mnożeniu.
Są tu grupy grupy cyklicznej dwuelementowej. Dirichlet pokazał, że jest nieskończenie wiele liczby pierwszych typów $4k+3$ oraz $4k+1$ (przez pokazanie, że *szereg ich odwrotności jest rozbieżny*). Przez to Dirichlet staje się ojcem analitycznej teorii liczb. 

## Kummer: Wielkie Twierdzenie Fermata i Wyższe Prawa Wzajemności

Eduard Kummer interesował się *WTF* (w przeciwieństwie do Dirichleta) i udowodnił jest dla szerokiej klasy wykłodników. Niec doszedł jednak do pojęcia *ideału* (zrobił'to później *R. Dedekind*).

Niech $\mathbb{Z}[i]$ będzie zbiorem liczb zespolonych w postaci $a+ bi,\, a,b \in \mathbb{Z}$. Jeśli liczba $(a+bi)/(1+i)$ też należy do $\mathbb{Z}[i]$ to możemy roboczo liczbę $a+bi$ nazywać parzystą. Ponieważ $(1+i)^2 = 2i$, więc liczba 2 jest teraz podwójnie parzysta (jest odpowiednikiem liczby całkowitej podzielnej przez 4). Kummer umiał przeprowadzić tego typu konstrukcję w dowolnym zbiorze typu $\mathbb{Z}[\omega]$, gdzie $\omega$ jest ustalonym pierwiastkiem z 1 a $p$ dowolną liczbą pierwszą (w naszym przykładzie p = 2 a $\omega$ = i, czyli pierwiastek z 1 czwartego stopnia.) W pierścieniach $\mathbb{Z}[\omega]$ na ogół nie ma jednoznaczności rozkładu na
czynniki pierwsze i dlatego Kummer rozważał tzw. **liczby idealne**. W naszym przypadku $\mathbb{Z}[\omega]$ mamy jednoznaczność rozkładu i dla p = 2 wzięliśmy zwykłą liczbę 1 + i. To wszystko potrzebne do udowodnienia wielkiego twierdzenia Fermata dla wielu przypadków.

Kummer interesował się intensywniej Wyższymi Prawami Wzajemności.

### Bikwadratowe prawo wzajemności

Bikwadratowe prawo wzajemności, czyli twierdzenie dotyczące kongruencji:
$$x^4 \equiv q \mod p$$
wymaga uogólnienia symbolu Legendre’a dla reszt kwadratowych.
Najprościej rzecz ujmując teraz nie ma dychotomi typu: reszta kwadratowa
(R) a niereszta kwadratowa (N) i brak najprostszych praw rachunkowych
typu: N × N = R, N × R = N . . .. Tym razem na wykładnikach
obowiązuje rachunek mod 4: są trzy rodzaje niereszt bikwadratowych (gdyż
są cztery niezerowe reszty mod 4: 1,2,3). Poniważ jednak chcemy, aby
bikwadratowy symbol Legendre’a był multyplikatywny, więc przyjmuje on
wartości ze zbioru {1, i, −1, −i}, który jest grupą cykliczną rzędu 4,
podobnie jak reszty {0, 1, 2, 3} z dodawaniem reszt mod 4. Tak więc już
pojawia się praktyczna konieczność rachunków w $\mathbb{Z}[\omega]$ – zwanym
pierścieniem Gaussa, który pierwszy zauważył, że aby badać reszty
bikwadratowe, trzeba koniecznie wyjść poza zwykłe liczby całkowite.

## Początki algebry liniowej i nieprzemiennej

**Hermann Grassmann** w Niemczech tzn.najpierw w Szczecinie, gdzie był
nauczycielem a potem w Berlinie, gdzie był profesorem, stworzył pierwsze
podstawy teorii **przestrzeni wektorowych**. Zrozumiał podstawowe
znaczenie pojęć liniowej niezależności i generowania podprzestrzeni przez
układ wektorów. Był zadowolony z możliwości uprawiania geometrii
niezależnie od **wymiaru** przestrzeni! Wprowadził pojęcie bazy, wymiaru przestrzeni, wektorów niezależnych.

Grassman napisał podręcznik w tak abstrakcyjny i współczesny sposób, że ówcześni matematycy nie potrafili docenić jego matematematycznego geniuszu, ponieważ byli przyzwyczajeni do algebry w postaci np. kwaternionów. W swoich czasach był bardziej ceniony jako językoznawca.

**William Hamilton** w Irlandii stworzył **kwaterniony**. Są to czterowymiarowe wyrażenia $a + bi + cj + dk$, gdzie
$a, b, c, d ∈ \mathbb{R}\, a, i, j, k$ są specjalnymi symbolami, które mnoży się następująco (deklarujemy):
$$ii = jj = kk = −1, ij = k, jk = i, ki = j, ji = −k, kj = −i, ik = −j$$

Zatem mnożenie tych symboli nie jest przemienne, czyli wyrażeń $a + bi + cj + dk$ również. Zwykły liczby $a,b,c,d$ są przemienne ze wszystkim. Zbiór kwaternionów jest pierwszym przykładem **ciała nieprzemiennego**, czyli struktury algebraicznej, gdzie wykonalne są cztery działa arytmetyczne (również dzielenie da się), ale mnożenie nie jest przemienne. W procesie uogólniania pojęcia liczby kwaterniony są najbliższym kuzynem liczb zespolonych – trójek liczb nie da się sensownie mnożyć (Frobenius). Problemem było mnożenie wektorów trzywymiarowych - ludzie nie wiedzieli jak to robić. Hamiltonowi nie udało się tego zrobić, ale trochę pomógł w mnożeniu wektorów czterowymiarowych. Kwaterniony też są pierwszym przykładem algebry centralnej.

## Rozwój teorii grup

Zasłużeni dla rozwoju teorii grup w 19 wieku matematycy to na pewno A.
Cayley i F. Klein. Wcześniej pojęcie grupy nie pojawiło się *explicite*, jako pojęcie abstrakcyjne. **A. Cayley** pierwszy podał aksomaty grupy, ale
jednocześnie udowodnił swoje słynne twierdzenie o reprezentacji: *każda
grupa może być traktowana jako grupa permutacji pewnego zbioru*. Łatwo je udowodnić, ale filozoficzne jest słabe, ponieważ niektórzy uważali, że pojęcie grupy nie jest przez to potrzebne (zbyt abstrakcyjne).

Natomiast **F. Klein** znalazł spektakularne zastosowania pojęcia grupy w
geometrii jako takiej. Mianowicie zdefiniował geometrię jako teorię
niezmienników pewnej grupy przekształceń. W geometrii szkolnej płaszczyzny najważnie pojęcia to mierzenie odległości i pól, a te pojęcia są niezmiennikami izometrii. Jako grupę weźmę grupę wszystkich izometrii (MD xd).

Niech $G_1=\{1,2,3,4\}$, przy czym działaniem jest modulo 5. Natomiast niech $G_2=\{1,3,5,7\}$ tym razem działanie to mnożenie modulo 8.W grupie G1 potęgi elementu 2 to: 2, 4, 8 = 3, 6 = 1 dają wszystkie elementy G1. Natomiast potęgi dowlnego elementu $g \in G_2$ dają
tylko $g, 1$. Obie grupy mają po 4 elementy, ale są algebraicznie różne: $G_1$
jest cykliczna , a $G_2$ to czwórkowa grupa Kleina.

## Koniec 19. wieku – twierdzenia Hilberta

Jak rozwój geometrii algebraicznej wpłynął na rozwój algebry abstrakcyjnej.

Jeśli w układzie równań liniowych można tak pododawać równania stronami
(wcześniej mnożąc obie strony tych równań przez liczby 6= 0) aby otrzymać
równanie ewidentnie sprzeczne: $0 \cdot x_1 + 0 \cdot x_2 + ... + 0 \cdot x_n = 1$, to wyjściowy układ równań też nie ma żadnych rozwiązań. 

Jeśli uzyskanie tak ewidentnej sprzeczności nie jest możliwe to wyjściowy układ ma rozwiązania.

**Twierdzenia Hilberta o zerach** (Nullstellensatz) uogólnia to
następująco: *Dowolny układ równań wielomianowych (wielu zmiennych):*
$$f_1(x_1, . . . , x_n) = 0, f_2(x_1, . . . , x_n) = 0, . . . , f_k (x_1, . . . , x_n) = 0$$
*o współczynnikach z ciała liczb zespolonych nie ma rozwiązań tylko w
sytuacji, gdy istnieją wielomiany* $g_1, g_2, . . . , g_k$ *takie, że zachodzi tożsamość*
$$g_1f_1 + g_2f_2 + . . . + g_k f_k = 1.$$

Tylko w takiej sytuacji nie ma rozwiązań.

**Twierdzenie Hilberta o bazie**. Stwierdza ono w zasadzie, że każdy układ równań wielomianowych (również o nieskończenie wielu równaniach!) jest
równoważny układowi równań ze skończoną liczbą równań. Oba powyższe
twierdzenia wyniosły geometrię algebraiczną na istotnie wyższy poziom, niż
zostawili ją włoscy geometrzy algebraiczni 19. wieku. Twierdzenie to
zdetronizowało w pewnym sensie wiodącą **teorię niezmienników**.