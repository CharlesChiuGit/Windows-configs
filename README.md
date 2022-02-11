# Windows-configs

## Install Apps from WinGet

- Watch Readme.md in [this subfolder](https://github.com/charleschiu2012/Windows-configs/tree/main/WinGet_Setup).

## Download other apps unavailable in winget via Window Repair Toolbox(WRT)

- You can find the WRT's download link in the _custom.xml_.

1. Replace the _custom.xml_ in the **Custom Tool** tab, and press the **Refresh list** buttom.
2. Edit the _custom.xml_ to add/remove the app as u like.
3. Download whatever app u want.

## UI setups

### Win10 theme

#### Use **Nord theme**, by [niivu](https://www.deviantart.com/niivu).

1. Download the **UltraUXThemePatcher** in WRT custom tool.
2. Download the Nord theme from [here](https://www.deviantart.com/niivu/art/Nord-Windows-10-Theme-837266272)
3. Unzip it and place the .theme files and folders containing the .msstyles files in **Windows\Resources\Themes** directory.

- The **Windows\Resources\Themes** directory structure: ![](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dd78c78e-d2e1-42b8-9d08-bc5df634a6c6/des574i-a6f255d3-4655-4394-9bd8-201993e37973.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RkNzhjNzhlLWQyZTEtNDJiOC05ZDA4LWJjNWRmNjM0YTZjNlwvZGVzNTc0aS1hNmYyNTVkMy00NjU1LTQzOTQtOWJkOC0yMDE5OTNlMzc5NzMucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.pO7T2yOZe-m9dw19aM9vJQ5kN_hs4nHckSpb0wgok48)

4. Execute the **UltraUXThemePatcher**.
5. Go to **Settings > Personalization > Themes** to apply the theme.
6. If u encounter some bug, please refer to [【密技】徹底爆改!! win10 系統 如同 macOS 舒適的體驗!](https://forum.gamer.com.tw/C.php?bsn=60030&snA=525114), the tips inside may help.

#

### Win11 theme

1. Follow the extra steps in [Installing Windows Themes (UPDATED)](https://www.deviantart.com/niivu/art/Installing-Windows-Themes-UPDATED-708835586).

#

### Icon replacement

#### Use **Lumicons**, by [vantler](https://www.deviantart.com/vantler).

#### Use **Lumicons Installer**, by [niivu](https://www.deviantart.com/niivu).

#### Use **Extra Lumicons pack & installer**, by [KENT FAN](https://home.gamer.com.tw/homeindex.php?owner=asd131205)

1. Download all three package/installer from [v1 pack](https://www.dropbox.com/sh/a4n0q8csomigfwe/AAAWoSZ2XLWcw9GVKJGzV3V4a?dl=0) and [v3 installer](https://drive.google.com/file/d/16x1gAKkGkFRloRzkfQvsHNTLDONUCUT1/view)
2. Run the v3 installer.
3. If there are some icons that doesn't change, use following apps to modify it.

   - Use **CustomizerGod** to modify **system icons**, i.e. _Control Panel_ icon or _Windows Explorer_ icon.

   - Use **FileTypesMan** to modify **file icon with same file extension**. i.e. _.jpg_, _.mp4_, _.zip_

   - Use **TileIconifier** to modify **Live Tiles Logo**.

   - Use built-in program to modify **Start Menu & Taskbar**. Go to **C:\ProgramData\Microsoft\Windows\Start Menu\Programs** and change the icon for Start Menu. Go to **%AppData%\Microsoft\Internet Explorer\Quick Launch\User Pinned\TaskBar** and change the icon for Taskbar.

4. Move **RecycleBinFolder** from desktop to Windows Explorer, by press **Win + R**, then type **explorer shell:RecycleBinFolder**.

#

### Set BetterDiscord to Discord

- Watch Readme.md in [this repo](https://github.com/charleschiu2012/BetterDiscord-configs)

### Set Spicetify to Spotify

- Watch Readme.md in [this repo](https://github.com/charleschiu2012/Spicetify-configs)

### Set Windows Terminal color scheme

- Watch Readme.md in [this repo](https://github.com/charleschiu2012/WindowsTerminal-configs)

### Change Skins of Logseq, PotPlayer, Zotero, Steam, Win11 Cursur(dark-theme)

- Watch Readme.md in [this repo](https://github.com/charleschiu2012/Apps-Skin)
