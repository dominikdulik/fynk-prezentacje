# CHANGELOG — HISTORIA PRACY

> Jeden plik. Cała historia. Wywołanie: **"zapisz"**
> Format wpisu: data → co zrobiono → decyzje → następne kroki

---

<!-- NOWE WPISY DODAWAJ NA GÓRZE, POD TĄ LINIĄ -->

---

## 2026-06-02 — Analiza 360° + korekty właściciela + deploy GitHub Pages

### CO ZROBIONO:
- Uwzględniono korekty Dominika: konwersja = telefon (nie formularz), budżet etapami, FYNK_brand → PL_Agencja brand
- Zaktualizowano `dane/briefing_digital_kampanie_2026-06.md` — korekty wbudowane jako sekcje z datą
- Zaktualizowano `dane/plan.md` — plan etapowy (Etap 1/2/3) zamiast tygodniowego
- Stworzono pełną analizę 360° `prezentacje/2026-06-02_fynk-analiza-360.html` — 5 zakładek (@CMO @SEO @CSO @COO + Diagnoza)
- Wdrożono na GitHub Pages: https://dominikdulik.github.io/fynk-prezentacje/2026-06-02_fynk-analiza-360.html

### DECYZJE:
- Konwersja FYNK = telefon od nieznanej firmy — GA4 tego nie mierzy; wdrożyć call tracking razem z SEO fixem
- SEO techniczne (fixy devops) > content SEO przy modelu B2B-telefonicznym
- Budżet reklamowy rośnie w 3 etapach: +2 400 → +1 350 → +1 700 PLN/mies.
- FYNK_brand → pieniądze idą na PL_Agencja brand (korekta właściciela)

### NASTĘPNE KROKI:
- DZIŚ: STOP FYNK_brand, zwiększyć PL_Projekty (40→120), PL_Brand (100→110) — 10 minut w Google Ads
- Do 05.06: zlecić deweloperowi SEO fix + call tracking razem
- Do 05.06: wdrożyć logowanie źródła leadu w LiveSpace
- Deadline dev fix: 13.06.2026

---

## 2026-06-01 — Analiza kampanii Google Ads + SEO + nowe prezentacje + GitHub Pages

### CO ZROBIONO:
- Napisano artykuł SEO: "Od czego zależy cena projektu opakowania?" (`analizy/2026-06-01_artykul-seo-cena-projektu-opakowania.md`)
- Stworzono interaktywną prezentację HTML artykułu (`prezentacje/2026-06-01_cena-projektu-opakowania.html`)
- Przeprowadzono pełną analizę 11 plików CSV Google Ads + GA4 (09.2025–05.2026): 45 755 PLN wydatku, 9 031 kliknięć, 80 prawdziwych leadów
- Stworzono 3 prezentacje analizy kampanii: strategia (pełna), dashboard, kampanie v2 (tab-based)
- Stworzono plik briefingowy dla agentów: `dane/briefing_digital_kampanie_2026-06.md`
- Zaktualizowano `dane/plan.md` — nowe zadania digital czerwiec 2026
- Wdrożono prezentację kampanii na GitHub Pages: **https://dominikdulik.github.io/fynk-prezentacje/2026-06-01_fynk-kampanie-v2.html**
- Utworzono publiczne repo `dominikdulik/fynk-prezentacje` na prezentacje do wysyłki

### DECYZJE:
- FYNK_brand campaign → STOP (brand na poz. 2.42 SEO, płacimy za darmowy ruch)
- PL_Projekty opakowań → skalować 40 → 120 PLN/dzień (najlepsza kampania, głoduje)
- Repo `pliki-dzielone` zostaje prywatne (zawiera raporty wewnętrzne); nowe publiczne repo `fynk-prezentacje` do wysyłki linków
- Bez cennika w artykule SEO — zakres 5k–50k+, wycena po briefie

### NASTĘPNE KROKI:
- Wyłączyć FYNK_brand campaign w Google Ads
- Zwiększyć budżety PL_Projekty: 40→120 PLN/dzień i PL_Brand: 100→150 PLN/dzień
- Zlecić deweloperowi: GA4 event "Brief Submitted" + SEO fix (razem, deadline 13.06)
- Uruchomić Google Retargeting (dane gotowe, 3 dni)
- Uruchomić LinkedIn Ads (Marketing Director, FMCG, PL) — czerwiec
- Opublikować artykuł SEO #1 na fynk.eu

---

## 2026-06-01 — Onboarding Pauliny + deploy prezentacji na GitHub Pages

### CO ZROBIONO:
- Napisano instrukcję onboardingową dla Pauliny (`analizy/2026-06-01_paulina-onboarding.md`) — co robi w systemie, jak działa, FAQ
- Zainstalowano Node.js (v22) i Railway CLI (v4.66) przez winget/npm
- Wdrożono prezentację i aplikację demo na GitHub Pages: **https://dominikdulik.github.io/fynk-graficy/**
- Repo publiczne: `dominikdulik/fynk-graficy` — index + prezentacja (11 slajdów) + aplikacja (demo z danymi mockup)
- Link zaktualizowany w pliku onboardingowym

### DECYZJE:
- GitHub Pages zamiast Railway — token GitHub już był skonfigurowany, deploy w 2 minuty bez dodatkowej konfiguracji
- Publiczne repo — Paulina otwiera link bez logowania, działa na każdym urządzeniu

### NASTĘPNE KROKI:
- Wysłać Paulinie link + plik onboardingowy
- Uzyskać token API do ActiveCollab → podmienić dane mockowe na prawdziwe (2 dni)

---

## 2026-05-30 — ICP Scoring: ocena prompty v5 + analiza bazy CRM 601 firm

### CO ZROBIONO:
- Ocena nowej prompty ICP (kandydat v5) vs aktualnej v4 — plik `analizy/2026-05-30_ocena-prompty-icp-v5.md`
- Automatyczny pre-scoring 1095 kontaktów / 601 unikalnych firm z LiveSpace CRM
- Wynik: HIGH FIT 3 firmy, MEDIUM FIT 132, LOW FIT 445, NO FIT 21
- Plik analityczny MD: `analizy/2026-05-30_icp-scoring-crm-analiza.md`
- Interaktywny dashboard HTML: `prezentacje/2026-05-30_icp-scoring-crm.html` (297 KB, filtry, wyszukiwarka, linki do CRM)

### DECYZJE:
- Nowa prompta v5 nie zastępuje v4 — uzupełnia ją; rekomendacja: scalenie obu (STOP GATE z v4 + WATCHLIST/ZASADA BRAKUJĄCYCH DANYCH z v5)
- Scoring CRM bez web research = pre-kwalifikacja, nie finalna ocena; firmy BRAK DANYCH wymagają 5 min Google/LinkedIn przed kontaktem

### NASTĘPNE KROKI:
- HIGH FIT: Monini (Zuzanna Adamska, tag top10) + Wipasz (polecenie) — kontakt telefoniczny w ciągu 24h
- MEDIUM FIT: uruchomić sekwencję LinkedIn + mail dla top 30 firm CORE ICP
- Scalić v4 + v5 w nową wersję promptu ICP do pliku dane/icp_prompta_gotowa.md

---

## 2026-05-27 — Analiza pozycjonowania cenowego FYNK (PL vs DE)

### CO ZROBIONO:
- Podłączono dane z INSERT (sprzedaz-w-okresie.csv) — 1 281 faktur, 5,5M PLN + 379k EUR, zakres 2025–2026
- Przeprowadzono analizę: top klienci PLN i EUR, breakdown miesięczny, średnia wartość faktury per klient
- Zidentyfikowano dwa modele klientów PL: fabryka DTP (Dino 2 700 PLN/FV, Netto 2 750 PLN/FV) vs partner strategiczny (Wedel 37 500 PLN/FV, Herbapol 21 700 PLN/FV)
- Porównano ceny FYNK z rynkiem PL (The New Look, grafmag, SAR 2025) i rynkiem DE (creatif.agency, freelancermap.de, sortlist.de)
- Zapisano analizę: `analizy/2026-05-27_pozycjonowanie-cenowe-pl-de.md`
- Zbudowano prezentację HTML: `prezentacje/2026-05-27_pozycjonowanie-cenowe-pl-de.html` (10 slajdów, 4 wykresy, kafle z linkami do źródeł)

### DECYZJE:
- Obiekcja "za drogi" na PL: NIE jest uzasadniona wobec agencji — klienci commodity porównują FYNK do freelancera (nieuczciwe zestawienie)
- Obiekcja "za drogi" na DE: bardzo mało prawdopodobna — FYNK jest 3–12× tańszy niż lokalne agencje DE
- Problem DE to koncept i portfolio, nie cena

### NASTĘPNE KROKI:
- Zebrać od handlowców: "czym klient zastąpił FYNK i za ile?" — dla każdego przegranego tematu
- Rozważyć podwyżkę cen strategii i tożsamości marki (potencjał +20–30%, poniżej rynku premium PL)
- Ocenić strategiczną wartość segmentu commodity (wysoki wolumen, niska marża, wysokie obiekcje cenowe)

---

