# Perfect Start

**Get all three starter Pokémon at the start of every game.**

Pick your starter as usual and the professor hands you the other two as well. Your rival still takes the Pokémon that counters yours, and the story plays out like the original.

A mod for [Gen1Recomp](https://github.com/bryanthaboi/gen1recomp).

## Supported games

| Game | Starters you get | When the other two arrive |
| --- | --- | --- |
| Red, Blue | Bulbasaur, Charmander, Squirtle | Right after Oak's gift, with the usual nickname prompt |
| Yellow | Bulbasaur, Charmander, Squirtle (plus Pikachu) | After Oak gives you the Pokédex |
| Gold, Silver, Crystal | Chikorita, Cyndaquil, Totodile | Right after Elm's gift |
| FireRed, LeafGreen | Bulbasaur, Charmander, Squirtle | Right after Oak's gift |
| Ruby, Sapphire, Emerald | Treecko, Torchic, Mudkip | Straight from Birch's bag, before the Zigzagoon battle |

All extra starters are level 5. The one you picked stays in slot 1.

## Features

- **Your rival is unchanged.** Your rival still picks the counter to your choice, so the first rival battle is the same as in the original.
- **The leftover Poké Ball disappears.** Once all three starters are yours, nothing is left on the table in Oak's lab (Red, Blue, FireRed, LeafGreen) or Elm's lab (Gold, Silver, Crystal). Yellow and the Hoenn games have no leftover ball.
- **One gift per save.** Evolving, releasing or trading away a starter never gives you another copy.
- **Safe with full parties.** If your party is full, the extra starters go to the PC. In FireRed through Emerald, if the PC is full too, the mod waits and tries again once there's room.
- **Works on existing saves.** Load a save that already has a starter, and the missing ones are handed over once. Saves that already got them never get them twice.
- **Never mid-battle.** Your party is only changed outside battles.

## Installing

1. Download `Perfect_Start-<version>.zip` from the [latest release](https://github.com/Tooandorisu/Perfect-Start/releases/latest).
2. In the Gen1Recomp launcher, press **Import mod .zip** and pick the file, or drop the zip onto the launcher window.
3. Enable **Perfect Start** in the mod manager.

One install covers every supported game. The launcher can also check this repository for updates.

## Upgrading

Import the new zip over the old version. Your saves are safe, and nobody receives their starters twice.

Coming from the old separate mods (**Perfect Start - Gen 2** or **Perfect Start - Gen 3**)? Remove them. This mod replaces both, and it recognizes saves they already handled.

## Good to know

- The mod manager shows **PATCHES ENGINE CODE** for this mod. That's expected: it hooks into each game's update loop to hand over the starters at the right moment.
- It only touches the code of the game you're playing. A Gold save never runs any Red code, and the other way round.

## Credits

- Made by Tooandorisu.
- Leftover Poké Ball idea by David.

See [CHANGELOG.md](CHANGELOG.md) for the version history.
