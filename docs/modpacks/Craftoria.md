# Craftoria
![Craftoria Cover](img/Craftoria start.png)

<div class="grid cards" markdown>
- :material-format-list-group: __Mod List__ [Craftoria MODLIST.md](https://github.com/TeamAOF/Craftoria7/blob/main/MODLIST.md)
- :simple-curseforge: __CurseForge__ [Craftoria](https://www.curseforge.com/minecraft/modpacks/craftoria)
- :fontawesome-brands-discord: __Discord Channel__ [\#craftoria](https://discord.com/channels/570630340075454474/1252708934729470094)
- :fontawesome-brands-github: __GitHub__ [Craftoria on GitHub](https://github.com/TeamAOF/Craftoria)
</div>

## Craftoria FAQ

### Setup / Performance
* Use Java 21
* ~8GB RAM (too much invites longer GC pauses)
* Try these args: `-XX:+UseZGC -XX:+ZGenerational`

### Pack Content
Mods, so many mods!
Quests!
Dimensions!

1. Vanilla: Overworld, Nether, and The End
1. The Bumblezone
1. Eternal Starlight
1. Deeper & Darker: The Otherside
1. Void (JAVD)
1. Compact Machines
1. Mining dims matching the vanilla ones (JAMD)

### "FAQ" FAQs
* Team chat is bound to `u` by default. (`y` in earlier versions). If no one can see your messages, you may have this toggled on.
* JDT Upgrades: use a smithing table to apply them.
* JDT Paxels: assemble a JDT pickaxe, axe, and shovel in a smithing table.

### Installing a Server
1. Download the _Craftoria_ server zip from Curseforge.
2. The README.md included in that zip has directions.
3. TLDR? Run the `startserver.bat` or `.sh` script.

### Need further help?
1. Open a post in our discord forum, [#support](https://discord.com/channels/570630340075454474/1028818900768538695). 
2. If you have one, include a crash-report, crash file, or latest log.
3. Knowledgable players are very welcome to answer questions there too!

### Found a Bug?
- Please let us know, with a post in our discord forum, [#bug-reports](https://discord.com/channels/570630340075454474/1028644155305496576)
- Github repo issues are also welcomed.

### Addendum: Permissions
* `ftbchunks.max_claimed` (chunk claim quota)
* `command.back` (to enable or disable `/back`)
* `ftbessentials.back.cooldown`
* `ftbessentials.rtp.cooldown`
* `ftbessentials.home.max`

To alter, use:
- `/ftbranks node add [rank] [permission] [value(s)]` 
- `/ftbranks node remove [rank] [permission]`

---