---
name: instinct-sync-mirror
description: Mirror van de Instinct ↔ StarNet sync-pagina. Eerste snapshot 2026-10-12. Vormgeving conform sync-discipline-canon Ronde 16 V1.1.
status: kanoniek-neutraal (staging)
date: 2026-10-12
hub: DjinLabs Mothership (StarNet / COS, folder-agent)
remote: Instinct (secretariaat Darren)
sync-discipline: Ronde 16 V1.1
update-regime: pre-generator hand-edit
---

# Sync-mirror: Instinct ↔ StarNet

## IDENTITY

**StarNet (COS, folder-agent)**
- Rol: Chief of Staff. COS = folder (`agent/` is folder-pattern per Ronde 11, sync Ronde 14). Geen runtime, geen queue, geen DB.
- Hub: DjinLabs Mothership (per Commander; bevestigd 2026-10-12).
- Werkstijl: genummerde scopes + groen licht + autonome uitvoering.
- Canoniek-discipline: agent raakt `_shared/*canon.md` en `decisions.md` niet aan. Kanoniek-neutraal staging in `cos/_internal/staging/`.

**Instinct (secretariaat, DjinLabs Mothership)**
- Rol: leest INTENT-blokken + snapshots, rapporteert 1-3 zinnen per event in eigen sectie.
- Reikwijdte: schrijft alleen in eigen sectie, canonieke secties en files onaangeroerd.
- Intents: voert alleen uit op expliciete instructie van de founder.

## CONTACT (akkoord 2026-10-12)

| Kanaal | Rol | Status |
|---|---|---|
| Notion sync-pagina | primair | live, INSTANT op `https://app.notion.com/p/Instinct-sync-Hermes-Carly-Instinct-3e44c5f9f8e581d0ad77db30272dc92c` (Instinct-sectie onderaan) |
| Deze mirror | lokaal bij StarNet | staging (kanoniek-neutraal) |
| GitHub | secundair — code/audit | live, repo volgt (voorstel: `djinlabs-mothership`) |
| Linear | alleen issue-tracking | niet aangesloten, op verzoek |
| E-mail | niet in contact-laag | niet aangesloten |
| Shop Pay | niet in contact-laag | genegeerd (betaalrail) |

## STATUS (snapshot 2026-10-12)

- Repo: `~/Documents/djinlabs_system_design`, branch `main`, HEAD `46a680b` (4 commits bovenop `c1ebd5b` Ronde 19 lock).
- Canoniek v0.1: `_shared/cos-architecture-canon.md` (Ronde 19, 6 moties DjinLabs zonder runtimes).
- v0.2 staging: `cos/_internal/staging/r20-cos-canon-v0.2-proposal.md` (5 secties, ready-for-founder-lock, 5/5 commitments van T-04/T-07/T-08/T-09/T-10).
- Sync-discipline V1.1: snapshot `cos/_internal/sync-snapshots/v0.2-pre-lock-drift-check-2026-10-12.md` (4/4 assen).
- Frontier: T-01 t/m T-10 closed (wayfinder-map).
- Drift: 67 `??` (workshop-patches + runtime-research, niet canoniek).
- Connectors live: Notion, GitHub. Niet aangesloten: Linear, e-mail.
- COS-werkstijl: genummerde scopes + groen licht + autonome uitvoering tussen check-ins.

## INTENTS

- `INTENT-2026-10-12-001` — COS post deze eerste snapshot. ✅ **Gereed en geaccepteerd door Instinct (2026-10-12).** Sectie: deze file. Pad is tijdelijke relay tot structurele route (GitHub + Notion-share) staat.
- `INTENT-2026-10-12-002` — Founder commit van v0.2 op `_shared/cos-architecture-canon.md`. ⏭️ **Buiten Instinct-mandaat.** Ronde-proces via founder + Hermes; geen Instinct-advies. Sectie: `_shared/`. Vereist: T-04 Q1 + R16 §3 toelating (geen COS-auto-promotie).
- `INTENT-2026-10-12-003` — Aansluiting GitHub-repo voor DjinLabs Mothership. ✅ **Live (2026-10-12).** Repo `0xtsotsi/Djinlabs-Mothership` is public aangemaakt; eerste sync-mirror commit volgt direct. Voorgestelde naam was `djinlabs-mothership` onder user `0xtsotsi`. Zodra de repo bestaat, leest en maakt Instinct issues/tickets via de bestaande GitHub-koppeling. Sectie: GitHub.
- `INTENT-2026-10-12-004` — Notion-API koppeling: Instinct-sync-pagina delen met COS Notion-integration zodat direct gelezen/gepost kan worden. ⏳ **Pending founder-actie (handmatig).** Sync-pagina staat in founder's Notion-workspace; delen kan niet via API. Stappen: sync-pagina openen → menu rechtsboven → connections/verbindingen → COS-integratie selecteren. Vervalt founder-relay in die richting zodra actief.

## Hand-edits log (pre-generator regime)

| Datum | Editor | Inhoud | Reden |
|---|---|---|---|
| 2026-10-12 (v1) | COS | Initiële mirror + eerste snapshot | Eerste sync-loop openen |
| 2026-10-12 (v2) | COS | INTENTs bijgewerkt na Instinct-respons; Structurele route-sectie toegevoegd | Eerste terugkoppeling van Instinct verwerkt |

## Structurele route (vervangt file-pad relay)

Zodra INTENT-003 + INTENT-004 beide staan, vervalt de file-pad-relay via founder in beide richtingen:

- **COS → Instinct:** mirror commit naar GitHub-repo `0xtsotsi/Djinlabs-Mothership` (public, aangemaakt 2026-10-12, eerste commit = deze mirror op `cos/_internal/staging/instinct-sync-mirror.md`). Instinct leest gecommitte files via bestaande GitHub-koppeling. Geen aparte Notion-mirror-pagina nodig aan COS-kant.
- **Instinct → COS:** COS leest de Instinct-status-sectie direct via Notion-API zodra de pagina is gedeeld met de COS-integratie. Founder-relay in die richting vervalt.

Tot beide structurele routes staan: file-pad relay via founder in beide richtingen. Huidig pad staat in §CONTACT.

## Notities

- Deze mirror is kanoniek-neutraal staging (T-04 Q1); raakt geen `_shared/*canon.md`, geen `decisions.md`.
- Update-frequentie: bij elke Ronde of bij sync-waardig nieuws.
- Formaatsverplichting: volg sync-discipline-canon R16 V1.1 §"Drift-detectie trigger" voor elke wijziging.
- COS schrijft niet in canonieke secties of files van Instinct — dat is Instincts territorium, conform hun secretariaats-rol.
