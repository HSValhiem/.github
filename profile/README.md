# Valheim Modding Information and Links

### Game Info
- Valheim Latest Version: 0.216.9
- Valheim Latest Test Version: ---
- Valheim Current Unity Engine: 2020.3.45
- Valheim Modpack Version: 0.215.2

### Latest Valheim Version Changes
- [0.216.9 WinMerge Change Report](https://hsvalhiem.github.io/Valheim-Sourcecode-Changes/)

### In House Custom Tools
- [Mod Source Checker](https://github.com/HSValhiem/HST_ModSourceChecker) Detects Changed Source code in Mods from Latest update
- [Mod Checker](https://github.com/HSValhiem/HST_ModChecker) Detects if a Mod uses Network Resources to Determing if its Server side or Client Side
- [Fancier Log](https://github.com/HSValhiem/HST_FancierLog) | [Fancier Log (PowerShell Script)](https://github.com/HSValhiem/HS_fancier_log_file) Displays the BepInEx Console Log in a Pretty Way

### Modding Info
- [Unity Scripting Reference](https://docs.unity3d.com/2020.3/Documentation/ScriptReference/index.html)
- [Valheim Prefab List](https://valheim-modding.github.io/Jotunn/data/prefabs/prefab-list.html)
- [Link to Check Latest Game Version](https://store.steampowered.com/news/app/892970)
- [Basic Plugin for Bepinex Guide(No Jotuun)](https://docs.bepinex.dev/articles/dev_guide/plugin_tutorial/1_setup.html)
- [Your First Mod with BepInEx](https://mroshaw.github.io/Subnautica/yourfirstmod_sn/codingthemod_bepinex.html)
- [Structuring your Thunderstore Package](https://github.com/ebkr/r2modmanPlus/wiki/Structuring-your-Thunderstore-package)
- [Manifest V1 (Thunderstore) + author field](https://github.com/ebkr/r2modmanPlus/wiki/Installing-mods-locally#manifest-v1-thunderstore--author-field)
- [Plugin Tutorial - Getting Started](https://docs.bepinex.dev/articles/dev_guide/plugin_tutorial/2_plugin_start.html)
- [How to Use Bepinex templates in VS2022](https://github.com/BepInEx/BepInEx.Templates)
- [Adding Content with Jotuun](https://valheim-modding.github.io/Jotunn/tutorials/pieces.html)
- [Valheim-Server-RPC-Guide](https://github.com/M4cs/Valheim-Server-RPC-Guide)
- [Nice Mod for RPC Examples](https://github.com/Mydayyy/Valheim-ServerSideMap)
- [BepInEx Patcher Example](https://github.com/blaxxun-boop/ConfigWatcher/blob/master/ConfigWatcher/ConfigWatcher.cs#LL9C1-L12C48)
- [Raft Mod Example](https://www.raftmodding.com/mods/aquariums)
- [BepInEx Utility Functions](https://github.com/BepInEx/BepInEx.Utility)
- [BepInEx Patcher Tutorial](https://docs.bepinex.dev/articles/dev_guide/preloader_patchers.html)
- [HOOKGEN Tutorial](https://github.com/MonoMod/MonoMod/blob/master/README-RuntimeDetour.md#using-hookgen)
= [Expand World Documentation](https://github.com/JereKuusela/valheim-expand_world)
- [Vanilla Prefabs List](https://valheim-modding.github.io/Jotunn/data/prefabs/overview.html)


### BepInEx Harmony Guides
- [Harmony Basics](https://api.raftmodding.com/modding-tutorials/harmony-basics)
- [Harmony Wiki](https://harmony.pardeike.net/articles/intro.html)
- [Harmony Patch Priorities](https://harmony.pardeike.net/articles/priorities.html)
- [Patcher Flow](https://outward.fandom.com/wiki/Mod_development_guide/Harmony)
- [HarmonyX Patch Paramaters](https://github.com/BepInEx/HarmonyX/wiki/Patch-parameters)
- [HarmonyX Prefix changes](https://github.com/BepInEx/HarmonyX/wiki/Prefix-changes)
- [HarmonyX Changes](https://github.com/BepInEx/HarmonyX/wiki/Difference-between-Harmony-and-HarmonyX)
- [HarmonyX Valid Patch Targets](https://github.com/BepInEx/HarmonyX/wiki/Valid-patch-targets)
- [HarmonyX Patching](https://github.com/BepInEx/HarmonyX/wiki/Patching-with-Harmony)


### Valid Default Methods
    void Start() is called is the GameObject is enabled
    void Awake() is called prior to Start()
    void Update() is called every frame, can be skipped for several frames to keep FPS up
    void FixedUpdate() is called every frame, will not be skipped
    void LateUpdate() is called after all other Update-methods
    void OnEnable()/OnDiable() is called when the GameObject is enabled/disabled
    void OnDestroy() is called when the GameObject is destroyed (via GameObject.Destroy)
    void OnGUI() is called when drawing and allows the script to use the GUI-API (described later on)
    
### .net Loader
- [DoorStop (The Loader for BepInEx)](https://github.com/NeighTools/UnityDoorstop)

### ModPack Related
- [Valheim Plus Replacments List](https://github.com/AzumattDev/Valheim-Plus-Replacements)

### Modding Tool BepInEx Plugins
- [BepInEx Developer Plugins](https://docs.bepinex.dev/articles/dev_guide/dev_tools.html)
- [Valheim Tooler](https://github.com/Astropilot/ValheimTooler)
- [Valheim Profiler](https://valheim.thunderstore.io/package/Azumatt/PerformanceTracker/)
- [Digitalroot.Valheim.PluginInfo](https://github.com/Digitalroot-Valheim/Digitalroot.Valheim.PluginInfo)
- [Digitalroot.CustomMonoBehaviours](https://github.com/Digitalroot-Valheim/Digitalroot.CustomMonoBehaviours)
- [RuntimeUnityEditor](https://github.com/ManlyMarco/RuntimeUnityEditor#readme)


### Usefull Modding Libraries
- [AzuMatt PieceManager](https://github.com/AzumattDev/PieceManager)
- [AzuMatt MountManager](https://github.com/AzumattDev/MountManager)
- [AzuMatt StatusEffectManager](https://github.com/AzumattDev/StatusEffectManager)
- [BepInEx ConfigurationManager](https://github.com/BepInEx/BepInEx.ConfigurationManager)
- [Blaxxun ServerSync](https://github.com/blaxxun-boop/ServerSync)
- [Blaxxun SkillManager](https://github.com/blaxxun-boop/SkillManager)
- [Blaxxun LocationManager](https://github.com/blaxxun-boop/LocationManager)
- [Blaxxun ItemManager](https://github.com/blaxxun-boop/LocationManager)
- [Blaxxun LocalizationManager](https://github.com/blaxxun-boop/LocationManager)
- [Blaxxun ItemDataManager](https://github.com/blaxxun-boop/LocationManager)
- [Blaxxun CreatureManager](https://github.com/blaxxun-boop/LocationManager)
- [Blaxxun PieceManager](https://github.com/blaxxun-boop/LocationManager)
- [Digital Root Modding Framework](https://github.com/Digitalroot-Valheim/DMF)
- [Github Release Version Checker Lib](https://github.com/Digitalroot-Valheim/VersionCheck)
- [RapidGUI Unity GUI Extensions](https://github.com/fuqunaga/RapidGUI)

### Obfuscating Code
- [XenocodeRCE-dnSpyDetector](https://github.com/XenocodeRCE/dnSpyDetector)
- [okieeee-dnSpyDetector](https://github.com/okieeee/dnSpyDetector)
- [CabboShiba/AntiDNSpyDetector](https://github.com/CabboShiba/AntiDNSpyDetector)
- [TheHellTower-MagicRenamer](https://github.com/TheHellTower/MagicRenamer)

### Docker/Server Hosting
- [Docker Container Hosted by Digital Ocean(free 120 Days)](https://github.com/azizn03/valheim_server_digitalocean)

### Unity Games with Active Modding Communities
- Cities: Skylines
- Kerbal Space Program
- RimWorld
- Besiege
- Factorio
- Minecraft
- Garry's Mod
- Subnautica
- The Forest
- Raft

### Tools
- [Unity Hub](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe)
- [Asset Ripper for Ripping Base Game Assets](https://github.com/AssetRipper/AssetRipper)
- [ValheimExportHelper Plugin for Asset Ripper](https://github.com/heinermann/ValheimExportHelper)
- [DNSpy](https://github.com/dnSpyEx/dnSpy)
- [DNSpy Plugin to help Reverse Obfuscated Code](https://github.com/holly-hacker/dnSpy.Extension.HoLLy)
- [Resharper for Visual Studio](https://www.jetbrains.com/resharper/download/#section=web-installer)
- [NG Missing Script Tool](https://assetstore.unity.com/packages/tools/utilities/ng-missing-script-recovery-102272#reviews)
- [Deobfuscation Tools](https://github.com/NotPrab/.NET-Deobfuscator)
- [Thunderstore Mod Uploader](https://github.com/Digitalroot-Valheim/Digitalroot.ModUploader)
- [Main World Map Image](https://preview.redd.it/5uljbr2k8ev71.jpg?width=3728&format=pjpg&auto=webp&v=enabled&s=176b911c42475d4b190f79305a7ead415bedb48d)

### Notable Valhiem Githubs
- [Blaxxon-boop(AKA Smoothbrain](https://github.com/blaxxun-boop)
- [Azumatt](https://github.com/AzumattDev)

### Online Tools
- [Normal Map Creator](https://cpetry.github.io/NormalMap-Online)
- [Stable Diff - AI Image Generation](https://stablediffusionweb.com/#demo)
- [craiyon - AI Image Generation](https://www.craiyon.com)
- [dream - AI Image Generation](https://dream.ai/create)
- [C# Code Example Lookup](https://csharp.hotexamples.com/)
- [Online C# Code Execution](https://dotnetfiddle.net/)
- [.net Code Lookup Tool](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.propertyinfo.setvalue?view=netframework-4.6.2)
- [Valheim Server Database](https://valheimservers.net)
- [Online YML Viewer](https://jsonformatter.org/yaml-viewer)

### Unity Tutorials
- [Valheim Unity Asset Creation](https://valheim-modding.github.io/Jotunn/tutorials/asset-creation.html)
- [Valheim-Unity-Project-Guide](https://github.com/Valheim-Modding/Wiki/wiki/Valheim-Unity-Project-Guide)
- [Mod Creation and Mod Stub for use with Jotunn Modding Framework](https://valheim-modding.github.io/Jotunn/guides/overview.html)
- [Creating Valheim Unity Project](https://github.com/Valheim-Modding/Wiki/wiki/Valheim-Unity-Project-Guide)
- [Creating a Patched Mono for DNspy Debugging](https://github.com/Neoshrimp/dnSpy-Unity-mono-unity2021.xx)
- [JotunnModStub](https://github.com/Valheim-Modding/JotunnModStub)

### C++ Resources
- [VCPKG Package Installer](https://vcpkg.io/en/getting-started.html)
- [Zip Library](https://github.com/sthagen/kuba---zip)
- [RapidYML](https://github.com/biojppm/rapidyaml#quick-start)
- [Parse YML in c++](https://stackoverflow.com/questions/365155/parse-yaml-files-in-c)
