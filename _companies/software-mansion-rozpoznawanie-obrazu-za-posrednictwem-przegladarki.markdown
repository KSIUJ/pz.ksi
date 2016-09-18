---
layout: project
ordering: 5
company: Software Mansion
company_img:
company_desc:
project: Rozpoznawanie obrazu za pośrednictwem przeglądarki
project_img:
technological_stack: |
    Przed końcem października opublikujemy kod bramki na niekomercyjnej licencji OpenSource. Bramka używa języków: C/C++ oraz Vala oraz łączy się z GStreamerem. Sugerujemy pozostawienie tych technologii. Do rozpoznawania obrazu można użyć dowolnych dostępnych bibliotek i narzędzi, w razie potrzeby możemy zasugerować którąś z nich. Oprócz samej części do przetwarzania wideo należy też stworzyć samą stronę. Nie narzucamy tutaj technologii, ale z naszej strony proponujemy użyć następujących:
    - Ruby on Rails, Node.js, Elixir lub Clojure na backendzie
    - React na frontendzie
methodology: |
    Ponieważ najczęściej zajmujemy się rozwojem startupów, to chcielibyśmy zastosować metodologię Lean (a w szczególności Lean Startup).
    - Z góry ustalamy orientacyjny „budżet” (czyli ilość czasu, jaki możemy poświęcić na projekt)
    - W trakcie projektu działamy w iteracjach – każda iteracja ma na celu zweryfikowanie pewnej tezy/pewnych tez. W przypadku tego projektu jedną z pierwszych tez do zweryfikowania będzie np. czy wybrane narzędzie do rozpoznawania obrazu nada się do ustalonego zadania
    - W trakcie projektu pozostajemy otwarci na tzw. pivot. Oczekujemy, że zespół szybko zorientuje się, jeżeli ustalony cel jest zbyt skomplikowany, żeby go ukończyć w ramach określonego czasu, albo gdy okaże się, że można osiągnąć szybciej coś innego, lepszego.
    - Oczekujemy też otwartej, bieżącej komunikacji
shipment_method: |
    Regularne spotkania (co 2-4 tygodni), na których zespół będzie prezentował osiągnięte cele i decydował, czy są na dobrej drodze do zakończenia projektu. Nie oczekujemy, że uda się osiągnąć zamierzony na początku cel, ale wymagamy, żeby w razie jego zagrożenia otwarcie o tym mówić, a w przypadku kryzysowym cel zmienić.
training: |
    Technologie użyte nie są typowe, więc oczekujemy chęci nauki na własną rękę - z naszej strony będzie dostępny specjalista, który będzie w stanie wskazać, czego się nauczyć oraz pomóc przy okazji problemów.
tools_provided: |
    Możemy udostępnić nasze serwery na potrzeby hostingu projektu. Jeżeli będzie potrzebny inny sprzęt, możemy go również dostarczyć.
mentor: |
    Z naszej strony oferujemy:
    - mentoring biznesowo-projektowy prowadzony przez wspólników (w ramach okresowego spotkania)
    - mentoring technologiczny w użytych technologiach (wskażemy kilka osób, które powinny być dostępne w razie potrzeby; możliwe będzie okazjonalnie także programowanie w parach)
worktime: Minimum 6-8 godzin tygodniowo.
location: |
    Sugerujemy w początkowej fazie poznawania technologii pracować na miejscu w naszym biurze (Na Zjeździe 11, Kraków) - będziemy wtedy w stanie pomóc z problemami technicznymi.
    W późniejszej fazie dobrze by było zrobić cotygodniowe spotkanie w formie standupu, ale oprócz tego wedle potrzeb udostępniamy stanowiska pracy w naszym biurze. Do komunikacji zdalnej sugerujemy utworzyć zespół na Slacku (lub podobnym narzędziu).
