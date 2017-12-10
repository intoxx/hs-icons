# Hearthstone Icons
A collection of Hearthstone related vector based icons.

## Sets
Classic, The Curse of Naxxramas, Goblins vs Gnomes, Black Rock Mountain, The Grand Tournament, The League of Explorers, Whispers of the Old Gods, One Night in Karazhan, Mean Streets of Gadgetzan, Journey to Un'Goro, Hall of Fame, Knights of the Frozen Throne, Kobolds and Catacombs.

<table>
<tr>
<td><img src="/PNG/Set_Classic.png?raw=true" alt="Classic" title="Classic" /></td>
<td><img src="/PNG/Set_Naxx.png?raw=true" alt="The Curse of Naxxramas" title="The Curse of Naxxramas" /></td>
<td><img src="/PNG/Set_GVG.png?raw=true" alt="Goblins vs Gnomes" title="Goblins vs Gnomes" /></td>
<td><img src="/PNG/Set_BRM.png?raw=true" alt="Black Rock Mountain" title="Black Rock Mountain" /></td>
</tr>
<tr>
<td><img src="/PNG/Set_TGT.png?raw=true" alt="The Grand Tournament" title="The Grand Tournament" /></td>
<td><img src="/PNG/Set_LOE.png?raw=true" alt="The League of Explorers" title="The League of Explorers" /></td>
<td><img src="/PNG/Set_OG.png?raw=true" alt="Whispers of the Old Gods" title="Whispers of the Old Gods" /></td>
<td><img src="/PNG/Set_Kara.png?raw=true" alt="One Night in Karazhan" title="One Night in Karazhan" /></td>
</tr>
<tr>
<td><img src="/PNG/Set_Gadgetzan.png?raw=true" alt="Mean Streets of Gadgetzan" title="Mean Streets of Gadgetzan" /></td>
<td><img src="/PNG/Set_Ungoro.png?raw=true" alt="Journey to Un'Goro" title="Journey to Un'Goro" /></td>
<td><img src="/PNG/Set_HOF.png?raw=true" alt="Hall of Fame" title="Hall of Fame" /></td>
<td><img src="/PNG/Set_ICC.png?raw=true" alt="Knights of the Frozen Throne" title="Knights of the Frozen Throne" /></td>
</tr>
<tr>
<td><img src="/PNG/Set_LOOT.png?raw=true" alt="Kobolds and Catacombs" title="Kobolds and Catacombs" /></td>
</tr>
</table>

## Classes
Druid, Hunter, Mage, Paladin, Priest, Rogue, Shaman, Warlock, Warrior.

<table>
<tr>
<td><img src="/PNG/Class_Druid.png?raw=true" alt="Druid" title="Druid" /></td>
<td><img src="/PNG/Class_Druid_Alt.png?raw=true" alt="Druid Alt" title="Druid Alt" /></td>
<td><img src="/PNG/Class_Hunter.png?raw=true" alt="Hunter" title="Hunter" /></td>
<td><img src="/PNG/Class_Hunter_Alt.png?raw=true" alt="Hunter Alt" title="Hunter Alt" /></td>
</tr>
<tr>
<td><img src="/PNG/Class_Mage.png?raw=true" alt="Mage" title="Mage" /></td>
<td><img src="/PNG/Class_Mage_Alt.png?raw=true" alt="Mage Alt" title="Mage Alt" /></td>
<td><img src="/PNG/Class_Paladin.png?raw=true" alt="Paladin" title="Paladin" /></td>
<td><img src="/PNG/Class_Paladin_Alt.png?raw=true" alt="Paladin Alt" title="Paladin Alt" /></td>
</tr>
<tr>
<td><img src="/PNG/Class_Priest.png?raw=true" alt="Priest" title="Priest" /></td>
<td><img src="/PNG/Class_Priest_Alt.png?raw=true" alt="Priest Alt" title="Priest Alt" /></td>
<td><img src="/PNG/Class_Rogue.png?raw=true" alt="Rogue" title="Rogue" /></td>
<td><img src="/PNG/Class_Rogue_Alt.png?raw=true" alt="Rogue Alt" title="Rogue Alt" /></td>
</tr>
<tr>
<td><img src="/PNG/Class_Shaman.png?raw=true" alt="Shaman" title="Shaman" /></td>
<td><img src="/PNG/Class_Shaman_Alt.png?raw=true" alt="Shaman Alt" title="Shaman Alt" /></td>
<td><img src="/PNG/Class_Warlock.png?raw=true" alt="Warlock" title="Warlock" /></td>
<td><img src="/PNG/Class_Warlock_Alt.png?raw=true" alt="Warlock Alt" title="Warlock Alt" /></td>
</tr>
<tr>
<td><img src="/PNG/Class_Warrior.png?raw=true" alt="Warrior" title="Warrior" /></td>
<td><img src="/PNG/Class_Warrior_Alt.png?raw=true" alt="Warrior Alt" title="Warrior Alt" /></td>
</tr>
</table>

