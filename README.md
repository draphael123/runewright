# Runewright

A spellcrafting twin-stick roguelite. You don't *pick* spells — you **build** them by socketing rune-words. A spell = **1 element + up to 2 modifiers**. Discovering combinations is the progression.

**Play:** [runewright.vercel.app](https://runewright.vercel.app) · single HTML file, no build step.

## Controls
- **WASD** — move
- **Mouse** — aim
- **Left / Right click** — cast your two spells
- **Space** — dash (brief i-frames)
- **Tab** — open the Forge (socket runes between rooms)
- **Esc** — pause

## The rune system
**Element bases:** Fire (burn), Frost (slow), Bolt (fast, low-cooldown), Venom (stacking poison), Arcane (raw force).

**Modifiers:** Chain (bounce), Split (3-shot), Pierce, Delay (halt → AoE detonate), Homing, Nova (impact burst), Amplify (+dmg/size), Haste (−cooldown).

Signature rune-words: **Fire + Delay** = sticky bomb · **Bolt + Pierce** = railgun · **Frost + Split** = slowing shotgun · **Venom + Homing** = seeking darts · **Arcane + Amplify + Nova** = heavy burst.

## Structure
Isaac-style branching floors — clear rooms, collect runes, forge your build, and reach the **Warden** boss at the far end. Beat it to descend a floor (heal + a harder crypt). A persistent **codex** (saved locally) tracks every rune and rune-word you discover, plus your deepest floor.

Single-file `index.html` · 2D canvas · vanilla JS.
