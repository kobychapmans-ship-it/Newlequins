# Newlequins HH1 — Revision 6 Full Audit

Revision 6 keeps the Revision 5 roster content but hardens the repository delivery layer.

## Repository delivery changes

The index now contains:

- A canonical `repositoryUrl` pointing directly to the public Newlequins `index.bsi`.
- An absolute raw GitHub URL for `Harlequin_Masque_HH1.catz`, instead of relying on relative URL resolution.
- Catalogue/index revision bumped to **6**.

This is intended to eliminate BattleScribe mobile resolving the catalogue against an incorrect base path.

## Full catalogue audit results

The Revision 5/6 catalogue was checked for:

- duplicate IDs
- unresolved `entryLink` targets
- unresolved `infoLink` targets
- unresolved category targets
- unresolved condition targets
- invalid modifier field targets
- invalid profile type IDs
- invalid characteristic IDs
- invalid cost types
- mandatory option groups with no choices
- min/max selection conflicts
- units without profiles/models
- units without root selectable entries
- root entries without primary HH1 categories
- force organisation categories not linked to the Crusade Detachment

All of these checks returned **0 structural errors**.

## Content present

### HQ
- Playwright
- Shadowseer

### Troops
- Troupe
- Unwritten Players

### Elites
- Death Jester
- Solitaire
- Continuity Blades
- Veil Mimes

### Fast Attack
- Skyweavers
- Starweaver
- Helion Sky Jesters

### Heavy Support
- Voidweavers
- Wraith-Mime
- Wraith-Chorister

### Lords of War
- Grand Marionette
- Vampire Masquerade

### Dedicated Transport
- Starweaver

The Revision 5 model option layout is retained:
- one Melee Weapon choice
- one Ranged Weapon choice
- multiple Unique Equipment selections where allowed

## Recommended data-source URL

Primary:
`https://raw.githubusercontent.com/kobychapmans-ship-it/Newlequins/main/index.bsi`

Diagnostic alternative:
`https://raw.githubusercontent.com/kobychapmans-ship-it/Newlequins/main/index.xml`

If `index.xml` works while `index.bsi` does not, the problem is BattleScribe's handling/cache of the compressed index rather than the repository catalogue.
