# Zagadnienia do nauki

## 1. Podstawy działania agentów i pętle pracy

- Czym są agenci AI i czym różnią się od zwykłego chatbota?
- Co to są pętle pracy agentów (agent loops)?
- Czym jest `self-improvement loop` i do czego można go bezpiecznie używać?
- Pętle uczenia się modelu: czym różnią się od pętli pracy agenta, treningu,
  pamięci i poprawiania instrukcji?
- Planowanie, wykonywanie zadań, obserwowanie wyników i korekta działania.
- Jak oceniać, czy agent rzeczywiście poprawił rezultat, a nie tylko wykonał
  więcej kroków?

## 2. Tworzenie i orkiestracja agentów w Codex

- Jak tworzyć agentów w Codex?
- Odpalanie i delegowanie zadań do sub-agentów w Codex.
- Podział odpowiedzialności między agentem głównym, sub-agentami i narzędziami.
- Przekazywanie kontekstu, wyników i ograniczeń między agentami.
- Praca równoległa, zależności między zadaniami oraz kontrola kosztu i czasu.
- Weryfikacja wyników sub-agentów i obsługa błędów.

## 3. Harness — uprząż i środowisko agenta

- Czym jest agent harness (uprząż agenta)?
- Z jakich elementów składa się harness: instrukcje, kontekst, narzędzia,
  uprawnienia, pamięć, pętle działania i walidacja?
- Jak projektować środowisko, w którym agent działa powtarzalnie i bezpiecznie?
- Jak definiować granice autonomii, punkty akceptacji i działania wymagające
  potwierdzenia użytkownika?
- Logowanie działań, śledzenie decyzji, koszty, czas wykonania i debugowanie.

## 4. Skills, instrukcje i rozszerzanie Codex

- Wszystko o skills: czym są, jak działają i kiedy warto je tworzyć.
- Jak tworzyć, testować, aktualizować i wersjonować własne skills?
- Czy skills muszą być instalowane osobno w każdym repozytorium?
- Różnica między skill, pluginem, narzędziem, instrukcją repozytorium i
  konfiguracją środowiska.
- Hierarchia instrukcji, pliki `AGENTS.md` i zakres ich obowiązywania.
- Hooki w Codex: czym są, jakie zdarzenia obsługują i jak je konfigurować?
- Bezpieczeństwo hooków, skills i narzędzi oraz ograniczanie ich uprawnień.

## 5. Narzędzia, dane i pamięć

- Jak agent korzysta z narzędzi, plików, terminala i usług zewnętrznych?
- MCP i integracje: czym są, jak je podłączać oraz jak kontrolować dostęp do
  danych?
- Zarządzanie kontekstem, pamięcią krótkoterminową i trwałą.
- Jak przygotowywać dane i dokumentację, aby agent mógł z nich korzystać
  rzetelnie?
- Prywatność, sekrety, uprawnienia i zasada najmniejszych uprawnień.

## 6. Testowanie, ewaluacja i ciągłe doskonalenie

- Jak tworzyć testy i przykładowe zadania dla agentów?
- Ewaluacja jakości, poprawności, bezpieczeństwa, kosztu i czasu działania.
- Jak rozpoznawać halucynacje, błędne decyzje i pozorną poprawę?
- Wersjonowanie promptów, skills, harnessu i konfiguracji.
- Pętle informacji zwrotnej oraz bezpieczne wdrażanie usprawnień.

## 7. Praktyczne korzystanie z modeli AI

- Dobieranie modelu do zadania: rozumowanie, kod, obraz, dźwięk, wyszukiwanie
  i praca z dużą ilością danych.
- Projektowanie promptów, kontekstu, przykładów i kryteriów dobrego wyniku.
- Rozbijanie dużych problemów na małe zadania możliwe do zweryfikowania.
- Praca z niepewnością: sprawdzanie źródeł, faktów, założeń i ograniczeń modelu.
- Multimodalność: analiza dokumentów, obrazów, nagrań i danych.
- Porównywanie narzędzi i budowanie własnego zestawu AI bez uzależniania się od
  jednej aplikacji.

## 8. Szybkie tworzenie aplikacji z pomocą AI

- Podstawy programowania potrzebne do świadomej współpracy z AI: Git, terminal,
  struktura aplikacji, API, bazy danych i podstawy web developmentu.
- Metodyka budowania aplikacji od pomysłu do działającego prototypu:
  problem, użytkownik, zakres MVP, implementacja, test i iteracja.
- Vibe coding z kontrolą jakości: jak prowadzić AI krok po kroku i rozumieć
  kod, który powstaje.
