# Daz To Unreal Bridge
This tool can be used to export Daz assets to the unreal engine.
Currently this tool can only be used on Windows. There are no plans to support other platforms.

## Install instructions for Windows
1) Make sure you have installed the unreal engine version you would like to use. (This is required for the setup)
   - You can download the latest version of unreal using the [hub](https://www.unrealengine.com/download).
   - Currently supported unreal engine versions are: [4.25, 4.26, 4.27, 5.+]
2) Download the [latest release](/releases/) of this plugin.
3) Unzip the downloaded release and open the folder of the unreal version you would like to use.

### Manually instal Unreal plugin
4) Copy the `DazToUnreal` folder. Now paste it at the desired install location.
   - a) You can install the plugin as an engine plugin, this makes it available to all unreal projects.
   - Paste it at: `%Program Files%\Epic Games\UE_[version]\Engine\Plugins\`

   - b) Install it only for one unreal project.
   - In this case, past it at `[Unreal Project Location]\[Project Name]\Plugins\`
   - If the folder does not exist, you need to create it. This should be at the root of the project, next to the .uproject file.

5) Open the unreal project.
6) Once opened, go to Edit->Plugins
7) Search for `DazToUnreal` and make sure the plugin is enabled. (You can find it in the Installed tab)
8) Restart unreal engine. The plugin should now be enabled.

### Manually instal Daz plugin
9) Copy `UE_[version]\DazToUnreal\Resources\dzunrealbridge.dll` to `C:\Daz 3D\Applications\64-bit\DAZ 3D\DAZStudio4 [Public Build]\plugins\`
10) Now you can export items from Daz to Unreal (File -> Send to...). Note: Both projects need to be open for this to work.
