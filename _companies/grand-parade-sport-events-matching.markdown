---
layout: project
ordering: 15
company: Grand Parade
company_img:
company_desc:
project: Sport events matching
project_img:
technological_stack: |
    - Scala
    Depending on solution:
    - Frameworks for HTTP access: Akka HTTP, Spray, Play Framework?
    - Text Search Engine: Elasticsearch
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
    Temat nie jest prosty, problematyka jest szeroka. Raczej dla ambitnych studentów ostatnich lat, już znających Scalę lub Javę oraz zagadnienia sieciowe.
project_roles: |
    Programista rozwiązania oraz osoba testująca pod kątem skalowalności i odporności.
copyrights: Niewyłączna bezpłatna licencja.
---
There are multiple feeds serving data about sport events. Each feed has its own specifics regarding names of the events and metadata it sends along with it (participants, competition etc.). The project's focus is to have a single system which based on user input is able to "learn" how to match events from different feeds.

Example:
There is a match between Liverpool and Manchester Utd taking place. Two feeds serve markets for this match, one of them names the event: "Liverpool vs. Man Utd." the second one ­"Liverpool v Manchester United", the system should mark the events as potentially matching and notify the user about potential match. When the user accepts the matching, the system should be able to match all future events from feed one where Manchester United (Man. Utd.) plays with another team to feed two matches with (Manchester United).