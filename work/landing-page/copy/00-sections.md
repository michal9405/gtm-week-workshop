# Struktura strony — szkielet sekcji

Kolejność sekcji i to, co każda ma zrobić. Copy do każdej z nich piszemy w osobnym pliku w tym
folderze (`01-hero.md`, `02-problem.md` i tak dalej), żeby dało się je poprawiać niezależnie.

Przed pisaniem: `content-library/brand/voice.md`. Problem najpierw, produkt później. Bez myślników
em, bez wykrzykników, bez emoji w body copy. Prawdziwe liczby z symbolem waluty.

| # | Sekcja | Zadanie | Źródło |
|---|---|---|---|
| 1 | Hero | Nazwa, edycja, data, miejsce, jedno zdanie o tym dla kogo to jest, dwa CTA. | `content-library/ticket-launch-landing-block.md` (gotowe) |
| 2 | Problem | Jedna myśl: firmy doklejają AI do zepsutego motion. Powód istnienia wydarzenia. | tamże + `post_2_not-more-ai-sdr-spam.md` |
| 3 | Dla kogo | Trzy profile: founder, GTM lead, operator. Po jednym zdaniu, bez person-marketingu. | typy biletów w `data/luma_ticket-sales.csv` |
| 4 | Agenda | Ścieżki i sale. Do uzupełnienia, gdy format będzie zamknięty. | `references/open-questions.md` |
| 5 | Prelegenci | Twarze i nazwiska. Tylko potwierdzeni, tylko za zgodą. | `data/attio_people.csv` (rekordy z LinkedIn) |
| 6 | Bilety | Tabela z cenami. Musi zgadzać się co do funta z Lumą. | `content-library/ticket-launch-landing-block.md` |
| 7 | Sponsorzy | Logotypy plus link do prospektu. | `content-library/sponsorship-prospectus.md` |
| 8 | FAQ | Data, miejsce, zwroty, faktury, dostępność. Krótkie odpowiedzi. | do napisania |
| 9 | CTA zamykające | Jedno zdanie i przycisk. Nic więcej. | `content-library/ticket-launch-landing-block.md` |

## Reguły dla copy

- Jedna myśl na sekcję. Jeśli sekcja robi dwie rzeczy, to są dwie sekcje.
- Jeden akcent acid green `#b8ff03` na widok. Jeden główny przycisk na ekran.
- Puste zostaje puste. Nie wpisujemy nazwiska prelegenta, logotypu sponsora ani liczby
  uczestników, dopóki nie ma potwierdzenia. Wątpliwości idą do `references/open-questions.md`.
- Jeśli zdanie mogłoby stać w folderze dowolnej konferencji, wycinamy je.
