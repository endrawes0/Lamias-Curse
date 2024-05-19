# Lamia's Curse
A Scrabble-based Deck-building Roguelike Dungeon Crawler

# Game Design Document
### Game Title
Lamia's Curse

### Subtitle (if any)
TBD

### Date
Ideation: May 12, 2024  
First playable draft: May 18, 2024  
Design doc created: May 18, 2024  
Updated: May 19, 2024

### Author(s)
Andrew Haddad, with inspiration and QA testing from his loving wife and nerdy brother.

## Table of Contents
 - [Executive Summary](#Executive-Summary)
 - [Gameplay Mechanics](#Gameplay-Mechanics)
 - [Story and Narrative](#Story-and-Narrative)
 - [Level Design](#Level-Design)
 - [Visual Design](#Visual-Design)
 - [Audio Design](#Audio-Design)
 - [Technical Requirements](#Technical-Requirements)
 - [User Interface](#User-Interface)
 - [Multiplayer](#Multiplayer)
 - [Appendices](#Appendices)

## Executive Summary
### Game Overview
The player moves through a series of increasingly challenging "dungeons" - each of which being an empty Scrabble board. The player collects, earns, and buys more powerful tiles and gameplay modifiers that allow them to pass through more challenging levels and increasingly difficult goals. After some number of levels, the player encounters regular boss battles that modify some aspect of the gameplay, such as decreasing the number of tiles in hand, reducing the size of the board, or removing score modifiers (Double Word/Triple Letter/etc).

### Genre
 - Puzzle - Like Scrabble/Crossword
 - Deck-building - Collecting tiles, consumables, gameplay modifiers
 - Roguelike - "Hardcore" gameplay, quick game loops, grid-based
 - Dungeon Crawler - Figurative/Literal dungeons/caves as a setting. Boss battles with unique challenges/abilities/rewards.

## Gameplay Mechanics
### Core Gameplay
- Interact with the board using a mouse to move tiles from hand to board.
- Standard Scrabble scoring with tile modifiers (e.g., double word, triple letter).
- Earn excess points to buy special tiles with additional qualities between levels.
- Collect special objects on the board to use in future rounds or boss battles.
- Score required to pass each level increases, necessitating higher scoring words. Players will need to use tiles bought from the store or found in previous dungeons and be strategic in expanding their Scrabble play towards higher scoring spaces and special objects.
- Focus on strategic tile placement rather than a limited number of turns. Some bosses may introduce a time element. The game will feature an abstract health system influenced by monsters, traps, and tiles that cost health to play.

### Game Modes
- Single-player campaign mode.

### Objectives and Goals
- Achieve the score goal to pass each dungeon.
- Defeat bosses with special challenges to progress.
- Collect pieces of the ancient artifact to lift the curse on the kingdom.

### Player Abilities
- Place tiles on the board to form words.
- Use special tiles and consumables to overcome obstacles and challenges.

### Progression System
- Increasing difficulty with each round.
- Boss battles with unique challenges.
- Stores between levels to buy special tiles and goods.

### Special Tiles and Consumables
- Special tiles: blanks, tiles that can be played as any vowel, tiles with higher value than regular tiles, tiles made of special materials that can be used against monsters, traps, or as bridges to special items.
- Consumables: bombs, weapons, trap disarm kits to make parts of the dungeons more accessible without losing health.

## Story and Narrative
### Setting and World
- **Medieval Kingdom**: The game is set in a mystical medieval kingdom that has fallen under a dark curse, plunging the world into an eternal night filled with terrifying creatures.
- **Ancient Curse**: The curse was placed by Lamia, a powerful sorceress and serpent-like creature from ancient myth. Lamia’s curse has brought unending night and unleashed monstrous beings upon the land.
- **Locations**: The kingdom consists of a castle, village, and surrounding woods, each filled with dungeons that hold pieces of the artifact needed to break the curse.

### Plot Summary
- Players are adventurers on a quest to lift a powerful curse placed on a kingdom by assembling an ancient artifact. Each dungeon holds a piece of the artifact, guarded by formidable bosses. These bosses represent trials that test the player’s skills and bravery. As players progress through the dungeons, they defeat the bosses, collect artifact pieces, and gradually restore the cursed kingdom, uncovering secrets of its ancient civilization and proving their worth as legendary heroes.

### Characters
- **The Adventurer (Player)**: A brave hero determined to restore light to the kingdom.
- **Lamia (Final Boss)**: A half-woman, half-serpent creature whose tongue or tail is the final artifact piece needed to lift the curse.
- **Dungeon Bosses**: Mythical creatures from Arthurian and Celtic legend, such as the Questing Beast and the Black Dog of Uther, each presenting unique challenges.
- **NPCs in Stores**: Helpful characters who provide the player with special tiles and consumables in exchange for points.

### Lore and Backstory
- **Ancient Civilization**: The kingdom once thrived under the protection of an ancient artifact, now shattered and hidden within dangerous dungeons.
- **The Curse**: Lamia, angered by the kingdom's prosperity, cast a dark spell that shattered the artifact and spread darkness. Her tongue or tail, as a symbol of her power, is the key to reversing the curse.
- **Hero’s Quest**: The adventurer must delve into various dungeons, defeat mythical bosses, and reassemble the artifact to restore the kingdom’s former glory and end the eternal night.

## Level Design
### Level Structure
- **Dungeon-themed Scrabble Boards**: Each dungeon represents a themed Scrabble board with unique challenges and increasing difficulty.
- **Progressive Difficulty**: Each level requires higher scores to pass, with tougher monsters and more complex traps.
- **Traps and Hazards**: Dungeons include spikes, pits, and other hazards that can only be navigated using special tiles like steel or planks.

### Key Locations
- **Dungeons**: Varied environments such as dark caves, ancient ruins, enchanted forests, and the castle’s catacombs.
- **Boss Battle Arenas**: Special arenas where players face off against mythical creatures with unique abilities.

### Level Flow
- **Starting Levels**: Begin with simpler dungeons that introduce basic mechanics and gradually increase in complexity.
- **Mid-Game Levels**: More challenging dungeons with tougher enemies and intricate puzzles.
- **Endgame Levels**: Complex dungeons leading to the final confrontation with Lamia.

### Puzzles and Challenges
- **Scrabble Challenges**: Standard word formation challenges with the addition of special tiles and consumables.
- **Boss-specific Challenges**: Smaller boards that can be expanded by lighting torches, overpowered enemies reducing hand size, or removing tiles from the deck.

## Visual Design
### Art Style
- **Inspiration**: Overhead views with simple pixel art inspired by "The Legend of Zelda."
- **Dungeon/Cave Theme**: Dark, eerie environments with medieval elements.

### Key Visual Themes
- **Dungeon Environments**: Spooky and atmospheric with elements like stalactites, candelabra, and dark lighting.
- **Medieval Elements**: Incorporating medieval architecture and artifacts to enhance the setting.

### Character Designs
- **Adventurer**: Simple, medieval-themed hero with practical gear.
- **Monsters**: Diverse designs based on mythical creatures from Arthurian and Celtic legends.

### Environment Designs
- **Integrated Scrabble Boards**: Each environment integrates the Scrabble board seamlessly with the dungeon’s theme.

### User Interface (UI) and Heads-Up Display (HUD)
- **Hand Display**: Positioned at the bottom of the screen.
- **Consumables and Collectables**: Displayed on the right.
- **Scoring and Objectives**: Positioned on the left.
- **Board Placement**: Central focus with tiles spinning or producing particle effects when placed or achieving objectives.

## Audio Design
### Music
- **Medieval Style**: Emphasis on instruments like lute, harp, finger cymbals, and drums to create a medieval atmosphere.
- **Cave and Spooky Themes**: Music designed to enhance the eerie, dungeon-crawling experience.
- **Boss Battles**: Faster-paced, intense music to heighten the excitement.
- **Stores**: Relaxing medieval instrumentals to provide a break from dungeon crawling.

### Sound Effects
- **Tile Placement**: Sounds of heavy stones being dropped or sparkly magic effects.
- **Ambient Sounds**: Dungeon atmospheres with dripping water, echoing footsteps, and distant growls.
- **Victory Signals**: Trumpets signaling the defeat of bosses and other important achievements.

### Voice Acting
- None planned.

## Technical Requirements
### Platform(s)
- PC/Mac.

### Engine and Tools
- Godot engine.

### System Requirements
- Playable on most/all modern PCs.

### Performance Considerations
- Smooth performance for 2D tile-based gameplay.

## User Interface
### Main Menu
- Start game, options, exit.

### In-Game HUD
- Display hand, score, objectives, and special items.

### Controls and Navigation
- Mouse controls for tile placement.

### Accessibility Options
- Options for colorblind mode, adjustable text size, and different color schemes to accommodate visually impaired players.

## Multiplayer (if applicable)
### Modes
- Not applicable.

### Networking Requirements
- Not applicable.

### Social Features
- Not applicable.

## Monetization (if applicable)
### Pricing Model
- Purchase on Steam.

### In-Game Purchases
- None planned.

### Advertising
- None.

## Appendices
### Concept Art
- Initial sketches of dungeons, characters, and UI.

### References
- Inspirations from Scrabble, roguelike games, and dungeon crawlers.

### Additional Notes
- Future updates and expansions planned based on player feedback.
