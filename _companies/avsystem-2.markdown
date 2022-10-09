---
layout: project
permalink:
company: AVSystem
company_img:
company_desc: |
  AVSystem jest polską firmą IT z Krakowa, która tworzy produkty głównie dla branży telekomunikacyjnej oraz nowoczesnych przedsiębiorstw wykorzystujących Internet Rzeczy. AVSystem tworzy również produkty wspierające marketing z użyciem otwartych sieci WiFi oraz jest głównym partnerem technologicznym Good Looda. Jesteśmy dumni z tego, że nasze oprogramowanie jest używane na całym świecie zarówno przez małe, średnie jak i duże firmy. Naszą pasją jest tworzenie nowoczesnych rozwiązań opartych o nowoczesne technologie.
project: Wsparcie M5StickC-Plus w projekcie Zephyr RTOS
project_img:
technological_stack: |
  Zephyr RTOS, Anjay LwM2M library, M5StickC-Plus, Język programowania: C, reszta do ustalenia
methodology: |
  Kanban i dwutygodniowe iteracje
shipment_method: |
  Iteration review (z demo) po każdym sprincie, w którym będą brali udział członkowie zespołu oraz deweloperzy z zespołu Embedded @AVSystem. Publiczny tracker zadań, do wyboru w ramach konsultacji z opiekunem projektu po stronie AVSystem
training: |
  Na początku chcielibyśmy zorganizować szkolenie z metodyki pracy oraz spotkanie zapoznawcze. Możemy zorganizować 1-2 szkolenia z technologii w zależności od potrzeb członków zespołu. Nędzie możliwość nauki na bieżąco oraz konsultacji bieżących zagadnień technicznych
tools_provided: |
  Zapewniamy zestawy developerskie M5StickC-Plus
mentor: |
  Mieszko Mieruński (m.mierunski@avsystem.com)
worktime: |
  Co najmniej 4h tygodniowo; spotkania co 2 tygodnie, konsultacje z zespołem według potrzeb
location: |
  Zdalnie, możliwość przychodzenia do biura na spotkania i okazjonalnej pracy z biura po ustaleniu (biuro: AVSystem, Radzikowskiego 47d, Kraków)
money: |
  Nie
later_employment: |
  Uproszczona rekrutacja na staż (płatny) dla wybranych osób
team_size: |
  2-4 osoby
requirements: |
  Preferowani kandydaci z doświadczeniem/zainteresowaniem podanymi technologiami, w tym embedded i znajomością C
project_roles: |
  1x Product Owner+Developer, 1-3x Developer
copyrights: |
  Open Source licencja Apache-2.0. Potrzebne podpisanie NDA
---
Wsparcie zestawu developerskiego M5StickC-Plus [(1)](https://shop.m5stack.com/products/m5stickc-plus-esp32-pico-mini-iot-development-kit) opartego o moduł ESP32-PICO w projekcie Zephyr RTOS [(2)](https://github.com/zephyrproject-rtos/zephyr) razem z obsługą protokołu LwM2M przy wykorzystaniu modułu Anjay-zephyr [(3)](https://github.com/AVSystem/Anjay-zephyr). Projekt zakłada dodanie obsługi sensorów a następnie przedstawienie ich jako obiektów IPSO.
Funkcjonalności (do ustalenia dokładny zakres i priorytety):
- Implementacja driverów dla peryferiów:
	- MPU6886,
	- 1.14 inch, 135*240 Colorful TFT LCD, ST7789v2,
	- AXP192.
- Implementacja trybu low power.
- Dodanie odpowiednich obiektów LwM2M.
- Umieszczenie kodu w repozytorium Zephyr Project.
- Implementacja przykładu w projekcie Anjay-zephyr-client.
