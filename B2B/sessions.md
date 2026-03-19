# Prezka B2B - Sessions

## Sesja 1 — ZAMKNIĘTA

### Co zrobiono — sesja 1
- Zbudowano strukturę 15 slajdów z pełnym flow i tekstem narracji
- Ustalono format: cold mailing, mało tekstu na slajdach, dużo wizualizacji
- Usunięto znaczniki czasu i blok nagłówkowy z narracji

### Stan po sesji 1
- 15 slajdów z tekstem narracyjnym gotowych — status: do opracowania
- Brak liczb i social proof — zaplanowano research

---

## Sesja 2 — ZAMKNIĘTA

### Cel sesji 2
Research merce.com — zebranie liczb, social proof i case studies do narracji.

### Co zrobiono — sesja 2
- Przeszukano bazę wiedzy merce-marketing (RAG)
- Pobrano i przeczytano PDF poradnik: "Jak skutecznie wdrożyć platformę eCommerce B2B" (19 str.)
- Wyciągnięto sitemapę merce.com — strona JS-rendered (Nuxt), WebFetch zwraca tylko CSS
- Przeszukano Perplexity dla każdego z 16 case studies z merce.com/realizacje
- Zidentyfikowano pełną listę klientów i dostępne liczby

### Kluczowe znaleziska — sesja 2

**Liczby twarde do slajdów:**

| Liczba | Kontekst | Klient |
|--------|---------|--------|
| +100% sprzedaży w roku 1 | Replatforming z Magento na merce | OCHNIK |
| 6 tygodni wdrożenia | Integracja Vendo ERP przez SOAP | HAYNE |
| 2x wyższa konwersja w 2 tyg. | Dynamiczne feedy produktowe | marketplace |
| Dziesiątki godzin/mies. oszczędności | Automatyzacja feedów | marketplace |
| 1,2 mld zł transakcji rocznie | Skala platformy | merce.com |
| 120+ salonów jako huby fulfillment | Ship-from-store | OCHNIK |
| 5-25x taniej sprzedać obecnemu klientowi | Usługi komplementarne, CLV | HAYNE |
| 73% kupujących B2B w USA to millenialsi | Rynek, wymusza cyfryzację | CMO merce, PDF |
| 90+ ekspertów | Zespół merce | merce.com |
| 2000 zmian platformy rocznie | Continuous Integration | merce.com |
| 15+ lat doświadczenia | Firma merce | merce.com |
| 5 lat średni czas żywotności platform | Argument za CI | PDF poradnik |

**Cytaty klientów (potwierdzone):**
- "Zyskaliśmy pełne spectrum eCommerce w jednym miejscu." (klient po migracji z Magento)
- "Platforma jest intuicyjna, klienci samodzielnie składają zamówienia. Słyszymy, że to NR 1 w branży."
- "Udostępnienie stanów z salonów przyniosło widoczny wzrost sprzedaży online." — Dawid Szrek, Manager e-commerce & IT, OCHNIK

**Klienci zidentyfikowani:**
OCHNIK, HAYNE, BIALCON (70 salonów, Hermes SQL), RESPOL (HVAC, Asseco SAFO),
New Balance Polska, W.KRUK, Grupa Play, HENDI, Arpex, 51015, SARA

**Wszystkie case studies (16):**
b2b-respol, erp-vendo-hayne, marketplace, ship-from-store-ochnik, wzrost-widocznosci-ochnik,
integracja-z-InPost-Pay-ochnik, aplikacja-mobilna-newbalance, spartavity-newbalance,
partnerzy-afiliacyjni-newbalance, complete-the-look-newbalance, porownywarka-produktow-hayne,
zakup-komplementarnych-produktow-hayne, cloud-services-play, optymalizacja-prezentacji-produktow-sara,
zarzadzanie-uprawnieniami, zwiekszenie-efektywnosci-planowania

### Ograniczenia researchu — sesja 2
- merce.com to Nuxt/Vue.js — pełna treść case studies niedostępna przez WebFetch (JS-rendered)
- Większość case studies podaje wyniki jakościowe, nie liczbowe
- Brak twardych danych dla: RESPOL, BIALCON, OCHNIK B2B (czas wdrożenia, % wzrostu)
- Potrzebne dane wewnętrzne od team merce — lista w sekcji "Dane do uzupełnienia" w kontekst.md

---

## Sesja 3 — OTWARTA

### Do zrobienia — sesja 3
- [ ] Wbudować liczby i social proof do slajdów w narracji (S7 i S14 priorytet)
- [ ] Zdecydować które case studies wchodzą do S7 (max 4 — HAYNE, RESPOL, OCHNIK, BIALCON)
- [ ] Ustalić czy cytat Dawida Szreka (OCHNIK) może być użyty w cold mailingu
- [ ] Uzupełnić S14 o konkretne liczby (+100% OCHNIK, 6 tyg. HAYNE)
- [ ] Zapytać team merce o brakujące dane (RESPOL, BIALCON, % zamówień bez handlowca)
- [ ] Zdecydować: czy "1,2 mld zł" wchodzi na slajd — skala vs. relevance dla B2B hook

### Otwarte pytania — sesja 3
- Który case study jest najbliższy profilowi odbiorcy cold mailingu?
- Czy BIALCON (70 salonów, Hermes SQL) lepszy przykład niż HAYNE dla opowieści o ERP?
- OCHNIK +100% to replatforming z Magento, nie czyste B2B bez ERP — jak to komunikować?
