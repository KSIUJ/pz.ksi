---
layout: project
permalink: 
company: IBM
company_img:
company_desc: |
    [www.ibm.pl](http://www.ibm.pl)
project: |
    High speed network interface performance tuning
project_img:
technological_stack: |
    Python or Java, shell script, Docker, Vms
methodology: |
    Agile
shipment_method: |
    Wewnętrzne repozytorium firmowe. Dostęp do dokumentacji i informacji szkoleniowych. Wsparcie mentora i zespołu pracującego w tym samym projekcie.
training:
    Dostęp do bazy szkoleń online i platform e-learningowych. Nauka na bieżąco, w razie potrzeb organizowane będą niezbędne szkolenia
tools_provided: |
    Firmowy laptop (Lenovo W540 lub podobny), zewnętrzny monitor. Zapewniony dostęp do potrzebnej infrastruktury w chmurze
mentor: |
    Tomasz Sekman
worktime: |
    ok 20h/tygodniowo przez 3 miesiące. Grafik elastycznie ustalany z mentorem.
location: |
    Praca w biurze z możliwością pracy zdalnej.
money: |
    Bezpłatne praktyki
later_employment: |
    Tak
team_size: |
    2 osoby
requirements: |
    Podstawowa znajomość wszystkich technologii lub ich istotnego podzbioru z wymienionych w stacku technologicznym. Znajomość języka angielskiego i doświadczenie w pracy w grupie będzie dodatkowym atutem. Nastawienie na rozwój i zdobywanie nowych umiejętności.

project_roles: |
    Back-end developer, Front-end developer, Tester. 
copyrights:
---
Develop a test suite which will evaluate network performance and execute the evaluation for multiple configurations.

For measurement the program should use both iperf and real application (for example iSCSI, NVMe-oF, db engine internal comm protocol). Test progam (server and client) will be running on bare-metal, VM and docker container. 

Another aspect is the test network topology (one sender and one receiver, one sender and multiple receivers, multiple senders and multiple receivers). The suite can be written in Python or Java.

Once the suite is prepared the student(s) will evaluate the network performance for multiple configurations - bonding, VLANs, bridges on top of VLANs and bonds. Selection of configuration items: bond mode, hashing type, number and length of rx/tx queues, DCA settings, number of CPU cores, Spectre/Meltdown fixes.
