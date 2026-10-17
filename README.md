# Plock Data Explorer

Zbuduj od razu, w jednym kroku, klikalny prototyp strony internetowej „Płock w liczbach” na demo hackathonowe. Nie zadawaj pytań, nie pokazuj planu, nie testuj w przeglądarce i nie uruchamiaj subagentów. Po napisaniu kodu sprawdź tylko, czy build przechodzi bez błędów. Braki uzupełnij rozsądnymi założeniami.

PROJEKT: „Płock w liczbach” — portal do analizowania i porównywania statystyk Płocka i okolic.

DLA KOGO: mieszkańcy, uczniowie, przedsiębiorcy i analitycy.

PROBLEM: trudno znaleźć i szybko porównać dane dotyczące rozwoju regionu.

JEDNA GŁÓWNA FUNKCJA: wybór regionu, wskaźnika i dwóch lat oraz interaktywne porównanie wyników.

EKRANY DEMO:

Strona główna z najważniejszymi wskaźnikami.

Eksplorator danych z mapą, filtrami i wykresami.

Porównanie regionów z różnicami liczbowymi i procentowymi.

MA NAPRAWDĘ DZIAŁAĆ: nawigacja między ekranami, filtry, wykresy, tabele, obliczenia zmian i eksport CSV.

UDAJEMY: rzeczywiste statystyki — użyj spójnych danych przykładowych, wyraźnie je oznaczając. Nie wymyślaj prawdziwych statystyk ani granic administracyjnych.

ZASADY TECHNICZNE:

React, TypeScript, Recharts lub podobne biblioteki.

Tylko frontend, jedna aplikacja SPA, bez backendu i zewnętrznych API danych.

Obsługa JSON i importu plików ODS z public/data/.

Interfejs w całości po polsku.

Normalna, responsywna strona internetowa — bez ramki telefonu.

Nowoczesny, profesjonalny wygląd, duże wykresy i czytelny interfejs na prezentację.

Kategorie: demografia, transport, środowisko, gospodarka, edukacja i jakość życia.

Dodaj wyszukiwarkę wskaźników oraz sekcję „Dla firm”.

PRIORYTET: działające wykresy, mapa, porównywarka i import ODS. Nie twórz statycznej makiety — zbuduj działający prototyp i sprawdź wyłącznie poprawność buildu.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/0a72e0ae-d806-4f66-b1bb-58569193fd69).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
