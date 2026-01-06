# Azurea: Factions Development Brief

## Purpose

This document serves as a project brief for developing detailed faction files across the Azurea worldbuilding project. It captures what's been established, what needs development, and provides templates and guidelines for maintaining consistency.

---

# Part One: Project Context

## What Already Exists

| Document                        | Contents                                                                |
| ------------------------------- | ----------------------------------------------------------------------- |
| **azurea_factions_overview.md** | Master index with 1-paragraph summaries for all major factions          |
| **Cosmology Tradition Files**   | Religious/cultural background for traditions (Light, Dark, Death, etc.) |
| **Geography Region Files**      | Political/economic factions embedded in regional development            |

## Development Goal

Create dedicated files for each major faction, providing:
- Detailed organizational structure
- Key figures with goals and complications
- Relationships with other factions
- Adventure hooks for gameplay use

---

# Part Two: Directory Structure

```
/Factions
├── azurea_factions_overview.md
├── azurea_factions_development_brief.md
├── Religious/
│   ├── the_solarian_church.md
│   ├── the_scouring.md
│   ├── the_flagellants.md
│   ├── the_monastics.md
│   ├── the_academics.md
│   ├── the_theosyn_revival.md
│   ├── the_axis_faith.md
│   ├── the_ostaran_tradition.md
│   ├── the_revnan_tradition.md
│   └── the_alysian_tradition.md
├── Political/
│   ├── the_regency_council.md
│   ├── the_church_hierarchy.md
│   ├── the_bridge.md
│   ├── the_council_of_captains.md
│   ├── the_duke_of_oakhold.md
│   └── the_northern_jarls.md
├── Economic/
│   ├── the_major_trading_houses.md
│   ├── the_guilds.md
│   └── the_shiranui_consortium.md
├── Cultural/
│   ├── the_goleuwyr.md
│   ├── the_urkhani.md
│   └── the_dragon_kin_hegemony.md
└── Undersea_Underworld/
    ├── the_ti_abzu.md
    ├── the_abgal_tako.md
    ├── the_rot_wendan.md
    ├── the_eald_delfen.md
    └── the_gastberend.md
```

**Total: 27 faction files**

---

# Part Three: Development Status

## Status Key

| Symbol | Meaning       | Description                                          |
| ------ | ------------- | ---------------------------------------------------- |
| ✅      | **Complete**  | Dedicated file with full development                 |
| ⚠️      | **Partial**   | Some information exists in Cosmology/Geography files |
| ❌      | **Needs Dev** | Named only, minimal detail                           |

## Religious Factions

| Faction                    | Status     | Target File                          | Notes                                   |
| -------------------------- | ---------- | ------------------------------------ | --------------------------------------- |
| The Solarian Church (Core) | ✅ Complete | `Religious/the_solarian_church.md`   | Structure in Cosmology; needs expansion |
| The Scouring               | ✅ Complete | `Religious/the_scouring.md`          | Militant zealots                        |
| The Flagellants            | ✅ Complete | `Religious/the_flagellants.md`       | Blood Field connection                  |
| The Monastics              | ✅ Complete | `Religious/the_monastics.md`         | Knowledge preservers                    |
| The Academics              | ✅ Complete | `Religious/the_academics.md`         | Doctrine questioners                    |
| The Theosyn Revival        | ✅ Complete | `Religious/the_theosyn_revival.md`   | Gods remembering names                  |
| The Axis Faith             | ✅ Complete | `Religious/the_axis_faith.md`        | Dwarven tradition                       |
| The Ostaran Tradition      | ✅ Complete | `Religious/the_ostaran_tradition.md` | Death/ancestor veneration               |
| The Revnan Tradition       | ✅ Complete | `Religious/the_revnan_tradition.md`  | Shadow/depth wisdom                     |
| The Alysian Tradition      | ✅ Complete | `Religious/the_alysian_tradition.md` | Folk/land practice                      |

## Political Factions

| Faction                 | Status     | Target File                            | Notes                         |
| ----------------------- | ---------- | -------------------------------------- | ----------------------------- |
| The Regency Council     | ✅ Complete | `Political/the_regency_council.md`     | Aurheim government            |
| The Church Hierarchy    | ✅ Complete | `Political/the_church_hierarchy.md`    | Vandgwyn power structure      |
| The Bridge              | ✅ Complete | `Political/the_bridge.md`              | Castellum Pontem independence |
| The Council of Captains | ✅ Complete | `Political/the_council_of_captains.md` | Golden Coast government       |
| The Duke of Oakhold     | ✅ Complete | `Political/the_duke_of_oakhold.md`     | Kingswood authority           |
| The Northern Jarls      | ✅ Complete | `Political/the_northern_jarls.md`      | Fragmented northern lords     |

## Economic Factions

