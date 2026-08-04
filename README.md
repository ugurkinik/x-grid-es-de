# X-Grid (ES-DE 3.2+)

X-Grid aims at larger libraries. When you have hundreds or thousands of games, you want enough items on screen to move quickly, without the layout feeling cramped or hard to read. Dense enough to browse fast, clear enough to stay comfortable.

**Tested only on Steam Deck with ES-DE 3.4.** Other devices and aspect ratios may work, but they are not verified yet.

## Install

1. Open the theme repository on GitHub.
2. Click the green **Code** button and choose **Download ZIP**.
3. Unzip the archive.
4. Copy the theme folder into `ES-DE/themes/` (that folder must contain `theme.xml` and `capabilities.xml`).
   - On Steam Deck this is typically `/home/deck/ES-DE/themes/`.
   - The `screenshares/` folder is documentation only; you can omit it when copying.
5. Fully restart ES-DE (a reload is not enough after installing or replacing a theme).
6. Go to **UI Settings → Theme** and select **X-Grid**.


## Screenshots

System view — `[System:M]`, Monochrome:

![System view, medium system grid](screenshares/1.png)

System view — `[System:L]`, Dark Orange:

![System view, large system grid](screenshares/2.png)

Game list — `[Game:S]` (4 columns), Light Orange:

![Game list, small game grid](screenshares/3.png)

Game list — `[Game:M]` (3 columns), Pip-Boy:

![Game list, medium game grid](screenshares/4.png)

Game list — `[Game:L]` (2 columns), Super Game Boy:

![Game list, large game grid](screenshares/5.png)


## Variants

Use **UI Settings → Theme Variant** to set system and game list sizes together. System is M or L; game is S, M, or L (6 combinations). Grid columns fill the right panel equally:

| Size | Columns |
|------|---------|
| Game S | 4 |
| Game M / System M | 3 |
| Game L / System L | 2 |

- `[System:M] [Game:S]`
- `[System:M] [Game:M]`
- `[System:M] [Game:L]`
- `[System:L] [Game:S]`
- `[System:L] [Game:M]`
- `[System:L] [Game:L]`

## Font size

Use **UI Settings → Theme Font Size** (`small` / `medium` / `large`) to scale status, grid, metadata, description, and help text.

## Color schemes

Use **UI Settings → Theme Color Scheme** to pick a palette:

- Monochrome
- Dark Orange (default)
- Light Orange
- Pip-Boy
- Pocket Gray
- Super Game Boy
- PlayStation 4
- PlayStation 5
- Xbox 360
- Xbox One
- Switch OLED
- Gamecube
- WII

## Bundled assets

These packs ship with the theme and must stay with it:

- `system-logos/system-logo-color/` ([ES-DE system logos](https://gitlab.com/es-de/themes/system-logos))
- `system-metadata/` ([ES-DE system metadata](https://gitlab.com/es-de/themes/system-metadata))
- `system-controllers-outline/` ([ES-DE system controllers](https://gitlab.com/es-de/themes/system-controllers-outline))

Keep these folders when you copy or update the theme.
