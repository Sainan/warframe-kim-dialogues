# warframe-kim-dialogues

All Kinemantik Instant Messaging conversations and various ways to explore them.

- [Convo Locator](https://browse.wf/kim-convo-locator) — find a conversation based on (part of) a message
- [Kimulacrum](https://browse.wf/kimulacrum) — web-based reimplementation of the KIM chat allowing you to take all conversations and paths.
- Flowcharts
  - [PNGs, English only](flowcharts)
  - [SVGs, all languages](flowcharts_svg)

## Scripts

- extract.bat: Invokes [Warframe Exporter](https://github.com/Puxtril/Warframe-Exporter) to extract the raw `*Dialogue_rom.dialogue` files. Makes some assumptions specific to my environment.
  - download.pluto: Kinda the same end goal but uses [warframe-cache-tools](https://github.com/Sainan/warframe-cache-tools) to grab the data. Assumes the repo is checked out in the same parent directory.
- Descender: Parses the raw `*Dialogue_rom.dialogue` files into the JSON files you can find in the data & metadata folders. Makes some assumptions specific to my environment.
- Dotinator: Converts the JSON files into DOT format then invokes Graphviz to make the flowchart PNGs.