| Faction                  | Status     | Target File                            | Notes                     |
| ------------------------ | ---------- | -------------------------------------- | ------------------------- |
| The Major Trading Houses | ✅ Complete | `Economic/the_major_trading_houses.md` | Merchant families         |
| The Guilds               | ✅ Complete | `Economic/the_guilds.md`               | Craft/trade organizations |
| The Shiranui Consortium  | ✅ Complete | `Economic/the_shiranui_consortium.md`  | Eastern trade alliance    |
| The Bridge               | ✅ Complete | `Economic/the_bridge.md`               | Criminal network          |

## Cultural Factions

| Faction                 | Status     | Target File                           | Notes                      |
| ----------------------- | ---------- | ------------------------------------- | -------------------------- |
| The Goleuwyr            | ✅ Complete | `Cultural/the_goleuwyr.md`            | Elves (Light children)     |
| The Urkhani             | ✅ Complete | `Cultural/the_urkhani.md`             | Shadow-kin (Dark children) |
| The Dragon-Kin Hegemony | ✅ Complete | `Cultural/the_dragon_kin_hegemony.md` | Southern dragon servants   |
| The Hafsbrœðr           | ✅ Complete | `Cultural/the_hafsbroedr.md`          | Wylltic Sea-Brothers       |
| The Völva Circle        | ✅ Complete | `Cultural/the_volva_circle.md`        | Wylltic seers/prophets     |
| The Wylltic Lords       | ✅ Complete | `Cultural/the_wylltic_lords.md`       | Wild Isle aristocracy      |

## Undersea & Underworld Factions

| Faction         | Status     | Target File                              | Notes               |
| --------------- | ---------- | ---------------------------------------- | ------------------- |
| The Ti-Abzu     | ✅ Complete | `Undersea_Underworld/the_ti_abzu.md`     | Mid-depth humanoids |
| The Abgal-Tako  | ✅ Complete | `Undersea_Underworld/the_abgal_tako.md`  | Cephalopod sages    |
| The Rot-Wendan  | ✅ Complete | `Undersea_Underworld/the_rot_wendan.md`  | Decay-Turners       |
| The Eald-Delfen | ✅ Complete | `Undersea_Underworld/the_eald_delfen.md` | Deep Dwarves        |
| The Gastberend  | ✅ Complete | `Undersea_Underworld/the_gastberend.md`  | Hospitality spirits |

---

# Part Four: Development Template

## For Each Faction, Develop:

### 1. Overview
| Element             | Description                                                         |
| ------------------- | ------------------------------------------------------------------- |
| **Type**            | Religious / Political / Economic / Cultural / Undersea / Underworld |
| **Status**          | Active / Fractured / Hidden / Emerging                              |
| **Scope**           | Imperial / Regional / Local                                         |
| **Primary Base**    | Where are they headquartered?                                       |
| **Symbol/Heraldry** | Visual identity (or "None formal")                                  |
| **Summary**         | 1-2 paragraphs on identity and purpose                              |

### 2. Leadership & Hierarchy
| Element                | Description                                  |
| ---------------------- | -------------------------------------------- |
| **Structure**          | How is the faction organized?                |
| **Current Leadership** | Table of positions and holders               |
| **Power Dynamics**     | Who actually holds power? Internal factions? |

### 3. Key Figures (2-3 per faction)
| Element          | Description                               |
| ---------------- | ----------------------------------------- |
| **Name**         | Full name and titles                      |
| **Role**         | Formal position and actual function       |
| **Age**          | Approximate                               |
| **Character**    | 1-2 paragraphs on personality and history |
| **Goal**         | What do they want?                        |
| **Complication** | What's stopping them?                     |

### 4. Goals & Tensions
| Element               | Description                   |
| --------------------- | ----------------------------- |
| **Primary Goal**      | The faction's main objective  |
| **Secondary Goals**   | Other significant aims        |
| **Internal Tensions** | Conflicts within the faction  |
| **External Tensions** | Conflicts with other factions |

### 5. Assets & Resources
| Element                  | Description                          |
| ------------------------ | ------------------------------------ |
| **Material Resources**   | Wealth, property, goods              |
| **Institutional Power**  | What institutions do they control?   |
| **Military/Enforcement** | Armed forces, guards, enforcers      |
| **Knowledge & Secrets**  | What do they know that others don't? |

### 6. Relationships
| Element              | Description            |
| -------------------- | ---------------------- |
| **Allied Factions**  | Who do they work with? |
| **Neutral Factions** | Who do they tolerate?  |
| **Hostile Factions** | Who are their enemies? |

### 7. Adventure Hooks (3-5 per faction)
| Element           | Description                |
| ----------------- | -------------------------- |
| **Situation**     | The setup                  |
| **The Question**  | What needs to be resolved? |
| **Complications** | What makes it difficult?   |

