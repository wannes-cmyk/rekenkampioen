# Changelog

Alle noemenswaardige wijzigingen aan Rekenkampioen staan in dit bestand.

Het formaat volgt [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) en het project volgt [Semantic Versioning](https://semver.org/spec/v2.0.0.html). Datums staan in ISO 8601 (JJJJ-MM-DD). Nieuwste versie bovenaan.

De versies tot en met 1.2.0 zijn achteraf samengesteld uit de git-geschiedenis van 24 oktober 2026. De bijhorende tags zijn achteraf op de juiste commits gezet.

## [Unreleased]

### Toegevoegd

- `CLAUDE.md` met afspraken voor elke sessie: doelgroep lagere school, branch per feature, commitstijl, commentaar en changelog.
- Dit changelogbestand.

### Gewijzigd

- De oude naam Tafels Kampioen is overal in de app vervangen door Rekenkampioen: de titels van de PDF-overzichten en werkbladen en de boodschap bij drie sterren.
- De geschiedenis in de browser wordt nu bewaard onder een nieuwe naam. Bestaande geschiedenis blijft leesbaar.

## [1.2.0] - 2026-10-24

### Toegevoegd

- Bedankpagina (`bedankt.html`) voor wie het feedbackformulier invult. Ze bedankt, legt uit wat er met de feedback gebeurt en nodigt uit om mee te werken aan de open source app.

## [1.1.0] - 2026-10-24

### Toegevoegd

- Zwevende 💬-knop rechtsonder die het feedbackformulier (Tally) in een nieuw tabblad opent. Er wordt geen extra script op de pagina geladen, zodat kinderen niet aan een externe tracker worden blootgesteld.
- Issue-sjabloon voor feature requests op GitHub, met een verwijzing naar het feedbackformulier voor leerkrachten en ouders.
- Anonieme bezoekcijfers via Simple Analytics, zonder cookies en zonder persoonsgegevens. De oefenresultaten van kinderen worden niet gemeten.
- README beschrijft het feedbackkanaal en de analytics.

## [1.0.1] - 2026-10-24

### Opgelost

- Klok lezen: 40 minuten wordt nu "twintig voor" in plaats van "tien over half", volgens de feedback van een juf.
- Klok lezen: 20 minuten wordt nu "twintig over" in plaats van een vorm met "voor half". "Voor half" en "over half" blijven bij 25 en 35 minuten.

## [1.0.0] - 2026-10-24

### Toegevoegd

- Eerste publieke versie van Rekenkampioen, verhuisd van het eerdere Tafels Kampioen (repo urban-succotash) naar een eigen repo.
- Oefenen van maal- en deeltafels, hoofdrekenen (splitsen, brug over het tiental, optellen en aftrekken tot 100 en 1000) en digitaal kloklezen voor het 2de en 3de leerjaar.
- Geschiedenis van gespeelde rondes in de browser (localStorage), met PDF-download per ronde.
- Afdrukbare werkbladen met oplossingen voor tafels en hoofdrekenen.
- MIT-licentie met copyright op naam van Wannes De Loore.
- Eigen adres: https://rekenkampioen.wannesdeloore.be/ (GitHub Pages, CNAME).

### Gewijzigd

- Naam van de app: van Tafels Kampioen naar Rekenkampioen, omdat de app meer dan tafels omvat.
- README verwijst naar het eigen domein.

[Unreleased]: https://github.com/wannes-cmyk/rekenkampioen/compare/v1.2.0...HEAD
[1.2.0]: https://github.com/wannes-cmyk/rekenkampioen/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/wannes-cmyk/rekenkampioen/compare/v1.0.1...v1.1.0
[1.0.1]: https://github.com/wannes-cmyk/rekenkampioen/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/wannes-cmyk/rekenkampioen/releases/tag/v1.0.0
