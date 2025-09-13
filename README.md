# Cities:Skylines Mods for Epic users
Some mod developer publish GitHub Repo but don't have any GitHub Releases.
Now that [Steam Workshop Downloader](https://steamworkshopdownloader.io/) is dead, you have to build by yourself which is not very easy.

So this repo have some compiled results.
They are basically latest version as of **13 Sep 2025**, and has not been updated since then.
Version 1.19.2-f3, which was released on 25 Mar 2025, is likely to be the final version of Cities: Skylines 1 and all Mods builder seems to have moved to CS:2.
Therefore, even though the compiled results have not been updated since then, it is highly likely that they will still work without any issues even today.

I don't play Cities:Skylines often, so I don't maintain this repository much.

## Other docs
* [Basic build steps for Epic users.](BuildSteps.md)
* [Small tips for Mod developers.](TipsForModDevs.md)
* ~[Compatibility Issues of 1.15.0-f7](Compatibility-1.15.0-f7.md)~
* [Google Docs - [Cities Skylines] Broken & Incompatible Mods - Patch 1.17.1-f4](https://docs.google.com/spreadsheets/d/1mVFkj_7ij4FLzKs2QJaONNmb9Z-SRqUeG6xFGqEX1ew/edit) (Official?)

Mods Directory: %LocalAppData%\Colossal Order\Cities_Skylines\Addons\Mods

## Security
Mod of Cities:Skylines is basically just a .NET library. There's no sandbox (I think) and they have various risks. I do believe that these repositories published on GitHub contain no malicious code, but you have to use them at your own risk. And I don't know about binaries in other repositories.

Anyway, I guarantee I've not done anything malicious. I just got it, edited it to get the build to pass, built it and pulished it here. Also, all Mods listed below have been tried by me at least once.

## Mods
### Mods with compiled binaries by original developers
| Name | Repo | Where | Note |
| -- | -- | -- | -- |
| ~[Fine Road Anarchy](https://steamcommunity.com/sharedfiles/filedetails/?id=1844440354)~ | ~[GitHub](https://github.com/klyte45/CS-FineRoadAnarchy)~ | ~[FineRoadAnarchy/_requiredDLLs](https://github.com/klyte45/CS-FineRoadAnarchy/tree/master/FineRoadAnarchy/_requiredDLLs)~ | Use Network Anarchy instead. |
| ~[Hide it, Bobby!](https://steamcommunity.com/sharedfiles/filedetails/?id=2513657277)~ | ~[GitHub](https://github.com/TheCSUser/HideItBobby)~ | ~[Releases](https://github.com/TheCSUser/HideItBobby/releases)~ | Broken. Use "Hide it!" instead. |
| [Yet Another Toolbar](https://steamcommunity.com/sharedfiles/filedetails/?id=2448994345) | [GitHub](https://github.com/sway2020/YetAnotherToolbar) | [Releases](https://github.com/sway2020/YetAnotherToolbar/releases) |
| [UnifiedUI](https://steamcommunity.com/sharedfiles/filedetails/?id=2255219025) | [GitHub](https://github.com/kianzarrin/UnifiedUI) | [Releases](https://github.com/kianzarrin/UnifiedUI/releases) | |
| ~~[Upgrade Untouchable: Convert stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2629141193)~~ | ~~[GitHub](https://github.com/klyte45/TouchThisTool)~~ | ~~[_requiredDLLs](https://github.com/klyte45/TouchThisTool/tree/master/_requiredDLLs)~~ | Folder does not exist in latest commit. |
| [Intersection Marking Tool](https://steamcommunity.com/sharedfiles/filedetails/?id=2140418403) | [GitHub](https://github.com/MacSergey/NodeMarkup) | [Releases](https://github.com/MacSergey/NodeMarkup/releases) | |
| [Network Multitool](https://steamcommunity.com/sharedfiles/filedetails/?id=2560782729) | [GitHub](https://github.com/MacSergey/NetworkMultitool) | [Releases](https://github.com/MacSergey/NetworkMultitool/releases) | |
| [Node Controller Renewal](https://steamcommunity.com/sharedfiles/filedetails/?id=2472062376) | [GitHub](https://github.com/MacSergey/NodeController30) | [Releases](https://github.com/MacSergey/NodeController30/releases/) | |
| ~~[Fine Road Tool](https://steamcommunity.com/sharedfiles/filedetails/?id=1844442251)~~ | ~~[GitHub](https://github.com/klyte45/CS-FineRoadTool)~~ | ~~[libs](https://github.com/klyte45/CS-FineRoadTool/tree/master/libs)~~ | Use Network Anarchy instead. |
| [Harmony](https://steamcommunity.com/sharedfiles/filedetails/?id=2040656402) | [GitHub](https://github.com/boformer/CitiesHarmony) | [Releases](https://github.com/boformer/CitiesHarmony/releases) | You need it to run the others! |
| [TM:PE](https://steamcommunity.com/sharedfiles/filedetails/?id=1637663252) | [GitHub](https://github.com/CitiesSkylinesMods/TMPE/) | [Releases](https://github.com/CitiesSkylinesMods/TMPE/releases) | |
| [Building Spawn Points](https://steamcommunity.com/sharedfiles/filedetails/?id=2511258910) | [GitHub](https://github.com/MacSergey/BuildingSpawnPoints) | [Releases](https://github.com/MacSergey/BuildingSpawnPoints/releases) | |
| [Automatic Pedestrian Bridge Builder](https://steamcommunity.com/sharedfiles/filedetails/?id=2030755273) | [GitHub](https://github.com/kianzarrin/PedestrianBridge/) | [Releases](https://github.com/kianzarrin/PedestrianBridge/releases) | |
| [Hide TMPE crosswalks](https://steamcommunity.com/sharedfiles/filedetails/?id=1934023593) | [GitHub](https://github.com/CitiesSkylinesMods/HideCrosswalks) | [Releases](https://github.com/CitiesSkylinesMods/HideCrosswalks/releases) | |
| [Picker](https://steamcommunity.com/sharedfiles/filedetails/?id=2172488844) | [GitHub](https://github.com/Quboid/Picker) | [Releases](https://github.com/Quboid/Picker/releases) | |
| [Move It](https://steamcommunity.com/sharedfiles/filedetails/?id=1619685021) | [GitHub](https://github.com/Quboid/CS-MoveIt) | [Releases](https://github.com/Quboid/CS-MoveIt/releases) | |
| ~[Transport Lines Manager](https://steamcommunity.com/sharedfiles/filedetails/?id=1312767991)~ | ~[GitHub](https://github.com/klyte45/TransportLinesManager)~ | ~[_requiredDLLs](https://github.com/klyte45/TransportLinesManager/tree/master/_requiredDLLs)~ | [^25]  Archived. |
| [Network Anarchy](https://steamcommunity.com/sharedfiles/filedetails/?id=2862881785) | [GitHub](https://github.com/Quboid/NetworkAnarchy) | [Releases](https://github.com/Quboid/NetworkAnarchy/releases) | |


### Mods with compiled binaries here
I compiled so you don't have to. Do it yourself if the date isn't close. "Build note" is not actively maintained now.

| Name | Repo | License |  Build note | Binary | Binary version |
| -- | -- | -- | -- | -- | -- |
| ~[Improved Public Transport 2](https://steamcommunity.com/sharedfiles/filedetails/?id=928128676)[^24]~ | ~[GitHub](https://github.com/bloodypenguin/ImprovedPublicTransport)~ | ~Not specified~ | [^1][^2][^3][^4][^6][^7][^8] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/10-June-2022) | v6.0.0-preview5 ([d3476d0](https://github.com/bloodypenguin/ImprovedPublicTransport/commit/d3476d0614cc59099025b15087451440debce520)) on 17 Feb 2022 |
| [Zoning Adjuster](https://steamcommunity.com/sharedfiles/filedetails/?id=2389414419) | [GitHub](https://github.com/algernon-A/ZoningAdjuster) | [MIT](https://github.com/algernon-A/ZoningAdjuster/blob/master/LICENSE.txt) | [^1][^2][^3][^4][^5][^9][^10] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/24-May-2023) | v1.6.2 ([923fc0f](https://github.com/algernon-A/ZoningAdjuster/commit/923fc0fc97ac246623990f25c2a82d3964009d8e)) on May 23, 2023 |
| ~[Extra Landscaping Tools](https://steamcommunity.com/sharedfiles/filedetails/?id=502750307)[^24]~ | ~[GitHub](https://github.com/bloodypenguin/Skylines-NaturalResourcesBrush) [^20]~ | ~[GPL-3.0](https://github.com/bloodypenguin/Skylines-NaturalResourcesBrush)~ | [^1][^2][^3][^6][^7][^8] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/10-June-2022) |  [91ad84a](https://github.com/bloodypenguin/Skylines-NaturalResourcesBrush/commit/91ad84aa78e7e41805094f5f8f7335247e89abee) on 25 Jan 2022 |
| [Daylight Classic](https://steamcommunity.com/workshop/filedetails/?id=530871278) | [GitHub](https://github.com/bloodypenguin/Skylines-DaylightClassic) | [GPL-3.0](https://github.com/bloodypenguin/Skylines-DaylightClassic/blob/master/LICENSE) | [^1][^2][^3][^6][^8] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/10-June-2022) | v1.12.2 ([775042d](https://github.com/bloodypenguin/Skylines-DaylightClassic/commit/775042d16e9f4ffbaba02ab9dca1be9f24f7101d)) on 8 May 2021 |
| ~[81 Tiles](https://steamcommunity.com/sharedfiles/filedetails/?id=576327847)[^24]~ | ~[GitHub](https://github.com/bloodypenguin/cities-skylines-unlimiter-1) [^21]~ | ~[GPL-3.0](https://github.com/bloodypenguin/cities-skylines-unlimiter-1/blob/master/LICENSE.md)~ | [^1][^2][^3][^4] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/10-June-2022) | [cbc08e8](https://github.com/bloodypenguin/cities-skylines-unlimiter-1/commit/cbc08e8f99838a2c54f59955fdb4bbdcc3c29249) on 26 Jan 2022 |
| [City Vitals Watch](https://steamcommunity.com/sharedfiles/filedetails/?id=410151616) | [GitHub](https://github.com/rob-williams/CityVitalsWatchMod/) | [BSD-3-Clause](https://github.com/rob-williams/CityVitalsWatchMod/blob/master/License.md) | [^1][^2][^3] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/10-June-2022) | [a059a13](https://github.com/rob-williams/CityVitalsWatchMod/commit/a059a132db2ee7aa8d4eb6c06838a4e3d6b2782b) on 1 Nov 2015 |
| [Precision Engineering](https://steamcommunity.com/sharedfiles/filedetails/?id=445589127) | [GitHub](https://github.com/Simie/PrecisionEngineering) | [MIT?](https://github.com/Simie/PrecisionEngineering/blob/master/LICENSE.txt) | [^1] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/10-June-2022) | [7d75828](https://github.com/Simie/PrecisionEngineering/commit/7d75828809851224ac9e397a4002b57b1d00c544) on 20 Oct 2021 |
 | [Network Extensions 2](https://steamcommunity.com/sharedfiles/filedetails/?id=812125426) | [GitHub](https://github.com/andreharv/NetworkExtensions) [^22] | Not specified | [^1][^2][^12][^13][^14] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/16-September-2022) | [71a11b2](https://github.com/andreharv/NetworkExtensions/commit/71a11b26a376b4bc3393aadd62fa51ddd9c5b6ae) on 16 Sep 2022 |
| [81 Tiles 2](https://steamcommunity.com/sharedfiles/filedetails/?id=2862121823) | [GitHub](https://github.com/algernon-A/EightyOne2) | [MIT](https://github.com/algernon-A/EightyOne2/blob/master/LICENSE.txt) | [^1][^3][^9] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/06-September-2025) | v1.0.4 ([552208d](https://github.com/algernon-A/EightyOne2/commit/552208def765381c9485107454aba3c20d3c4153)) on Apr 18, 2024 |
| [Loading Screen Mod Revisited](https://steamcommunity.com/sharedfiles/filedetails/?id=2858591409) | [GitHub](https://github.com/algernon-A/LSM-Revisited/) | Not specified | [^1][^23] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/06-September-2025) | v1.1.11 ([1e9b747](https://github.com/algernon-A/LSM-Revisited/commit/1e9b74721911f8e7afcef5430488aad6b571a55e)) on Mar 25, 2025 |
| [Airport Roads](https://steamcommunity.com/sharedfiles/filedetails/?id=465127441) | [GitHub](https://github.com/SamsamTS/CS-AirportRoads) | [GPL-2.0](https://github.com/SamsamTS/CS-AirportRoads/blob/master/LICENSE) | [^1][^2][^3] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/16-September-2022) | [b2fca31](https://github.com/SamsamTS/CS-AirportRoads/commit/b2fca31e4b23de2844d08e2c310601d8d6f726c9) on 29 May 2018 |
| [Improved Transport Manager](https://steamcommunity.com/sharedfiles/filedetails/?id=2888964436) | [GitHub](https://github.com/klyte45/ImprovedTransportManager) | Not specified | - | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/18-February-2023) | [4419774](https://github.com/klyte45/ImprovedTransportManager/commit/4419774e96125ccb073d5f1badba5e93c87a4c40) on 4 Feb 2023 |
| ~[Move It](https://steamcommunity.com/sharedfiles/filedetails/?id=1619685021)~ | ~[GitHub](https://github.com/Quboid/CS-MoveIt)~ | ~[MIT](https://github.com/Quboid/CS-MoveIt/blob/master/LICENSE.txt)~ | Temporary[^26] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/22-March-2023) | v2.10.1([0f4724f](https://github.com/Quboid/CS-MoveIt/commit/0f4724f2fb55e53fe3cf4bf0b930d11f0a64c0c6)) on 18 March 2023 |
| [RON, the network replacer](https://steamcommunity.com/sharedfiles/filedetails/?id=2405917899) | [GitHub](https://github.com/algernon-A/RON) | [MIT](https://github.com/algernon-A/RON/blob/master/License.txt) | | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/14-March-2024) | v1.1.1 ([7d5c721](https://github.com/algernon-A/RON/commit/7d5c72134dae737fff6146c4f5ea5f7418d00af2)) on Sep 21, 2023 |
| ~[Font Selector](https://steamcommunity.com/workshop/filedetails/?id=412149127)?~ | ~[GitHub](https://github.com/nyjin/CitiesSkylineFontSelectorMod)~ | ~[Apache License 2.0](https://github.com/nyjin/CitiesSkylineFontSelectorMod/blob/master/LICENSE)~ | [^27][^28] | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/22-March-2023) | [4cd8c58](https://github.com/nyjin/CitiesSkylineFontSelectorMod/commit/4cd8c581154f914e20b6a252eaa904c5f908b772) on 24 July 2017 |
| [Empty It!](https://steamcommunity.com/sharedfiles/filedetails/?id=1661072176) | [GitHub](https://github.com/keallu/CSL-EmptyIt) | [MIT](https://github.com/keallu/CSL-EmptyIt/blob/master/LICENSE) | | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/26-June-2023) | v1.6 ([a2fbb71](https://github.com/keallu/CSL-EmptyIt/commit/a2fbb71d680f91fb02bf4a236b0c75faa2bb5525)) on May 23, 2023 |
| [Auto Rocket Launch](https://steamcommunity.com/sharedfiles/filedetails/?id=1651041757) | [GitHub](https://github.com/mshsheng/CSL-AutoRocketLaunch/tree/master/CSL-AutoRocketLaunch) | [MIT](https://github.com/mshsheng/CSL-AutoRocketLaunch/blob/master/LICENSE) | | [Release](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/releases/tag/06-September-2025) | [ab7f14b](https://github.com/mshsheng/CSL-AutoRocketLaunch/commit/ab7f14b4f3a46abd8ab1618ba7db6ce9685568f9) on  Apr 2, 2019 |

[^1]: You have to add references.
[^2]: You should delete PostBuildEvent (and sometimes PreBuildEvent) to build successfully. Or update it to match your environment, in that case theres no need for [^8][^9][^10].
[^3]: Do not copy files that overlap with "CitiesSkylines/Cities_Data/Managed" folder.
[^4]: You should not copy "CitiesHarmony.Harmony.dll" and "CitiesHarmony.Harmony.xml" but do copy "CitiesHarmony.API.dll". You also have to add CitiesHarmony mod if you haven't.
[^5]: This mod can be used with other mod named "[UnifiedUI (UUI)](https://steamcommunity.com/sharedfiles/filedetails/?id=2255219025)".
[^6]: This repo use OptionsFramework with Git submodule. If you download a zip file, you also have to download OptionsFramework and put it in the directory (in the way directory name matches).
[^7]: This repo use RedirectionFramework with Git submodule. If you download a zip file, you also have to download RedirectionFramework and put it in the directory.
[^8]: You have to copy "Locale" folder manually.
[^9]: You have to copy "Translations" folder manually.
[^10]: You have to copy "Resources" folder manually.
[^11]: PostBuildEvent is doing `pdb2mdb.exe` but you don't have to.
[^12]: Move all `*.crp` in sub directories to the mod directory (NetworkExtensions2). ``forfiles /P "bin/Release" /S /M *.CRP /C "cmd /c move @file \"bin/Release\""``
[^13]: Mod folder must be "NetworkExtensions2" and nothing else. Maybe it should be in `%LOCALAPPDATA%/Colossal Order/Cities_Skylines/Addons/Mods` not in `%programfiles%\Epic Games\CitiesSkylines\Files\Mods`. Read [this](https://steamcommunity.com/workshop/filedetails/discussion/812125426/3995220924714723313/).
[^14]: The size of the repository is big. Don't forget to delete the directory and zip files after the build if it matters.
[^20]: Name of the mod is "Extra Landscaping Tools" but project name is "NaturalResourcesBrush". Never mind.
[^21]: Name of the mod is "81 Tiles" but repo name is "cities-skylines-unlimiter-1", and "EightyOne.csproj". I will not repeat this further.
[^22]: Files in "CitiesSkylines/Cities_Data/Managed" folder like ICities.dll and ColossalManaged.dll are in the [repository](https://github.com/andreharv/NetworkExtensions/tree/master/References). No comment.
[^23]: The compiled binaries are in your mods folder under AppData/Local.
[^24]: Incompatible with v1.15.0-f7? See [Compatibility Issues of 1.15.0-f7](Compatibility-1.15.0-f7.md).
[^25]: Dlls are managed by Git LFS. You can't download as ZIP.
[^26]: ~Latest release was not yet in GitHub Release as of March 23, 2023. Download from the original repository if there's latest one.~ Now March 23, 2023 there's latest release.
[^27]: The link to GitHub is not in Steam page and the name of the author is different. I don't think they are same.
[^28]: 81 Tiles 2 is incompatible with this mod. ([source](https://github.com/algernon-A/EightyOne2/blob/5f00e199c16a21e6c6aaaced4cd98a864b23a6ee/Code/ConflictDetection.cs#L125))

### Mods with compiled binaries by someone else
Binaries compiled by someone other than the original developer like this here.
Currently there's nothing. I'll add link when it is mentioned in [Issues](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/issues) or [Pull Requests](https://github.com/kurema/CitiesSkylinesModsRepoForEpicUsers/pulls).

| Name | Original Repo | License | Compiled by | Link | Note |
| -- | -- | -- | -- | -- | -- |
| - | - | - | - | - |
