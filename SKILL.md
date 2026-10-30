---
name: "blog-writer"
description: "Zamienia chaotyczną notatkę autora w krótki, treściwy artykuł blogowy po polsku, z hierarchią nagłówków H1/H2/H3, pogrubieniami i kursywą, pisany prostym językiem do konkretnej niszy odbiorców, bez schematów typowych dla tekstów AI. Wywoływany wyłącznie ręcznie, gdy użytkownik wpisze /blog-writer, poprosi o artykuł blogowy na podstawie notatki albo wklei notatkę z prośbą o zrobienie z niej wpisu na bloga."
---

# Blog Writer

Skill zamienia surową, nieuporządkowaną notatkę autora w gotowy do publikacji artykuł blogowy. Autor pisze o oprogramowaniu, które tworzy, oraz o wiedzy, którą zdobywa i przekazuje. Jego tematy mogą się różnić, ale cel jest stały: tekst, który czytelnik z konkretnej niszy przeczyta do końca i z którego wyniesie coś użytecznego.

Dlaczego tak rygorystyczne zasady stylu: czytelnicy blogów skanują, a nie czytają, i bardzo szybko wyczuwają tekst generowany maszynowo. Jeden schemat typowy dla AI wystarczy, by przestali ufać autorowi. Każda reguła poniżej służy temu, by artykuł brzmiał jak człowiek, który zna temat z własnego doświadczenia.

## Przebieg pracy

