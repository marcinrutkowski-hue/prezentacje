# Kontekst prezentacji — Sprzedaż B2B online bez wymiany ERP

## Metadane

- **Projekt:** Prezentacja B2B dla merce.com
- **Temat:** Jak rozwijać sprzedaż online B2B bez ingerencji w ERP
- **Hook:** "Uniezależnij się od ERP" — ale prawdziwy strach to destabilizacja tego co działa
- **Odbiorcy:** CEO, Head of Sales, CTO / IT Director firm produkcyjnych i dystrybucyjnych B2B
- **Format:** Prezentacja wysyłana w cold mailingu — odbiorca czyta PDF samodzielnie, bez prezentera. Każdy slajd musi być samonośny.
- **Wersja narracji:** PDF (v2) — 16 slajdów, tekst i liczby widoczne na slajdach

---

## Teza główna

Firmy B2B nie odkładają modernizacji sprzedaży przez brak budżetu.
Odkładają przez strach przed destabilizacją działającej infrastruktury IT.

**Prawdziwy ból:** Nie "ERP jest przestarzały" — tylko "ERP działa i boimy się go ruszyć."

**Odpowiedź merce:** Nie wymieniamy ERP. Dokładamy warstwę commerce nad nim.

---

## Dylemat "big bang"

Firmy B2B stoją przed pozornym wyborem:

1. **Wymienić ERP** → projekt 12–18 miesięcy, 100–500k PLN, ryzyko operacyjne
2. **Czekać** → brak kanału online, ręczna obsługa zamówień, blokada wzrostu

**Trzecia droga:** warstwa commerce nad istniejącym ERP — to właśnie robi merce.

---

## Koszt status quo

- Ręczne przepisywanie danych między systemami
- Rozbieżności w stanach magazynowych
- Opóźnienia w realizacji zamówień
- Handlowcy jako operatorzy excela zamiast sprzedawcy
- Blokada skalowania sprzedaży online

---

## Jak merce rozwiązuje problem

### merceLayer — integracja bez wymiany
- **6 metod integracji:** REST API, SOAP, database views, procedury składowane, pliki, webhooks
- Dostosowujemy się do infrastruktury klienta — nie odwrotnie
- ERP pozostaje źródłem prawdy — zero zmian w pracy zespołu
- Przeniesienie procesów sprzedażowych z ERP do eCommerce → redukcja licencji ERP per user

### Oszczędność vs. migracja ERP
- **Czas:** tygodnie zamiast 12–18 miesięcy
- **Koszt:** oszczędność 100–500k PLN na samej migracji ERP

---

## Kluczowe komponenty merce

| Komponent | Rola |
|-----------|------|
| **merceLayer** | Integracja z ERP/PIM/CRM przez gotowe konektory lub open API |
| **merceLinker** | Marketplace B2B |
| **merceApp** | Kanał mobilny dla handlowców i klientów |
| **Headless storefront (Raccoon)** | API-first, niezależny od backendu, SSR, MPA/SPA hybrid |

---

## Funkcje B2B out-of-the-box

- Customer-specific pricing (indywidualne cenniki)
- Rabaty i dopłaty produktowe
- Zarządzanie resztówkami magazynowymi
- Hierarchie ról i uprawnień (RBAC) po stronie klienta
- Workflow akceptacji zamówień (approval flows)
- Budżety zakupowe
- Obsługa RFQ i quoting z AI
- Masowe dodawanie wariantów do koszyka (B2B)

---

## LICZBY PLATFORMY (źródło: merce.com)

| Liczba | Co oznacza |
|--------|-----------|
| **1,2 mld zł** | wartość transakcji przetwarzanych rocznie |
| **2000** | zmian platformy rocznie (Continuous Integration) |
| **90+** | ekspertów (analiza, wdrożenie, rozwój) |
| **15+ lat** | doświadczenia w transformacji cyfrowej |
| **5 lat** | średni czas żywotności platform (argument za CI) |

---

## CASE STUDIES — SZCZEGÓŁY

### DARCO — B2B + D2C (instalacje grzewcze i wentylacja)
- **+300% zamówień B2B** po wdrożeniu
- **+25% wzrost** w kolejnym roku (~15 000 zamówień rocznie)
- **600 aktywnych klientów B2B** na platformie
- **50 nowych klientów B2B** w ciągu kilku miesięcy od startu
- Zamówienia dostępne **24/7**, realizacja w **48h**
- Bonus: uruchomienie kanału D2C — wcześniej niemożliwe bez salonów fizycznych
- Monitoring trendów konsumenckich bez budowania infrastruktury stacjonarnej
- Cytaty: Tomasz Domaradzki (CEO) + Łukasz Duda — potwierdzone, dokładne brzmienie: blog /darco-podejscie-user-oriented
- Źródło: merce.com/blog/cyfryzacja-uwalnia-uspione-moce-firm-b2b + merce.com/blog/darco-podejscie-user-oriented

