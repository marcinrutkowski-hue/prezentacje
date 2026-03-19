# Prezka B2B - Narracja slajdów

> Format: storytelling, nie wykład — każdy slajd to jeden argument
> Tempo: spokojne, ~20–25 min
> Styl: bezpośredni, drugoosobowy, bez żargonu
> Status: **ok** = zatwierdzony | **brak ok** = do przejrzenia

---

## Progress

🟡🟡🟡🟡🟡🟡🟡🟡🟡🟡🟡🟡🟡🟡🟡

0 gotowych · 15 do opracowania · 0 krytyczne

🟢 ok &nbsp; 🟣 treść gotowa, wymaga dopracowania flow &nbsp; 🟡 do poprawki &nbsp; 🔴 gruntowna zmiana

---

## Flow prezentacji

```
OTWARCIE (S1–S3) — strach, nie brak budżetu
  S1  Hook / pytanie       "Kiedy ostatnio straciłeś zamówienie przez excel?"   1:00
  S2  Mit nr 1             "Najpierw musicie wymienić ERP" — kto to słyszał?    1:00
  S3  Koszt stania w miejscu  Ręczne dane, błędy, handlowcy jako operatorzy     1:00

DYLEMAT (S4–S5) — pozorny wybór
  S4  Big bang vs. czekanie  12+ miesięcy i 100-500k vs. blokada wzrostu        1:00
  S5  Trzecia droga         Warstwa commerce nad ERP — nie zamiast              1:00

DOWÓD (S6–S8) — jak to działa
  S6  6 metod integracji    REST, SOAP, views, procedury, pliki, webhooks       1:30
  S7  Case studies          HAYNE, RESPOL, OCHNIK, BIALCON — realne ERP-y       1:30
  S8  ERP zostaje           Zero zmian w pracy zespołu. Synchronizacja w tle    1:00

WARTOŚĆ (S9–S12) — co firma zyskuje
  S9  Gotowe funkcje B2B    Cenniki, hierarchie, workflow, budżety out-of-box   1:00
  S10 Automatyzacja         AI: quoting, limity, routing, dokumenty             1:00
  S11 Biznes bez IT         Zespół zmienia procesy bez angażowania developerów  1:00
  S12 Jeden ekosystem       Koniec silosów: ERP, PIM, CRM, logistyka w centrum  1:00

ROZDZIELENIE DECYZJI (S13) — kluczowy argument
  S13 Dwie niezależne decyzje  eCommerce i ERP to dwa projekty — nie jeden      1:00

ZAMKNIĘCIE (S14–S15) — skala i krok
  S14 Co zyskujesz          Skala bez proporcjonalnego wzrostu zespołu          1:00
  S15 Następny krok         Nie projekt — rozmowa o Twoim stacku i bólu        1:00
```

**Łącznie: 15 slajdów · ~18 minut**

---

## Slajdy

### 1 — Hook
**Na slajdzie:** "Kiedy ostatnio straciłeś zamówienie przez excel?"
**Design:** Ciemne tło, jedno pytanie, duża czcionka
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Zacznę od pytania, które rzadko pada wprost.

Ile zamówień obsługujesz ręcznie? Ile danych przepisujesz między systemami każdego dnia? Ile razy handlowiec zamiast sprzedawać — siedzi i uzgadnia arkusze?

To jest koszt stania w miejscu. Nie jest widoczny w jednej linii budżetu, ale jest realny.

---

### 2 — Mit
**Na slajdzie:** "Najpierw musicie wymienić ERP"
**Design:** Duży cytat, przekreślony
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Każda firma B2B, która myślała o sprzedaży online, usłyszała to zdanie.

Od integratora. Od dostawcy platformy. Czasem od własnego IT.

"Najpierw musicie wymienić ERP."

I projekt stoi. Albo nie wychodzi w ogóle poza rozmowę w zarządzie.

Chcę dziś rozbić ten mit. Bo to nieprawda.

---

### 3 — Koszt status quo
**Na slajdzie:** Lista: ręczne dane / błędy / handlowcy jako operatorzy
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Tymczasem każdy dzień bez kanału online ma swoją cenę.

Ręczne przepisywanie zamówień między systemami. Rozbieżności w stanach magazynowych, które wychodzą dopiero przy realizacji. Handlowcy, którzy zamiast sprzedawać — administrują.

To nie jest problem techniczny. To problem biznesowy.

---

### 4 — Dylemat big bang
**Na slajdzie:** Dwa wyjścia: wymiana ERP 12 mies. / 100–500k PLN | czekanie = blokada
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Pozorny wybór wygląda tak:

Albo decydujesz się na wymianę ERP — projekt na rok, ryzyko operacyjne, budżet rzędu kilkuset tysięcy. Albo czekasz — i nie masz kanału online.

Większość firm czeka. I traci.

---

### 5 — Trzecia droga
**Na slajdzie:** Schemat: ERP → warstwa merce → kanały (B2B portal, app, marketplace)
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Jest trzecia droga.

Zamiast wymieniać ERP — dołożyć nad nim warstwę commerce. Taką, która synchronizuje dane, przyjmuje zamówienia, obsługuje klientów. Bez ingerencji w back-office.