## 2026-05-27 — Przykładowa aplikacja Systemu Oceny Grafika + instrukcja workflow

### CO ZROBIONO:
- Zbudowano przykładową aplikację HTML (`prezentacje/2026-05-27_app-oceny-grafika.html`) — standalone, działa bez API ani serwera
- Aplikacja ma 4 zakładki: Dashboard (ranking, wykres strat, alerty), Graficy (Tryb A kreatywni + Tryb B techniczni), Deal Lookup (wpisz numer → kto pracował + win rate w tej kategorii), Filtry (grafik × kategoria × rynek × status)
- Dane mockowe: 8 grafików kreatywnych (Sandra, Michał, Jeroen, Kornelia, Julia, Klaudia, Katarzyna, Natalia), 5 technicznych (Kuba, Filip, Maja, Bartek, Marta), 15 dealów
- Napisano instrukcję workflow krok po kroku (`analizy/2026-05-27_system-oceny-grafika-instrukcja-workflow.md`)

### DECYZJE:
- Aplikacja najpierw jako mockup HTML — żeby pokazać jak działa bez czekania na AC API
- Format instrukcji: krok po kroku per osoba (kto, kiedy, co robi), z tabelą podsumowującą nowe czynności

### NASTĘPNE KROKI:
- Uzyskać token API do ActiveCollab (jedyna blokada)
- Podmienić dane mockowe na prawdziwe dane z AC + LiveSpace (2 dni robocze)

---

## 2026-05-26 — Analiza RIP 2026 + System Oceny Grafików + Prezentacja HTML

### CO ZROBIONO:

**Analiza RIP 2026 (40 strat, 6 handlowców):**
- Odczytano plik `RIP tematy 2026 (1).xlsx` (6 arkuszy: Karol, Julka, Grzegorz, Ania, Śliwka, Flo)
- Stworzono 6 podsumowań per handlowiec + analizę zbiorczą (7 plików .md w `/analizy`)
- Zidentyfikowano 3 typy porażki: cenowa, kwalifikacyjna, konceptualna
- Kluczowe odkrycie: Flo traci wyłącznie na konceptach (feedback Müllera — 5 konkretnych błędów egzekucji); Multikino (Julka) — klient nie zapytał o negocjację zakładając sztywność FYNK

**System Oceny Skuteczności Grafika (4 etapy):**
- Etap 1: diagnoza + architektura systemu — most AC↔LiveSpace przez `[deal_id]` w nazwie zadania AC
- Etap 2: scorecard design — karta per grafik (win rate, revenue attribution, rev/h, kategorie, rynek)
- Etap 2B: Tryb A (kreatywny/win rate) vs Tryb B (techniczny: revision rate, on-time, repeat); model atrybucji LEAD/SUPPORT dla wielu autorów
- Etap 3: aplikacja Flask — 4 widoki (dashboard, karta grafika, deal lookup, filtry), 2 dni budowy po dostępie AC API
- Uzasadnienie pola `Powód przegranej` w LiveSpace (dropdown 6 wartości)
- Gotowe wiadomości dla Patrycji i Pauli

**Prezentacja HTML (11 slajdów):**
- `prezentacje/2026-05-26_system-oceny-grafika.html`
- Nawigacja klawiaturą/dotykiem, linki do plików źródłowych

### DECYZJE:
- Pole `Powód przegranej` w LiveSpace — wdraża **Patrycja Kuras** (6 wartości: Cena / Kreacja / Zakres / Relacja / Timing / ICP)
- Aplikacja zamiast skryptów — różnica 1-2 dni budowy, przepaść w użyteczności
- Paula aktywnie oznacza LEAD (kolejność nawiasów w AC) — brak zmiany procedury
- 4. grafik przy dużych SKU → wyłączony z win rate (tylko Tryb B)

### NASTĘPNE KROKI:
- Patrycja: dodać pole `Powód przegranej` w LiveSpace (15 min)
- Dominik: przekazać dostęp do ActiveCollab API (token + URL) → Claude buduje aplikację
- Wysłać wiadomości do Patrycji i Pauli (`analizy/2026-05-26_wiadomosc-patrycja-paula.md`)

### PLIKI:
- `analizy/2026-05-26_INDEX-sesja-rip-graficy.md` — indeks całej sesji
- `analizy/2026-05-26_RIP-analiza-zbiorcza.md` — główna analiza strat
- `analizy/2026-05-26_system-oceny-grafika-etap[1/2/2b/3].md` — dokumentacja systemu
- `prezentacje/2026-05-26_system-oceny-grafika.html` — prezentacja dla zespołu

---

## 2026-05-25 — Korekty mapy firmy + mapa procesów + GitHub

### CO ZROBIONO:
- Dodano mapę procesów operacyjnych do HTML (Specjaliści / Sprzedaż / Realizacja / Klienci) na podstawie schematu z obrazka
- Karol Jasiński → Junior Account Manager (chip JUNIOR)
- Kate: pełne nazwisko Lenssinck-Kołyniak, przeniesiona do Rynek PL
- Piotr Brodziak → New Business DE, 100% NB (nie obsługuje klientów)
- Usunięto stawki z prezentacji HTML (30 chip-salary)
- Usunięto wakat AM DE z prezentacji
- Plik wrzucony do GitHub: dominikdulik/pliki-dzielone

### NASTĘPNE KROKI:
- Uzupełnić dane Piotra Brodziak (wynagrodzenie, forma zatrudnienia)
- Zweryfikować czy wakat AM DE nadal aktualny

---

## 2026-05-25 — Finalizacja mapy firmy FYNK + korekty danych pracowniczych

### CO ZROBIONO:
- Zaktualizowano `dane-firmowe/specjalisci.md` — pełna baza ~35 osób
- Zaktualizowano `prezentacje/2026-05-25_mapa-firmy-stanowiska.html` — mapa ze wszystkimi kartami pracowniczymi
- Usunięto stawki z prezentacji HTML (gotowa do pokazania zewnętrznie)
- Usunięto wakat AM DE z prezentacji

### DECYZJE:
- Kate: **Katarzyna Lenssinck-Kołyniak** — pełne nazwisko, Rynek **PL** (nie DE), AM/Marketing Manager, nieobecna (opieka nad synem)
- Paulina Stanisławska = Asystentka KAM DE (inna osoba niż Paulina Śliwa/Śliwka)
- Piotr Brodziak = **New Business DE, 100% NB** — nie obsługuje klientów
- Marcin Szumowski używa drugiego imienia Maciek
- Urszula Kotowska = pełne nazwisko Office Manager
- GD levels uzupełnione: Maja, Marta, Filip, Bartek → MID

### NASTĘPNE KROKI:
- Uzupełnić dane o Piotrze Brodziaku (wynagrodzenie, forma zatrudnienia)
- Zweryfikować wakat AM DE — czy jest kandydat?

---

## 2026-05-25 — Baza pracowników FYNK + analiza rekrutacji BOK

### CO ZROBIONO:
- Zbudowano bazę `/dane-firmowe/specjalisci.md` — 34 pracowników z rolami, stawkami, formami zatrudnienia (kreacja + BOK + zarząd)
- Odczytano dane z 2 plików Excel (Obowiązki na stanowiskach.xlsx + zakres obowiązków BOK 2026.xlsx) metodą XML z archiwum ZIP
- Skrzyżowano dane z listą stawek godzinowych kreacji i danymi CRM (unikalne nazwy właścicieli szans)
- Zbudowano mapę firmy z hierarchią, opisem operacyjnym i 12 rekomendacjami (`analizy/2026-05-25_mapa-firmy-fynk.md`)
- Przeanalizowano 2 ogłoszenia rekrutacyjne (Asystent BOK + Junior AM) pod kątem skuteczności pozyskania zdecydowanych kandydatów
- Zbadano rynek rekrutacyjny agencji kreatywnych w Krakowie (mediany wynagrodzeń, metody rekrutacji, employer branding)
- Przygotowano prezentację HTML dla koordynujących rekrutację (`prezentacje/2026-05-25_rekrutacja-bok-analiza.html`)

### DECYZJE:
- Kate Lenssinck — nieobecna z powodów rodzinnych (syn w szpitalu), NIE odchodzi — skorygowano w pamięci i plikach
- Patrycja Kuras — nadal w firmie, perspektywa IX 2026 to planowanie, nie alarm

### NASTĘPNE KROKI:
- Uzupełnić brakujące dane w specjalisci.md: nazwisko Uli (Office Manager), poziomy GD (Maja/Marta/Filip/Bartek), wyjaśnić Paulina Ś. (DE) vs Śliwka (PL)
- Rozważyć zmiany w ogłoszeniach: zadanie rekrutacyjne, klienci z nazwy, ścieżka kariery, prowizja z liczbami
- Podnieść dolne widełki Asystenta BOK (rynek: 6 790 PLN mediana, oferta: 5 000–6 000)

---

## 2026-05-25 — Analiza NB Hunters + prezentacje HTML dla spotkania z Patrycją

