# Chemp-Physics-MelonLoader-Mod-Template
A visual studio MelonLoader mod template for the VR game "Chemp Physics".

# How do I use it?
## Getting started
Download + extract the 'ChempModTemp.rar' file and navigate to:

`ChempModTemp\Chemp Physics Mod Template\Chemp Physics Mod Template.sln`

Open the `Chemp Physics Mod Template.sln` file.

Visual Studio will open, and it will automatically bring you to the `ChempMod.cs` file. This is where you will code your mod.
## Creating your code for the mod
You will require C# knowledge (more/less depending on how complicated your mod is)
The template references the game's `Assembly-CSharp.dll` file (last updated 8/8/25) meaning you can use namespaces from the actual game itself.
Once you finish coding and want to test, move onto the next step.
## Building your mod
To build your mod, navigate to the "Build" tab at the top of VS.
Then, click "Build Solution".
This will build your mod to a MelonLoader compatible DLL file.
Only use the generated mod DLL. You will not need any others.
Once built, it will either tell you it failed to build and details, or it will succeed and tell you to file location.
Navigate there, and there you will find your DLL file.
## Installing your mod
After patching Chemp Physics (tutorial at https://discord.gg/nYK5nS8C2y), you have to plug your headset into your PC.
Ensure developer mode is on via your Meta Horizon app on your mobile phone, then click the file folder in sidequest.
Navigate to `sdcard/MelonLoader/com.XORWIREGames.ChempPhysics/Mods`.
Place your generated .dll file into that folder.
## And you're done!
Happy modding!
