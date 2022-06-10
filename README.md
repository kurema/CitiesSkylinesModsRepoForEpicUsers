# Cities:Skylines Mods for Epic users
Some mod developer publish GitHub Repo but don't have any Releases.
Now that [Steam Workshop Downloader](https://steamworkshopdownloader.io/) is dead, you have to build by yourself which is not very easy.

So this repo have some compiled results.
It's basically latest version as of 10 June 2022 and is not be updated since then. So it can too old for you.

## Mods
### Mods with compiled dll
| Name | Repo | Where | Note |
| -- | -- | -- | -- |
| Fine Road Anarchy | [GitHub](https://github.com/klyte45/CS-FineRoadAnarchy) | in [FineRoadAnarchy/_requiredDLLs](https://github.com/klyte45/CS-FineRoadAnarchy/tree/master/FineRoadAnarchy/_requiredDLLs) |

### Mods you have to build
I did so you don't have to. Only if the date is close.

| Name | Repo | License |  Build note | Binary | Binary version |
| -- | -- | -- | -- | -- | -- |
| [Improved Public Transport 2](https://steamcommunity.com/sharedfiles/filedetails/?id=928128676) | [GitHub](https://github.com/bloodypenguin/ImprovedPublicTransport) | Not specified | [^1][^2][^3][^4][^6][^7][^8] | | v6.0.0-preview5 ([d3476d0](https://github.com/bloodypenguin/ImprovedPublicTransport/commit/d3476d0614cc59099025b15087451440debce520)) on 17 Feb 2022 |
| [Zoning Adjuster](https://steamcommunity.com/sharedfiles/filedetails/?id=2389414419) | [GitHub](https://github.com/algernon-A/ZoningAdjuster) | [MIT](https://github.com/algernon-A/ZoningAdjuster/blob/master/LICENSE.txt) | [^1][^2][^3][^4][^5][^9][^10] | | v1.5.3 ([26bea3e](https://github.com/algernon-A/ZoningAdjuster/commit/26bea3eaec58c57ceeb53ed08fcdce607e266482)) on 2 Jun 2022 |
| [Extra Landscaping Tools](https://steamcommunity.com/sharedfiles/filedetails/?id=502750307) | [GitHub](https://github.com/bloodypenguin/Skylines-NaturalResourcesBrush) [^20] | [GPL-3.0](https://github.com/bloodypenguin/Skylines-NaturalResourcesBrush) | [^1][^2][^3][^6][^7][^8] | |  [91ad84a](https://github.com/bloodypenguin/Skylines-NaturalResourcesBrush/commit/91ad84aa78e7e41805094f5f8f7335247e89abee) on 25 Jan 2022 |
| [Daylight Classic](https://steamcommunity.com/workshop/filedetails/?id=530871278) | [GitHub](https://github.com/bloodypenguin/Skylines-DaylightClassic) | [GPL-3.0](https://github.com/bloodypenguin/Skylines-DaylightClassic/blob/master/LICENSE) | [^1][^2][^3][^6][^8] | | v1.12.2 ([775042d](https://github.com/bloodypenguin/Skylines-DaylightClassic/commit/775042d16e9f4ffbaba02ab9dca1be9f24f7101d)) on 8 May 2021 |
| [81 Tiles](https://steamcommunity.com/sharedfiles/filedetails/?id=576327847) | [GitHub](https://github.com/bloodypenguin/cities-skylines-unlimiter-1) [^21] | [GPL-3.0](https://github.com/bloodypenguin/cities-skylines-unlimiter-1/blob/master/LICENSE.md) | [^1][^2][^3][^4] | | [cbc08e8](https://github.com/bloodypenguin/cities-skylines-unlimiter-1/commit/cbc08e8f99838a2c54f59955fdb4bbdcc3c29249) on 26 Jan |
| [City Vitals Watch](https://steamcommunity.com/sharedfiles/filedetails/?id=410151616) [^22] | [GitHub](https://github.com/rob-williams/CityVitalsWatchMod/) | [BSD-3-Clause](https://github.com/rob-williams/CityVitalsWatchMod/blob/master/License.md) | [^1][^2][^3] | | [a059a13](https://github.com/rob-williams/CityVitalsWatchMod/commit/a059a132db2ee7aa8d4eb6c06838a4e3d6b2782b) on 1 Nov 2015 |



[^1]: You have to add references.
[^2]: You should delete PostBuildEvent to build successfully. Or update it to match your environment, in that case theres no need for [^8][^9][^10].
[^3]: Do not copy files that overlap with "CitiesSkylines/Cities_Data/Managed" folder.
[^4]: You should not copy "CitiesHarmony.Harmony.dll" and "CitiesHarmony.Harmony.xml" but do copy "CitiesHarmony.API.dll". You also have to add CitiesHarmony mod if you haven't.
[^5]: This mod can be used with other mod named "[UnifiedUI (UUI)](https://steamcommunity.com/sharedfiles/filedetails/?id=2255219025)".
[^6]: This repo use OptionsFramework with Git submodule. If you download a zip file, you also have to download OptionsFramework and put it in the directory (in the way directory name matches).
[^7]: This repo use RedirectionFramework with Git submodule. If you download a zip file, you also have to download RedirectionFramework and put it in the directory.
[^8]: You have to copy "Locale" folder manually.
[^9]: You have to copy "Translations" folder manually.
[^10]: You have to copy "Resources" folder manually.
[^20]: Name of the mod is "Extra Landscaping Tools" but project name is "NaturalResourcesBrush". Never mind.
[^21]: Name of the mod is "81 Tiles" but repo name is "cities-skylines-unlimiter-1", and "EightyOne.csproj". I will not repeat this further.
[^22]: You have to enabled this in the "CAMERA SCRIPT" section of the "CONTENT MANAGER", not "MODS".

## Build steps

