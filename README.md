# MW2CR VR by zseeker

An unofficial VR build for **Call of Duty: Modern Warfare 2 Campaign Remastered (MW2CR)**, based on [Overlord](https://github.com/Aeka0/Overlord).

## Compatibility

This package targets the **FitGirl MW2CR release containing executable version 1.1.2.1279292 (the accessibility variant)**. It was built and checked against that specific executable variant. Other repacks, game versions, or executables may not work. Check the game executable before installing if you are unsure which version you have.

You must have a legally obtained copy of MW2CR and install the required base Overlord/H2-Mod data separately. This client package does not contain the game or the base H2-Mod fastfiles.

## Requirements

- Windows PC and the compatible MW2CR installation described above
- The separate base H2-Mod/Overlord release data, including its `h2-mod` folder
- A VR headset and runtime supported by Overlord (for example SteamVR/OpenXR)

## Install

1. Install MW2CR and the required base Overlord/H2-Mod data. Confirm that the game folder contains the `h2-mod` folder.
2. Download `overlord-RelWithDebInfo-3fcbf03971b9.zip` from the [Beta 6 variant release](https://github.com/MohamedHussien-zseeker/mw2cr-vr-by-zseeker/releases/tag/beta-6-variant-1279292).
3. Extract the ZIP into the MW2CR game folder, preserving the folders in the archive. Allow the package files to be added alongside the existing `h2-mod` data.
4. Connect your headset and start its VR runtime. Launch `overlord.exe` from the game folder and follow the first-run setup.
5. In Overlord, open **VR Settings → Basics**, select the available VR backend, then choose **Singleplayer**.

Keep a backup of your game folder before replacing files. If the game does not start, first confirm that the executable is the supported 1.1.2.1279292 variant and that the separate base data is installed.

## What the package includes

The ZIP contains the compiled Overlord client overlay and its support files. It does not include MW2CR, the game's executable, or the base H2-Mod fastfiles. Those must be obtained separately.

## Credits and notices

- **Overlord:** created by [Aeka0](https://github.com/Aeka0/Overlord) and its contributors. This build is based on that project; please see its repository for upstream documentation and license details.
- **zseeker:** variant port build and package.
- This is an unofficial community build and is not affiliated with or endorsed by Activision, Infinity Ward, or FitGirl Repacks.

Please review [Overlord's third-party notices](https://github.com/Aeka0/Overlord/blob/main/THIRD_PARTY_NOTICES.md) and the upstream license before redistribution. Do not redistribute game files or base fastfiles.