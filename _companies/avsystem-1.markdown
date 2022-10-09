---
layout: project
permalink:
company: AVSystem
company_img:
company_desc: |
  AVSystem jest polską firmą IT z Krakowa, która tworzy produkty głównie dla branży telekomunikacyjnej oraz nowoczesnych przedsiębiorstw wykorzystujących Internet Rzeczy. AVSystem tworzy również produkty wspierające marketing z użyciem otwartych sieci WiFi oraz jest głównym partnerem technologicznym Good Looda. Jesteśmy dumni z tego, że nasze oprogramowanie jest używane na całym świecie zarówno przez małe, średnie jak i duże firmy. Naszą pasją jest tworzenie nowoczesnych rozwiązań opartych o nowoczesne technologie.
project: Aktualizator POI
project_img:
technological_stack: |
  TypeScript, front w ReactJS, reszta do ustalenia
methodology: |
  Scrum, zapewnimy Scrum Mastera
shipment_method: |
  Sprint review (z demo) po każdym sprincie, w którym będą brali udział członkowie zespołu oraz deweloperzy z zespołu Good Lood @AVSystem. Publiczny tracker zadań, do wyboru w ramach konsultacji z scrum masterem
training: |
  Na początku chcielibyśmy zorganizować szkolenie ze Scruma oraz spotkanie zapoznawcze. Możemy zorganizować 1-2 szkolenia z technologii w zależności od potrzeb członków zespołu. Będzie możliwość nauki na bieżąco oraz konsultacji bieżących zagadnień technicznych, UI/UX
tools_provided: |
  Brak
mentor: |
  Łukasz Gurdek (l.gurdek@avsystem.com)
worktime: |
  Co najmniej 10h tygodniowo; spotkania scrumowe co 2 tygodnie, konsultacje z zespołem według potrzeb
location: |
  Zdalnie, możliwość przychodzenia do biura na spotkania i okazjonalnej pracy z biura po ustaleniu (biuro: AVSystem, Radzikowskiego 47d, Kraków)
money: |
  Nie
later_employment: |
  Uproszczona rekrutacja na staż (płatny) dla wybranych osób
team_size: |
  3-4 osoby
requirements: |
  Preferowani kandydaci z doświadczeniem/zainteresowaniem podanymi technologiami, a także z własną inicjatywą/pomysłami/otwartym umysłem, gdyż projekt obejmuje fazę projektową
project_roles: |
  1x Product Owner+Developer (przewidywana rotacja w tej roli), 2-3x Developer
copyrights: |
  Open Source licencja MIT. Potrzebne podpisanie NDA
---
Centralne miejsce do zarządzania obecnością w platformach POI (e.g. Google Maps,Tripadvisor, Facebook, OpenStreetMap). Możliwość zmiany atrybutów dla danej lokalizacji w panelu admina i automatyczna ich replikacja przez API platformy.
Funkcjonalności (do ustalenia dokładny zakres i priorytety):
- Obsługiwane atrybuty: m.in. nazwa, nr telefonu, godziny otwarcia i wiele innych.
- Templating: możliwość zdefiniowania templejtów wartości dla poszczególnych platform na podstawie atrybutów bazowych.
- Customizacja: możliwość nadpisania konkretnej wartości dla konkretnej lokalizacji
dla konkretnej platformy.
- Logowanie oauthowe do platform: brak konieczności konfiguracji credentiali do API w kodzie.
- Matching istniejących wpisów w platformach i tworzenie nowych w razie konieczności.
- API do pobierania danych dot. lokalizacji dla “własnych celów”.
- Multi-tenant.
- Śledzenie zmian dokonywanych poza platformą.
- Modułowość – osobno frontend, logika dla poszczególnych platform, backend.
