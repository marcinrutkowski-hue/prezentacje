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
- "Platforma jest intuicyjna, klienci samodzielnie skladają zamówienia. Słyszymy, że to NR 1 w branży."
- "Udostępnienie stanów z salonów przyniosło widoczny wzrost sprzedaży online." — Dawid Szrek, Manager e-commerce & IT, OCHNIK

**Uwaga metodyczna:**
- merce.com = Nuxt/Vue.js, JS-rendered — WebFetch zwraca tylko CSS na wszystkich podstronach
- Perplexity wyciąga co Google zaindeksował ze snippetów — może nie mieć pełnej treści
- DARCO pochodzi z bloga merce, nie z case study na /realizacje
- BIALCON i W.KRUK — potwierdzeni jako klienci, brak pub. danych liczbowych

---

## Sesja 3 — OTWARTA

### Do zrobienia
- [ ] Wbudować liczby do narracji — priorytet: S7 (case studies) i S14 (co zyskujesz)
- [ ] Wybrać 3–4 case studies do S7: DARCO (+300%), HAYNE (6 tyg.), RESPOL (skala), OCHNIK (+100%)
- [ ] Dodać statystykę rynkową do S2 lub S3: 82% firm oczekuje automatyzacji B2B
- [ ] Rozważyć: cytat Dawida Szreka jako osobny slajd lub element S7
- [ ] Zapytać team merce: czas wdrożenia RESPOL i BIALCON, dane zamówień bez handlowca

### Otwarte pytania
- DARCO +300% — czy to B2B bez wymiany ERP, czy migracja z ERP? Weryfikować przekaz
- OCHNIK +100% — to replatforming z Magento (nie typowe "bez ERP") — jak to wpleść?
- Który case study jest najbliższy profilowi odbiorcy cold mailingu (producent/dystrybutor B2B)?
- Czy RESPOL (hurtownia HVAC, 75k SKU, 13 oddziałów) nie jest lepszym przykładem niż OCHNIK dla B2B hook?
