# warframe-kim-dialogues

All Kinemantik Instant Messaging conversations and various ways to explore them.

- [Convo Locator](https://kim.browse.wf/convo-locator) — find a conversation based on (part of) a message
- [Kimulacrum](https://kim.browse.wf/kimulacrum) — web-based reimplementation of the KIM chat allowing you to take all conversations and paths.
- [Flowcharts](flowcharts)

## Scripts

- extract.bat: Invokes [Warframe Exporter](https://github.com/Puxtril/Warframe-Exporter) to extract the raw `*Dialogue_rom.dialogue` files. Makes some assumptions specific to my environment.
- Hell-Scrubber: Parses the raw `*Dialogue_rom.dialogue` files into the JSON files you can see here. Makes some assumptions specific to my environment.
- Dotinator: Converts the JSON files into DOT format then invokes Graphviz to make the flowchart PNGs.
