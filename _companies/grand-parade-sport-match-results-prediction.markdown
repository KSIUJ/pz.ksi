---
layout: project
ordering: 12
company: Grand Parade
company_img:
company_desc:
project: Sport match results prediction
project_img:
technological_stack: Scala
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
    1­ - 2 osoby. Dopuszczalna większa ilość osób w przypadku chęci przetestowania alternatywnych rozwiązań lub automatyzacji testów odporności (resilience tests).
requirements: |
    Raczej dla ambitnych studentów znających Scalę lub Javę.
project_roles: |
    Programista rozwiązania oraz osoba testująca pod kątem skalowalności i odporności.
copyrights: Niewyłączna bezpłatna licencja.
---
Analysis of previous games can be used to estimate probability of certain games' statistics, i.e. based on Real Madrid's and Bayern's performance this season, there is a 75% chance of Real winning the next game between them. The system should be able to aggregate and collect statistics fro various sources (feeds, websites, manual input) and based on those (including quality of statistics) calculate the probable outcome of a game. The most important part of this system are algorithms which calculate probability of a team winning the game. There should be a way to add/remove statistics from the calculation, adding modifiers to the calculations (i.e. Real's performance will not be best because Ronaldo is not playing in the next game).

Big Data may be used but not a necessity.

Potential extension might include real­time estimation with streaming.

There are two potential directions for this project:
- client side, betting helper
- bookmaker side, prices adjustments