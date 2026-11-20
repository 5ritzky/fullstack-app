# STATUS — Social RPG

> A social RPG about power, dependence, alliances, independence and hierarchy — where status should follow from social facts, not from a score alone.

**[▶ Play STATUS BETA](https://5ritzky.github.io/fullstack-app/status-beta/)** · **[Playtest guide](PLAYTEST.md)** · **[Русская версия README](README.ru.md)**

**Current build:** `v0.4.0-beta`  
**Game languages:** Русский · English · Deutsch · Español  
**Platform:** Browser · GitHub Pages  
**Setting:** Meridian Group

## What is STATUS?

STATUS is an experimental narrative social RPG. The player navigates a corporate environment where choices can affect relationships, obligations, access to information and social position.

The central design question is:

**Why do specific actions lead to a specific social position — and what evidence would make other characters recognise that position?**

The project explores four broad approaches to the social environment:

- **Cooperation** — working with others and building reciprocal trust.
- **Independence** — protecting autonomy and acting without relying on a group.
- **Confrontation** — openly challenging decisions, authority or unfair treatment.
- **Alliances** — coordinating interests and building support with other characters.

The game model separates R/S/P indicators from relationships, story facts, obligations, events, status and access. A score change alone is not intended to grant a social status.

## What this BETA contains

- A browser-playable experimental story arc set in Meridian Group.
- Four NPC profiles.
- R/S/P indicators, relationship values and obligations.
- A visible record of consequences and social events.
- Eight status concepts represented in the model.
- Four interface/story languages: RU / EN / DE / ES.
- Undo, save export and import controls.
- A tester feedback form that creates a report locally for the player to copy or download.
- A defined ending for the current test arc.

## Important: what this BETA is — and is not

This build is a **mechanics demonstration for playtesting**, not a final commercial release.

The current status-transition rules are an experimental, testable hypothesis. They are **not a replacement for the approved v0.3 model**. In particular, playtesters should report cases where a status appears unsupported by social facts, where a required transition cannot be reached, or where the consequences are unclear.

The purpose of this BETA is to expose inconsistencies and gather reproducible evidence before the status rules are treated as final.

## How to play and help

1. [Open the browser game](https://5ritzky.github.io/fullstack-app/status-beta/).
2. Select one of the four available languages.
3. Complete the current story arc. Follow a consistent approach rather than trying to guess a “correct” answer.
4. Pay attention to relationships, obligations, delayed consequences and the explanation of the final status.
5. Use the in-game **Tester feedback** section. The report is generated on your device; it is not submitted automatically.
6. [Read the playtest guide](PLAYTEST.md), then submit a report using one of the GitHub issue templates:
   - [Technical bug](https://github.com/5ritzky/fullstack-app/issues/new?template=bug_report.md)
   - [Game logic / status transition](https://github.com/5ritzky/fullstack-app/issues/new?template=game_logic.md)
   - [Translation / localization](https://github.com/5ritzky/fullstack-app/issues/new?template=localization.md)

A useful report describes **what you did, what you expected, what actually happened, and how to reproduce it**. You do not need to share your name or other personal information.

## Privacy and local data

The current game page states that it uses no cookies, advertising or server-side event uploads. Game saves and generated feedback reports are handled locally in the browser. The browser may clear local saves. Reports must be copied or downloaded and submitted manually if you want the team to receive them.

Do not include passwords, personal identifiers or confidential information in a report.

## Project status

The public BETA is being used to test:

1. Whether the four approaches produce meaningfully different consequences.
2. Whether relationships and obligations affect later scenes.
3. Whether social status transitions are reachable and supported by observable facts.
4. Whether the current story arc feels complete without relying on promised future content.

The BETA should not yet be treated as proof that these criteria have been met.

## Repository structure

- `status-beta/` — browser game build published through GitHub Pages.
- `PLAYTEST.md` — playtest protocol (Russian and English).
- `.github/ISSUE_TEMPLATE/` — structured feedback templates.

The game is currently published from the `status-beta-2026-11` branch. Project documentation and issue templates are maintained on the default `main` branch.

## Contributing feedback

Please use the issue templates rather than opening a general issue with no reproduction details. For discussion or questions, see the repository’s Issues area. Community Discussions may be enabled separately after the initial playtest setup.

## License

No repository license has been declared yet. Until a license is added, do not assume that the game code, text or other project assets may be reused or redistributed.
