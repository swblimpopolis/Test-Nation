# AbsoluteUnits unit sprites  <-- THIS IS THE DEFAULT UNIT SET

Drop map sprites here. The packer only picks up .png / .jpg / .jpeg, so this
file is ignored.

- Filename must be the exact unit name from jsons/Units.json, spaces included:
  `Crystal Guardian.png`
- Size: 95 x 81 px is the most common of the 467 stock AbsoluteUnits regions;
  64 x 56 and 77 x 65 are also widely used. Keep it wider than it is tall.
- Transparent background. Unlike NationIcons, sprites are NOT tinted, so paint
  them in full colour.

Optional variants, all resolved before the plain name:
- `Crystal Guardian-Modern era.png`   era-specific
- `Crystal Guardian-1.png`            layer tinted to the nation's inner colour
- `Crystal Guardian-2.png`            layer tinted to the nation's outer colour

After adding a file, repack: delete game.atlas + game.png and launch Unciv, or
run `java -jar Unciv.jar mod-ci` from the mod root.
