# Dynasty Draft

Draft an eight-man NBA rotation from team-of-the-decade packs, then take it through a home-and-away gauntlet against eight all-time great teams. Open `index.html` in a browser; there is no build step.

- **Packs**: 50 franchise-decade packs (e.g. 1990s Bulls), each roughly the ten players with the most games for that team in that decade. A few packs swap in a headliner with fewer games (LeBron on the 2010s Lakers, Kawhi on the 2010s Raptors).
- **Cards**: stats are per-game averages across only that player's seasons with that team in that decade, so 90s Jordan and 80s Jordan are different cards. They are compiled by hand and approximate. Tiers run Bronze → Silver → Gold → Emerald → Sapphire → Ruby → Amethyst → Diamond → Pink Diamond → Galaxy Opal → Dark Matter.
- **Photos**: loaded at runtime from the Wikipedia API, restricted to free-licensed images (`pilicense=free`). Each card back links to the image's file page for credit. Cards fall back to a monogram when no free photo exists or the network is unavailable.
- **Luck**: some packs hold a Moments card (+3 OVR) or a bonus reroll. Players have hot and cold nights, and every game shows its pre-game odds. The season tracks how many wins you've banked above or below those odds.
- **Games**: watch each game live (play-by-play, quarter scores, live win probability) or sim ahead. Full box scores with FG/3P/FT, REB, AST, STL, BLK and TO.
