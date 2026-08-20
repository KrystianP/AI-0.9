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
