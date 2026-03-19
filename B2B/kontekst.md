# Prezka B2B - Kontekst

## Prezentacja: Sprzedaż B2B online bez wymiany ERP

- **Temat:** Jak rozwijać sprzedaż online B2B bez ingerencji w ERP
- **Hook:** "Uniezależnij się od ERP" — ale prawdziwy strach to destabilizacja tego co działa
- **Odbiorcy:** CEO, Head of Sales, CTO / IT Director firm produkcyjnych i dystrybucyjnych B2B
- **Format:** Prezentacja sprzedażowa / konferencja

---

## Teza główna

Firmy B2B nie odkładają modernizacji sprzedaży przez brak budżetu.
Odkładają przez strach przed destabilizacją działającej infrastruktury IT.

**Prawdziwy ból:** Nie "ERP jest przestarzały" — tylko "ERP działa i boimy się go ruszyć."

**Odpowiedź merce:** Nie wymieniamy ERP. Dokładamy warstwę commerce nad nim.

---

## Hook i narracja otwierająca

**Hook:** "Sprzedaż B2B online — bez wymiany ERP, bez ingerencji w back-office"

**Dlaczego to działa:**
- Każda firma B2B, która myślała o sprzedaży online, słyszała: "najpierw musicie wymienić ERP"
- To zdanie blokuje projekty na miesiące albo lata
- merce rozbija ten mit — i pokazuje, że to nieprawda

---

## Dylemat "big bang"

Firmy B2B stoją przed pozornym wyborem:

1. **Wymienić ERP** → projekt 12+ miesięcy, 100–500k PLN, ryzyko operacyjne
2. **Czekać** → brak kanału online, ręczna obsługa zamówień, blokada wzrostu

**Trzecia droga:** warstwa commerce nad istniejącym ERP — to właśnie robi merce.

---

## Koszt status quo (do narracji)

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

### Case studies (do użycia)
| Firma | ERP | Metoda | Czas |
|-------|-----|--------|------|
| HAYNE | Vendo | SOAP | 6 tygodni |
| RESPOL | Asseco SAFO | Web Services | — |
| OCHNIK | LSI | Views/adaptery | — |
| BIALCON | Hermes SQL | — | — |

### Oszczędność vs. migracja ERP
- **Czas:** tygodnie zamiast 12+ miesięcy
- **Koszt:** oszczędność 100–500k PLN na samej migracji ERP

---

## Kluczowe komponenty merce

| Komponent | Rola |
|-----------|------|
| **merceLayer** | Integracja z ERP/PIM/CRM przez gotowe konektory lub open API |
| **merceLinker** | Marketplace B2B |
| **merceApp** | Kanał mobilny dla handlowców i klientów |
| **Headless storefront** | API-first, niezależny od backendu |

---

## Funkcje B2B out-of-the-box

- Customer-specific pricing (indywidualne cenniki)
- Rabaty i dopłaty produktowe
- Zarządzanie resztówkami magazynowymi
- Hierarchie ról i uprawnień po stronie klienta
- Workflow akceptacji zamówień (approval flows)
- Budżety zakupowe
- Obsługa RFQ i quoting z AI

---

## Dane do uzupełnienia (brakuje w bazie)

| Metryka | Skąd wziąć |
|---------|-----------|
| % redukcji błędów w zamówieniach po integracji | Dane z OMS klientów |
| Wzrost wolumenu sprzedaży przy tym samym zespole | Case studies B2B |
| Koszt TCO: integracje punktowe vs. merce | Analiza projektów |
| % zamówień B2B bez udziału handlowca po wdrożeniu | merceApp analytics |
