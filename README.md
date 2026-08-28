# x0cero

I write emulators and systems software from scratch in Rust.

## Emulators

| | |
|---|---|
| [**gameboy**](https://github.com/x0cero/gameboy) | Game Boy + Game Boy Color emulator. Runs Pokémon Red. Passes dmg-acid2. |
| [**gba**](https://github.com/x0cero/gba) | Game Boy Advance emulator. Runs Pokémon FireRed, frame-identical to mGBA. |
| [**nds**](https://github.com/x0cero/nds) | Nintendo DS emulator. Runs Pokémon Platinum into 3D overworld gameplay. |

<p>
  <img src="https://raw.githubusercontent.com/x0cero/gameboy/master/screenshots/pokemon-red.gif" height="180" alt="Pokémon Red on the gameboy emulator">
  <img src="https://raw.githubusercontent.com/x0cero/gba/master/screenshots/firered-demo.gif" height="180" alt="Pokémon FireRed on the gba emulator">
  <img src="https://raw.githubusercontent.com/x0cero/nds/master/screenshots/outdoor.png" height="180" alt="Pokémon Platinum overworld on the nds emulator">
</p>

## Other projects

- [**magi**](https://github.com/x0cero/magi): three-agent decision CLI inspired by Evangelion. Consults Melchior, Balthasar, and Casper in parallel and returns their verdicts.

All of it is written from first principles: CPU cores, PPU/GPU pipelines, audio, and timing, without emulation libraries.