### CO ZROBIONO:
- Odczytano dane z exportów LiveSpace XLS (olefile + xlrd): Grzegorz `14-11.xls`, Piotr `14-12.xls`
- Zbudowano pełną analizę lejka sprzedaży obu hunterów na podstawie oficjalnych stat-exportów CRM
- Przygotowano dwie oddzielne prezentacje HTML z nawigacją (5 sekcji każda):
  - `prezentacje/2026-05-25_nb-analiza-grzegorz-dziala.html`
  - `prezentacje/2026-05-25_nb-analiza-piotr-brodziak.html`
- Dane w prezentacjach podlinkowane do źródeł (LiveSpace export, data i godzina pobrania)

### DECYZJE:
- Grzegorz: ultimatum 30.06.2026 — jeden zamknięty deal lub koniec projektu NB
- Piotr: kontynuacja z miesięcznym checkpointem — min. 20 portfolio/m-c i 3 spotkania diag./m-c; deal do Q3 lub decyzja
- Dane do analiz: używamy stat-exportów XLS z LiveSpace (nie API — zbyt wolne), skrypt `skrypty/read_xls.py`

### NASTĘPNE KROKI:
- Spotkanie z Patrycją Kuras — prezentacje gotowe do pokazania
- Weryfikacja: czy deal Piotra z II.26 to NB czy klient DE z przeszłości
- Zapytać Patrycję: co z 14 omówionymi kosztorysami Grzegorza — dlaczego żaden nie zamknięty?

---

## 2026-05-25 — Transkrypcja rozmowy sprzedażowej + framework analizy nagrań

### CO ZROBIONO:
- Zainstalowano Python 3.12 + ffmpeg + faster-whisper (model medium) na maszynie
- Przeprowadzono transkrypcję nagrania `phone_20260512-091138_606455352.m4a` (13:12, PL 100%)
- Zapisano: `analizy/2026-05-12_transkrypcja-rozmowa-aleksandra-opakowania.md`
- Zapisano: `analizy/2026-05-12_podsumowanie-rozmowa-aleksandra-opakowania.md`
- Udokumentowano workflow transkrypcji + skrypt `skrypty/transcribe.py`

### DECYZJE:
- Format transkrypcji: timestampy + ciągły tekst + adnotacje o lukach
- Nomenklatura pliku: `RRRR-MM-DD_transkrypcja-[osoba]-[temat].md`
- Narzędzie: faster-whisper medium (CPU, int8) — dobra jakość dla PL, czas ~1:1 z nagraniem
- Domyślny model: `medium` — można zmienić na `large-v3` dla trudniejszych nagrań

### NASTĘPNE KROKI:
- Dominik dostarczy folder z nagraniami rozmów handlowców
- Zbudować skrypt batch do transkrypcji całego folderu z automatycznym oznaczaniem specjalisty
- Zbudować framework oceny jakości/skuteczności rozmów sprzedażowych
- Każdy plik będzie zawierał: transkrypcja + scorecard specjalisty

---

## 2026-05-22 — Raport telefonów z celami + heatmapa aktywności

### CO ZROBIONO:
- Dodano kolumny celów do raportu: Rola (NB/Account), Cel/dzień, Avg/dzień, % celu, Proj/msc, Cel/msc, % proj/msc
- Przywrócono karty per handlowiec (init, pasek postępu % celu, proj/msc)
- Wygenerowano czystą heatmapę `prezentacje/2026-05-22_aktywnosc-heatmapa.html` — 9 handlowców × 7 dni, tylko aktywność bez celów
- Pobrano brakujący dzień 14.05 → wykryto skąd „zaginione" 20 Łukasza (miał 20 zdarzeń 14-maja)
- Re-fetch 19–22.05 z -Force dla weryfikacji danych Łukasza — potwierdzone 0 w tych dniach
- Zbudowano skrypt `skrypty/generate_heatmap.ps1` i `generate_calls_report_targets.ps1`
- Wszystkie pliki wypchnięte do repo GitHub `dominikdulik/pliki-dzielone`

### DECYZJE:
- Cele: NB Hunter = 10/dzień (220/msc), Account = 5/dzień (110/msc) — źródło: zasady-decyzyjne-trigger-points.md
- NB Hunter: Grzegorz Działa, Piotr Brodziak; Account: pozostali 7 handlowców
- Wyniki % celu dziennego: Paulina Śliwa 240%, Karol Jasiński 236%, Julia Steczko 226%, Grzegorz 215%
- Red flag: Paulina Stanislawski 20% celu (proj 21/110 msc) — wymaga rozmowy

### NASTĘPNE KROKI:
- Wyjaśnić z Łukaszem brak aktywności 19–22.05 (4 dni z rzędu 0)
- Rozmowa z Pauliną Stanislawski dot. aktywności

---

## 2026-05-22 — Panel aktywności telefonicznej handlowców (LiveSpace API)

### CO ZROBIONO:
- Odkryto właściwy endpoint LiveSpace: `Wall/getList` (nie `Wall/getItemList`) z filtrem `type_name=phone`
- Zbudowano `skrypty/fetch_calls.ps1` — pobiera zdarzenia telefoniczne z API, dedupl. per firma+handlowiec+dzień, ochrona przed podwójnym fetchem (-Force do nadpisania)
- Zbudowano `skrypty/generate_calls_panel.ps1` — generuje `prezentacje/panel_telefony.html` z CSS bar charts
- Zbudowano `skrypty/calls_scheduler_runner.ps1` — uruchamiany przez Windows Task Scheduler
- Zarejestrowano zadanie `FYNK_Calls_Panel` w Task Scheduler: codziennie o 07:00
- Wdrożono metodykę "zdarzenie u klienta": 1 firma + 1 handlowiec + 1 dzień = 1 zdarzenie (eliminuje duplikaty company/contact)
- Pobrano dane za 6 dni (15–22.05): 455 unikalnych zdarzeń po dedupl. (raw: 653 wpisów)
- Wygenerowano raport: `prezentacje/2026-05-22_raport-telefony-handlowcy.html`

### DECYZJE:
- Metodyka: liczymy unikalne firmy odwiedzone (nie wpisy wall) — zbliżone do "wykonanych" w LiveSpace
- API nie zwraca kierunku połączenia (incoming/outgoing) — niemożliwe do filtrowania po stronie API; różnica ~1/dzień vs LiveSpace
- Scheduler działa bez uprawnień admina (bez RunLevel Highest)

### NASTĘPNE KROKI:
- Zweryfikować liczby z handlowcami (czy 128 zdarzeń Grzegorza za tydzień jest realne)
- Rozważyć zapytanie do LiveSpace support o pole `direction` w Wall/getList
- Panel URL: prezentacje/panel_telefony.html (regenerowany każdego ranka o 07:00)

---

## 2026-05-22 — Konfiguracja GitHub repo pliki-dzielone

### CO ZROBIONO:
- Zainstalowano Git 2.54 (winget)
- Sklonowano prywatne repo: github.com/dominikdulik/pliki-dzielone
- Skonfigurowano token GitHub w ~/.git-credentials — połączenie działa automatycznie
- Zaktualizowano README.md i wypchnięto na main

### DECYZJE:
- Repozytorium pliki-dzielone służy do wymiany plików między konwersacjami Claude

### NASTĘPNE KROKI:
- Czekamy na narzędzie do kontroli aktywności handlowców z innej konwersacji — trafi do repo gdy będzie gotowe

---

## 2026-05-21 — Segmentacja branżowa bazy + BOK + pitch Patrycja

### CO ZROBIONO:
- Zbudowano prezentację segmentacji branżowej 4 003 firm z LiveSpace → `prezentacje/2026-05-21_segmentacja-branzowa-bas.html` (987KB)
- 453 mapowania tagów (TM) + rozbudowany classifyByName: amgen, ardex, aramark, agrarfrost, alebrowar, animonda, allnutrition, archicom, anwim i 30+ wzorców
- Zbudowano prezentację BOK — 968 firm bez NIP i bez WWW → `prezentacje/2026-05-21_bok-firmy-do-weryfikacji.html` (253KB); każdy kafel = link do LiveSpace; Paulina Śliwa 434, Florian 258, Karol 77, Piotr 69, Kate 54
- Zbudowano pitch deck dla Patrycji nt. Menedżera Operacji Sprzedaży → `prezentacje/2026-05-21_menedzer-ops-sprzedazy-pitch.html` (9 slajdów)
- Sprawdzono: brak opiekuna „Biuro FYNK" w eksporcie CSV — 0 firm do wykluczenia

### DECYZJE:
- Ogłoszenia wypuszczone 20.05: Junior Account Manager + Asystent BOK
- Łukasz Kumorowski — najprawdopodobniej opuszcza FYNK; Oliwia Dudzińska — zostaje
- Planowana rozmowa z Patrycją o Menedżerze Operacji Sprzedaży — argument: ciągłość operacyjna + ryzyko absencji

### NASTĘPNE KROKI:
- Rozmowa z Patrycją — użyć pitch deck `2026-05-21_menedzer-ops-sprzedazy-pitch.html`
- BOK: weryfikacja 968 firm — priorytet Paulina Śliwa (434) i Florian (258)
- Wysłać raporty Patrycji (Grzegorz + Piotr + klucz nawigacyjny)
- Decyzja o Grzegorzu: deadline 30.06.2026

