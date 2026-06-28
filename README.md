# An EAT THE REICH System (Unofficial)
<p align="center">
   	<img src='https://raw.githubusercontent.com/Limpbark/eat-the-reich-v14/refs/heads/main/assets/ETR-compatible-with-logo.webp'/>
</p>

<p align="center">
    <img alt="Foundry Version 14 support" src="https://img.shields.io/badge/Foundry-v14-informational">
    <img alt="Latest Release Download Count" src="https://img.shields.io/github/downloads/Limpbark/eat-the-reich-v14/latest/total"> 
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/Limpbark/eat-the-reich-v14">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Limpbark/eat-the-reich-v14">
    <img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/Limpbark/eat-the-reich-v14?label=latest%20release" /> 
</p>
<p align="center">
    <!-- <img alt="GitHub" src="https://img.shields.io/github/license/Limpbark/eat-the-reich-v14">  -->
    <a href="https://github.com/Limpbark/eat-the-reich-v14/issues">
        <img alt="GitHub issues" src="https://img.shields.io/github/issues/Limpbark/eat-the-reich-v14">
    </a> 
    <a href="https://github.com/Limpbark/eat-the-reich-v14/network">
        <img alt="GitHub forks" src="https://img.shields.io/github/forks/Limpbark/eat-the-reich-v14">
    </a> 
    <a href="https://github.com/Limpbark/eat-the-reich-v14/stargazers">
        <img alt="GitHub stars" src="https://img.shields.io/github/stars/Limpbark/eat-the-reich-v14">
    </a>
</p>
<p align="center">
   	<a href='https://ko-fi.com/G2G3I91JQ' target='_blank'>
        <img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' />
    </a>
</p>

> [!NOTE]
> This is a community fork maintained by [Limpbark](https://github.com/Limpbark), updated for **Foundry VTT V14** (the codebase now targets minimum core version 14). It is based on the original [Eat the Reich system](https://github.com/philote/eat-the-reich) by Joseph Hopson (ephson). All credit for the original implementation goes to ephson and contributors.

### An Unofficial EAT THE REICH System for Foundry VTT
EAT THE REICH is a chaotic, ultra-violet tabletop RPG where players take on the roles of vampiric commandos on a bloody mission to tear through Nazi-occupied France during World War II. Written by [Grant Howitt](https://bsky.app/profile/gshowitt.bsky.social) and illustrated by [Will Kirkby](https://bsky.app/profile/chamonkee.bsky.social), and published by [Rowan, Rook and Decard](https://rowanrookanddecard.com). The game blends pulpy action, dark humor, and horror as players use their supernatural abilities to slaughter Nazis and consume their blood. With fast-paced mechanics and a rebellious tone, EAT THE REICH delivers an over-the-top, cathartic power fantasy drenched in gore and irreverence.

Find the books here: 
[EAT THE REICH](https://rowanrookanddecard.com/product-category/game-systems/eat-the-reich)

This Eat the Reich Package for Foundry VTT is an independent production by Joseph Hopson (ephson) and is not affiliated with Rowan, Rook and Decard or Will Kirkby. It is published under the RR&D Community License.

If you’ve enjoyed my work and find value in what I create, please consider supporting me with a small donation on [Ko-fi](https://ko-fi.com/G2G3I91JQ). I truly love what I do, and your support helps me dedicate time and resources to ongoing development. Every contribution, no matter the size, makes a difference and allows me to continue doing what I’m passionate about. Thank you for considering—it means the world to me.

## Screenshots
![Screenshot of the character sheet, item sheets, dice roll dialog](assets/screenshot.webp)
![Screenshot of the location sheet, threat sheet, GM dice roll dialog](assets/screenshot2.webp)
![Screenshot of the light mode of the character and item sheets](assets/screenshot3.webp)
![Screenshot of the Flashback functionality](assets/screenshot4.webp)
![Screenshot of Character tokens](assets/screenshot5.webp)

## How to Install
You can install the latest released version of the system by using this manifest link in Foundry VTT. [Instructions](https://foundryvtt.com/article/tutorial/): 
https://raw.githubusercontent.com/Limpbark/eat-the-reich-v14/main/system.json

> [!NOTE]
> The manifest is served from `raw.githubusercontent.com` rather than the usual `releases/latest/download/system.json` link. This avoids [Foundry issue #9861](https://github.com/foundryvtt/foundryvtt/issues/9861), where the installer's short manifest-fetch timeout trips on the multi-hop redirect that GitHub release-asset URLs take through its CDN.

## Features
- Character Sheet
- NPC/Threat Sheet
- Location Sheet
- Item Sheets for [advance, bonus, description, equipment, objective]
- Basic Dice Pool support
    - Dice can be marked as used in the chat
    - flashback re-rolling
- Supports light and dark modes
- Languages:
    - English
    - [Nicoloye](https://github.com/Nicoloye) added a French translation
    - Español
    - Polski
    - Português (Brasil)
    - Italiano
- Compendium:
    - Pre-made characters with their items
    - Paris map scene

### TODO
- Styling
    - GM rolls could be a different style than player rolls in chat
    - custom dice images for Dice so Nice
- Macros
    - PC roll without stats
    - GM roll without Threat rating
- Rolls
    - Make Injuries effect the sheet/rolls automatically somehow...

# License & Acknowledgements
The ‘Eat The Reich’ game is copyright © 2023 Rowan, Rook and Decard. All artwork in the game is copyright © 2023 Will Kirkby. You can find out more and support these games at [rowanrookanddecard.com](https://rowanrookanddecard.com)

Eat the Reich Images are used from the community RRD:
https://rowanrookanddecard.com/rrd-community-licence

### Icons used
Occupy iconby Cathelineau under CC BY 3.0
https://game-icons.net/1x1/cathelineau/occupy.html

Fanged skull iconby Lorc under CC BY 3.0
https://game-icons.net/1x1/lorc/fanged-skull.html

Upgrade iconby Delapouite under CC BY 3.0
https://game-icons.net/1x1/delapouite/upgrade.html

Skills iconby Delapouite under CC BY 3.0
https://game-icons.net/1x1/delapouite/skills.html

Backpack iconby Delapouite under CC BY 3.0
https://game-icons.net/1x1/delapouite/backpack.html

Strongbox iconby Delapouite under CC BY 3.0
https://game-icons.net/1x1/delapouite/strongbox.html

Flying target iconby Delapouite under CC BY 3.0
https://game-icons.net/1x1/delapouite/flying-target.html

Info iconby Delapouite under CC BY 3.0
https://game-icons.net/1x1/delapouite/info.html
