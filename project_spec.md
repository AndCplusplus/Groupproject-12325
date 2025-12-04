
## Table of Contents

1. [App Overview](#App-Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
1. [Build Notes](#Build-Notes)

## App Overview
Build your roster for a game of kill team
### Description 

**Uses Battlescribe API to select and build a playable roster of units for the tabletop game known as kill team**

### App Evaluation

<!-- Evaluation of your app across the following attributes -->

- **Category:** tabletop
- **Mobile:** easy access to stats and knowledge
- **Story:** Pull up your teams info during a game
- **Market:** tabletop players
- **Habit:** Users open the app before a match and during a match to make changes and see stats
- **Scope:** Small

## Product Spec

### 1. User Features (Required and Optional)

Required Features:

- Selectable teams
- Selectable units
- Saved teams

Stretch Features:

- tac ops
- unit stats

### 2. Chosen API(s)

- https://github.com/BSData/wh40k-killteam
- ...



### 3. User Interaction

Required Feature

- User selects team 
- User selects legal units the team has
    - Team gets saved and is able to be viewed anytime.

## Wireframes

![](https://i.imgur.com/6FmBzwc.png)

┌───────────────────────────────┐
│ App Splash / Load Data        │     // On first load fetch + cache data
└───────────────────────────────┘
             ↓
┌───────────────────────────────┐
│ Home / Faction List           │     // List of factions (e.g. Aeldari, Chaos, etc)
│ ───────────────────────────── │
│ [Search bar]                  │
│ ┌Faction A________]           │
│ ┌Faction B________]           │
│ ┌Faction C________]           │
└───────────────────────────────┘
             ↓  (tap faction)
┌───────────────────────────────┐
│ Kill-Team / Sub-faction List  │     // After selecting faction
│ ┌KillTeam X__________]        │
│ ┌KillTeam Y__________]        │
│ ┌KillTeam Z__________]        │
└───────────────────────────────┘
             ↓  (tap kill-team)
┌───────────────────────────────┐
│ Unit / Operative List         │     // All possible units/operatives for that kill-team
│ ┌Unit 1  [+]  (cost, stats)   │
│ ┌Unit 2  [+]  (cost, stats)   │
│ ┌Unit 3  [+]  (cost, stats)   │
│ ...                           │
└───────────────────────────────┘
             ↓  (tap + / select)
┌───────────────────────────────┐
│ Roster / Build Screen         │     // Current team being built
│ ┌Selected Unit 1  [-]        │
│ ┌Selected Unit 2  [-]        │
│ ┌Unit 3 (dropdown: upgrades) │
│ ┌Total Points:  XXX          │
│ ┌Validate / Save Roster       │
└───────────────────────────────┘
             ↓  (save / export)
┌───────────────────────────────┐
│ Saved Rosters / Load Roster   │     // List of user's saved teams
│ ┌Roster Alpha [view / edit]   │
│ ┌Roster Beta  [view / edit]   │
└───────────────────────────────┘




## Build Notes

Here's a place for any other notes on the app, it's creation 
process, or what you learned this unit!  

For Milestone 2, include **2+ Videos/GIFs** of the build process here!

## License

Copyright **yyyy** **your name**
