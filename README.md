# Kartverket-Prosjekt

## Kort prosjektbeskrivelse
Dette repoet er per i dag et **grunnskjelett** uten implementert applikasjonskode. Formålet med denne versjonen er å etablere en ryddig, produksjonsnær dokumentasjonsstruktur som gjør prosjektet tydelig for bidragsytere og arbeidsgivere.

- **Hva det er:** Et initialisert Git-repo for et fremtidig Kartverket-/geodata-prosjekt.
- **Hvorfor det finnes:** For å bygge et strukturert fundament før funksjonalitet utvikles.
- **Hvem det er for:** Utviklere, tekniske intervjuere og potensielle arbeidsgivere som evaluerer prosjektmodenhet.

## Hovedfunksjoner
Siden kodebasen foreløpig er tom, finnes det ingen runtime-funksjoner ennå. Denne versjonen demonstrerer i stedet:

- Tydelig prosjektpresentasjon og forventningsstyring.
- Dokumentasjon av oppsett, avhengigheter og begrensninger.
- En plan for arkitektur, drift og videre forbedringer.

## Teknologistack
Per nå er følgende verifiserbart i repoet:

- **Git** for versjonskontroll.
- **Markdown** for prosjektdokumentasjon.

> Når applikasjonskode legges til, bør denne seksjonen oppdateres med språk, rammeverk, database, API-er og testverktøy.

## Prosjektstruktur
```text
Kartverket-Prosjekt/
├── .git/
├── .gitkeep
├── README.md
└── docs/
    └── WIKI_STRUCTURE.md
```

## Lokal kjøring
Det finnes foreløpig ingen kjørbar applikasjon i repoet.

### Forventet fremtidig oppsett
Når applikasjonskode legges til, anbefales dette minimumsoppsettet i README:

1. Installer nødvendige språk/runtime (for eksempel Node.js, Python, Java eller .NET).
2. Opprett miljøvariabler i en lokal `.env` (uten å commite hemmeligheter).
3. Start lokal database/API-avhengigheter (f.eks. Docker Compose eller lokale tjenester).
4. Kjør bygg/test/start-kommandoer.

### Miljøvariabler (mal)
Følgende er eksempel-kategorier som normalt må dokumenteres når funksjonalitet kommer:

- `DATABASE_URL` – tilkoblingsstreng for lokal/ekstern database.
- `API_BASE_URL` – base-URL til intern/ekstern API.
- `API_KEY` / `TOKEN` – autentiseringsnøkler.
- `PORT` – lokal port for webserver.

> Viktig: Dersom lokale tjenester (database/API) ikke er tilgjengelige, skal det beskrives tydelig i denne seksjonen med konkrete feilmeldinger og forventet utviklermiljø.

## Kjente begrensninger og antakelser
- Repoet inneholder ikke applikasjonskode ennå.
- Ingen byggekjedekonfigurasjon eller testløp er tilgjengelig i nåværende tilstand.
- Eventuelle kjøreinstruksjoner må oppdateres når første funksjonelle versjon introduseres.

## Screenshots
Legg inn skjermbilder når UI/CLI foreligger.

- `docs/screenshots/home.png` *(placeholder)*
- `docs/screenshots/flow.png` *(placeholder)*

## Arkitektur / design (nåværende og planlagt)
### Nåværende
- Minimal repository-kjerne med fokus på dokumentasjon.

### Planlagt retning
Når implementasjon starter, bør arkitekturbeskrivelsen dekke:

- Systemkontekst (klient, backend, databaser, tredjepartsintegrasjoner).
- Datatilgang og modellering.
- Feilhåndtering, logging og observability.
- Sikkerhetskrav (autentisering, autorisering, secrets-håndtering).

## Hva dette prosjektet demonstrerer for arbeidsgivere
Selv i en tidlig fase viser prosjektet:

- **Profesjonell dokumentasjonspraksis:** Klar struktur, tydelige antakelser og realistiske begrensninger.
- **Engineering-disciplin:** Fokus på lesbarhet og vedlikehold før kompleksitet introduseres.
- **Skalerbarhet i prosess:** Et oppsett som gjør senere implementasjon enklere å onboarde til.

## Videre anbefalte steg
1. Legg til første vertikale slice (f.eks. enkel endpoint + persistens).
2. Dokumenter faktiske kommandoer for kjøring/testing.
3. Etabler CI for lint/test.
4. Legg til arkitekturdiagram og konkrete skjermbilder.
