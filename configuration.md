
# Configuration

## eqclient.ini

Located in the root everquest folder, `eqclient.ini` holds global settings for all accounts. Annotations in the following code block are for settings that can't be changed in-game.

``` ini
[Defaults]
EnableSystemCommand=0  # (1)
UseWASDDefault=1
GraphicsMemoryModeSwitch=1
APVOptimizations=TRUE
DisableWestBugFix=0
Sound=1
ClientCore0=-1  # (2)
ClientCore1=13  # (3)
TextureQuality=1
VertexShaders=TRUE
14PixelShaders=TRUE
20PixelShaders=TRUE
MultiPassLighting=FALSE
PostEffects=FALSE
UseLitBatches=TRUE
ItemPlacementShowOverlay=TRUE
ChatFontSize=3
ShowNamesLevel=4
MousePointerSpeedMod=0
ShowSpellEffects=1
MixAhead=8
TrackPlayers=1
TrackSortType=NORMAL
TrackFilterType=0
Sound44k=0
StickFigures=0  # (4)
HidePlayers=0
HidePets=0
HideMercs=0
AllLuclinPcModelsOff=0
UseLuclinHumanMale=1
UseLuclinHumanFemale=1
UseLuclinBarbarianMale=1
UseLuclinBarbarianFemale=1
UseLuclinEruditeMale=1
UseLuclinEruditeFemale=1
UseLuclinWoodElfMale=1
UseLuclinWoodElfFemale=1
UseLuclinHighElfMale=1
UseLuclinHighElfFemale=1
UseLuclinDarkElfMale=1
UseLuclinDarkElfFemale=1
UseLuclinHalfElfMale=1
UseLuclinHalfElfFemale=1
UseLuclinDwarfMale=1
UseLuclinDwarfFemale=1
UseLuclinTrollMale=1
UseLuclinTrollFemale=1
UseLuclinOgreMale=1
UseLuclinOgreFemale=1
UseLuclinHalflingMale=1
UseLuclinHalflingFemale=1
UseLuclinGnomeMale=1
UseLuclinGnomeFemale=1
UseLuclinIksarMale=1
UseLuclinIksarFemale=1
UseLuclinVahShirMale=1
UseLuclinVahShirFemale=1
UISkin=Default  # (5)
UseNewUIEngine=1  # (6)
DefaultChannel=8
LastCharSel=Characterx
ShowCreationHelp=0
Music=10
SoundVolume=10
SpellParticleOpacity=1.000000
EnvironmentParticleOpacity=1.000000
ActorParticleOpacity=1.000000
NoNameApprove=1
WindowedModeXOffset=-8
WindowedModeYOffset=-8
AllowResize=1
Maximized=1
RestoredXOffset=0
RestoredYOffset=0
RestoredWidth=1920
RestoredHeight=1080
AlwaysOnTop=0
[Options]
ClickThroughMask=0
Camera1-Distance=30.000000
Camera1-DirHeading=192.000000
Camera1-Heading=0.000000
Camera1-Pitch=0.000000
Camera1-Height=5.000000
Camera1-Zoom=90.000000
Camera1-Change=1
Camera2-Distance=82.000000
Camera2-DirHeading=277.000000
Camera2-Heading=0.000000
Camera2-Pitch=0.000000
Camera2-Height=18.000000
Camera2-Zoom=90.000000
Camera2-Change=1
MaxFPS=150
MaxBGFPS=30
NameFlashSpeed=5
Realism=1
ClipPlane=15
LODBias=10
XMouseSensitivity=4
YMouseSensitivity=4
[TextColors]
User_1_Red=255
User_1_Green=255
User_1_Blue=255
User_2_Red=255  # (7)
[VideoMode]
Width=1920
Height=1080
FullscreenRefreshRate=0
FullscreenBitsPerPixel=32
WindowedWidth=1920
WindowedHeight=1017
[BristlebaneWasHere]
IHateFun=0  # (8)
[News]
LastRead=00000000
Automatic=0
```

1.  Allows use of the `/system` command. Off by default for security.  
2.  Processor core available to a specified client. -1 (default) gives access to all cores. The # after ClientCore is for the instance of the game.
3.  Example: set the second client to only use core 13
4.  Replace character models with stick figures. Off by default.
5.  Set your characters to all utilize a specific UI. Default will use separate UI skins for each character.
6.  Set to 0 to use the old User Interface Engine
7.  Text color settings continue for User_2 through User_130+ (truncated for brevity)
8.  Turns off "April fools" event font

## Other config files

**`<character>_<server>.ini`**
::    This file stores character-specific settings, such as 'Actions' window settings, abilities, blocked buffs, blocked pet buffs, disciplines, hotbar settings, socials, and saved spell sets. It is located in the root EverQuest folder: **`C:\EverQuest\<character>_<server>.ini`**, where `<character>` represents the character name, and `<server>` represents the [server short name](general/server-short-names.md).

**`UI_<character>_<server>.ini`**
::    This file stores character-specific User Interface (UI) settings, such as window locations, window fade delay settings, chat channel autojoin settings (including channel names and applicable passwords), etc. It is located in the root EverQuest folder: **`C:\EverQuest\UI_<character>_<server>.ini`**, where `<character>` represents the character name, and `<server>` represents the [server short name](general/server-short-names.md).

**`AT_default_<character>_<server>.ini`**
::    This file is used to store character specific in-game audio triggers. When using the in-game Audio Triggers, any custom .wav files should be saved in the **`C:\EverQuest\AudioTriggers\shared`** folder. The file is found in the EverQuest\userdata folder: **`C:\EverQuest\userdata\AT_default_<character>_<server>.ini`**, where `<character>` is the character name and `<server>` is the [server short name](general/server-short-names.md).
