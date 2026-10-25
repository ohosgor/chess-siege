# Chess Siege: Glitch Tactics

A pixel-art tower-defence game played with chess pieces. A glitch army storms the board from the entry gates; place your King, pawns, knights, bishops, rooks and queens, build walls, lay traps and hold out for 20 waves.

**Play in the browser:** https://ohosgor.github.io/chess-siege/

The game's interface is in Turkish.

## How to play

- Drag the King (Şah) from the arsenal onto the board. If the King falls, the run is over.
- Place pieces and traps between waves, then press **Dalga Başlat** (start wave). Pieces attack on their own.
- Kills earn materials and Initiative. Spend materials on pieces, traps and upgrades; spend Initiative on tactical moves during battle.
- Every second wave, and after elite and boss waves, pick one of three tactic cards.
- A guided first game (Sabo Paşa) and a full "Nasıl oynanır" (how to play) guide are in the main menu.

## Controls

| Key | Action |
| --- | --- |
| Drag / tap | Place from the arsenal; tap a piece for info and range |
| `Space` | Start wave / pause |
| `1`–`9` | Select an arsenal item |
| `R` | Rotate the selected pawn |
| `U` | Upgrade the selected piece |
| `F` | Battle speed 1× / 2× / 3× |
| `K` | Toggle oblique / top-down camera |
| `Z` `X` `C` `V` | Tactical moves |

## Running locally

Everything (art, sound and music) is generated inside `index.html`; there is no build step and no network dependency. Open `index.html` in a modern browser, or serve the folder:

```sh
python3 -m http.server
```

Progress, settings and the current run are saved in the browser's `localStorage`.

## Credits

Chess piece art is Colin M.L. Burnett's "Cburnett" set, downscaled to 32×32 pixel art. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
