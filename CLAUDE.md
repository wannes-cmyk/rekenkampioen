# Rekenkampioen

Gratis, open source oefenapp voor kinderen van de lagere school. Live op https://rekenkampioen.wannesdeloore.be/ (GitHub Pages). Repo: wannes-cmyk/rekenkampioen. Eigenaar: Wannes De Loore. Persoonlijk project, MIT-licentie, geen support.

Lees bij de start van elke sessie `CHANGELOG.md` (Unreleased en laatste versie), `README.md` en de laatste 10 commits.

## Doelgroep

- De app is voor de lagere school. Vandaag zijn 2de en 3de leerjaar ingebouwd.
- Elke feature request vermeldt de specifieke doelgroep (leerjaar of leerjaren). Staat die er niet bij of is ze onduidelijk, vraag er dan naar voor je bouwt.
- Over onderwijsinhoud (rekenstrategieën, klokwoorden, schoolconventies) gok je niet. Vraag het. Feedback van leerkrachten is de bron.

## Stack en grenzen

- Zuiver HTML, CSS en vanilla JavaScript. jsPDF via CDN voor PDF. Geen build-stap.
- Geen frameworks of nieuwe dependencies zonder te vragen.
- Geen externe scripts of trackers die kinderen zien. Externe diensten gaan via een link (zoals het Tally-formulier), niet via een embed. Enige uitzondering: Simple Analytics, zonder cookies en zonder persoonsgegevens.
- Nooit namen of andere persoonsgegevens van kinderen in code, issues, commits of logs.
- Taal in de app: Vlaams Nederlands.

## Werkwijze per feature

1. Werk op een eigen branch per feature, vertrokken van een bijgewerkte `main`. Naam: `feature/korte-naam`, of `fix/korte-naam` voor een bugfix. Nooit rechtstreeks op `main`.
2. Eén feature per branch. Kleine commits met een duidelijke boodschap.
3. Test de logica voor je pusht. Rekenlogica test je programmatisch. Meld wat je getest hebt en wat niet.
4. Werk `README.md` bij als opties of gedrag veranderen.
5. Zet de wijziging in `CHANGELOG.md` onder `[Unreleased]`, in dezelfde branch.
6. Push de branch en open een pull request naar `main`. Wannes merget zelf.
7. Eindmelding: twee zinnen over wat er veranderd is, de link naar de pull request, en wat Wannes moet nakijken.

## Commits

- Nederlands, gebiedende wijs: "Voeg ... toe", "Los ... op".
- Behoud de `Co-Authored-By`-regel die de sessie meegeeft.

## Commentaar in de code

- Leg uit waarom, niet wat. De code zegt al wat er gebeurt.
- Kort, in het Nederlands, boven het blok.
- Leg schoolregels en uitzonderingen uit (bv. waarom "voor half" bij 25 en 35 minuten blijft).
- Laat geen uitgecommentarieerde code staan. Git bewaart de geschiedenis.
- Een commentaar dat niet meer klopt, pas je aan in dezelfde commit.

## Changelog

Formaat: [Keep a Changelog 1.1.0](https://keepachangelog.com/en/1.1.0/). Versies: [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

- Bestand `CHANGELOG.md`, nieuwste versie bovenaan, datums in ISO 8601 (2026-10-24).
- Wijzigingen verzamel je onder `[Unreleased]`.
- Groepeer per type: Toegevoegd, Gewijzigd, Verouderd, Verwijderd, Opgelost, Beveiliging.
- Schrijf voor mensen (leerkrachten, ouders). Geen dump van de git-log.
- Noem verouderde of verwijderde functies en alles wat iets breekt altijd.
- Een ingetrokken versie krijgt `[YANKED]` achter de datum.
- Nieuwe feature is minor, bugfix is patch, grote breuk is major.

## Een release maken

Pas na een merge op `main`, en alleen als Wannes het goed vindt:

1. Maak van `[Unreleased]` een nieuwe versiesectie met datum en zet er een lege `[Unreleased]` boven.
2. Werk de linkregels onderaan bij.
3. Maak een geannoteerde tag `vX.Y.Z` op de commit en push de tag.
