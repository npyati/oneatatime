# one · at · a · time

A word ladder puzzle game where you transform one word into another by changing **one letter at a time**.

[Play Now](https://squaresga.me/oneatatime.html)

## How to Play

Transform one word into another by changing **one letter at a time**. Each step must be a real word!

### Example

Let's turn **WARM** into **COLD**:

```
start  → WARM
move 1 → WORM  (changed A to O)
move 2 → FORM  (changed W to F)
move 3 → FORD  (changed M to D)
move 4 → CORD  (changed F to C)
finish → COLD  (changed R to L)

✓ solved in 5 moves!
```

### The Basics

- **Click a box** (or press 1-4) to select which letter to change
- **Type a letter** to make your move
- **Par** shows the shortest possible path
- **Click any guess** to rewind and try a different path
- Click the starting word to start over

### Pro Tips

- **? button** gives you a hint (but we count these!)
- **Refresh button** (↻) starts a fresh puzzle
- Press **backspace** to undo your last move
- Press **escape** to restart from the beginning
- Turn on **"filter letters"** to see which letters are possible

## Features

- **Perfect 4s Mode**: Only generate puzzles with par 4 where all four letters must change
- **Par 7+ Mode**: Challenge yourself with harder puzzles that have par 7 or higher
- **Rainbow Celebrations**: Solve without hints for a colorful victory animation
- **Perfect Score Sparkles**: Get rainbow sparkle text for solving at par with no hints
- **Persistent Settings**: Your preferences are saved across sessions
- **Share Results**: Share your solutions with friends

## Settings

Access the settings menu by clicking the logo at the top:

- **Show par**: Display the optimal solution length
- **Filter letters**: Highlight which letters can make valid words
- **Perfect 4s only**: Generate only par-4 puzzles where all letters change
- **Par 7+ only**: Generate only harder puzzles with par 7 or higher

## Tech Stack

- Pure JavaScript (no frameworks)
- jQuery for DOM manipulation
- CSS animations for visual effects
- LocalStorage for settings persistence

## License

MIT License - feel free to use and modify!

---

Now get out there and start transforming!
