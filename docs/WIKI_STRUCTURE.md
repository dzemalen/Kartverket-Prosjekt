# Forslag til GitHub Wiki-struktur

Dette repoet er fortsatt lite, men en enkel Wiki-struktur vil gjøre prosjektet mer robust når kodebasen vokser.

## 1) Overview
**Formål:** Gi leseren rask systemforståelse.

Anbefalt innhold:
- Problemområde og mål.
- Hvem systemet er for.
- Lenker til README, arkitektur og setup.

## 2) Setup Guide
**Formål:** Praktisk onboarding for utviklere.

Anbefalt innhold:
- Krav til språk/runtime.
- Installasjon av avhengigheter.
- Miljøvariabler (`.env`-oversikt).
- Lokale kjørekommandoer.
- Vanlige feil (f.eks. utilgjengelig DB/API).

## 3) Architecture
**Formål:** Forklare tekniske valg og systemgrenser.

Anbefalt innhold:
- Komponentdiagram (frontend/backend/database/tredjepart).
- Dataflyt for sentrale use cases.
- Begrunnelser for valgte mønstre.

## 4) Database Notes
**Formål:** Dokumentere datamodell og drift.

Anbefalt innhold:
- ER-diagram eller tabelloversikt.
- Migreringsstrategi.
- Seed-data for lokal utvikling.
- Feilsøking av tilkobling og credentials.

## 5) Future Improvements
**Formål:** Synliggjøre prioriteringer og modenhet.

Anbefalt innhold:
- Teknisk gjeld.
- Planlagte features.
- Ytelse/sikkerhet/observability-forbedringer.
- Prioritering (kort/medium/lang sikt).

## Praktisk publiseringsforslag
- Opprett Wiki-sider med navnene over.
- Hold README kortfattet og linker-inn i Wiki for dypdykk.
- Oppdater Wiki ved hver større teknisk endring for å holde dokumentasjonen troverdig.