---

## 2026-05-22 — Kontekst strategiczny: transformacja AI, USP, rekrutacje

### CO ZROBIONO:
- Dominik przekazał pełny kontekst organizacyjny na najbliższe miesiące
- Przeanalizowano dwa linki dot. pozycjonowania i USP: Seth Godin (brandforbrands.com) + TrinityP3 (trinityp3.com)
- Zaktualizowano pamięć: rekrutacje, Patrycja (odejście wrzesień 2026), status G&P, kontekst emocjonalny Dominika

### DECYZJE:
- Rekrutacje aktywne (od 20.05): Junior AM + Asystent BOK (Łukasz Komorowski odchodzi)
- Rekrutacja do uruchomienia przyszły tydzień: Menadżer Operacyjny Sprzedaży (zastąpi Patrycję do września)
- Decyzja o Grzegorzu i Piotrze: do 31.05.2026
- USP kierunek: agencja + AI + działania prospołeczne (klient wspiera pośrednio ważne org. przez współpracę z FYNK)

### NASTĘPNE KROKI:
- Wrócić do tematu transformacji AI — jak operacyjnie skalować, które procesy automatyzować
- Wrócić do linków Seth Godin + TrinityP3 jako baza pod pozycjonowanie FYNK
- Notatka Dominika: zapytać Grega, która książka Sethа Godina mówi o USP

---

## 2026-05-20 — Raport sprzedaż YTD 2026 (01.01–20.05)

### CO ZROBIONO:
- Wygenerowano raport HTML sprzedaży YTD 2026 z danych LiveSpace (eksport 20.05.2026 16:08)
- Zakres: 388 wygranych szans, 1 666 733 PLN, okres 01.01–20.05.2026
- Uwzględniono zmianę opiekuna: Karol Jasiński zastąpił Irynę Kyryliv od 15.04.2026
- Raport zawiera: trend miesięczny, 8 kart opiekunów, top 10 klientów, top produkty, źródła pozyskania — wszystko z linkami do źródeł CSV i LiveSpace

### DANE KLUCZOWE:
- Peak: marzec 501 845 PLN / 90 szans
- Najlepszy avg ticket: Piotr Brodziak 14 206 PLN (3 szanse — potencjał niewyorzystany)
- Najzdrowszy portfel: Katarzyna Lenssinck (koncentracja top klienta: tylko 21,9%)
- Problem: Julia Steczko avg 2 497 PLN, NETTO 54 szanse × avg 1 311 PLN
- Karol: 7 szans / 17 550 PLN — za krótki okres na ocenę (wrócić w czerwcu)

### NASTĘPNE KROKI:
- Wrócić do raportu w czerwcu 2026 — pełna ocena Karola po pełnym miesiącu
- Rozmowa z Julią: podnieść avg ticket (teraz 2 497 PLN — najniższy w firmie)
- Sprawdzić: ile podobnych klientów jak MULLER POLSKA (36 350 PLN avg) ma Paulina w bazie bez aktywności

### PLIKI:
- `prezentacje/2026-05-20_raport-sprzedaz-2026-YTD.html`
- Źródło: `livespace_export_list_2026-05-20_16-08(1).csv` (Downloads)

---

## 2026-05-20 — Analiza bazy CRM + sprzątanie folderu

### CO ZROBIONO:
- Wygenerowano raport HTML analizy bazy 5408 firm z LiveSpace (ICP scoring 1-10, Chart.js, tabela interaktywna)
- Sprawdzono dane o nowych klientach w 2026: 10 nowych vs 174 stałych (94.6% przychodów od stałych)
- Zapisano regułę w CLAUDE.md i pamięci: scoring klienta = zawsze `dane/icp_prompta_godowa.md`
- Posprzątano folder Asystenci: skrypty → `skrypty/`, JSON-y CRM (~110 MB) → `dane/crm/`, stare wersje → archiwum, plik .fdf → `FYNK/prawo/`

### DECYZJE:
- Prompta do scoringu ICP: jedyne źródło to `dane/icp_prompta_gotowa.md`
- Struktura folderów: root tylko `.env`, `changelog.md`, `CLAUDE.md` — wszystko inne w podfolderach

### NASTĘPNE KROKI:
- Odpytać API LiveSpace o wygrane szanse w 2026 (wymaga klucza w env)

---

## 2026-05-20 — Wnioski z zestawienia opiekunowie/klienci

### CO ZROBIONO:
- Przeanalizowano raport HTML zestawienia sprzedaży (sty 2025–maj 2026, 720 szans, PLN 3,042,797)

### WNIOSKI (do powrotu):

**1. Julia Steczko — wolumen bez wartości**
163 szanse, avg PLN 2,575 — najniżej ze wszystkich. 82% wartości = DINO POLSKA (148 małych zleceń). Bez Dino zostaje ~PLN 75K. Jeden klient = jeden punkt awarii. Do sprawdzenia: czy Dino to strategia czy operacyjna obsługa bez podbijania wartości?

**2. Anna Sada — ta sama pułapka, inny klient**
HORTEX (PLN 252K) + NETTO (PLN 130K) = 68% jej wartości. Bez tych dwóch klientów: PLN 178K z 156 szans i lat pracy.

**3. Paulina Śliwa — najlepsza ekonomia pracy**
Najmniej szans z top 5 (133), PLN 924K łącznie, avg PLN 6,947. LOTTE WEDEL: 10 zleceń za PLN 390K = avg PLN 39K/zlecenie. Model wart kopiowania — jak wejść w duże projekty.

**4. Florian Kaczmarczyk — mały wolumen, wysoka jakość**
88 szans, avg PLN 5,130. Klienci DE (Müller + Krüger = 71% wartości) — ticket wyższy, ale też koncentracja.

**5. Iryna Kyryliv (usunięta) — PLN 538K portfela wisiało w powietrzu**
145 szans, PLN 538K — 3. największa wartość w firmie. Odeszła. Kto przejął tych klientów? Nie widać ich u innych opiekunów. Niewidoczna dziura.

**6. Piotr Brodziak — potencjał bez skali**
Avg PLN 14,206 — najwyższy w firmie. Tylko 3 szanse. Co blokuje wolumen?

**7. Top produkty = praca poprawkowa, nie strategiczna**
Dominuje: Projekt w linii (100x), DTP (79x), Zmiany w projekcie (76x). Firma żyje z małych zleceń, nie z dużych wdrożeń.

### NASTĘPNE KROKI (3 rzeczy do zrobienia):
1. Julia + Anna — rozmowa o dywersyfikacji: co robimy żeby nie być zależnym od 1-2 klientów
2. Paulina — czy model LOTTE WEDEL da się przenieść? Ile podobnych klientów ma w bazie bez aktywności?
3. Iryna Kyryliv — audyt: gdzie są ci 145 klientów teraz? Kto ich obsługuje?

---

## 2026-05-20 — Zestawienie opiekunowie/klienci + eksport danych LiveSpace

### CO ZROBIONO:
- Zbadano dokumentację LiveSpace API (api-docs.livespace.io) — strona JS-rendered, niedostępna dla WebFetch
- Pobrano PDF dokumentacji API (v1.13, maj 2024) — format binarny, nieczytelny bez narzędzi
- Zapoznano się z PHP SDK LiveSpace (C:\Users\Dominik\Downloads\livespace_sdk_php) — metody: Contact/addContact, Contact/addContacts, Contact/editContact, Contact/addCompany, Contact/editCompany, Deal/get, Deal/getAll, Deal/addDeal, Deal/addDeals, Deal/editDeal
- Przetestowano wszystkie endpointy API bezpośrednio na fynk.livespace.io
- Potwierdzono działające endpointy: Wall/getList (4 typy: activity/note/phone/email), Deal/getAll (60+ pól)
- Zidentyfikowano niedostępne endpointy: Todo/getAll, Contact/getContact, User/getAll, Note/getAll, Report/getAll (błąd 540/550)
- Sporządzono szczegółową rozpiskę możliwości API (co można wyciągnąć z aktywności handlowców)
- Wczytano pliki eksportu LiveSpace (3x CSV + 7x XLS stat):
  - livespace_export_list_2026-05-20_16-08(1).csv — 866 wygranych szans sprzedaży (sty 2025–maj 2026)
  - livespace_export_list_2026-05-20_16-08.csv — 40 zadań na dziś (36 bez BIURO FYNK, wszystkie niewykonane)
  - livespace_export_list_2026-05-20_16-07.csv — 5436 firm/kontaktów
  - livespace_export_stat_*.xls — statystyki aktywności (Spotkania/Telefony/Emaile/Połączenia) — dane liczbowe niedostępne (brak Excela/Pythona), wyciągnięto tylko nazwy kolumn i handlowców
- Wygenerowano raport HTML: prezentacje/2026-05-20_zestawienie-opiekunowie-klienci.html
- Przeniesiono stare wersje prezentacji (v1/v2/v3 ICP dashboard + stary ranking) do prezentacje/archiwum

