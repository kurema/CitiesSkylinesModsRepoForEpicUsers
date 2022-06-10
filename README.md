# Cities:Skylines Mods for Epic users
Some mod developer publish GitHub Repo but don't have any Releases.
Now that [Steam Workshop Downloader](https://steamworkshopdownloader.io/) is dead, you have to build by yourself which is not very easy.

So this repo have some compiled results.
It's basically latest version as of 10 June 2022 and is not be updated since then. So it can too old for you.

## Mods
### Mods with compiled dll
| Name | Repo | License | Description | Note |
| -- | -- | -- | -- | -- |

### Mods you have to build
I did so you don't have to. Only if the date is close.

| Name | Repo | License | Link to binary |  Build note | Compiled version |
| -- | -- | -- | -- | -- | -- |
| [Improved Public Transport 2](https://steamcommunity.com/sharedfiles/filedetails/?id=928128676) | [GitHub](https://github.com/bloodypenguin/ImprovedPublicTransport) | Not specified | | [^1][^2][^3][^4][^5][^6][^8] | d3476d0 on 17 Feb 2022 |

[^1]: You have to add references.
[^2]: You should delete PostBuildEvent to build successfully.
[^3]: Do not copy files that overlap with "CitiesSkylines/Cities_Data/Managed" folder.
[^4]: You should delete "CitiesHarmony.Harmony.dll" and "CitiesHarmony.Harmony.xml" but keep "CitiesHarmony.API.dll".
[^5]: This repo use OptionsFramework with Git submodule. If you download a zip file, you also have to download OptionsFramework and put it in the directory.
[^6]: This repo use RedirectionFramework with Git submodule. If you download a zip file, you also have to download RedirectionFramework and put it in the directory.
[^8]: You have to copy "Locale" folder manually.

## Build steps

