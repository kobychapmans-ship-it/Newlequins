# Newlequins — Horus Heresy 1st Edition BattleScribe Repository

## Revision 4 — HH1 force-organisation category fix

This revision fixes the issue where every unit appeared under **Uncategorised**.

The previous catalogue placed category IDs on the root `entryLink` using the legacy `categoryEntryId` attribute. Horus Heresy 1st Edition BattleScribe catalogues instead use a nested `categoryLinks` block on each root entry link, with a `primary="true"` category link.

Revision 4 now follows the official HH1 structure:

```xml
<entryLink ...>
  <categoryLinks>
    <categoryLink name="Troops" targetId="..." primary="true"/>
  </categoryLinks>
</entryLink>
```

### Crusade Detachment
- HQ: 1–3
- Troops: 2–6
- Elites: 0–4
- Fast Attack: 0–3
- Heavy Support: 0–3
- Lords of War: 0–1, maximum 25% of the army
- Dedicated Transport

### Units by slot

**HQ**
- Playwright
- Shadowseer

**Troops**
- Troupe
- Unwritten Players

**Elites**
- Death Jester
- Solitaire
- Continuity Blades
- Veil Mimes

**Fast Attack**
- Skyweavers
- Starweaver
- Helion Sky Jesters

**Heavy Support**
- Voidweavers
- Wraith-Mime
- Wraith-Chorister

**Lords of War**
- Grand Marionette
- Vampire Masquerade

**Dedicated Transport**
- Starweaver

## Structural verification

- Root entries converted to HH1 categoryLinks: 17
- Root category problems: 0
- Force-category problems: 0
- Unit categories absent from Crusade Detachment: 0
- Duplicate IDs: 0
- Unresolved entry links: 0
- Unresolved info links: 0
- Unresolved category links: 0

## Repository URL

`https://raw.githubusercontent.com/kobychapmans-ship-it/Newlequins/main/index.bsi`