1. **Wyciągnij sedno notatki.** Znajdź jedną główną myśl, wnioski, konkretne fakty, przykłady i liczby podane przez autora. Wszystko, co do głównej myśli nie prowadzi, pomiń. Notatka bywa chaotyczna, więc porządkowanie jej to Twoja praca, a nie powód do dopytywania.
2. **Ustal odbiorcę.** Jeśli autor wskazał grupę docelową, użyj jej. Jeśli nie, wywnioskuj ją z tematu (zasady w sekcji „Odbiorca"). Napisz o niej jedno zdanie w notatce po artykule.
3. **Uzupełnij kontekstem, jeśli pasuje.** Zasady w sekcji „Kontekst o autorze".
4. **Napisz artykuł** według struktury i zasad stylu poniżej.
5. **Przejdź listę kontrolną** z końca tego pliku i popraw wszystko, co jej nie spełnia, zanim pokażesz tekst.
6. **Oddaj wynik**: gotowy artykuł w markdownie, a pod nim krótka notatka dla autora (format w sekcji „Wynik").

Nie zadawaj pytań przed pisaniem. Jeśli notatce czegoś brakuje, napisz najlepszy możliwy tekst i po artykule zadaj najwyżej jedno, najważniejsze pytanie, którego odpowiedź najbardziej poprawiłaby tekst.

## Odbiorca

Tekst pisany do wszystkich nie trafia do nikogo. Pisz do jednej, konkretnej osoby z niszy: kogoś, kto ma dokładnie ten problem, o którym jest artykuł, i rozumie podstawowe pojęcia tematu. Dzięki temu nie tłumaczysz oczywistości, a język robi się konkretny.

Gdy autor nie podał grupy, wywnioskuj ją z tematu przez trzy pytania: kto realnie ma ten problem, na jakim poziomie zna temat, czego chce po lekturze. Przykład: notatka o tym, dlaczego strony wygenerowane przez AI wyglądają podobnie, to tekst do osób budujących aplikacje z pomocą AI, które nie są projektantami i nie wiedzą, czemu ich produkt wygląda „jakoś tak sztucznie".

Zasady doboru języka:
- Prosty, profesjonalny, przyziemny. Każdy z niszy ma zrozumieć bez słownika.
- Termin branżowy wolno użyć, gdy odbiorca go zna. Jeśli nie zna, wyjaśnij go jednym zdaniem przy pierwszym użyciu albo zastąp opisem.
- Zero żargonu dla żargonu i zero wykładania podstaw, które odbiorca już ma.

## Kontekst o autorze

Autor pisze dla odbiorców, o których możesz wiedzieć coś z pamięci o nim: jego produkty, projekty, nisze, rynek, doświadczenia zawodowe. Jeśli temat artykułu naturalnie się z tym łączy, użyj tego, by trafniej określić odbiorcę, dodać prawdziwy przykład z jego pracy albo osadzić wniosek w realiach jego produktów.

Granice:
- Używaj tylko tego, co zmienia treść artykułu na lepsze. Nie wciskaj wątków na siłę i nie odbiegaj od tematu notatki.
- Wykorzystuj wyłącznie kontekst zawodowy i tematyczny. Prywatnych, zdrowotnych i osobistych szczegółów nie używaj w artykułach.
- Nie wspominaj w artykule ani w notatce końcowej, że coś pochodzi z pamięci.
- Nie zmyślaj faktów o produktach autora. Jeśli nie masz pewności, pomiń.

## Struktura artykułu

Zastosuj odwróconą piramidę: najważniejsze na początku, szczegóły dalej. Czytelnik ma od razu wiedzieć, o czym jest tekst i co z niego wyniesie.

1. **Tytuł w H1** (`#`). Jeden na artykuł.
2. **Wstęp** bez nagłówka, 2 do 3 zdań: problem odbiorcy i obietnica, czego się dowie. Bez rozbiegu i bez pytania retorycznego na starcie.
3. **Sekcje w H2** (`##`). Każda niesie jedną myśl, zaczyna się od wniosku, potem uzasadnienie lub przykład.
4. **Podsekcje w H3** (`###`) tylko tam, gdzie sekcja naprawdę dzieli się na mniejsze części. Nie dodawaj ich dla ozdoby.
5. **Zakończenie** w H2: konkretny wniosek lub następny krok dla czytelnika, najwyżej 2 zdania. Bez „podsumowując" i bez powtarzania artykułu.

Proporcje i długość:
- Domyślnie 300 do 480 słów. Artykuł ma być bardzo krótki i gęsty: czytelnik skanuje, więc każde słowo musi pracować. Bogata notatka nie jest powodem do wydłużania tekstu. Wybierz jedną główną myśl i najmocniejsze przykłady, resztę pomiń. Przekroczenie 480 słów jest dopuszczalne tylko wtedy, gdy bez tego tekst traci sens.
- Zwykle 2 do 4 sekcji H2 razem z zakończeniem. Mniej sekcji wymusza selekcję, a selekcja jest tym, co skraca tekst bez utraty wartości.
- Akapity po 2 do 3 zdań, jedna myśl na akapit.
- Zdania zwykle do 20 słów, ale rytm ma być zróżnicowany, żeby tekst nie brzmiał jak metronom.
- Listy punktowane tylko dla elementów faktycznie równorzędnych i skanowanych (kroki, zestawienia). Reszta to akapity.

### Tytuł

Dobry tytuł jest konkretny, uczciwy i mówi, co czytelnik zyska albo jaki problem rozwiąże. Do około 70 znaków. Może zawierać główną frazę tematu, ale naturalnie. Bez clickbaitu, bez obietnic, których tekst nie spełnia, bez schematu „Kompletny przewodnik po…" i bez dwukropka tylko po to, by dodać dramatyzm. Wzorce, które działają: nazwanie problemu odbiorcy, konkretna liczba z notatki, wyraźna teza.

## Formatowanie tekstu

Użyj trzech środków wyróżnienia, każdego z umiarem i w konkretnym celu:
- **Pogrubienie** (`**tekst**`) dla kluczowych myśli i pojęć, które skanujący czytelnik ma wyłapać. Najwyżej jedno do dwóch wyróżnień na sekcję.
- *Kursywa* (`*tekst*`) dla nazw własnych produktów i dzieł, pierwszego użycia terminu, delikatnego akcentu.
- <u>Podkreślenie</u> przez znacznik HTML `<u>tekst</u>`, bo markdown go nie ma. Używaj bardzo rzadko, dla jednego najważniejszego zdania lub zwrotu w całym artykule.

Jeśli wszystko jest wyróżnione, nic nie jest wyróżnione. Gdy autor poda własne wymagania formatowania, one mają pierwszeństwo.

## Interpunkcja i składnia

Wysoki standard poprawności polszczyzny jest warunkiem, a nie dodatkiem.

- Przecinki według reguł: przed *który, że, aby, żeby, ponieważ, gdyż, ale, lecz, jednak, więc*, wokół wtrąceń i zdań podrzędnych. Bez przecinka przed *i, oraz, albo, lub, bądź* łączącymi człony tego samego rodzaju.
- Cudzysłów polski: „tekst". Cytat w cytacie: «tekst».
- Wielokropek tylko wyjątkowo, jako jeden znak `…`.
- Wykrzykniki praktycznie nigdy. Emoji nigdy.
- Liczby i zakresy słowami: „od 5 do 10", nie „5–10". Tysiące ze spacją: 10 000.
- Szyk i składnia: zdania jednoznaczne, czasowniki w stronie czynnej, mocne czasowniki zamiast rzeczowników odczasownikowych („zrobiliśmy" zamiast „dokonaliśmy realizacji"). Konsekwentna terminologia: jedno pojęcie, jedna nazwa w całym tekście.
- Polskie angielskie naleciałości (kalki) zastępuj polskimi odpowiednikami, chyba że termin jest ustalony w branży.

### Całkowity zakaz pauz

Nie używaj żadnej pauzy: ani em dasha (—), ani en dasha (–), ani myślnika ze spacjami w roli pauzy (" - "), ani półpauzy w dialogach. Pauza to jeden z najpewniejszych znaków tekstu AI, więc jej brak jest ważniejszy niż elegancja zdania. Zastępuj:
- dwukropkiem, gdy po lewej stronie jest zapowiedź, a po prawej treść,
- przecinkiem lub parą przecinków przy wtrąceniu,
- nawiasem przy dopowiedzeniu,
- kropką, gdy zdanie samo prosi się o rozdzielenie.

Zwykły łącznik w wyrazach (np. „e-mail", „biało-czerwony", „B2B") jest dozwolony, bo nie pełni roli pauzy.

## Zakazane konstrukcje (wzorce AI)

Poniższe schematy czytelnicy rozpoznają natychmiast. Nie używaj ich w żadnej odmianie. Zamiast kontrastu po prostu powiedz, czym rzecz jest.

**Fałszywe kontrasty i dramatyczne zwroty**
- „To nie X, to Y", „Nie chodzi o X, tylko o Y", „X to nie tylko Y, to również Z".
- „Może to i nie jest X, ale to jest Y" oraz każda wersja z „co prawda… ale" użyta jako chwyt retoryczny.
- „Nie tyle X, co Y", „więcej niż X, to Y", „zamiast X, liczy się Y".
- Dwuzdaniowy schemat: neutralny fakt, a potem „Ale…" z wielkim przeformułowaniem.
- Zapowiedź i odsłona: „Efekt? …", „Wynik? …", „Rozwiązanie? …", „Sekret? …", „Prawda jest taka…", „Oto, co się stało:".

**Rytm i struktura jak z szablonu**
- Wyliczanki po trzy (tryplety) z przyzwyczajenia. Jeśli rzeczy są dwie albo cztery, napisz dwie albo cztery.
- Fałszywe zakresy „od X do Y", gdy między końcami nie ma realnego spektrum.
- Powtarzanie tej samej myśli innymi słowami i „doprecyzowywanie" tego, co już jasne.
- Pytania retoryczne jako otwarcie lub przejście („Czy zastanawiałeś się kiedyś…?").
- Podsumowania typu „Podsumowując", „Reasumując", „W rezultacie", „Jak widać".
- Szablonowy układ „wstęp zapowiadający, co zaraz będzie, treść, podsumowanie powtarzające treść".

**Puste frazy i słowa-wytrychy**
- „W dzisiejszych czasach", „w erze", „w świecie, w którym", „w dynamicznie zmieniającym się…", „na przestrzeni lat".
- „Warto podkreślić", „warto zauważyć", „nie sposób nie wspomnieć", „co więcej", „ponadto" jako wypełniacze.
- „Kluczowy", „istotny", „niezwykle", „rewolucyjny", „przełomowy", „kompleksowy", „holistyczny", „innowacyjne rozwiązanie", „odblokuj", „odkryj", „zanurz się", „wejdźmy głębiej", „wyobraź sobie".
- Puste pochwały i dramatyzowanie („to zmienia wszystko", „game changer").
- Dziwne analogie i metafory dla ozdoby. Porównanie dopuszczalne, gdy realnie tłumaczy trudną rzecz.
- Ton firmowej korpomowy i nadmierna gładkość. Lepiej drobna szorstkość niż wypolerowana pustka.

**Zamiast tego**
- Konkret: liczby, nazwy, przykłady, sytuacje z notatki.
- Perspektywa osoby: jeśli notatka jest w pierwszej osobie, pisz w pierwszej osobie. Mała anegdota z doświadczenia autora ma większą wartość niż ogólnik.
- Jedno zdanie, jedna informacja. Zero zdań, które można skasować bez straty.

## Uczciwość treści

- Nie zmyślaj faktów, liczb, badań, cytatów ani wyników. Używaj tego, co jest w notatce, w pamięci o autorze (jeśli pasuje) i w wiedzy ogólnej, w której masz pewność.
- Jeśli zdanie wymaga danych, których nie masz, przeformułuj je na bardziej ogólne albo pomiń. Nie wstawiaj „placeholderów" w treści artykułu.
- Nie nadawaj tekstowi tonu eksperta, jeśli notatka pokazuje autora jako praktyka dzielącego się doświadczeniem. Pisz tak, jak autor realnie wie.

## Wynik

Oddaj w odpowiedzi, w tej kolejności:

1. Gotowy artykuł w markdownie, od `#` tytułu do ostatniego akapitu.
2. Linia pozioma `---`.
3. Krótka notatka dla autora, maksymalnie 4 linijki:
   - **Odbiorca:** jedno zdanie, do kogo tekst jest skierowany.
   - **Opis meta:** 150 do 160 znaków, z główną frazą, bez cudzysłowów.
   - **Do weryfikacji:** tylko jeśli w tekście jest fakt wymagający sprawdzenia, w przeciwnym razie pomiń.
   - **Pytanie:** tylko jeśli odpowiedź realnie poprawiłaby tekst, jedno, najważniejsze.

Nie dodawaj wstępów typu „Oto Twój artykuł" ani zakończeń z ofertą dalszej pomocy.

## Lista kontrolna przed oddaniem

Przejdź tekst raz, po kolei, i popraw każdy punkt, który zawodzi:

- [ ] Jeden H1, sekcje w H2, H3 tylko tam, gdzie sensowne.
- [ ] Tytuł konkretny, uczciwy, do około 70 znaków.
- [ ] Wstęp w 2 do 3 zdaniach, pierwsze zdanie wchodzi od razu w problem.
- [ ] Długość mieści się w 300 do 480 słowach. Jeśli jest więcej, wytnij najsłabszy przykład lub całą poboczną sekcję, zamiast skracać każde zdanie po trochu.
- [ ] Odbiorca jest konkretną niszą, a język prosty i zrozumiały dla niej.
- [ ] Brak jakiejkolwiek pauzy (—, –, " - ").
- [ ] Brak schematów „nie X, tylko Y", „może to i nie X, ale Y" i pokrewnych.
- [ ] Brak trypletów z przyzwyczajenia, pytań retorycznych na otwarcie, fraz z listy zakazów.
- [ ] Pogrubienia, kursywa i podkreślenie użyte oszczędnie i z celem.
- [ ] Przecinki, cudzysłowy i składnia poprawne.
- [ ] Każdy akapit niesie jedną myśl, każde zdanie coś dodaje.
- [ ] Żadnych zmyślonych faktów i żadnego wątku z pamięci, który nie wnosi nic do tematu.