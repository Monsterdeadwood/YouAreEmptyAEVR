> [!IMPORTANT]
> **[TEST BUILDS & DISCUSSION · FLAT2VR DISCORD](https://discord.gg/P4q9zt7ek)**
> Testing, build requests, feedback and discussion happen in the **Flat2VR Modding Discord**. Join the server and find the **You Are Empty: Absolute Edition VR** thread.

<p align="center">
  <img src="assets/vr-banner.png" alt="You Are Empty: Absolute Edition VR" width="690">
</p>

# You Are Empty: Absolute Edition VR

[Flat2VR Discord](https://discord.gg/P4q9zt7ek) · [All projects](PORTFOLIO.md)

![Project status](assets/vr-status.svg)

A VR mod for You Are Empty: Absolute Edition with a tracked right-hand weapon, an independent left hand and melee with either hand. R47 supports starting a new game on an installation with no player profile or saves.

**Package baseline on this page: R47 first-run test package.**

## Installation

1. Ask for the **YAEVR R47** first-run test package in the You Are Empty thread on Flat2VR. Keep your supported Absolute Edition installation separate.
2. Extract the complete mod folder.
3. Connect PC VR through your active OpenXR runtime, then open **RUN.bat**.
4. If automatic detection fails, put the full path to the game folder in **GAME_PATH.txt**.
5. The launcher resumes Save0 if present, then falls back to the newest regular save. With no saves, it starts the first campaign level. Use **RUN.bat --slot SLOT_NAME** to choose a slot or **RUN.bat --new-game** to start a new game.
6. Keep the console open. If you run into a problem, share the generated diagnostics ZIP in the Discord thread.

Current test-package availability is coordinated in Discord. Use the complete package for your supported game build; this project page is separate from a release download.

## What this project brings to VR

- Tracked right-hand weapons, an independent left palm and melee with either hand.
- A 12-weapon test loadout and controller-directed interaction.
- Both-hand blocking/release on tested static walls through sampled source-derived collision envelopes.
- VR-accessible inventory, recenter and pause controls.
- SMAA High, FSR 1 and current OpenXR runtime selection.
- On first launch, R47 creates missing profile settings from the installed game’s templates and preserves existing settings.

<details>
<summary><b>Controller quick reference</b></summary>

| Input | Action |
| --- | --- |
| Right trigger / left trigger | Fire / supported secondary action |
| A or right grip | Interact |
| B / X / Y | Reload / jump / crouch toggle |
| Left stick / click | Move / sprint toggle until stick release |
| Right stick horizontal / vertical / click | Turn / previous-next weapon / inventory |
| Left grip hold | Inventory; release to close |
| Left Menu tap / hold | Recenter / pause-resume |

The complete package control sheet takes precedence for its version and interaction profile.

</details>

## Features in newer test builds

- **Ultrawide startup and English interface.** The R49–R50 follow-ups use the measured game viewport and provide a fully English launcher interface in R50. An R50 test with 2560×1080 input produced stereo on a fresh profile. Repeat startup on all reported configurations and physical-headset tests remain open.

## Current status

**Experimental preview.** R47 checks in the actual game with XR Sim covered a fresh profile with no saves and resuming the most recent save when Save0 is missing. RUN.bat was also tested from a fresh extraction with both supported executables.

- Physical Meta/SteamVR acceptance and full-campaign coverage remain open.
- The met6 first-person issue, Thunder carry/throw, flamethrower damage/ammo and all cinematic/new-VM transitions remain incompletely qualified.

[Detailed status and validation scope](docs/PROJECT_STATUS.md)

## Testing & feedback

Post in the game’s [Flat2VR thread](https://discord.gg/P4q9zt7ek) with your **mod version, game/store version, headset, OpenXR runtime, GPU, reproduction steps and the package’s diagnostic ZIP**. A short video is helpful for visual or handling problems.

<!-- COMMUNITY_TESTERS_START -->
## ❤️ Community testers — thank you!

These VR projects improve thanks to the people sharing test reports, logs, videos and practical feedback across the portfolio.

alvaro · Arkturus [CODA] · Arkturus Primacronus [HD2M] · Arthur G [ORE] · Bestgamer3 · Chtiblue · creative name [SC℧M] · Derp Dog · DNana51 [R1Δ] · Gritt [F2VR] · headbangerle. · huligan01 · jeremiasadasmki · Kerin\_Serica [1984] · kilo · Lawyer [WYRD] · little\_boxbr · Lord Beardsteak · MeWhenINameMyself · MetalikSix · neoz\_1980 · Notagameaddict · Pelmeschka · Potato Pancake Person · ReseTV · Rusty Gere · SilentBang [LTS] · SilentVortigaunt · Terry · ThE LaNd GuLl · Thomas-3D-VR · Uruz [F2VR] · Willthethrill · wxorys\_ · Xavier H. G.

[Full community credits, games, feedback contributors and testing volunteers](TESTERS.md).

The linked list shows which games each person helped with. Thank you as well to everyone whose reports arrived without a public display name.

<!-- COMMUNITY_TESTERS_END -->

## Other VR mods by Monsterdeadwood

| Game / project | Focus | Visibility |
| --- | --- | --- |
| [Assassin’s Creed VR](https://github.com/Monsterdeadwood/AC1VR) | First-person exploration, tracked climbing and sword interaction | Private |
| [Crysis 2: VRevamp](https://github.com/Monsterdeadwood/C2VR) | Original Crysis 2 in VR with tracked weapons, physical melee and a spatial HUD | Public |
| [Star Wars: The Force Unleashed II VR](https://github.com/Monsterdeadwood/TFU2VR) | Tracked dual lightsabers, telekinesis and Force powers | Public |
| [NOVA · Counter-Strike: Global Offensive (Legacy) VR](https://github.com/Monsterdeadwood/CSGOVR) | Local 5v5 bot matches, motion-controlled aiming and haptics | Public |
| [TimeShift VR](https://github.com/Monsterdeadwood/TimeShiftVR) | Controller-driven time powers, tracked weapons and roomscale posture | Public |
| [Alone in the Dark (2008) VR](https://github.com/Monsterdeadwood/AloneInTheDark2008VR) | Tracked items, wall contact and the original throw controls | Public |
| [Rainbow Six Siege VR](https://github.com/Monsterdeadwood/SiegeVR) | Shadow Legacy stereo and two-handed weapon handling | Public |
| [Burnout Paradise Remastered VR](https://github.com/Monsterdeadwood/BUrnOutPvr) | Head-tracked stereo driving, vehicle menus and boost effects | Public |
| [Titanfall 1 VR](https://github.com/Monsterdeadwood/Titanfall1VR) | R1Delta pilot aiming, stereo viewing and Titan cockpits | Public |
| [Metro 2033 VR](https://github.com/Monsterdeadwood/Metro2033VR) | Original Metro 2033 with tracked interaction and PhysX experiments | Public |
| [Insurgency VR](https://github.com/Monsterdeadwood/InsurgencyVR) | Early VR mod project for stereo rendering and the game camera | Private |
| [Counter-Strike: Source VR](https://github.com/Monsterdeadwood/CSSVR) | Early VR mod project for stereo rendering and head tracking | Private |

Private repository links are available to invited collaborators. Public project pages are marked above.

## Credits & development notes

Project maintained by [Monsterdeadwood](https://github.com/Monsterdeadwood). This is an independent fan VR project; you need your own supported copy of the original game.

Documentation reviewed: **15 November 2026**.
