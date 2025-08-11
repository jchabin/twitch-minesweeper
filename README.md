# twitch-minesweeper

```
https://jchabin.github.io/twitch-minesweeper?c=CHANNEL_NAME&w=WIDTH&h=HEIGHT&d=DIFFICULTY
```
Add this as an OBS source, replace the parameters as specified below.
| Param | Description |
|-|-|
| **CHANNEL_NAME** | Twitch channel name |
| **WIDTH** | Width of the game board -- Defaults to 8 |
| **HEIGHT** | Height of the game board -- Defaults to 8 |
| **DIFFICULTY** | Integer for difficulty, see below for more information -- Defaults to 0 |

---

Difficulty integer is in the range [0, 4] and controls what percentage of the game board is covered by mines, according to the below table.
| Difficulty | Mine Percentage |
|-|-|
| **0** | 15.625% -- Matches Beginner/Intermediate difficulty in Windows Minesweeper 1990 |
| **1** | 17.5% |
| **2** | 20.625% -- Matches Expert difficulty in Windows Minesweeper 1990 |
| **3** | 25% |
| **4** | 35% |