### HAYNE — integracja z Vendo ERP (B2B optyka)
- **ERP:** Vendo, integracja przez SOAP
- **Czas wdrożenia: 6 tygodni**
- Pełna synchronizacja: stany, cenniki, zdjęcia, usługi specjalne
- Automatyczne wystawianie faktur, księgowanie, statusy płatności w eCommerce
- Reklamacje i zwroty: pełna automatyzacja — zgłoszenia z eCommerce do ERP i z powrotem
- Synchronizacja klientów B2B i pracowników składających zamówienia w imieniu firm
- Dashboardy real-time, monitoring KPI
- RBAC: handlowcy samodzielnie nadają uprawnienia klientom w grupach rabatowych
- CLV: **5–25x taniej** sprzedać obecnemu klientowi niż pozyskać nowego
- Ocena merce: "modelowy przykład złożonej integracji B2B"

### RESPOL — audyt i platforma B2B (HVAC hurtownia)
- **Firma:** rodzinna hurtownia od 1989 r., 30+ lat na rynku
- **Skala:** 75 000+ produktów, 13 oddziałów, 200+ osób
- **ERP:** Asseco SAFO, integracja przez Web Service
- Klienci B2B: deweloperzy, instalatorzy, architekci, instytucje publiczne
- Wdrożone: panel B2B z widokiem stanów sieciowych (wszystkie oddziały), statusy zamówień, indywidualne cenniki
- Wyzwanie: brak centralnego magazynu przy 75 tys. SKU — rozwiązane przez synchronizację stanów sieciowych
- Efekty: przyspieszenie logistyki, wzrost satysfakcji klientów B2B
- Metodyka wymagań: MoSCoW (warsztaty, mapowanie procesów, KPI)

### OCHNIK — replatforming + omnichannel (fashion 120+ salonów)
- **+100% sprzedaży** w roku 1 po replatformingu z Magento
- Kolejne lata: kilkukrotne wzrosty obrotów
- **+151% widoczności w TOP3** (styczeń 2023 – styczeń 2024)
- **+126% widoczności w TOP10**
- **+309% ruchu nonbrand**
- **-80% TTFB** po wdrożeniu Raccoon Storefront (SSR, lazy loading, MPA/SPA hybrid)
- PageSpeed: 90+/100 punktów
- Ship-from-store: 120+ salonów jako huby fulfillment
- InPost Pay: merce stworzył plugin jako jeden z pierwszych na rynku PL — teraz standard wdrożeń; uproszczenie checkout = wzrost konwersji mobilnej
- Cytat: "Udostępnienie stanów z salonów przyniosło widoczny wzrost sprzedaży online." — Dawid Szrek, Manager e-commerce & IT, OCHNIK
- SEO realizowane z agencją Altavia Kamikaze + K2
- ERP w narracji: LSI, integracja przez widoki i adaptery

### Arpex — B2B (dystrybutor zabawek, b2b.arpex.com.pl)
- **ERP:** Comarch ERP XL, integracja
- Platforma wielojęzyczna (multilingual)
- Zarządzanie marketingiem bez angażowania IT — autonomia dla zespołu marketingowego
- Aktualizacje platformy bez przestojów ERP
- Źródło: merce.com/blog/nowa-platforma-b2b-dla-arpex

### Rosa Plast — B2B + B2C (profile PVC + filamenty 3D)
- Automatyczna generacja TDS PDF dla każdego produktu
- Integracja Mapbox (lokalizacja dystrybutorów/partnerów)
- Multi-currency B2B
- Platforma obsługuje zarówno kanał B2B jak i B2C

### SARA Workwear — B2B + B2C (odzież robocza, ~500 pracowników, od 1992)
- **ERP:** Streamsoft Prestiż, integracja dwukierunkowa
- **3 poziomy cenowe** dla różnych grup klientów
- Oddzielne domeny B2B i B2C
- Platforma wielojęzyczna
- Problem: ERP jednowariantowy → duplikaty w katalogu, przeładowanie wyników
- Rozwiązanie: grupowanie wg atrybutów, **masowe dodawanie wariantów do koszyka**
- Wyniki: zwiększona liczba produktów w koszyku, poprawa konwersji, spójne UX B2B

### Grupa Play / 3S Data Center — automatyzacja cloud B2B
- **Etap 1 (Q2/Q3 2023):** Autoprovisionig usług VEEAM — automatyzacja rejestracji i obsługi zamówień
- **Etap 2 (2024):** Obsługa usług i rozliczeń Virtual Data Center (VMware)
- **Etap 3 (2024):** Rozwój obszaru partnerskiego na platformie (Microsoft 365)
- Zero manualnej pracy przy konfiguracji środowisk — API-driven
- Skrócenie czasu realizacji + eliminacja błędów ręcznych
- 3S Data Center = Platynowy Partner VEEAM

