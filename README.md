# Newlequins Horus Heresy 1.0 — Revision 10

BattleScribe: **2.03** · Game system revision: **165** · Catalogue revision: **10**.

## Sources
- Prior Newlequins Revision 9 catalogue (retains all homebrew units, detachments, and upgrades).
- User-uploaded **New Rosterd.html**, BattleScribe 7th-edition Harlequins roster, for weapon statistics, Solitaire cost, special-rule text, and ordinary Harlequin wargear.
- `https://github.com/BSData/wh40k-7th-edition` is the relevant published 7th-edition reference repository.
- Homebrew profiles not established by the attached roster retain the previous catalogue's values rather than being guessed.

## Death Jester
- Replaced only the Death Jester's generic Shrieker Cannon selection with a **Death Jester Shrieker Cannon** equipment entry.
- It has **both** 7th-edition firing profiles:
  - Shrieker: 24", S1, AP5, Assault 1, Bio-explosive, Bladestorm, Pinning, Poisoned (2+).
  - Shuriken: 24", S6, AP5, Assault 3, Bladestorm.
- It displays Bio-explosive, Bladestorm, Pinning and Poisoned (2+) from the source.
- Replaced the old abbreviated Death Is Not Enough and Precision Shots descriptions with the supplied 7e rules; Independent Character linked.
- Wraith-Mime's **generic** Shrieker Cannon is deliberately unchanged.

## Solitaire
- Maintained the official **145pts** base price from the uploaded roster.
- Removed duplicate mandatory +5pt Kiss and +8pt Caress links from the Solitaire unit entry: its **included paired** standard weapons now supply their own weapon profiles and rules at zero added points.
- Cegorach's Rose + Caress remains an optional separate **+15pt** substitution; the 0-point Kiss + Caress is the default option.
- Restored full source descriptions for Blitz, Impossible Form, Prismatic Blur, The Path of Damnation and Precision Strikes.
- Added Fearless and Deep Strike info links in accordance with the source.

## Reference equipment and rules
- Updated 11 existing shared-rule descriptions and installed 19 new shared-rule records; refreshed 13 local source-matched special rules.
- Restored 13 missing rule links to weapon-containing equipment entries.
- Corrected published Miststave, Harlequin's Caress, Harlequin's Embrace, Star Bolas and Zephyrglaive profiles where present.
- Corrected published Prismatic Cannon profiles to three firing modes: Dispersed, Focussed and Lance.
- Added the **Plasma Grenade** throwing profile to Plasma Grenades.
- Corrected abbreviated Flip Belt, Holo-suit, Holo-fields and Mirage Launchers equipment descriptions from the attached 7e export.
- Retains custom Orchestral Prism Array, custom Shrieker Battery and other Newlequins-only weapon profiles without inventing new statistics.

## Validation
- Duplicate XML IDs: **0**.
- Broken local entry/info/category references: **0**.
- Solitaire standard 145pt selection: **confirmed** (paired standard weapons cost 0).
- Death Jester Shrieker Cannon firing profiles: **2**.
- Prismatic Cannon firing profiles: **3**.
- No runtime roster-export test was run inside the BattleScribe application.

## Repository import
Extract these four files into the repository root, replacing previous `index.xml`, `index.bsi`, README and old catalogue files. Remove the previous `Newlequins_HH1_v165_r9.catz` or leave it unreferenced; index.bsi points only to the new R10 catalogue.

Data index: `https://raw.githubusercontent.com/kobychapmans-ship-it/Newlequins/main/index.bsi`
