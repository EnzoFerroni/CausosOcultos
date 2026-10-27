<div align="center">

<img src="docs/icon.png" width="120" alt="Causos Ocultos app icon"/>

# Causos Ocultos: Quixeramobim

[![iOS](https://img.shields.io/badge/iOS-26.2%2B-000000?logo=apple)](https://developer.apple.com/ios/)
[![watchOS](https://img.shields.io/badge/watchOS-26.2%2B-000000?logo=apple)](https://developer.apple.com/watchos/)
[![SpriteKit](https://img.shields.io/badge/SpriteKit-SwiftUI-F05138?logo=swift&logoColor=white)](https://developer.apple.com/spritekit/)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)](LICENSE.md)

A survival horror game for iPhone and Apple Watch inspired by the folklore of Quixeramobim, in the Brazilian sertão.

<a href="https://apps.apple.com/br/app/causosocultosquixeramobim/id6759735287">
  <img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg" height="48" alt="Download on the App Store"/>
</a>

</div>

## Table of Contents

- [About](#about)
- [How to Play](#how-to-play)
- [Screenshots](#screenshots)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Team](#team)
- [License](#license)

## About

*O Grito do Sertão: A Noite do Capelobo.* You are Val, the youngest of a big family,
at her first Santo Antônio festival, who ignores grandma's "haunted" tales and stays out late. Then a howl
that does not belong to this world breaks the silence. The Capelobo, a creature from
northern Brazilian folklore, is hunting, and the only goal is to survive until dawn.

Built at the Apple Developer Academy | Mackenzie, with a hand-drawn, cross-hatched
art style. The game is published on the App Store and its text is in Portuguese.

## How to Play

- Move between the rooms of the house: entrance, kitchen, shelf and window.
- Barricade doors and windows before the Capelobo breaks in.
- Find out the creature's story and weak points, then strike back at the right moment.
- Survive each hour of the night until morning comes.
- On the Apple Watch, turn the Digital Crown to switch between rooms and use the
  watch to lure the Capelobo away.

## Screenshots

| Story | Story |
| :---: | :---: |
| <img src="docs/screenshots/1.png" width="400"> | <img src="docs/screenshots/2.png" width="400"> |
| **Nightfall** | **Gameplay** |
| <img src="docs/screenshots/3.png" width="400"> | <img src="docs/screenshots/4.png" width="400"> |

## Built With

- SpriteKit scenes for the intro, tutorial and every room of the house
- SwiftUI for menus, the HUD and navigation
- WatchConnectivity to sync the iPhone game with the watchOS companion app
- AVFoundation for the soundtrack and sound cues
- Digital Crown input and haptics on Apple Watch

## Getting Started

Requirements: Xcode 26 or later. Run on an iPhone simulator or device with iOS 26.2;
the Apple Watch companion needs a paired watch simulator or device.

```bash
git clone https://github.com/EnzoFerroni/CausosOcultos.git
cd CausosOcultos
open CausosOcultosQuixeramobim.xcodeproj
```

## Project Structure

```
CausosOcultosQuixeramobim/
├── Scenes/
│   ├── FillerScenes/    Intro, tutorial, victory and defeat scenes
│   └── GameScenes/      Rooms of the house and their close-ups
├── Entities/            Player, Enemy, Barricade, Breach
├── Managers/            GameController, SceneManager, SoundManager, iPhone connectivity
├── View/                SwiftUI menu, game, intro and game over views
└── Models/              Enums, fonts
CausosOcultosQuixeramobimW Watch App/   watchOS companion (camera view, crown input)
```

## Team

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <a href="https://github.com/carolssun"><img src="https://github.com/carolssun.png" width="90" alt="Carolina Sun"/></a>
        <br/><sub><b>Carolina Sun</b></sub><br/><br/>
        <a href="https://github.com/carolssun"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/carolina-sun/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="25%">
        <a href="https://github.com/dayoleal"><img src="https://github.com/dayoleal.png" width="90" alt="Dayô Araújo"/></a>
        <br/><sub><b>Dayô Araújo</b></sub><br/><br/>
        <a href="https://github.com/dayoleal"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/dayo-araujo/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="25%">
        <a href="https://github.com/EnzoFerroni"><img src="https://github.com/EnzoFerroni.png" width="90" alt="Enzo Ferroni"/></a>
        <br/><sub><b>Enzo Ferroni</b></sub><br/><br/>
        <a href="https://github.com/EnzoFerroni"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/enzoferroni/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="25%">
        <a href="https://github.com/LosadaT"><img src="https://github.com/LosadaT.png" width="90" alt="Francisco Losada"/></a>
        <br/><sub><b>Francisco Losada</b></sub><br/><br/>
        <a href="https://github.com/LosadaT"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/francisco-losada-totaro/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
    </tr>
    <tr>
      <td align="center" width="25%">
        <a href="https://github.com/hissapinto"><img src="https://github.com/hissapinto.png" width="90" alt="Isabela Hissa Pinto"/></a>
        <br/><sub><b>Isabela Hissa Pinto</b></sub><br/><br/>
        <a href="https://github.com/hissapinto"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/isabela-hissa-pinto-05aa741b9/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="25%">
        <a href="https://github.com/JonasFNMelo"><img src="https://github.com/JonasFNMelo.png" width="90" alt="Jonas Melo"/></a>
        <br/><sub><b>Jonas Melo</b></sub><br/><br/>
        <a href="https://github.com/JonasFNMelo"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/jonas-melo-/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="25%">
        <a href="https://github.com/TamiresMendesS"><img src="https://github.com/TamiresMendesS.png" width="90" alt="Tamires Mendes"/></a>
        <br/><sub><b>Tamires Mendes</b></sub><br/><br/>
        <a href="https://github.com/TamiresMendesS"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/tamires-mendes-6006792b7/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="25%">
        <a href="https://github.com/YasminMSouza"><img src="https://github.com/YasminMSouza.png" width="90" alt="Yasmin Mendes"/></a>
        <br/><sub><b>Yasmin Mendes</b></sub><br/><br/>
        <a href="https://github.com/YasminMSouza"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/yasmin-mendes-629a29267/"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
    </tr>
  </table>
</div>

Fork of the team repository [C11G3/CausosOcultosQuixeramobim](https://github.com/C11G3/CausosOcultosQuixeramobim).

## License

Copyright (c) 2026 Carolina Sun, Dayô Araújo, Enzo Ferroni, Francisco Losada, Isabela Hissa Pinto,
Jonas Melo, Tamires Mendes and Yasmin Mendes.
Released under [Creative Commons Attribution-NonCommercial 4.0](LICENSE.md), as chosen
by the team: you may share and adapt the work with credit, but not for commercial use.
