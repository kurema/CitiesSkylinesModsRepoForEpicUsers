# Basic build steps for Epic users.
See [here](https://community.simtropolis.com/forums/topic/73404-modding-tutorial-0-your-first-mod/).

0. If you don't have Visual Studio intalled, get and get it done from [here](https://visualstudio.microsoft.com/vs/community/).
1. Download!

![image](https://user-images.githubusercontent.com/10556974/173033113-6de95f36-ed05-4332-aceb-df3373569b8b.png)

2. Find `*.sln` and open with Visual Studio (just click).
3. Restore NuGet Packages

![image](https://user-images.githubusercontent.com/10556974/173042083-d635dc92-3f00-4941-9ebd-284f0fa696a2.png)

4. Add bunch of references.
  * Following files are in `%programfiles%\Epic Games\CitiesSkylines\Cities_Data\Managed`.
    * Assembly-CSharp.dll / ColossalManaged.dll / ICities.dll / UnityEngine.dll / UnityEngine.UI.dll etc.
  * `EManagersLib.API.dll` can be found in [here](https://github.com/Quistar-LAB/EManagersLib/releases/latest)

![image](https://user-images.githubusercontent.com/10556974/173042156-02ec699e-e591-42df-b233-89af4af8c61a.png)

5. Open `*.csproj` with text editor and search "&lt;PostBuildEvent&gt;", read and delete or modify.
6. Select "Release".

![image](https://user-images.githubusercontent.com/10556974/173045291-93eb6da5-9e7d-4d15-8489-562a63d02ee8.png)
  
If there's no "Release", use "Configuration Manager...".  
![image](https://user-images.githubusercontent.com/10556974/173042949-de5a3f0e-949c-46cc-8fd5-15bdeac39a2d.png)

7. Press F6.
  
![image](https://user-images.githubusercontent.com/10556974/173044235-a19cdcb3-81f6-4993-b469-9075a8aed107.png)

8. If it succeed the files are in "bin/" under the directory of *.csproj.
  
