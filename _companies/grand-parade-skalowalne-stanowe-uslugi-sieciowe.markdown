---
layout: project
ordering: 16
company: Grand Parade
company_img:
company_desc:
project: Skalowalne stanowe usługi sieciowe o wysokiej dostępności w oparciu o Akka
project_img:
technological_stack: |
    - Scala, Akka, system aktorów
    - Opcjonalnie: Akka Persistence, Akka Cluster, Cassandra, Kafka, Akka Streams
methodology: Dowolna
shipment_method: |
    Sugeruje się udostępnienie repozytorium Git. Pytania drogą mailową lub na konsultacjach w siedzibie firmy Grand Parade, raz w tygodniu 1h.
training: |
    Szkolenia nie są przewidziane. Materiały są dostępne w internecie:
    1. “Building Scalable Stateful Services” by Caitie McCaffrey
        - [https://www.youtube.com/watch?v=H0i_bXKwujQ](https://www.youtube.com/watch?v=H0i_bXKwujQ)
        - [http://highscalability.com/blog/2015/10/12/making­-the-­case-­for-­building-­scalable-­stateful-­services-­in-­t.html](http://highscalability.com/blog/2015/10/12/making­-the-­case-­for-­building-­scalable-­stateful-­services-­in-­t.html)
    2. [Akka Documentation](http://akka.io/docs/)
tools_provided: Nie.
mentor: Adam Dziendziel ( adam.dziendziel@grandparade.co.uk )
worktime: 160h
location: Zdalnie.
money: Nie jest planowana.
later_employment: |
    Przewidujemy możliwość zatrudnienia lub zaoferowania płatnych praktyk.
team_size: |
    1 - ­2 osoby. Dopuszczalna większa ilość osób w przypadku chęci przetestowania alternatywnych rozwiązań lub automatyzacji testów odporności (resilience tests).
requirements: |
    Raczej dla ambitnych studentów znających Scalę lub Javę.
project_roles: |
    Programista rozwiązania oraz osoba testująca pod kątem skalowalności i odporności.
copyrights: Niewyłączna bezpłatna licencja.
---
Obecnie panujący trend w budowaniu usług sieciowych (z ang. web services) preferuje usługi bezstanowe. W takim podejściu serwer aplikacji obsługując żądania użytkownika komunikuje się z bazą danych. Zasadniczo, przy braku mechanizmów typu “cache”, serwer aplikacji nie przechowuje stanu i każde żądanie powoduje wysłanie zapytania o dane do bazy. Takie rozwiązanie umożliwa łatwe skalowanie serwerów aplikacji ­ wystarczyb uruchomić więcej instancji i zrównoważyć obciążenie (ang. load balancing).

Skalując usługi bezstanowe zwiększamy obciążenie serwera baz danych. Wprowadzenie warstwy “cache” nie zawsze jest rozwiązaniem, w szczególności gdy to operacje zapisu generują znaczącą część obciążenia. Horyzontalne skalowanie baz danych bywa problematyczne i stawia przez wyborem dostępności lub spójności (ang. availability versus consistency, AP vs CP systems, CAP theorem).

Komunikacja przez sieć z serwerem baz danych wprowadza opóźnienia. W systemach czasu rzeczywistego (z ang. real­time), do których zaliczają się także systemy bukmacherskie rozwijane przez firmę Grand Parade, każda milisekunda się liczy.

Alternatywą na usług bezstanowych są systemy, w których serwer aplikacji przechowuje stan obiektów domenowych (z ang. domain model entities) w pamięci. Baza danych jest używana tylko aby zapewnić możliwość odbudowy stanu po restarcie aplikacji i może być uproszczona do dziennika zdarzeń (z ang. event log). Żądanie odczytu powoduje odczytanie albo odtworzenie stanu z dziennika zdarzeń tylko jeśli dane obiektu nie są jeszcze w pamięci. Żądanie powodujące modyfikacją obiektu skutkuje tylko dodaniem wpisu do dziennika zdarzeń. Takie podejście nazywa się event sourcing.

Skalując poziomo usługi stanowe poprzez uruchomienie kolejnych instancji pojawia się problem dystrybucji żądań pomiędzy instancjami (routing). Podstawową kwestią jest rozdzielenie obiektów domenowych pomiędzy instancje, aby żądania dotyczące danego obiektu trafiały do tej instancji, która ten obiekt obsługuje i może posiadać go w pamięci.

Dodatkowo, system powinien być odporny na zagrożenia takie jak awaria pojedynczego serwera, skutkująca niedostępnością jednej instancji serwera albo tymczasowe problemy w komunikacji sieciowej między instancjami, wliczając tzw. podzielenie się sieci (z ang. network partition). Wystąpienie którejkolwiek z tych sytuacji nie powinno powodować przestoju w działaniu systemu, ani naruszenia spójności danych.

Scala z modelem aktorów oraz biblioteki Akka, Akka Persistence i Akka Cluster wydają się być obiecującą bazą do budowy skalowalnych systemów typu stateful.

Zadaniem projektu jest wykonanie prototypu systemu usług stanowych w oparciu w Akkę i zaproponowanie routingu oraz rozwiązań, które stworzą system skalowalny oraz wysokiej dostępności. System powinien być spójny lub ostatecznie spójny (ang. eventually consistent).