### DECYZJE:
- Wykluczony opiekun "BIURO FYNK" z zestawienia per CLAUDE.md i polecenie użytkownika
- Łączna wartość wygranych szans (bez BIURO FYNK): PLN 3 042 797 / 720 szans
- Dane XLS stat (aktywności/połączenia) wymagają Pythona lub MS Excel — nie dało się odczytać liczb

### DANE Z PLIKÓW EKSPORTU LIVESPACE — PODSUMOWANIE:

**Opiekunowie (wg wartości wygranych szans sty2025–maj2026):**
1. Paulina Śliwa — 133 szanse, PLN 924,017 (avg PLN 6,947), 17 klientów
   - Top: LOTTE WEDEL PLN 390,689 | Lewiatan PLN 84,020 | SOTI NATURAL PLN 81,869
2. Katarzyna Lenssinck — 173 szanse, PLN 633,535 (avg PLN 3,662), 19 klientów
   - Top: Owolovo PLN 118,710 | Iglotex SA PLN 112,196 | Roleski PLN 75,970
3. Anna Sada — 156 szanse, PLN 559,641 (avg PLN 3,587), 9 klientów
   - Top: HORTEX PLN 252,250 | NETTO PLN 129,800 | HERBAPOL-LUBLIN PLN 109,588
4. Florian Kaczmarczyk — 88 szanse, PLN 451,455 (avg PLN 5,130), 6 klientów
   - Top: Müller Handels GmbH PLN 183,326 | Krüger GmbH PLN 137,726 | HNC PLN 61,095
5. Julia Steczko — 163 szanse, PLN 419,730 (avg PLN 2,575), 9 klientów
   - Top: DINO POLSKA PLN 344,350 (148 szans!) | Lambertz Polonia PLN 39,575
6. Piotr Brodziak — 3 szanse, PLN 42,618 (avg PLN 14,206), 1 klient (PICO Food GmbH)
7. Karol Jasiński — 3 szanse, PLN 7,600, 3 klientów
8. Łukasz Kumorowski — 1 szansa, PLN 4,200

**Zadania niewykonane 20.05.2026:** 36 (Oliwia Dudzińska 19, Piotr Brodziak 7, Grzegorz Działa 4, Katarzyna Lenssinck 3)

**Top produkty:** Projekt w linii (100x), DTP (79x), Zmiany w projekcie (76x), Wizualizacja 2D (34x), Projekt master (30x)

**Statystyki wg XLS (kategorie — bez liczb):**
- stat_16-08.xls: Nowe osoby / Nowe firmy per handlowiec
- stat_16-08(1).xls: Nowe/Wygrane/Przegrane/Nieaktualne szanse per handlowiec
- stat_16-09.xls: Spotkanie/Telefon/E-mail aktywności per handlowiec (z podtypami)
- stat_16-09(1).xls: Wysłane wiadomości per handlowiec
- stat_16-09(2).xls: Liczba wykonanych połączeń per handlowiec
- stat_16-09(3).xls: Liczba przychodzących połączeń per handlowiec

### NASTĘPNE KROKI:
- Otworzyć pliki XLS w Excelu i przekazać dane liczbowe — dołączyć statystyki aktywności do raportu HTML
- Rozważyć automatyczny raport aktywności przez Wall/getList (dane live z API)
- Zainstalować Python (pip install xlrd) żeby móc odczytywać XLS bez Excela

---

## 2026-05-20 — Pełna mapa LiveSpace API (Postman Collection)

### CO ZROBIONO:
- Odkryto że dokumentacja na api-docs.livespace.io działa jako Postman Documenter (SPA niedostępna dla WebFetch)
- Wyciągnięto Collection ID z kodu HTML strony: `18953771-ed1b8f0c-14de-43bf-aaa3-0208f8a73a2c`
- Pobrano pełną kolekcję Postman (960KB JSON) przez endpoint API Postman Documenter
- Zapisano lokalnie: `C:\Users\Dominik\Desktop\asystenci\livespace_api_collection.json`
- Zmapowano kompletną listę modułów i metod: Person/Company (Contact), Deal, Task (Todo), Wall, Space, Products, Costs, User, Team + narzędzia
- Zidentyfikowano kluczowe odkrycia vs dotychczasowa wiedza

### DECYZJE:
- `Wall/getList` to właściwy endpoint do pobierania notatek/aktywności (type_name: note/email/activity/phone) — wcześniej nieznany
- `Todo/*` — pełny dostęp do zadań (wcześniej zwracał 540 bo szukaliśmy w złym module)
- `Default/getDatasets` — umożliwia pobieranie listy pól własnych (custom fields) dla firm/kontaktów/szans
- Notatki do szans: `Deal/addDealNote`, do firm/osób: `Contact/addCompanyNote` / `addContactNote`
- Połączenia telefoniczne rejestrować przez `Contact/addContactCall` z direction + duration

### NASTĘPNE KROKI:
- Zaktualizować CLAUDE.md o nowe endpointy (szczególnie Wall, Todo, addNote)
- Przetestować `Wall/getList` — pobranie historii aktywności dla Grzegorza/Piotra
- Przetestować `Todo/getTodoObjects` — zadania przypisane do handlowców
- Rozważyć analizę custom fields przez `Default/getDatasets`

---

## 2026-05-20 — Konfiguracja trybu plan jako domyślny

### CO ZROBIONO:
- Zmieniono `defaultMode` w `.claude/settings.json` z `"bypassPermissions"` na `"plan"`
- Od teraz Claude Code domyślnie uruchamia się w trybie plan dla tego projektu (przedstawia plan przed wykonaniem operacji)

### DECYZJE:
- Tryb `plan` zamiast `bypassPermissions` — większa kontrola nad autonomicznymi akcjami Claude

---

## 2026-05-19 — Analiza NB: Grzegorz Działa + Piotr Brodziak + klucz nawigacyjny

### CO ZROBIONO:
- Przeparsowano eksport aktywności CRM Piotra Brodzkiego (XLSX 23-20): 10 928 aktywności
- Zidentyfikowano że Piotr działa wyłącznie na rynku DE — 100% ICP-zgodna baza (REWE, dm, Tchibo, Henkel, Kerrygold, PICO Food)
- Piotr ma min. 10 firm w fazie Realizacja (zamknięte/aktywne), w tym Henkel, Kerrygold/Ornua, PICO Food
- Piotr pisze wzorowe notatki CRM po niemiecku (research-level przed każdym kontaktem)
- Sporządzono raport diagnostyczny Grzegorza Działy → `analizy/2026-05-19_grzegorz-nb-raport.md`
- Sporządzono raport diagnostyczny Piotra Brodzkiego → `analizy/2026-05-19_piotr-brodziak-nb-raport.md`
- Przygotowano klucz nawigacyjny NB Hunter (mapa decyzji dzień po dniu, oparta na procedurach firmowych)

### DECYZJE:
- Grzegorz wymaga korekty fundamentalnej: audit 19 szans ICP v4, obowiązkowe notatki, closing z Patrycją — deadline 30.06.2026
- Piotr jest na właściwej ścieżce — potrzebuje większego wolumenu outreach i Floriana jako mentora do closing calls DE
- Piotr Q1 poniżej celu (67%) wynika z długości cyklu sprzedaży DE (3–6 msc), nie z błędu procesu
- Klucz nawigacyjny dla NB Huntera gotowy do wdrożenia z Grzegorzem — może dać Patrycji

### NASTĘPNE KROKI:
- Patrycja otrzymuje oba raporty + klucz nawigacyjny
- Audit 19 szans Grzegorza z dashboardem ICP v4 — ten tydzień
- Florian Kaczmarczyk jako mentor closing call dla deali DE Piotra (dm, REWE, Tchibo)
- Decyzja o roli Grzegorza: deadline 30 czerwca 2026

---

## 2026-05-19 — ICP v4: nowa prompta kwalifikacyjna + dashboard CRM

### CO ZROBIONO:
- Przeprowadzono audit poprzedniej prompity ICP — zbyt skomplikowana, 10 kroków, za mało sprzedażowa
- Research online: frameworki B2B (CHAMP > BANT, MEDDPICC-lite, Trigger Velocity) → wnioski wdrożone
- Napisano nową promptę kwalifikacyjną v4 (`dane/icp_scoring_prompt.md`) — 5 kroków zamiast 10, Trigger jako #1 priorytet, reguła 48h, matryca Entry Points
- Stworzono gotową promptę do wklejenia w ChatGPT/Claude (`dane/icp_prompta_gotowa.md`) — jedno pole do uzupełnienia
- Wygenerowano nowy dashboard ICP v4 (`prezentacje/2026-05-19_icp_dashboard_v4.html`, 1748 KB):
  - 4025 firm (bez Biuro FYNK), scoring po 5 wymiarach
  - Wyniki: **14 HIGH FIT | 591 MEDIUM | 2180 LOW | 1240 NO/DQ**
  - Nawigacja po opiekunach (Florian, Paulina, Grzegorz, Piotr, Julia, Karol, Łukasz, Oliwia, Katarzyna i inni)
  - Każda firma: badge z wynikiem, tooltip z uzasadnieniem, etykieta akcji (ZADZWON DZIS / LinkedIn / Alert / Zamknij), przyciski mail/tel/www/CRM
  - Filtrowanie po kategorii + wyszukiwarka

