# Nacho Cheese

An octopus sits on a pile of cheese, facing 8 doors. Mice keep opening the doors to steal the cheese. Slam the doors shut before they get away!

**▶ Play it here: https://muffinking1979.github.io/nacho-cheese/**

## How to play

Each home-row key sends one of the octopus's arms to a door. The key for each door is shown under it. In Round 1 they match the keyboard:

```
A  S  D  F        J  K  L  ;
```

- When a door opens and a mouse peeks out, press that door's key before the timer ring runs out to slam it. Each mouse caught is worth **100 points**.
- If you're too slow, the mouse runs out and takes a wedge of cheese.
- Catch **8 mice** to clear a round. Your score and cheese carry over to the next round.
- Run out of cheese and it's **game over**.
- Only one arm can reach at a time, and slamming an empty door tangles the octopus for a moment, so mashing keys won't save you.
- The pile holds up to 15 wedges.

## The rounds

| Round | Keys → doors (left to right) | What's new |
|---|---|---|
| 1 | `A S D F  J K L ;` | Mice only. |
| 2 | `A S D F  J K L ;` | Faster mice. Some doors hide **cheese**: press that door's key in time and the arm **grabs** it and brings it back to your pile (+50 points if it's full). Wait too long and the door closes on it. |
| 3 | `A S D F  J K L ;` | Some doors hide a **cat**. Slam it (+200). If you don't, it eats **all** your cheese. The cat waits long enough that you can recover from one wrong key. |
| 4 | `J K L ;  A S D F` | Your hands swap sides. |
| 5 | `J K L ;  A S D F` | **Double mice** (marked ×2). Slam the door and the second mouse bursts right back out. You can't stop it. Miss, and both steal cheese. |
| 6 | `; L K J  F D S A` | The keys are mirrored. |
| 7 | `; L K J  F D S A` | **Cheese bonanza**: only mice and cheese, about 3 cheese doors for every mouse. Grab them to stock up! |
| 8 | Scrambled, new every time | Mice, double mice, cheese and cats. **Endless.** It only ends when your cheese runs out. |

## High scores

When the game ends, players with a top-10 score enter their initials. The high score list is shown at the end of every game. Scores are saved in your browser only.

## Running locally

It's one HTML file with no dependencies. Open `index.html` in any modern browser.

On the title screen, press **2** through **8** to practice from that round. Practice games don't record high scores.
