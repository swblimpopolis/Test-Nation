# FantasyHex unit sprites

Drop map sprites here. The packer only picks up .png / .jpg / .jpeg, so this
file is ignored.

- Filename must be the exact unit name from jsons/Units.json, spaces included:
  `Crystal Guardian.png`
- Size: 32 x 28 px (135 of the game's 152 FantasyHex sprites use exactly this).
- Transparent background. Unlike NationIcons, sprites are NOT tinted, so paint
  them in full colour.

Optional variants, all resolved before the plain name:
- `Crystal Guardian-Modern era.png`   era-specific
- `Crystal Guardian-1.png`            layer tinted to the nation's inner colour
- `Crystal Guardian-2.png`            layer tinted to the nation's outer colour

After adding a file, repack: delete game.atlas + game.png and launch Unciv, or
run `java -jar Unciv.jar mod-ci` from the mod root.
