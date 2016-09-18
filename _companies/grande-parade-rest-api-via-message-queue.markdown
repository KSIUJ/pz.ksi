---
layout: project
ordering: 13
company: Grande Parade
company_img:
company_desc:
project: REST API via message queue
project_img:
technological_stack: |
    - Scala
    - Kafka
    - Akka HTTP
    - Akka Actors
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
Microservices architecture scales well but there are certain aspects of it that need careful consideration, like REST API. By default services provide stateless implementation calling database every time user wants to access data, but not all communication is done synchronously, when the same aggregate (Domain Driven Design methodology) is accessed synchronously and asynchronously there are problems with mutable state.

This project should focus on possibility to access data in asynchronous way when called by REST API.

In details: there are two services

- gateway service handling REST API
- business logic service handling only messages (i.e. Kafka)

When a user calls REST API of the system, the gateway service sends a message via queue to the business logic service and waits (in a non­blocking way) for response, whenever it gets the response it sends it back to the REST API user. The system should be able to handle validation of provided data and timeouts. It should be able to handle timeouts and track requests.