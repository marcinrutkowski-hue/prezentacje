# Prezka B2B - Sessions

## Sesja 1 — ZAMKNIĘTA

### Co zrobiono
- Zbudowano strukturę 15 slajdów z pełnym flow i tekstem narracji
- Ustalono format: cold mailing, mało tekstu na slajdach, dużo wizualizacji
- Usunięto znaczniki czasu i blok nagłówkowy z narracji

---

## Sesja 2 — ZAMKNIĘTA

### Cel
Research merce.com — zebranie liczb, social proof i case studies do narracji.

### Co zrobiono
- Przeszukano bazę wiedzy merce-marketing (RAG)
- Pobrano i przeczytano PDF: "Jak skutecznie wdrożyć platformę eCommerce B2B" (19 str.)
- Wyciągnięto sitemapę merce.com (Nuxt/Vue.js — JS-rendered, WebFetch zwraca tylko CSS)
- Przeszukano Perplexity dla każdego z 16 case studies z merce.com/realizacje
- Drugie przejście Perplexity po każdym case study z osobna — wyciągnięto szczegóły

### Kluczowe znaleziska

**Liczby twarde — gotowe do slajdów:**

| Liczba | Kontekst | Klient |
|--------|---------|--------|
| **+300% zamówień B2B** | Migracja z ERP na merce | DARCO |
| **+25% rok 2** (~15 000 zamów./rok) | Wzrost po stabilizacji | DARCO |
| **6 tygodni** wdrożenia | Integracja Vendo ERP SOAP | HAYNE |
| **+100% sprzedaży** rok 1 | Replatforming z Magento | OCHNIK |
| **+151% TOP3** / **+126% TOP10** | SEO Raccoon Storefront | OCHNIK |
| **+309% ruchu nonbrand** | SEO po wdrożeniu | OCHNIK |
| **-80% TTFB** | PageSpeed Raccoon | OCHNIK |
| **2x konwersja** w 2 tyg. | Dynamiczne feedy marketplace | marketplace |
| dziesiątki godz./mies. oszczędności | Automatyzacja feedów | marketplace |
| **5–25x** CLV vs. nowy klient | Usługi komplementarne | HAYNE |
| **37% mniej** naruszeń danych | RBAC wg Global Ecom Security 2021 | HAYNE |
| **1,2 mld zł** transakcji/rok | Skala platformy | merce.com |
| **75 000 SKU**, 13 oddziałów, 200+ osób | Skala B2B RESPOL | RESPOL |
| **73%** kupujących B2B to millenialsi | Rynek USA | CMO merce, Merit Report |
| **82%** firm oczekuje pełnej automatyzacji B2B | Rynek CEE | Forrester 2023 |

**Cytaty klientów (potwierdzone):**
- "Zyskaliśmy pełne spectrum eCommerce w jednym miejscu." (migracja z Magento)
- "Platforma jest intuicyjna, klienci samodzielnie składają zamówienia. Słyszymy, że to NR 1 w branży."
- "Udostępnienie stanów z salonów przyniosło widoczny wzrost sprzedaży online." — Dawid Szrek, Manager e-commerce & IT, OCHNIK

**Uwaga metodyczna:**
- merce.com = Nuxt/Vue.js, JS-rendered — WebFetch zwraca tylko CSS na wszystkich podstronach
- Perplexity wyciąga co Google zaindeksował ze snippetów — może nie mieć pełnej treści
- DARCO pochodzi z bloga merce, nie z case study na /realizacje
- BIALCON i W.KRUK — potwierdzeni jako klienci, brak pub. danych liczbowych

---

## Sesja 3 — ZAMKNIĘTA

### Cel
Głębszy research — 24 URLe dostarczone przez użytkownika (blogi + realizacje szczegółowe).

### Co zrobiono
Perplexity search dla wszystkich 24 URLi w 3 batchach. Wyciągnięte dane:

**Nowe dane — DARCO:**
- **600 aktywnych klientów B2B** na platformie
- **50 nowych klientów B2B** w ciągu kilku miesięcy od wdrożenia
- Zamówienia 24/7, realizacja w 48h
- Cytaty: Tomasz Domaradzki (CEO) + Łukasz Duda — potwierdzone, brzmienie do weryfikacji w /darco-podejscie-user-oriented

**Nowe dane — Arpex:**
- ERP: Comarch ERP XL z integracją
- Platforma wielojęzyczna
- Marketing bez angażowania IT — autonomia departamentu
- Aktualizacje bez przestojów ERP
- b2b.arpex.com.pl

**Nowe dane — Rosa Plast:**
- Automatyczna generacja TDS PDF per produkt
- Integracja Mapbox (lokalizacja partnerów)
- Multi-currency B2B
- Kanały: B2B + B2C

**Nowe dane — SARA Workwear (~500 pracowników):**
- ERP: Streamsoft Prestiż, integracja dwukierunkowa
- 3 poziomy cenowe dla grup klientów
- Oddzielne domeny B2B i B2C
- Platforma wielojęzyczna
- Problem ERP jednowariantowy → rozwiązanie: masowe dodawanie wariantów