- Czytanie błędów, debugowanie, refaktoryzacja i utrzymywanie aplikacji.
- Projektowanie interfejsów, doświadczenia użytkownika i dostępności.
- Logowanie, testy automatyczne, CI/CD, wdrażanie, domeny i monitoring.
- Integracje z API, webhooki, OAuth, płatności i powiadomienia.

## 9. Automatyzacja procesów i tworzenie systemów

- Mapowanie własnych procesów: wejście, decyzja, działanie, wynik i wyjątki.
- Rozpoznawanie zadań, które warto automatyzować, delegować agentowi albo
  pozostawić człowiekowi.
- Automatyzacje wyzwalane zdarzeniami, harmonogramem i zmianą danych.
- Łączenie aplikacji, formularzy, poczty, kalendarza, plików i baz danych.
- Obsługa błędów, ponawianie, alerty, ręczne zatwierdzenia i audyt działań.
- Projektowanie procesów odpornych na awarie i łatwych do odtworzenia.

## 10. Dane, wiedza i osobisty system operacyjny

- Budowanie własnej bazy wiedzy oraz wyszukiwanie informacji z zachowaniem
  źródeł i kontekstu.
- Porządkowanie danych, nazewnictwo, metadane, wersjonowanie i kopie zapasowe.
- RAG i wyszukiwanie semantyczne: kiedy są potrzebne, a kiedy wystarczy dobrze
  przygotowany kontekst.
- Projektowanie osobistego systemu pracy: cele, projekty, zadania, notatki,
  decyzje i przeglądy.
- Mierzenie oszczędności czasu, jakości wyników i realnego wpływu automatyzacji.

## 11. Bezpieczeństwo i odpowiedzialne użycie AI

- Ochrona danych osobowych, poufnych dokumentów, kluczy API i pieniędzy.
- Prompt injection, wyciek danych, niebezpieczne narzędzia i ataki na agentów.
- Zasada najmniejszych uprawnień, separacja środowisk i bezpieczne sekrety.
- Weryfikacja działań finansowych, prawnych i innych wysokiego ryzyka przez
  człowieka.
- Licencje, prawa autorskie, zgody na wykorzystanie danych i pochodzenie treści.

## 12. Produkty, zarabianie i pomnażanie kapitału

- Odkrywanie problemów, za które ludzie lub firmy rzeczywiście chcą zapłacić.
- Walidacja pomysłu przed budową: rozmowy, landing page, prototyp i pierwsza
  sprzedaż.
- Modele biznesowe dla narzędzi AI, usług automatyzacyjnych i produktów
  cyfrowych.
- Kalkulowanie kosztu modeli, infrastruktury, obsługi i pozyskania klienta.
- Sprzedaż, marketing, dystrybucja, obsługa klienta i mierzenie retencji.
- Zarządzanie ryzykiem: AI ma wspierać decyzje finansowe, ale nie zastępuje
  analizy ani odpowiedzialności człowieka.

## 13. Zmiana sposobu pracy i życia

- Audyt własnego czasu, energii, pieniędzy i powtarzalnych obciążeń.
- Eliminowanie, upraszczanie, automatyzowanie i delegowanie — w tej kolejności.
- Budowanie nawyku codziennego eksperymentowania i cotygodniowego przeglądu.
- Praca w krótkich cyklach: hipoteza, działający rezultat, pomiar i poprawa.
- Ochrona uwagi, zdrowia, relacji i czasu offline przed nadmierną optymalizacją.
- Rozróżnianie efektownego używania AI od rozwiązań, które faktycznie poprawiają
  życie.

## 14. Warp jako środowisko do zarządzania agentami

Warp warto potraktować jako ważny element nauki, ale nie jako „kolejny chatbot”.
To środowisko agentowe łączące terminal, lokalnych agentów i warstwę Oz do
uruchamiania agentów w chmurze. Jest szczególnie istotne dla celu szybkiego
budowania aplikacji, ponieważ agent może pracować bezpośrednio na repozytorium,
uruchamiać polecenia, obserwować wyniki, poprawiać błędy i wykonywać zadania
wielokrokowe.

### Warp lokalnie

- Agent Mode: prowadzenie wieloetapowych zadań bezpośrednio w terminalu.
- Przekazywanie agentowi konkretnego kontekstu: plików, URL-i, obrazów,
  fragmentów kodu i wyników poleceń.
- Praca agenta z aktywnym procesem, np. serwerem developerskim, debuggerem,
  bazą danych lub powłoką interaktywną.
- Planowanie, listy zadań, review diffów i poprawianie kodu na podstawie uwag.
- Rozdzielanie rozmów i sesji, zarządzanie kontekstem oraz praca na wielu
  zadaniach równocześnie.
- Wybór modelu, kontrola kosztów, limity i rozumienie, kiedy zmienić model.

### Zarządzanie zachowaniem agentów