### DECYZJE:
- Trigger zakupowy = #1 kryterium scoringu (research potwierdza: odpowiedź w 48h = 10x wyższa konwersja)
- CHAMP zamiast BANT: zaczynamy od wyzwań klienta, nie od budżetu
- Scoring v4 bardziej konserwatywny niż v3 (14 HIGH vs 21) — lepszy sygnał, mniej szumu

### NASTĘPNE KROKI:
- Handlowcy dzwonią do 14 HIGH FIT firm w ciągu 48h
- Przegląd 591 MEDIUM — sekwencja LinkedIn + mail ten tydzień

---

## 2026-05-18 — Naprawa dashboardu HTML (base64 JSON)

### CO ZROBIONO:
- Zdiagnozowano przyczynę pustego dashboardu: 314 firm miało cudzysłowy w oficjalnych nazwach (np. `"KLAUDEX"`, `"KABANOS"`) — łamały składnię JavaScript
- Przepisano generację HTML: dane JSON zakodowane w base64, ładowane przez `JSON.parse(atob(...))` — eliminuje wszelkie problemy z escapowaniem
- Dodano `try/catch` z komunikatem błędu i wskaźnik `Ładowanie danych...`
- Naprawiono filtry Segment DE i Aktywni klienci (boolean zamiast string)
- Karty statystyk w nagłówku są klikalne i filtrują tabelę

---

## 2026-05-18 — Analiza ICP całej bazy CRM + dashboard HTML

### CO ZROBIONO:
- Wczytano eksport LiveSpace (5 417 rekordów), wykluczono BIURO FYNK (1 392 rekordy) → 4 025 firm w analizie
- Przeprowadzono automatyczny scoring ICP dla wszystkich 4 025 firm (5 wymiarów: branża, skala, trigger, marketing, decydent)
- Wynik: **11 HIGH FIT | 750 MEDIUM FIT | 2 926 LOW FIT | 338 NO FIT | 39 firm DE**
- Zbudowano tabelę master (`dane/crm_master_tabela.csv`) z kolumnami: Firma, NIP, Opiekun, Status, Branża, Kraj, Przychód CRM, Email, WWW, Telefon, ICP Score, ICP Fit, Trigger
- Uzupełniono brakujące dane przez web research dla 10 firm
- Zapisano prompt ICP scoring do `dane/icp_scoring_prompt.md`
- Wygenerowano raport analityczny `analizy/2026-05-18_icp_analiza_bazy_crm.md`
- Wygenerowano interaktywny dashboard `prezentacje/2026-05-18_icp_crm_dashboard.html`

### DECYZJE:
- Wykluczyć BIURO FYNK ze wszystkich przyszłych analiz prospectingowych
- HIGH FIT (11 firm) → kontakt w ciągu 24h przez opiekunów

---

## 2026-05-18 — FYNK 2.0: Strategia transformacji w erze AI

### CO ZROBIONO:
- Przeprowadzono analizę strategiczną: jak FYNK ma się transformować w obliczu AI
- Zidentyfikowano unikalny moat FYNK (10 lat danych o półce, sieć zaufania, wiedza regulacyjna PPWR, CRM 4025 firm)
- Zdefiniowano nowe USP: "Brand Intelligence dla FMCG — wiemy co sprzedaje na półce, teraz możemy to udowodnić szybciej"
- Opracowano 4 nowe linie usług gotowe do uruchomienia
- Zaproponowano 3-fazowy plan transformacji: Proof of Concept → Produktyzacja → Skalowalny model
- Zebrano globalną inspirację: JKR (shelf data), Pearlfisher (metodologia), Superside (BaaS), Accenture Song (AI+data)
- Pełna strategia zapisana w: `analizy/2026-05-18_fynk_transformacja_ai_strategia.md`

### DECYZJE:
- AI = narzędzie produkcyjne, nie konkurent — FYNK używa AI do 3× szybszej obsługi, nie do zastępowania eksperta
- Główny shift: z "sprzedajemy godziny wykonania" → "sprzedajemy wiedzę, która przekłada się na wyniki"
- Najszybszy proof of concept: FYNK Shelf Intelligence Audit™ (8–15K PLN, 3–5 dni, AI + interpretacja eksperta)
- PPWR Compliance Sprint™ = naturalny trigger dla istniejących klientów FMCG (deadline z karą)
- Brand-as-a-Service: docelowo 10 klientów × 15K PLN/msc = 150K PLN/msc recurring

### NASTĘPNE KROKI:
- Wtorek 19.05: jeden telefon do aktywnego klienta (Hortex/Roleski/dr Oetker) z ofertą próbkowego Shelf Audit
- Zbudować 1-stronicowy opis FYNK Shelf Intelligence Audit™ jako narzędzie sprzedażowe
- Stworzyć szablon Brand AI Kit jako add-on do kolejnych 5 projektów
- Przygotować landing page lub deck PPWR Sprint™ dla bazy CRM

---

## 2026-05-18 — ICP Dashboard PRO v3 + Prompta kwalifikacyjna world-class