## Game Modes
Wild, Standard: Kraken, Standard: Mammoth.

<table>
<tr>
<td><img src="/PNG/Mode_Wild.png?raw=true" alt="Wild" title="Wild" /></td>
<td><img src="/PNG/Mode_Standard_Kraken.png?raw=true" alt="Standard Kraken" title="Standard Kraken" /></td>
<td><img src="/PNG/Mode_Standard_Kraken_Alt.png?raw=true" alt="Standard Kraken Alt" title="Standard Kraken Alt" /></td>
<td><img src="/PNG/Mode_Standard_Mammoth.png?raw=true" alt="Standard Mammoth" title="Standard Mammoth" /></td>
</tr>
</table>

## Misc
Battle.Net, Gadgetzan Grimy Goons, Kabal and Lotus.

<table>
<tr>
<td><img src="/PNG/Misc_BattleNet.png?raw=true" alt="BattleNet" title="BattleNet" /></td>
<td><img src="/PNG/Misc_Gadgetzan_GrimyGoons.png?raw=true" alt="Grimy Goons" title="Grimy Goons" /></td>
<td><img src="/PNG/Misc_Gadgetzan_Kabal.png?raw=true" alt="Kabal" title="Kabal" /></td>
<td><img src="/PNG/Misc_Gadgetzan_Lotus.png?raw=true" alt="Jade Lotus" title="Jade Lotus" /></td>
</tr>
</table>

## Optimized SVG
[Scour](https://github.com/scour-project/scour) was used with the following options:
```
scour <input> <output> --remove-descriptive-elements --enable-comment-stripping --enable-id-stripping
```

<!--
## Converting SVG to XAML
To use SVG files in XAML they need to follow Microsoft's format. The following steps may be entirely disgusting, but do produce a perfect result.

1. Open the SVG file in Internet Explorer.
- Print the page, choosing the *Microsoft XPS Document Writer* (or similarly named device) and save the resulting file.
- Open the XPS file with 7Zip or equivalent file archive tool, and extract the contents.
- Find the file `Documents\Pages1.fpage` in the extracted directory tree, and open it in a text editor.
- Depending on the SVG you may need to copy the whole `<Canvas>` element or just a single `<Path>` element.
- Copy the XAML elements into your application.
-->

## License

<a rel="license" href="https://creativecommons.org/publicdomain/zero/1.0/">
	<img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/p/zero/1.0/88x31.png" />
</a>
<br />This work is released into the public domain under the <a rel="license" href="https://creativecommons.org/publicdomain/zero/1.0/">Creative Commons CC0 Public Domain Dedication</a>.

These are derived artworks based on graphics that appear in the game Hearthstone &copy; Blizzard Entertainment. Use of these artworks must comply with the relevant terms and conditions set out by Blizzard Entertainment.