- Project Rules i globalne reguły: jak definiować sposób pracy agenta.
- `AGENTS.md`, skills, profile wykonawcze i MCP w Warp.
- Saved prompts, slash commands i Workflows jako powtarzalne procedury.
- `/orchestrate`: dzielenie zadania na podzadania i praca wielu agentów.
- Uprawnienia, akceptowanie poleceń, auto-approval, przejęcie kontroli i punkty
  wymagające decyzji człowieka.
- Pełne użycie terminala przez agenta oraz granice bezpiecznej autonomii.

### Oz i agenci działający w chmurze

- Różnica między lokalnym agentem w Warp a cloud agentem uruchamianym w tle.
- Uruchamianie agentów przez harmonogramy, webhooki i zdarzenia z GitHuba,
  Slacka lub innych usług.
- Środowiska wykonawcze, sekrety, repozytoria i izolacja pracy agenta.
- Równoległe uruchamianie agentów oraz koordynowanie ich wyników.
- CLI, API i SDK Oz: kiedy używać interfejsu Warp, a kiedy budować własną
  warstwę sterującą.
- Monitorowanie, audyt, koszty, retry, anulowanie i raportowanie przebiegów.

### Projekty praktyczne w Warp

- Agent, który analizuje repozytorium, tworzy plan i przygotowuje zmianę do
  review.
- Agent, który uruchamia testy, diagnozuje błędy i proponuje poprawkę.
- Workflow, który powtarzalnie tworzy projekt, sprawdza jego jakość i uruchamia
  lokalne środowisko.
- Zestaw wyspecjalizowanych agentów: badacz, implementer, tester i reviewer.
- Bezpieczna automatyzacja jednego własnego procesu z ręcznym zatwierdzeniem
  działań wysokiego ryzyka.

## 15. Praca agentów na różnych gałęziach Git

### Po co używać wielu gałęzi

- Izolowanie osobnych zadań, eksperymentów i zmian przygotowywanych przez
  różnych agentów.
- Umożliwienie kilku agentom pracy równolegle bez nadpisywania sobie plików.
- Zachowanie stabilnej gałęzi głównej, gdy agent dopiero bada problem albo
  generuje duży zakres zmian.
- Łatwe porównanie, odrzucenie lub zaakceptowanie wyniku pracy agenta.
- Rozdzielenie pracy na funkcję, poprawkę błędu, testy, refaktoryzację i
  eksperyment z nowym narzędziem AI.

### Kiedy zakładać osobną gałąź

- Gdy zadanie zmienia kod, konfigurację lub strukturę projektu.
- Gdy agent ma działać autonomicznie albo wykonać wiele kroków.
- Gdy zadanie jest eksperymentem i nie wiadomo jeszcze, czy rozwiązanie będzie
  dobre.
- Gdy kilka agentów ma pracować równocześnie nad różnymi częściami aplikacji.
- Gdy zmiana powinna przejść osobny review i testy przed połączeniem z główną
  gałęzią.

### Kiedy gałąź nie jest potrzebna

- Przy samym czytaniu repozytorium, analizie, wyszukiwaniu informacji lub
  przygotowaniu planu.
- Przy małej, oczywistej zmianie, jeśli pracujemy sami i mamy aktualny stan
  repozytorium.
- Gdy zadanie dotyczy wyłącznie lokalnego eksperymentu, który nie ma zostać
  zapisany w projekcie.

### Workflow Warp + agenci + Git

- Jeden agent lub zadanie = jedna jasno nazwana gałąź.
- Przed startem: sprawdzenie czystego stanu, aktualnej gałęzi i synchronizacji
  z repozytorium.
- Agent pracuje wyłącznie w swojej gałęzi i nie łączy zmian samodzielnie z
  główną gałęzią bez zatwierdzenia.
- Po zakończeniu: diff, testy, `git diff --check`, przegląd zmian i dopiero
  potem merge albo pull request.
- Przy wielu agentach: osobne gałęzie, osobne zakresy plików i jasna kolejność
  łączenia wyników.
- Nauka rozwiązywania konfliktów, rebase, cherry-pick, wycofywania zmian oraz
  odzyskiwania pracy agenta po błędzie.

### Tematy do przećwiczenia w Warp

- Uruchomienie dwóch agentów na dwóch gałęziach i bezpieczne połączenie ich
  wyników.
- Agent implementujący funkcję, drugi agent piszący testy, a trzeci wykonujący
  review — każdy na właściwie odizolowanym zakresie pracy.
- Zatrzymanie nieudanego eksperymentu agenta bez naruszania głównej gałęzi.
- Konflikt zmian wygenerowanych przez dwóch agentów i jego ręczne rozwiązanie.
- Porównanie pracy wielu gałęzi z pracą wielu agentów w jednym katalogu.

  
