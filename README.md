> [!IMPORTANT]
> **[TEST BUILDS & DISCUSSION · FLAT2VR DISCORD](https://discord.gg/P4q9zt7ek)**
> Testing, build requests, feedback and discussion happen in the **Flat2VR Modding Discord**. Join the server and find the **You Are Empty: Absolute Edition VR** thread.

![You Are Empty: Absolute Edition VR — Monsterdeadwood VR mods](assets/vr-banner.svg)

# You Are Empty: Absolute Edition VR

[English](README.md) · [Русский](README_RU.md) · [Flat2VR Discord](https://discord.gg/P4q9zt7ek) · [All projects](PORTFOLIO.md)

![Project status](assets/vr-status.svg)

A VR mod for You Are Empty: Absolute Edition with a tracked weapon, an independent left palm, both-hand melee and native-game interaction. R46 keeps the R45 gameplay branch and fixes a reported startup compatibility rejection.

**Current documented branch: R46 startup compatibility preview.**

## Installation

1. Get the current **YAEVR R46** test package in the You Are Empty thread on Flat2VR. Keep your supported Absolute Edition installation separate.
2. Extract the complete single mod folder.
3. Connect PC VR through your active OpenXR runtime, then open **RUN.bat**.
4. If automatic detection fails, put the game’s full folder path in **GAME_PATH.txt**. The launcher loads Save0; use RUN.bat --slot SLOT_NAME for another slot.
5. Keep the console open. After testing, share the generated local diagnostics ZIP in the Discord thread.

Current test-package availability is coordinated in Discord. Use the complete package for your supported game build; this project page is separate from a release download.

## What this project brings to VR

- Tracked right-hand weapons, an independent left palm and melee with either hand.
- A 12-weapon test loadout and controller-directed interaction.
- Both-hand blocking/release on tested static walls through sampled source-derived collision envelopes.
- VR-accessible inventory, recenter and pause controls.
- SMAA High, FSR 1 and current OpenXR runtime selection.
- R46 startup fix retains exact checks on supported game modules and models.

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

## Current status

**Experimental preview.** R45 collision, twelve-weapon and Save0 checks used the actual game with XR Sim. R46 exercised startup/gameplay with the reported game and Steam DLL identities.

- Physical Meta/SteamVR acceptance and full-campaign coverage remain open.
- The met6 first-person issue, Thunder carry/throw, flamethrower damage/ammo and all cinematic/new-VM transitions remain incompletely qualified.

[Detailed status and validation scope](docs/PROJECT_STATUS.md)

## Testing & feedback

Post in the game’s [Flat2VR thread](https://discord.gg/P4q9zt7ek) with your **mod version, game/store version, headset, OpenXR runtime, GPU, reproduction steps and the package’s diagnostic ZIP**. A short video is helpful for visual or handling problems.

## Other VR mods by Monsterdeadwood

| Game / project | Focus | Visibility |
| --- | --- | --- |
| [Assassin’s Creed VR](https://github.com/Monsterdeadwood/AC1VR) | First-person exploration, climbing and sword interaction | Private |
| [Crysis 2: VRevamp](https://github.com/Monsterdeadwood/C2VR) | Nanosuit combat, physical interaction and spatial UI | Public |
| [Star Wars: The Force Unleashed II VR](https://github.com/Monsterdeadwood/TFU2VR) | Dual lightsabers, independent telekinesis and Force powers | Public |
| [NOVA · CS:GO Legacy VR](https://github.com/Monsterdeadwood/CSGOVR) | CS:GO Legacy local matches with motion controls | Public |
| [TimeShift VR](https://github.com/Monsterdeadwood/TimeShiftVR) | Time powers, nine weapons and roomscale posture | Public |
| [Alone in the Dark 2008 VR](https://github.com/Monsterdeadwood/AloneInTheDark2008VR) | Survival-horror VR and held-item interaction | Public |
| [Rainbow Six Siege VR](https://github.com/Monsterdeadwood/SiegeVR) | Legacy Siege stereo and tracked weapon handling | Public |
| [Burnout Paradise Remastered VR](https://github.com/Monsterdeadwood/BUrnOutPvr) | Stereo driving, vehicle menus and native effects | Public |
| [Titanfall 1 VR](https://github.com/Monsterdeadwood/Titanfall1VR) | Pilot combat and Titan cockpit VR | Public |
| [Metro 2033 VR](https://github.com/Monsterdeadwood/Metro2033VR) | Original Metro VR and native physics experiments | Public |
| [Insurgency VR](https://github.com/Monsterdeadwood/InsurgencyVR) | Early VR integration research | Private |
| [Counter-Strike: Source VR](https://github.com/Monsterdeadwood/CSSVR) | Counter-Strike: Source VR development | Private |

Private repository links are available to invited collaborators. Public project pages are marked above.

## Credits & development notes

Project maintained by [Monsterdeadwood](https://github.com/Monsterdeadwood). This is an independent fan VR project; you need your own supported copy of the original game.

Documentation reviewed: **14 November 2026**.