### CO ZROBIONO:
- Przeanalizowano oryginalną promptę ICP i zidentyfikowano 7 krytycznych braków (brak stop gate, trigger na #4, brak championa, brak velocity, brak win theme, PPWR niedowykorzystany, brak LinkedIn message)
- Zbudowano nowy framework PRO oparty na EARL + MEDDPICC-lite: Pain/ROI proxy, Trigger/Velocity, Champion signal, Win Theme, mapowanie konkurencji
- Przepisano promptę kwalifikacyjną od zera — gotowa do użycia przez zespół z ChatGPT/Claude
- Wygenerowano `prezentacje/2026-05-18_icp_crm_dashboard_v2.html` (scoring v2, 4025 firm, dark theme off)
- Wygenerowano `prezentacje/2026-05-18_icp_crm_dashboard_v3.html` (scoring PRO v3, dark theme): HIGH FIT 21 firm, MEDIUM 742, HOT <30 dni: 1813, DE: 27
- Dodano kolumny: Velocity (HOT/WARM/MED/COLD/FROZEN) + Win Theme (cross-sell / win-back / PPWR / cold outreach)
- Przygotowano gotową instrukcję dla zespołu do skopiowania i wysłania
- Skrypty generujące: `gen_dashboard_v2.ps1` i `gen_dashboard_v3.ps1`

### DECYZJE:
- Framework scoringu PRO: Pain/ROI +25 | Trigger/Velocity +25 | Branza +25 | Skala +15 | Champion proxy +5 | DE bonus +5
- Próg HIGH FIT podniesiony do ≥75 pkt (v2 miał ≥65) — bardziej wymagający, lista 21 firm zamiast 74
- Prompta v3 dodaje: Stop Gate (3 pytania eliminacyjne), Win Theme per firma, LinkedIn DM gotowy do skopiowania
- Szacowana skuteczność konwersji po nowym frameworku: 40-50% vs 20-25% przy starej prompcie

### NASTĘPNE KROKI:
- Używać `prezentacje/2026-05-18_icp_crm_dashboard_v3.html` jako głównego narzędzia prospectingu
- Wysłać instrukcję zespołowi (gotowy tekst z poprzedniej wiadomości)
- 21 firm HIGH FIT → telefony poniedziałek–środa (sprint 18–29.05)
- Dla każdej firmy HIGH FIT uruchomić promptę PRO w ChatGPT/Claude przed telefonem
- Po sprincie zaktualizować scoring na podstawie wyników rozmów

---

## 2026-05-18 — ICP Radar: filtracja i scoring pełnej bazy LiveSpace

### CO ZROBIONO:
- Pobrano pełną bazę LiveSpace CRM: 4771 szans (1949 open + 2602 won + 220 lost)
- Zbudowano grupowanie po firmach ze wszystkich procesów i statusów — 1801 unikalnych firm
- Wykluczono firmy z opiekunem BIURO FYNK (13 firm)
- Zastosowano scoring ICP (5 wymiarów: branżowe/skala/trigger/marketing/decydent) na całej bazie
- Wygenerowano `prezentacje/2026-05-18_icp-radar-fynk.html`: prezentacja z kaflem-nawigacją, kartami firm z linkami do LiveSpace

### WYNIKI SCORINGU:
- HIGH FIT (75-100): 131 firm — zadzwon dzis/jutro
- MEDIUM FIT (55-74): 1008 firm — LinkedIn + mail
- LOW FIT (35-54): 635 firm — obserwuj 60 dni
- Klienci FYNK w bazie: 165 firm z historią wygranych projektów

### NASTĘPNE KROKI:
- Przejść przez HIGH FIT 131 firm i zweryfikować manualnie top 20-30
- Uruchomić sekwencje kontaktowe dla HIGH FIT (telefon) i MEDIUM FIT (LinkedIn)
- Rozważyć głębszy research (online) dla top 10-15 firm HIGH FIT przed kontaktem

---

## 2026-05-17 — Sprint NB Grzegorz + Piotr | Plan 2-tygodniowy z LiveSpace

### CO ZROBIONO:
- Przeanalizowano portfele Grzegorza (611 firm PL) i Piotra (160 firm DE) z LiveSpace CRM
- Grzegorz: 0 HOT, 9 WARM, 273 COLD, 329 NO FIT (54% portfela poza ICP — kluczowy insight)
- Piotr: 1 HOT (PICO Food 89 pkt), 28 WARM, 119 COLD — aktywny pipeline
- Wygenerowano `prezentacje/2026-05-17_nb-sprint-grzegorz-piotr.html`: plan dzienny 18-29.05 z listami firm per dzień
- Grzegorz: ~29 firm/dzień (282 total), Piotr: ~15 firm/dzień (148 total)
- Dodano sekcję egzekucji dla Patrycji: daily check-in, MQL definicja, scorecard, red flags, system konsekwencji 3-poziomowy

### DECYZJE:
- Listy NB = TYLKO własne portfele handlowców (nie losowe firmy z bazy)
- Grzegorz skupia się na PL FMCG/Kosmetyki — tam ma kompetencje
- Po sprincie: czyścić portfel Grzegorza z NO FIT firm (329 do przepisania lub archiwizacji)

### NASTĘPNE KROKI:
- Patrycja wdraża plan z Grzegorzem i Piotrem w poniedziałek 18.05 rano
- Check-in Patrycja → Dominik: środa 20.05 i 27.05
- Po sprincie: analiza wyników (MQL, rozmowy, wpisy CRM)

---

## 2026-05-17 — Ranking bazy LiveSpace + ICP Scoring v3.0

### CO ZROBIONO:
- Stworzono framework kwalifikacji ICP v3.0 (`analizy/2026-05-17_icp-kwalifikacja-master.md`) — 100-punktowy scoring 5-osiowy, 9 segmentów, dane zewnętrzne (PPWR, 40% churn, CMO→CFO), gotowy prompt dla handlowca
- Napisano skrypt `skrypty/livespace-ranking.ps1` — pobiera 5 213 deali, grupuje w 1 996 firm, scoruje każdą firmę i generuje HTML
- Wygenerowano interaktywną prezentację `prezentacje/2026-05-17_ranking-bazy-livespace.html` z wynikami dla Patrycji
- Wyniki scoringu: 33 HOT / 131 WARM / 1 120 COLD / 712 NO FIT
- Naprawiono krytyczny błąd: JS template literals w PowerShell here-stringu były konsumowane jako escape chars → puste wiersze tabeli → brak działania JS
- Naprawiono: KPI kafle klikalne (filtrują tabelę), kliknięcie wiersza otwiera firmę w LiveSpace

### DECYZJE:
- Scoring 5 osi: Branża (25) + Budżet (25) + Trigger/recency (25) + Usługi (15) + Kontakt (10)
- W przyszłości: template JS w PS1 musi używać konkatenacji stringów, nie template literals (`` ` `` to escape char PowerShell)

### NASTĘPNE KROKI:
- Patrycja weryfikuje listę HOT/WARM z zespołem
- Rozważyć eksport do CSV dla handlowców
- Dodać filtr "zaniedbane szanse" (last_active > 90 dni)

---

## 2026-05-15 — Podłączenie LiveSpace API + mapowanie bazy danych CRM

### CO ZROBIONO:
- Podłączono LiveSpace API — zapisano klucze do `.env` (BASE_URL, API_KEY, API_SECRET, ACCOUNT_ID)
- Zweryfikowano połączenie: token sesji, SHA1, pierwsze zapytanie — status 200 OK
- Sprawdzono dostępność endpointów aktywności (Note, Event, Activity, Task, Call) → wszystkie zwracają 540 (brak dostępu w planie API)
- Zmapowano dane dostępne z `Deal/getAll`: 220 szans, 9 aktywnych handlowców (Grzegorz Działa 63, Florian Kaczmarczyk 41, Anna Sada 19...)
- Odkryto endpoint bazy firm: `Contact/getAll?type=company` → **3 300 firm** z pełnymi polami (NIP, adres, email, owner, client_status, last_active_date)
- Zmapowano dostępne pola firmy: identyfikacja, kontakt, adres, status, właściciel, daty, tagi, relacje

### DECYZJE:
- Klucze API przechowywane w `.env` (nie w kodzie)
- Jedyny działający endpoint do firm: `Contact/getAll?type=company` (nie `Company/getAll`)

### NASTĘPNE KROKI:
- Wybrać konkretną analizę z bazy firm: export CSV / segmentacja / zaniedbane / połączenie z szansami
- Rozważyć upgrade planu LiveSpace API dla dostępu do logów aktywności (calls, notes, tasks)

---

## 2026-05-15 — Analiza modelu biznesowego FYNK/GC/OFF + plan dnia

### CO ZROBIONO:
- Zaplanowano dzień: ZUS (pilne), umowa Kaka Dziona, FV LIDL, prezentacja kawa bio aktywna → Renata
- Wczytano i przeanalizowano schemat modelu biznesowego (Prezentacja1.pdf)
- Zidentyfikowano strukturę 3 podmiotów: FYNK Sp. z o.o. (Średnia+), GC Green Cat JDG Dominika (Ekonomiczna), Offgrid Minds (Premium, nowa spółka B2B)
- Zmapowano przepływy kapitału: FYNK→GC (gotówka), FYNK→KLIENT (3 typy faktur), OFF→KLIENT (niezależny)
- Zidentyfikowano 3 red flags: podstawa prawna gotówki FYNK→GC, właściciel OFF, relacja OFF↔FYNK

### NASTĘPNE KROKI:
- Odpowiedzieć na 3 pytania COO: podstawa prawna GC←FYNK, kto jest właścicielem OFF, czy OFF korzysta z zasobów FYNK
- Dokończyć analizę ryzyk i rekomendację struktury po uzyskaniu odpowiedzi

---

## 2026-05-15 — Analiza sprzedaży przed spotkaniem z Patrycją

### CO ZROBIONO:
- Przygotowano pełną analizę sprzedaży Jan–Kwiecień 2026 na spotkanie z Patrycją Kuras (13:00)
- Wczytano i przeanalizowano dane z programu księgowego (`sprzedaz-w-okresie(2).csv`) — faktury kwiecień 2026
- Zidentyfikowano regres: kwiecień ~407 500 PLN vs. Q1 średnia 477K PLN (−70K)
- Zidentyfikowano trend Kate: 4 miesiące spadku z rzędu (104K→63K→56K→49K)
- Potwierdzono: Grzegorz i Piotr = 0 PLN w kwiecień; 100% klientów kwiecień = stara baza (zero NB)
- Utworzono analizę MD: `analizy/2026-05-15_analiza-patrycja-spotkanie.md`
- Utworzono prezentację HTML: `prezentacje/2026-05-15_analiza-patrycja-spotkanie.html` (9 slajdów)

### DECYZJE:
- Kwiecień to regres, nie stabilizacja — wymaga konfrontacji z danymi
- Kate wymaga natychmiastowego 1:1 z diagnozą (4 miesiące trendu spadkowego)

---

## 2026-05-15 — Aktualizacja bazy wiedzy: profil FYNK i Green Cat

### CO ZROBIONO:
- Wczytano 3 pliki zewnętrzne z folderu `dane dla claude\` na pulpicie
- Dodano do `dane/profil.md` pełną sekcję **FYNK SP. Z O.O.**: adres, kontakt, rok założenia, zarząd, misja, wizja, wartości, pozycjonowanie, USP, UVP, nagrody (10 wyróżnień), cytaty klientów (8 opinii)
- Dodano do `dane/profil.md` sekcję **GREEN CAT**: adres JDG, kontakt, rok założenia (2013), misja, pozycjonowanie, nagroda Art of Packaging 2018

---

## 2026-05-15 — Aktualizacja analizy: dane Iry + korekty prezentacji

### CO ZROBIONO:
- Wczytano arkusz `H:\zestawienia_miesiace.xlsx` (arkusz 2026) — uzupełniony przez Dominika o dane Iry za kwiecień
- Ira kwiecień: **23 770 PLN** (EUR-billed) — suma 4 msc: 185 299 PLN
- Zaktualizowano wiersz Iry w tabeli zespołu (z "brak danych" na 23 770 PLN)
- Poprawiono opiekuna Lotte Wedel: **Śliwka** (38 760 PLN kwiecień)
- Zmieniono ton slajdu oceny: z "Co zrobiła / Czego nie" na "Zrealizowane / Do zamknięcia w Q2"

### DECYZJE:
- Lotte Wedel = klient Śliwki — duże zlecenie (38 760 PLN) do rozwinięcia

---

## 2026-05-14 — Analiza ICP: kwalifikacja firm do prospectingu FYNK

### CO ZROBIONO:
- Przeprowadzono analizę ICP dla EURO-NET Sp. z o.o. (RTV EURO AGD) — wynik: **2/10 LOW FIT**
- Przeprowadzono analizę ICP dla Lambertz Polonia Sp. z o.o. — wynik: **9/10 HIGH FIT** (aktywny klient FYNK, FMCG confectionery, 14 krajów EU, +29% wzrost)

### DECYZJE:
- EURO-NET: zdyskwalifikować, nie wracać przez 12 msc (chyba że sygnał FMCG launch)
- Lambertz: nie prospectować — zarządzać i rozwijać; zaplanować wejście Q2 (brief na Q4 sezon)

### NASTĘPNE KROKI:
- Zabezpieczyć relację Lambertz instytucjonalnie (min. 2 kontakty po stronie klienta)

---

## 2026-05-13 — Warsztat BOK: analiza i prezentacja celów NB + AM

### CO ZROBIONO:
- Przeanalizowano transkrypt warsztatu FYNK × Patrycja × Paweł (78 min, 13.05.2026)
- Zestawiono ustalenia spotkania z danymi z plików: `project_zespol_sprzedazy_2025_2026.md`, `project_patrycja_sprzedaz.md`, `plan.md`
- Przygotowano prezentację HTML: `prezentacje/2026-05-13_cele-BOK.html` (10 slajdów)

### DECYZJE:
- Cele Q1 były ustawione na 41% możliwości zespołu → wymagają rewizji na Q2
- Powrót do tygodniowych check-inów Patrycji z każdym specjalistą
- Ania Sada bez celu mimo 330K PLN w Q1 → zakontraktować priorytetowo
- Grzegorz: decyzja o roli NB Hunter do końca Q2 2026

### NASTĘPNE KROKI:
- Fix lejka LiveSpace (Patrycja, do 15.05)
- Zakontraktowanie Ani (Dominik + Patrycja, ten tydzień)
- Kalkulacja celów od tyłu: 500K → pipeline → gap NB → aktywności (do 31.05)

---

## 2026-05-13 — Przetworzenie procedur firmowych → dane-firmowe/

### CO ZROBIONO:
- Wczytano i zdekodowano plik `procedury_zebrane_08.04.2026_v2.txt` (15 obszarów proceduralnych)
- Utworzono folder `dane-firmowe/` z 16 plikami .md (README + 15 procedur)

### DECYZJE:
- Struktura: jeden plik = jeden obszar proceduralny

---

## 2026-05-13 — Przebudowa prezentacji dla Patrycji + wznowienie sesji

### CO ZROBIONO:
- Przebudowano `prezentacje/2026-05-13_patrycja-analiza-i-batche.html` na pełne 11 slajdów na bazie `analizy/2026-05-13_analiza-sprzedaz-dla-patrycji.md`
- Dodano slajd 9: "7 Pytań do Ciebie" z ponumerowanymi kartami pytań (Grzegorz, Piotr, cele, system premiowy, Ania, mix klientów, data CRM)
- Dodano slajd 10: "Następne Kroki — Terminy" z kolorowym kodowaniem dat (czerwony 20.05, żółty 23.05, niebieski 27.05, zielony 28.05)
- Otwarto prezentację w przeglądarce do podglądu
- Przygotowano gotową treść maila do Patrycji (p.kuras@fynk.eu) z instrukcją obsługi batchy

### DECYZJE:
- Prezentacja dla Patrycji = wyłącznie `_patrycja-analiza-i-batche.html` (jedna plik z analizą + batche)
- Outlook COM automation niedostępny — wysyłka ręczna

### NASTĘPNE KROKI:
- Wysłać mail do p.kuras@fynk.eu z załącznikiem `2026-05-13_patrycja-analiza-i-batche.html`

---

## 2026-05-13 — Analiza sprzedaży Q1 + kwalifikacja CRM dla Patrycji

### CO ZROBIONO:
- Stworzono prezentację HTML `prezentacje/2026-05-13_analiza-sprzedaz-Q1.html` (9 slajdów, oznaczenia źródeł "i")
- Przeprowadzono pełną diagnozę sprzedaży: 5 głównych problemów (obsługa zamiast sprzedaży, fikcyjne cele, brak NB, mały bilet 1 200 PLN, brak kalibracji celów)
- Stworzono `analizy/2026-05-13_analiza-sprzedaz-dla-patrycji.md` — pełna analiza do wysyłki do Patrycji (wyniki Q1, czerwone flagi, luki w procesie, oczekiwania Q2 z terminami)
- Przefiltrowano CRM (2 714 firm → 277 ICP) i podzielono na 19 batchy po 15 firm
- Stworzono `analizy/2026-05-13_crm-batche-kwalifikacji.md` — gotowe prompty do ChatGPT Deep Research
- Zapisano `dane/crm_icp_filtered.csv` — przefiltrowana lista 277 firm
- Stworzono prezentację HTML `prezentacje/2026-05-13_patrycja-analiza-i-batche.html` (9 slajdów + 19 batchy z przyciskiem "Kopiuj prompt")
- Przygotowano email do Patrycji (p.kuras@fynk.eu) z załącznikami — wysyłka przez Outlook ręcznie

### DECYZJE:
- Wysyłamy do Patrycji tylko batche CRM + CSV (nie pełną analizę zarządczą)
- Firmy wykluczone z kwalifikacji: klienci UA, UK, litwa, USA, wędkarstwo, auta, restauracje (~1 472 firm)
- 965 firm bez tagu w CRM → faza 2 po uzupełnieniu branż przez handlowców
- Próg NB Hunter: nie kwalifikować firm pod projekty poniżej 8 000 PLN

### NASTĘPNE KROKI:
- Patrycja: 1:1 Grzegorz + Piotr do 20.05
- Patrycja: cel Q2 dla Ani + progi kwalifikacji w CRM do 23.05
- Patrycja: propozycja celów Q2 dla zespołu do 27.05
- Spotkanie przeglądowe Dominik + Patrycja: 28.05
- Uzupełnić tagi dla 965 firm bez branży w CRM

---

## 2026-05-13 — CSO: konfiguracja agenta + proces NB + analiza cold calling

### CO ZROBIONO:
- Skonfigurowano agenta @cso (dane/CSO.md) w CLAUDE.md — wywołanie aktywne
- Przeanalizowano 8 prezentacji z /prezentacje — diagnoza sprzedaży Q1 2026
- Stworzono plik `analizy/2026-05-13_nb-kwalifikacja-firm-proces.md`:
  - Definicja kwalifikowanego leada (4 kryteria, progi wejścia do lejka)
  - Prompt ICP do Deep Research (ocena firmy 1–10, HIGH/MEDIUM/LOW FIT)
  - Ocena promptu — 4 luki + gotowe rozwiązania
  - Outbound opener template z triggerem
  - Tabela decyzyjna i checkpoint koniec maja
- Przeanalizowano `dane-firmowe/09_cold-calling.md` vs proces NB
- Zidentyfikowano 4 modyfikacje potrzebne w procedurze cold calling

### DECYZJE:
- Folder `dane-firmowe/` zidentyfikowany jako źródło procedur operacyjnych FYNK
- Próg kwalifikacji leada: 7–10 = HIGH FIT (wchodzi do lejka), 5–6 = nurturing, 1–4 = zamknij
- `09_cold-calling.md` wymaga aktualizacji — decyzja o formie (update vs nowy plik) odroczona

### NASTĘPNE KROKI:
- Zdecydować: update `09_cold-calling.md` czy nowy plik `09b_cold-calling-NB.md`
- Napisać outbound opener (gotowy do użycia przez handlowców)
- Odblokować Google Ads (FYNK_brand 10→60 PLN/dzień, reaktywować DE)
- Odsłuch 3 rozmów Grzegorza — znaleźć etap śmierci leadów

---

## 2026-05-13 — Health check struktury folderów + sprzątanie .claude

### CO ZROBIONO:
- Przeskanowano pełną strukturę folderu /asystenci
- Wykryto błędny folder `prezentacje/.claude/settings.local.json` (stworzony automatycznie przez Claude Code przy jednorazowym otwieraniu pliku HTML)
- Usunięto `prezentacje/.claude` — struktura projektu przywrócona do porządku

### DECYZJE:
- `.claude` istnieje TYLKO w głównym folderze `/asystenci` — nigdy w podfolderach
- Jednorazowe uprawnienia do otwierania plików HTML nie są przenoszone do stałego settings

---

## 2026-05-13 — Start sesji COO + przegląd changelog

### CO ZROBIONO:
- Aktywowano tryb COO (protokół zero — przeskanowano profil.md, plan.md)
- Zweryfikowano changelog — 1 wpis z 2026-05-12 (inauguracja)
- Sprawdzono stan planu: 105 linii, zadania z 2026-05-12 nadal otwarte

### NASTĘPNE KROKI:
- Domknąć zadania z poniedziałku: LIDL FV, KAWA, EURO RTV AGD
- Ruszać z prospectingiem tygodnia (50 kontaktów LinkedIn)

---

## 2026-05-12 — Inauguracja changelog

### CO ZROBIONO:
- Stworzono plik changelog.md jako centralny dziennik pracy
- Dodano komendę "zapisz" do CLAUDE.md

### DECYZJE:
- Jeden plik `changelog.md` w głównym folderze (nie w /dane)
- Nowe wpisy zawsze na górze (najnowsze widoczne od razu)
- Wywołanie ręczne: "zapisz"

### NASTĘPNE KROKI:
- Przy każdym "zapisz" — dopisać nowy wpis na górze

---
