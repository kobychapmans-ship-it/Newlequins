# Newlequins — BattleScribe HH v1 repository

Revision 7 is rebuilt to use the uploaded working Rangdan Confederacy repository as the structural baseline.

## Repository files
- `Harlequin_Masque_HH1.catz`
- `index.bsi`
- `index.xml`
- `README.md`

## Data Index URL
`https://raw.githubusercontent.com/kobychapmans-ship-it/Newlequins/main/index.bsi`

## HH1 target
- Game system ID: `ca571888-56a9-c58e-ddaf-54f4713538bc`
- Game system revision: **165**
- BattleScribe version: **2.03**

## Structural baseline
The catalogue follows the same top-level layout as the supplied working Rangdan catalogue:
1. publications
2. categoryEntries
3. forceEntries
4. entryLinks
5. sharedSelectionEntries
6. sharedRules
7. sharedProfiles

Root unit links and shared selection entries use `import="true"` like the Rangdan baseline.
Dedicated Transports are nested inside eligible units instead of existing as their own force-org category.

## Crusade Detachment
- HQ 1–3
- Troops 2–6
- Elites 0–4
- Fast Attack 0–3
- Heavy Support 0–3
- Lords of War 0–1, maximum 25% of roster points

## Roster
HQ: Playwright, Shadowseer
Troops: Troupe, Unwritten Players
Elites: Death Jester, Solitaire, Continuity Blades, Veil Mimes
Fast Attack: Skyweavers, Starweaver, Helion Sky Jesters
Heavy Support: Voidweavers, Wraith-Mime, Wraith-Chorister
Lords of War: Grand Marionette, Vampire Masquerade

Starweaver Dedicated Transport access is nested under Troupe, Unwritten Players, Continuity Blades and Veil Mimes.

## Model options
- Melee Weapon: exactly one choice
- Ranged Weapon: exactly one choice
- Unique Equipment: as many individual options as allowed

## Audit
Top-level layout exact baseline match: True
Missing expected units: 0
Missing restored/custom upgrades: 0
Duplicate IDs: 0
Unresolved entry links: 0
Unresolved info links: 0
Unresolved category links: 0
Unresolved condition targets: 0
Root entry category/import issues: 0
Selection group structural issues: 0
Missing Melee/Ranged/Unique sections: 0
Root unit categories absent from Crusade Detachment: 0
Extra top-level catalogue sections: 0
Missing baseline top-level catalogue sections: 0
