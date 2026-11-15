# You Are Empty: Absolute Edition VR — project status

[← Project page](../README.md) · [Flat2VR testing & discussion](https://discord.gg/P4q9zt7ek)

Reviewed **15 November 2026**. Documented branch: **R47 first-run test package**.

## What has been checked

- R47 checks in the actual game with XR Sim covered a fresh profile with no saves and resuming the most recent save when Save0 is missing. RUN.bat was also tested from a fresh extraction with both supported executables.
- R45 collision, twelve-weapon and Save0 checks used the actual game with XR Sim. R46 exercised startup and gameplay with the reported game and Steam DLL identities.

## Follow-up tests reviewed 16 November 2026

R50 qualified the English help, errors and control labels. A standard cold BAT run and a 2560×1080 fresh-profile XR Sim run produced stereo pairs. Other wide attempts hit a frame timeout or a game-script startup failure. The results are scoped to the tested game and profile identities.

Verification records used for this section

- `YAE_R49_ULTRAWIDE_RU_QUALIFICATION_20261116.json`
- `YAE_R50_ENGLISH_QUALIFICATION_20261116.json`

## Current limits

- Physical Meta/SteamVR acceptance and full-campaign coverage remain open.
- The met6 first-person issue, Thunder carry/throw, flamethrower damage/ammo and all cinematic/new-VM transitions remain incompletely qualified.

## Build access

Ask for the current complete test package in the game’s Flat2VR thread. A local build record does not by itself mean a file has been uploaded to this repository’s Releases.

## Documentation basis

This overview was reconciled against the project’s recorded package notes and validation records. The following names identify the records reviewed; they are not download links:

- `YAEVR_R47_First_Run_Fix_20261114/README_EN.txt`
- `YAE_R47_FIRST_RUN_FIX_QUALIFICATION_20261114.json`
- `YAE_R46_STARTUP_FIX_QUALIFICATION_20261114.json`
- `YAE_R45_COLLISION_PERFORMANCE_DISCORD_QUALIFICATION_20261112.json`

Game execution, simulator validation and physical-headset feedback are reported separately above. Features from a separate experimental branch are identified explicitly.

## Кратко по-русски

VR-мод You Are Empty: Absolute Edition с оружием от контроллера, независимой левой ладонью, ближним боем обеими руками и взаимодействием с предметами игры. R47 может начать новую игру, даже если профиль и сохранения ещё не созданы.

- Принятие в физических Meta/SteamVR-шлемах и вся кампания ещё требуют проверки.
- Проблема первого лица met6, перенос/бросок Thunder, урон/боезапас огнемёта и все переходы сцен/новых VM ещё не проверены полностью.
