# Harlequin Masque — Horus Heresy 1st Edition BattleScribe Repository

Standalone fan-made Harlequin army catalogue for **The Horus Heresy (HH v1)**.

## Data Index URL

`https://raw.githubusercontent.com/kobychapmans-ship-it/Newlequins/main/index.bsi`

## Repository files

This repository deliberately uses the same four-file public layout as the Rangdan Confederacy repository:

- `Harlequin_Masque_HH1.catz`
- `index.bsi`
- `index.xml`
- `README.md`

## Revision 2 — roster-creation compatibility rebuild

Revision 2 is a structural compatibility rebuild for the HH1 BattleScribe game system.

- Targets `(HH V1) Warhammer 30,000 - The Horus Heresy` game-system ID `ca571888-56a9-c58e-ddaf-54f4713538bc`, revision **165**.
- Converts the inherited 7th-edition catalogue profiles from the old BattleScribe 2.00 profile format to BattleScribe 2.03.
- Replaces 7th-edition profile type IDs with the HH1 game-system profile IDs for Unit, Vehicle, Weapon, Wargear Item, Transport and Psyker profiles.
- Replaces all old characteristic IDs with the matching HH1 characteristic IDs.
- Converts old `profileTypeId`, `characteristicTypeId` and `costTypeId` attributes to the BattleScribe 2.03 `typeId` structure.
- Removes catalogue-local profile/cost type definitions so the official HH1 `.gst` supplies them.
- Re-targets live characteristic modifiers, including the Playwright's Skyweaver Jetbike +1 Toughness and +1 Wound, to the HH1 characteristic fields.
- Keeps the standard Crusade Detachment and adds a normal Allied Detachment.
- Keeps all core Harlequin units and the custom Playwright Masque additions.
- Keeps the revised Veil Mime `Silent Performance` timing in normal battle order.

## Crusade Detachment

- HQ: 1–3
- Troops: 2–6
- Elites: 0–4
- Fast Attack: 0–3
- Heavy Support: 0–3
- Lords of War: 0–1, maximum 25% of roster points
- Dedicated Transports: available separately

## Allied Detachment

- HQ: 1
- Troops: 1–2
- Elites: 0–1
- Fast Attack: 0–1
- Heavy Support: 0–1
- Dedicated Transports: available separately

## Core Harlequin units retained

Troupe, Shadowseer, Death Jester, Solitaire, Skyweavers, Starweaver and Voidweavers.

## New Playwright Masque units

- Playwright
- Unwritten Players
- Continuity Blades
- Veil Mimes
- Helion Sky Jesters
- Wraith-Mime
- Wraith-Chorister
- Grand Marionette
- Vampire Masquerade

## New armoury

Phractal Phase Blade, Phractal Phase Lance, Phractal Phase Dagger, Heart Phase Gauntlet, Riveblades, Helical Scythe Pinions, Linked Prism Pistols, Blind-Barrage Launcher, Tearè Grenades, Goesh Gyer Mask, Helion Skyboard and Writ of the Great Jest.

## Updating after Revision 1

After replacing the four repository files, refresh the Newlequins data source. If BattleScribe has cached Revision 1, delete the local Harlequin Masque catalogue/data and refresh this repository so Revision 2 downloads cleanly.
