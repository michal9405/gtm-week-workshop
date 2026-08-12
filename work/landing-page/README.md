# Landing page — GTM Tech Week London 2027

Folder roboczy na materiały do landinga. Wszystko, co powstaje przy budowie strony, ląduje tutaj.
`data/` zostaje nietknięte (read-only), `content-library/` to biblioteka źródłowa — kopie i warianty
trzymamy w tym folderze.

## Jak to mieć u siebie na dysku

Ten folder jest w repo na branchu `claude/landing-page-materials-kp2l11`. Żeby pracować na nim
lokalnie w `~/Documents`:

```bash
cd ~/Documents
git clone <url-repo> gtm-week-workshop
cd gtm-week-workshop
git checkout claude/landing-page-materials-kp2l11
```

Materiały są w `work/landing-page/`. Jeśli repo już masz sklonowane:
`git fetch origin claude/landing-page-materials-kp2l11 && git checkout claude/landing-page-materials-kp2l11`.

Uwaga: reszta `work/` jest w `.gitignore` (to lokalne outputy warsztatowe). Ten folder ma
wyjątek, bo jest wspólną pracą, nie brudnopisem.

## Struktura

| Folder | Co tu wrzucamy |
|---|---|
| `copy/` | Teksty sekcji: hero, problem, agenda, tickets, speakers, FAQ, CTA. Jeden plik na sekcję. |
| `assets/` | Grafiki, logotypy sponsorów, zdjęcia prelegentów, OG image, ikony. |
| `references/` | Inspiracje, screeny konkurencji, benchmarki, notatki z researchu. |
| `drafts/` | Wersje robocze całej strony (HTML, wireframe, struktura sekcji). |

## Punkt startu — co już istnieje w repo

- `content-library/ticket-launch-landing-block.md` — gotowy blok hero + tabela biletów (Early Bird
  £295, Standard £495, Operator £395, Founder £195, Team of 4 £1,580). To jest baza pod sekcję ticketów.
- `content-library/sponsorship-prospectus.md` — pakiety sponsorskie, jeśli landing ma sekcję dla sponsorów.
- `content-library/post_1_gtm-is-engineering.md`, `post_2_not-more-ai-sdr-spam.md` — ton i argumenty,
  z których można wyciągnąć copy.
- `data/attio_people.csv` — 109 realnych prelegentów z LinkedIn (reszta rekordów to `to-verify`,
  nie używać na stronie).
- `data/luma_ticket-sales.csv` — typy biletów, do których musi się zgadzać sekcja cenowa.
- `data/competitor_events.csv` — czym się różnimy od innych wydarzeń.

## Zasady (nie do pominięcia)

**Voice** — przed napisaniem jakiegokolwiek publicznego tekstu przeczytaj
`content-library/brand/voice.md`. Twarde reguły: bez myślników em, bez wykrzykników, bez emoji
w body copy, prawdziwe liczby z symbolem waluty, problem najpierw, nie produkt. Jest lista słów
zakazanych (synergy, leverage, unlock, seamless, world-class).

**Wygląd** — `content-library/brand/kit.md`. Tło off-white `#fefaef` (nie białe), czarny tekst,
acid green `#b8ff03` jako jeden akcent na widok, magenta `#fc3dd5` jako drugi. Layout do lewej,
dużo powietrza, jedna myśl na sekcję.

**Fakty** — data eventu jest wstępna (2027-04-21), waluta GBP. Nie wymyślamy nazwisk prelegentów,
sponsorów ani liczb. Puste zostaje puste, wątpliwe idzie do `references/open-questions.md`.

## Do ustalenia

- Data i miejsce — potwierdzone czy nadal tentative?
- Ilu prelegentów pokazujemy w wersji 1 i czy mamy zgody na nazwiska i zdjęcia?
- Które logotypy sponsorów możemy wyświetlić publicznie?
- Gdzie idzie CTA: Luma checkout czy własny formularz?