ERP dalej robi to co robił. Tylko teraz ma obok siebie kanał sprzedaży online, który z nim współpracuje.

---

### 6 — 6 metod integracji
**Na slajdzie:** Lista 6 metod: REST API / SOAP / DB views / procedury / pliki / webhooks
**Czas:** 1:30 | **Status:** do opracowania

**Tekst:**
Najczęstsze obiekcje IT brzmią: "nasz ERP nie ma API" albo "nasz ERP jest za stary."

merce integruje się z każdym ERP. Nie dlatego, że mamy magię — ale dlatego, że mamy sześć różnych metod integracji.

REST API. SOAP. Widoki bazodanowe. Procedury składowane. Pliki. Webhooks.

Dostosowujemy się do infrastruktury klienta. Nie odwrotnie.

---

### 7 — Case studies
**Na slajdzie:** Tabela: HAYNE / Vendo / SOAP / 6 tyg. | RESPOL / Asseco SAFO | OCHNIK / LSI | BIALCON / Hermes SQL
**Czas:** 1:30 | **Status:** do opracowania

**Tekst:**
To nie teoria.

HAYNE — Vendo przez SOAP, sześć tygodni do uruchomienia.
RESPOL — Asseco SAFO przez Web Services.
OCHNIK — LSI przez widoki i adaptery.
BIALCON — uruchomił Fashion B2B bez wymiany Hermes SQL, z którym pracuje od lat.

Żadna z tych firm nie wymieniała ERP.

---

### 8 — ERP zostaje źródłem prawdy
**Na slajdzie:** Schemat: ERP = źródło prawdy. merce = warstwa nad nim. Strzałki synchronizacji.
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
ERP dalej jest źródłem prawdy. Ceny, stany, dane klientów — wszystko płynie z ERP.

Synchronizacja dzieje się w tle. Zespół pracuje na tych samych danych co zawsze.

Zero zmian w procesach wewnętrznych. Zero szkoleń na nowy system back-office.

---

### 9 — Gotowe funkcje B2B
**Na slajdzie:** Lista out-of-the-box: cenniki / hierarchie / workflow / budżety / resztówki
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Warstwa commerce to nie tylko integracja. To pełny zestaw funkcji B2B, którego nie trzeba pisać od zera.

Indywidualne cenniki dla każdego kontrahenta. Hierarchie ról i uprawnień po stronie klienta. Workflow akceptacji zamówień. Budżety zakupowe. Obsługa resztówek magazynowych.

Wszystko out-of-the-box.

---

### 10 — Automatyzacja z AI
**Na slajdzie:** AI automatyzuje: quoting / limity kredytowe / routing / dokumenty
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
I do tego AI, które automatyzuje to co robiłeś ręcznie.

Wyliczanie cen w zapytaniach ofertowych. Walidacja limitów kredytowych. Routing zamówień do właściwej osoby. Generowanie dokumentów.

Sprzedaż bez administracji.

---

### 11 — Biznes bez angażowania IT
**Na slajdzie:** Zespół biznesowy składa ścieżki zakupowe z komponentów. IT nie jest w pętli.
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
I jeszcze jedno.

Zmiana modelu cenowego, nowa ścieżka zakupowa, nowy workflow — to nie musi być projekt IT.

Zespoły biznesowe składają procesy z gotowych komponentów. Testują. Iterują. Bez ticketów developerskich.

---

### 12 — Jeden ekosystem danych
**Na slajdzie:** Diagram: ERP + PIM + CRM + logistyka → wszystko przez merce API
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
I na koniec — koniec silosów.

ERP, PIM, CRM, logistyka — każdy mówi co innego, dane się rozjeżdżają, ktoś musi ręcznie uzgadniać.

merce staje się centralnym węzłem. Jeden spójny zestaw danych od oferty do realizacji zamówienia.

---

### 13 — Dwie niezależne decyzje
**Na slajdzie:** Oś czasu: eCommerce teraz → ERP kiedy indziej (lub nigdy)
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
I najważniejszy argument.

Decyzja o platformie eCommerce i decyzja o zmianie ERP to dwa niezależne projekty. Możesz je rozdzielić w czasie.

Nie musisz robić obu naraz. Nie musisz blokować sprzedaży online na ERP za dwa lata.

Zacznij sprzedawać online teraz. ERP zmienisz kiedy będziesz gotowy — albo nie zmienisz wcale.

---

### 14 — Co zyskujesz
**Na slajdzie:** 3 efekty: czas (tygodnie, nie miesiące) / koszty (bez migracji ERP) / skala (więcej zamówień, ten sam team)
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Co z tego wynika konkretnie.

Uruchamiasz kanał B2B w tygodnie, nie miesiące. Nie ponosisz kosztu migracji ERP — 100 do 500 tysięcy złotych zostaje w firmie.

I skalujesz sprzedaż bez proporcjonalnego wzrostu zespołu — bo automatyzacja przejmuje administrację.

---

### 15 — Następny krok
**Na slajdzie:** Jedno zdanie + kontakt
**Czas:** 1:00 | **Status:** do opracowania

**Tekst:**
Nie proponuję projektu. Proponuję rozmowę.

Jak wygląda Twój stack? Który ERP? Gdzie jest największy ból?

Jeśli masz te odpowiedzi — mamy następny krok.

