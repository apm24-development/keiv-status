# KeivApp: stan usług

Monitor dostępności KeivApp na [Upptime](https://upptime.js.org) (open source, MIT). Działa w
GitHub Actions, poza serwerami KeivApp, więc pokazuje też awarię całego serwera.

- Strona statusu: https://status.keiv.app (GitHub Pages) i zakładka „Status” na keiv.app.
- Usługi i adresy: `.upptimerc.yml`.
- Incydenty to zgłoszenia z etykietą `status`, wpływem (`minor`, `major`, `critical`,
  `maintenance`) i etykietą usługi (`panel`, `logowanie`, `allegro`, `kaufland`, `ai`, `strona`).
  Kolejne wpisy to komentarze zaczynające się od „Badamy:”, „Przyczyna znana:”, „Obserwujemy:”
  albo „Rozwiązane:”. Strona keiv.app pokazuje tylko wpisy członków organizacji i automatu.

**Stan:** automaty wyłączone do startu produkcji (app.keiv.app). Uruchomienie opisuje nagłówek
`.upptimerc.yml`.
