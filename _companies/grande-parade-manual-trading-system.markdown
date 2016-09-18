---
layout: project
ordering: 14
company: Grande Parade
company_img:
company_desc:
project: Manual trading system
project_img:
technological_stack: |
    - Scala
    - Kafka
    - Akka HTTP
methodology: Dowolna
shipment_method: |
    Sugeruje się udostępnienie repozytorium Git. Pytania drogą mailową lub na konsultacjach w siedzibie firmy Grand Parade, raz w tygodniu 1h.
training: Konsultacje z pracownikami firmy.
tools_provided: Nie.
mentor: Michał Łosiewicz (michal.losiewicz@grandparade.co.uk)
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
When a sporting event takes place there is no "automatic" data feed about what happens there (were there goals or cards?, etc.), there is an actual person there watching the game and providing data about what happens in the match. This project should focus on providing a "console" for a person like that to fill data about a game taking place. Based on a set of rules and supported markets (i.e. match winner ­who wins the game, first goalscorer ­ who scored the first goal) it should send data via a defined output (Kafka, HTTP any plugged in) about what happened in the game.

Requirements:
- ability to add new sports and markets to the system (football should be done first with at least 2­ - 3
- markets and adding new content should be possible and easy, i.e. new type class or configuration)
- incidents in the game (scored goal, red card) should result markets (i.e. Ronaldo got a red card means he will not score)
- there should be a possibility to add new outputs with relative ease (Alpakka project?)