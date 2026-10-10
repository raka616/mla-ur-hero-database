
# Mobile Legends: Adventure — UR Hero Database

**Data Contributor: Muhammad Raka Prasetya**

An independent community database documenting Ultra Rare (UR) heroes in Mobile Legends: Adventure (MLA), including release dates, notable characteristics, gameplay mechanics, and contributor observations.

## About This Database

This database compiles 21 UR heroes based on information provided by Muhammad Raka Prasetya. Its purpose is to document hero release history, unique abilities, attribute scaling, team synergy, and gameplay strategies.

The information is organized into release timelines, hero notes, and featured mechanics. Details that have not been independently verified are identified as contributor-provided information.


## UR Hero Release List

### 2023

| No. | Hero | Release Date |
|---:|---|---|
| 1 | Achlys Alice | 26 May 2023 |
| 2 | Eos Silvanna | 28 July 2023 |
| 3 | Ember Irithel | 29 September 2023 |
| 4 | Helia Karihmet | 1 December 2023 |

### 2024

| No. | Hero | Release Date |
|---:|---|---|
| 5 | Mystic Mystia | 2 February 2024 |
| 6 | Singularity Lunox | 29 March 2024 |
| 7 | Erza | 12 July 2024 |
| 8 | Everblight Shah Torre | 6 September 2024 |
| 9 | Genesis Shar | 1 November 2024 |
| 10 | Skuld Norns | 27 December 2024 |

### 2025

| No. | Hero | Release Date |
|---:|---|---|
| 11 | Sentient Alina | 21 February 2025 |
| 12 | Infinia Crocell | 18 April 2025 |
| 13 | Apexis Cluster | 13 June 2025 |
| 14 | Noctis Tokinibara | 8 August 2025 |
| 15 | Kryos Sinmara | 17 October 2025 |
| 16 | Heartcore Angela | 28 November 2025 |

### 2026

| No. | Hero | Release Date |
|---:|---|---|
| 17 | Lionheart Sekhet | 16 January 2026 |
| 18 | Omniversal Akashic | 20 March 2026 |
| 19 | Nightseer Esmeralda | 15 May 2026 |
| 20 | Empyrean Ingrid | 10 July 2026 |
| 21 | Aeon Rista | 4 September 2026 |

## Featured Mechanics: Genesis Shar

**Mechanics contributor: Muhammad Raka Prasetya**

The following section records gameplay observations supplied by the contributor. These mechanics should be checked against current in-game descriptions and testing.

### Enemy Copy Mechanic

- Genesis Shar can create a copy of an enemy hero that fights as an allied unit.
- The copied hero can contribute additional actions and battlefield control.
- According to the contributor, crowd-control interactions can disrupt enemy positioning and influence enemy targeting.

### Skill Interactions

According to the contributor's observations:

- At full Awaken (A0), the copy can benefit from effects associated with Genesis Shar's own Soul Skill and Orlay Skill upgrade levels.
- These effects are described as depending on Genesis Shar's upgrades rather than the copied hero's corresponding upgrade levels.

### Attribute Scaling

The contributor describes the copy's HP and Attack as scaling with Genesis Shar's Star Level.

At Star Level 9, the contributor-provided model is:

`Clone stats = min(140% × enemy stats, 700% × Genesis Shar stats)`

In this model:

- `140% × enemy stats` represents the enemy-relative scaling limit.
- `700% × Genesis Shar stats` represents the cap based on Genesis Shar's own attributes.
- The lower of these two values determines the modeled clone stats.

This is a contributor-provided interpretation of the mechanic, not an independently verified official formula.

### Investment Considerations

Based on this model, improving Genesis Shar's own attributes may increase the cap on the copied hero's stats. Star Level, Soul Vessel, Orlay, and Glory are areas the contributor identifies for further testing.

## Future Documentation

Planned additions include:

- Skill descriptions and unique mechanics for every UR hero.
- Attribute scaling and upgrade breakpoints.
- Team synergy and counterplay.
- PvE and PvP applications.
- Soul Vessel, Orlay, Glory, and Star Level investment notes.
- Official references and reproducible in-game testing where available.

## Contributor & Attribution

**Primary Data Contributor: Muhammad Raka Prasetya**

The initial list of 21 heroes, release dates, and gameplay observations in this repository were compiled from information provided by Muhammad Raka Prasetya.

New contributions should identify their authors and cite supporting references whenever possible.

## Disclaimer

This is an independent community documentation project. It is not an official Mobile Legends: Adventure website and is not affiliated with or endorsed by the game's developers.

Release dates, event details, hero classifications, and gameplay mechanics should be cross-checked against official announcements and current in-game information. All game names and trademarks belong to their respective owners.
