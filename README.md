# 🦈 Shark Game (Scratch)

My first game, built in Scratch during CS50x Week 0.

▶️ **Play it:** https://scratch.mit.edu/projects/1442667048/

## How it works

- Arrow keys steer the shark, which swims continuously
- Crystals give +1 point and respawn at a random safe position
- Up to 3 lightning bolts spawn as clones, 5 seconds apart; each lives 10 seconds and never spawns within 120px of the shark
- Touching a lightning bolt ends the game; the green flag resets everything

## What I learned

- **Loops:** a `forever` loop moves the shark; arrow keys only change its direction
- **Clones:** one hidden "factory" sprite creates the lightning bolts
- **`repeat until`:** try random positions until one is far enough from the shark
- **Conditionals:** code inside an `if` only runs when the condition is true. A `wait` placed inside the `if` made the lightning disappear instantly. Moving it outside the `if` fixed the timing.

## Files

- `Shark Game.sb3`: the Scratch project file (open it at scratch.mit.edu → File → Load from your computer)
