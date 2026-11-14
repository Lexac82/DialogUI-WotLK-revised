# DialogUI (WotLK 3.3.5a)

Immersive quest / gossip / book dialog frames for WoW 3.3.5a. Replaces the
default Blizzard frames with parchment-styled panels.

Fork of [Stefan2102's WotLK port](https://github.com/Stefan2102/DialogUI-WotLK).

## Differences from the original port

**Added / Fixed**
- Focus mode split into two independent options: center dialogs and screen dimmer
- Long NPC names now truncated with "..." instead of disappearing behind the portrait
- Button text now renders correctly in WotLK 3.3.5a
- Centralized color palette in one place
- Refactored repetitive XML into Lua generation, merged duplicated templates, unified naming conventions

**Removed**
- Dark mode — light parchment only
- Auto-advance — all NPC interactions are manual
- Right-side frame anchor — always docks left
- Key icon textures and key badge labels — buttons show clean text only
- `/dui` slash command alias

## Screenshots

<img width="75%" height="75%" alt="image" src="docs/QuestGreeting.jpg" />

<img width="75%" height="75%" alt="image" src="docs/QuestDetails.jpg" />

<img width="75%" height="75%" alt="image" src="docs/GossipFrame.jpg" />

<img width="75%" height="75%" alt="image" src="docs/BookFrame.jpg" />

<img width="75%" height="75%" alt="image" src="docs/settings.png" />

## Credits

- Original: [Sxus](https://github.com/Jslquintero/DialogUI)
- WotLK port: [Bset](https://github.com/ghbset/DialogUI-WotLK)
- Inspiration: [DialogueUI](https://www.curseforge.com/wow/addons/dialogueui)