**Nowe dane — RESPOL:**
- 30+ lat na rynku (od 1989)
- Efekty: przyspieszenie logistyki, wzrost satysfakcji klientów
- Asseco SAFO przez Web Service

**Nowe dane — Grupa Play / 3S Data Center:**
- Etap 1 (Q2/Q3 2023): Autoprovisionig VEEAM
- Etap 2 (2024): Virtual Data Center (VMware)
- Etap 3 (2024): Obszar partnerski (Microsoft 365)
- Zero manualnej pracy — pełna automatyzacja API

**Nowe dane — OCHNIK InPost Pay:**
- merce stworzył plugin InPost Pay jako jeden z pierwszych na rynku PL
- Ochnik = pilot → teraz standard wdrożeń merce
- Uproszczenie checkout → wzrost konwersji mobilnej

**Nowe dane — New Balance:**
- Complete the Look: cross-sell stylizacji, API endpoints, szablony, direct add-to-cart
- Afiliacja: performance marketing, płatność za skuteczne transakcje, eliminacja fraudu → standardowy moduł merce

**Nowy cytat z bloga:**
- Paweł Szewczyk: platforma przenosi procesy z ERP do eCommerce → redukcja licencji ERP per user
- Szacunek rynkowy: 20–40% ogólny wzrost sprzedaży B2B po wdrożeniu platformy eCommerce

---

## Sesja 4 — ZAMKNIĘTA

### Cel
Przebudowa planu prezentacji — wersja PDF (cold mailing bez prezentera).

### Co zrobiono
- Ocena poprzedniej struktury (15 slajdów z narratorem) pod kątem czytelności w PDF
- Zidentyfikowane problemy: tekst był w narracji, nie na slajdach; case studies w jednej tabeli; brak slajdu "kim jest merce"
- Przebudowano plan na 16 slajdów — każdy slajd samonośny
- Przepisano narrację: nagłówki jako tezy, tekst pomocniczy na slajdzie, liczby i cytaty widoczne w PDF

### Kluczowe decyzje strukturalne
- **S6 nowy:** "Kim jest merce" — 4 liczby platformy + lista klientów (odbiorca cold mailingu nie zna merce)
- **S7–S10:** case studies rozbite na osobne slajdy (HAYNE, DARCO, RESPOL) — zamiast tabeli zbiorczej
- **S11:** cytat Dawida Szreka (OCHNIK) wbudowany w slajd "ERP zostaje"
- **S12:** funkcje B2B jako tabela z przykładami firm
- **S13:** automatyzacja — 3 konkretne przykłady (marketplace, Grupa Play, Arpex)
- **S14:** "Dwie niezależne decyzje" — oś czasu jako główny element wizualny
- **S15:** podsumowanie z 3 liczbami + statystyka millennialsi
- **S16:** CTA — 3 pytania otwierające rozmowę zamiast oferty

### Numery slajdów (wersja PDF)
| S | Temat | Dominujący element |
|---|-------|--------------------|
| 1 | Hook | pytanie otwierające |
| 2 | Mit | przekreślony cytat |
| 3 | Koszt stania w miejscu | lista + 82% Forrester |
| 4 | Fałszywy dylemat | tabela 2 złych opcji |
| 5 | Trzecia droga | schemat 3-warstwowy |
| 6 | Kim jest merce | 4 liczby + logotypy klientów |
| 7 | 6 metod integracji | tabela metod + HAYNE anchor |
| 8 | Case study: HAYNE | 6 tygodni |
| 9 | Case study: DARCO | +300% zamówień B2B |
| 10 | Case study: RESPOL | 75 000 SKU · 13 oddziałów |
| 11 | ERP zostaje + cytat | schemat + Dawid Szrek |
| 12 | Funkcje B2B | tabela z przykładami |
| 13 | Automatyzacja | 3 bloki z firmami |
| 14 | Dwie decyzje | oś czasu |
| 15 | Co zyskujesz | 3 liczby + millennialsi |
| 16 | CTA | 3 pytania + kontakt |

---

## Sesja 5 — OTWARTA

### Do zrobienia
- [ ] Weryfikacja cytatów DARCO: Tomasz Domaradzki + Łukasz Duda — wejść na blog /darco-podejscie-user-oriented i wyciągnąć dokładne brzmienie
- [ ] Rozważyć: dodać OCHNIK +100% jako 4. case study (S10b) lub zostawić go tylko w S6 (lista klientów)
- [ ] Design brief: przygotować wskazówki kolorystyczne i layoutowe dla każdego slajdu
- [ ] Zapytać team merce: czas wdrożenia RESPOL i BIALCON, % zamówień B2B bez udziału handlowca

### Otwarte pytania
- DARCO +300% — czy komunikować jako "bez wymiany ERP" czy "zamiast ERP"? Weryfikować przekaz
- OCHNIK — replatforming z Magento (nie typowe "bez ERP") — czy umieszczać w głównym flow case studies?
- Czy SARA lub Arpex pasują lepiej do S13 (automatyzacja) niż S12 (funkcje)?
- Slajd S6 "kim jest merce" — czy lista klientów jako logotypy czy tekst?