money: |
    Symboliczne (kwota jeszcze do ustalenia, ale będzie to kilka tysięcy złotych do podziału na zespół). Jeżeli projekt uda się dokończyć z sukcesem, to widzimy następujące opcje:
    - Jeżeli projekt będzie umiarkowanie udany możemy zaoferować symboliczne wynagrodzenie w zamian za opublikowanie kodu na githubie open-source – w formie dema naszych technologii, więc może być na restryktywnej licencji (np. tylko do celów edukacyjnych)
    - Jeżeli projekt będzie dobrej jakości, to za trochę większe wynagrodzenie chcielibyśmy opublikować kod na githubie pod naszym kontem – z tego tytułu możemy zaoferować trochę wyższe wynagrodzenie
    - Jeżeli projekt okaże się mieć dodatkowy potencjał biznesowy, to chcielibyśmy mieć opcję odkupienia pełni praw majątkowych za już niesymbolicznym wynagrodzeniem.
    - Niezależnie od wyniku chcielibyśmy otrzymać na wytworzone oprogramowanie nieograniczoną, niewyłączną bezpłatną licencję z możliwością sublicencjonowania. 
later_employment: |
    Nie możemy tego obiecać, ale gwarantujemy możliwość przejścia procesu rekrutacyjnego poza kolejnością. Możliwe jest późniejsze zatrudnienie w dwóch trybach: w ramach stażu wakacyjnego po ukończeniu roku lub na stałe. Jeżeli projekt okaże się perspektywiczny, to możliwe jest zatrudnienie w celu dalszego jego rozwoju.
team_size: 3-5 osób
requirements: |
    W tym projekcie przydałyby się zdywersyfikowane umiejętności – preferowalnie przynajmniej jedna osoba z doświadczeniem w web-developmencie, ale też osoby z pewną wiedzą na temat rozpoznawania obrazu oraz na temat przetwarzania wideo.
    Nie wymagamy konkretnego doświadczenia.
project_roles: |
    Cały zespół powinien być odpowiedzialny kształt projektu, ale wyznaczymy jedną osobę jako Project Managera, odpowiedzialnego za płynny przebieg prac.
    Zakładamy, że każdy członek zespołu będzie pracował nad kodem.
copyrights: Patrz punkt o gratyfikacji finansowej.
---
Przez ostatnie dwa lata w Software Mansion mieliśmy szansę zbudować potężne doświadczenie w zakresie przetwarzania multimediów online.

Od kilku miesięcy rozpoczęliśmy prace nad własnymi produktami i jednym z efektów jest bramka WebRTC. WebRTC to kolekcja protokołów i API służących do transmisji mediów w trybie peer-to-peer. Rzeczona bramka emuluje peera i pozwala używać tego standardu w architekturze klient-serwer. Zaletą tej technologii jest to, że jest ona natywnie obsługiwana przez wszystkie główne przeglądarki (poza safari).

W ramach tego projektu chcielibyśmy zintegrować bramkę z rozpoznawaniem obrazu i osiągnąć rozpoznawanie obrazu w czasie rzeczywistym bezpośrednio z przeglądarki. Rodzaj rozpoznawanego obrazu jest do ustalenia z zespołem – jesteśmy otwarci na propozycje, chcielibyśmy tylko, żeby projekt miał potencjalne praktyczne zastosowanie. Kilka naszych pomysłów (niekoniecznie każdy da się zrealizować w ramach projektu):

- privacy screen – ukrywanie danych, gdy w obrazie z kamery pojawi się więcej niż jedna osoba
- autoryzacja – rozpoznawanie twarzy właściciela
- automatyczne wylogowywanie – gdy przed ekranem nie ma żadnej twarzy, wyloguj użytkownika.
- rozpoznawanie oświetlenia i dostosowanie kolorystyki strony do rodzaju światła (np. jasna za dnia, ciemna w nocy)
- rozpoznawanie miejsca – rozpoznawanie na podstawie tła, czy użytkownik jest np. w domu, czy w pracy