---

# Part Five: Development Queue

## Round 1: Core Power Players (Priority 1)

These factions are central to the post-Passing political situation and should be developed first.

| Priority | Faction                     | Notes                              |
| -------- | --------------------------- | ---------------------------------- |
| 1.1      | **The Regency Council**     | Aurheim's fragile government       |
| 1.2      | **The Church Hierarchy**    | Vandgwyn's power structure         |
| 1.3      | **The Solarian Church**     | Expand core religious institution  |
| 1.4      | **The Council of Captains** | Golden Coast's merchant government |

## Round 2: Militant & Economic Powers (Priority 2)

| Priority | Faction                      | Notes                             |
| -------- | ---------------------------- | --------------------------------- |
| 2.1      | **The Scouring**             | Militant faction burning heretics |
| 2.2      | **The Major Trading Houses** | Economic power players            |
| 2.3      | **The Shiranui Consortium**  | Eastern influence                 |
| 2.4      | **The Northern Jarls**       | Fragmented northern authority     |

## Round 3: Religious Traditions (Priority 3)

| Priority | Faction                   | Notes             |
| -------- | ------------------------- | ----------------- |
| 3.1      | **The Theosyn Revival**   | Gods waking up    |
| 3.2      | **The Axis Faith**        | Dwarven tradition |
| 3.3      | **The Ostaran Tradition** | Death veneration  |
| 3.4      | **The Alysian Tradition** | Folk practice     |

## Round 4: Cultural Groups (Priority 4)

| Priority | Faction                     | Notes          |
| -------- | --------------------------- | -------------- |
| 4.1      | **The Goleuwyr**            | Elvish people  |
| 4.2      | **The Urkhani**             | Shadow-kin     |
| 4.3      | **The Dragon-Kin Hegemony** | Southern power |

## Round 5: Undersea & Underworld (Priority 5)

| Priority | Faction             | Notes               |
| -------- | ------------------- | ------------------- |
| 5.1      | **The Ti-Abzu**     | Mid-depth humanoids |
| 5.2      | **The Abgal-Tako**  | Cephalopod sages    |
| 5.3      | **The Rot-Wendan**  | Decay-Turners       |
| 5.4      | **The Eald-Delfen** | Deep Dwarves        |
| 5.5      | **The Gastberend**  | Hospitality spirits |

## Round 6: Remaining Factions (Priority 6)

| Priority | Faction                  | Notes                   |
| -------- | ------------------------ | ----------------------- |
| 6.1      | **The Flagellants**      | Blood Field connection  |
| 6.2      | **The Monastics**        | Knowledge preservers    |
| 6.3      | **The Academics**        | Doctrine questioners    |
| 6.4      | **The Revnan Tradition** | Shadow tradition        |
| 6.5      | **The Bridge**           | Neutral strategic point |
| 6.6      | **The Duke of Oakhold**  | Kingswood authority     |
| 6.7      | **The Guilds**           | Craft organizations     |

---

# Part Six: Session Instructions

## Starting a New Session

When beginning a new conversation to continue this work:

1. **Provide this document** as context
2. **Specify which faction** you want to develop (reference the queue in Part Five)
3. **Provide relevant source files** (the overview, any Cosmology/Geography files that mention the faction)
4. **Note any completed work** since last session (update the status table)

## Example Prompt

> "This is a continuation of the Azurea worldbuilding project. Please see the attached Factions Development Brief for context.
> 
> We're working on **Round 1: Core Power Players**.
> 
> Please develop **1.1 The Regency Council** using the template in Part Four."

## After Each Session

Update this document:
1. Change status from ❌ or ⚠️ to ✅ for completed factions
2. Note any new NPCs, locations, or relationships created
3. Record any decisions that affect other factions

---

# Appendix: Cross-Reference

## Factions by Source File

| Source File                          | Factions Mentioned                                               |
| ------------------------------------ | ---------------------------------------------------------------- |
| `The_Solarian_Church.md`             | Solarian Church, Scouring, Flagellants, Monastics, Academics     |
| `azurea_crown_lands_development.md`  | Regency Council, Church Hierarchy, The Bridge                    |
| `azurea_golden_coast_development.md` | Council of Captains, Trading Houses, Guilds, Shiranui Consortium |
| `azurea_kingswood_development.md`    | Duke of Oakhold, Alysian Tradition                               |
| `azurea_fjordlands_development.md`   | Northern Jarls                                                   |
| `Goleuwyr_Adaptation.md`             | Goleuwyr                                                         |
| `azurea_dragonlands_development.md`  | Dragon-Kin Hegemony                                              |

---

*Document Version: 2.0*
*Last Updated: January 2026*
*ALL FACTIONS COMPLETE — Development Queue Finished*