### Marketplace — dynamiczne feedy produktowe
- **2x wyższa konwersja** produktów promo w 2 tygodnie kampanii
- **Dziesiątki godzin/mies.** oszczędności na konfiguracji feedów
- Elastyczna "gra cenowa" + sezonowe pozycjonowanie przy niższym koszcie kliknięcia

### New Balance Polska — omnichannel
- Aplikacje mobilne iOS + Android (merceApp)
- **Spartavity:** program lojalnościowy — punkty online i offline, wymiana na vouchery
- **Afiliacja:** precyzyjna weryfikacja zamówień, śledzenie kliknięć i konwersji, rozliczanie prowizji w real-time; płatność tylko za skuteczne transakcje; eliminacja fraudu → standardowy moduł merce
- **Complete the Look:** cross-sell stylizacji — nowe API endpoints, szablony zestawów, direct add-to-cart; wzrost wartości koszyka

---

## CYTATY KLIENTÓW (potwierdzone)

> "Przenosząc sprzedaż z Magento na merce, zyskaliśmy pełne spectrum eCommerce w jednym miejscu."

> "Platforma jest intuicyjna, klienci samodzielnie składają zamówienia. Słyszymy, że to NR 1 w branży."

> "Udostępnienie stanów z salonów przyniosło widoczny wzrost sprzedaży online."
> — Dawid Szrek, Manager e-commerce & IT, OCHNIK

> [Tomasz Domaradzki, DARCO — CEO quote potwierdzony, dokładne brzmienie: blog /darco-podejscie-user-oriented]

> [Łukasz Duda, DARCO — quote potwierdzony, dokładne brzmienie: blog /darco-podejscie-user-oriented]

---

## STATYSTYKI RYNKOWE

> "73% specjalistów dokonujących zakupów B2B w USA to millenialsi (20–35 lat)."
> — Paweł Szewczyk, CMO merce (źródło: Merit Millennial B2B Report)

- 82% firm oczekuje pełnej automatyzacji zakupów B2B (Forrester 2023)
- 60% firm w CEE planuje wzrost wydatków na chmurę (Forrester 2023)
- RBAC redukuje ryzyko naruszeń danych o 37% (Global Ecommerce Security Report 2021)
- Ogólny szacunek: 20–40% wzrost sprzedaży B2B po wdrożeniu platformy eCommerce

---

## RANKING — NAJSILNIEJSZE ARGUMENTY DO SLAJDÓW

1. **DARCO: +300% zamówień B2B** — bez wymiany ERP, 600 aktywnych klientów
2. **HAYNE: 6 tygodni** — legacy ERP Vendo SOAP, bez wymiany, pełna automatyzacja
3. **OCHNIK: +100% sprzedaży** rok 1 + SEO TOP3 +151% + InPost Pay (cytat Dawida Szreka)
4. **RESPOL: 75 000 SKU, 13 oddziałów** — skala złożoności B2B
5. **1,2 mld zł** transakcji rocznie — skala zaufania platformy
6. **Cytat Dawida Szreka** — real person, real quote, na slajdzie
7. **2x konwersja** marketplace w 2 tygodnie
8. **Grupa Play:** zero manualnej pracy — cloud B2B autoprovisionig
9. **82% firm** oczekuje automatyzacji (Forrester) — statystyka otwierająca S3

---

## PEŁNA LISTA KLIENTÓW

OCHNIK, HAYNE, DARCO, BIALCON (70 salonów, Hermes SQL), RESPOL (HVAC, Asseco SAFO),
New Balance Polska, SARA Workwear, W.KRUK, Grupa Play (3S Data Center), HENDI, Arpex, Rosa Plast, 51015

---

## DANE DO UZUPEŁNIENIA (zapytać team merce)

| Metryka | Skąd wziąć |
|---------|-----------|
| Czas wdrożenia RESPOL, BIALCON | Dane wewnętrzne |
| % zamówień B2B bez udziału handlowca po wdrożeniu | OMS analytics |
| ROI z integracji merce vs. własna integracja punktowa | Analiza TCO |
| Wyniki DARCO rok 3+ | Klient |
| Dokładne cytaty Tomasz Domaradzki + Łukasz Duda (DARCO) | Blog /darco-podejscie-user-oriented |
| ERP klienta w case study OCHNIK | Potwierdzić: LSI Software? |

---

## UWAGI METODYCZNE

- merce.com = Nuxt/Vue.js, JS-rendered — WebFetch zwraca tylko CSS na wszystkich podstronach
- Blog merce = Ghost CMS (mercecom.ghost.io) — server-side rendered, Perplexity może indeksować
- DARCO pochodzi z bloga merce, nie z /realizacje — ważne przy cytowaniu
- BIALCON i W.KRUK — potwierdzeni jako klienci, brak pub. danych liczbowych
- Perplexity = Google snippets — może nie mieć pełnej treści artykułów
