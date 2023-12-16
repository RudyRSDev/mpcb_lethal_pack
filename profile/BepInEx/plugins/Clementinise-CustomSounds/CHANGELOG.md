-   **2.1.2**

    -   Enhanced unique key generation logic for sounds to resolve issues with duplicate sound handling (Now, the key includes both the sound name and percentage to ensure uniqueness)
    -   Refined sound name parsing in C# to handle cases without percentages
    -   Debugged and fixed the ListAllSounds method to ensure consistent listing of sounds on subsequent calls, addressing an issue where the list of sounds was not displaying correctly
    -   Corrected instantiation of TerminalNode objects in Unity, now using `ScriptableObject.CreateInstance<T>()` to avoid errors related to ScriptableObject instantiation
    -   Various small fixes and changes

-   **2.1.1**

    -   Forgot to update the LCSoundTools dependency

-   **2.1.0**

    -   Added a new config setting to address issues with joining servers: "EnableNetworking" (Whether or not to use the networking built into this plugin. If set to true everyone in the lobby needs CustomSounds to join and also "EnableNetworking" set to true.)
    -   Added aliases for the `CUSTOMSOUNDS` command and its sub-commands
    -   The bundle asset is now embedded in the DLL
    -   CustomSounds now supports random sounds via the latest update of LCSoundTools (For example, with 2 files named `JackOLanternHit-25.wav` and `JackOLanternHit-75.wav`, there will be 2 possible sounds for one AudioClip with respectively 25% and 75% chances of playing)
    -   You can now also give names to audio clips to better describe what sound they are replacing (For example, `JackOLanternHit-Funny-Laugh.wav` will display as "JackOLanternHit [Funny Laugh]" in the terminal)
    -   Various small fixes and changes

-   **2.0.0**

    -   Added new terminal commands: "customsounds sync", "customsounds unsync" and "customsounds force-unsync"
    -   EXPERIMENTAL: As the host, you can now sync your custom sounds with all clients in the lobby via the terminal (requires CustomSounds to be installed on their end)

-   **1.2.4**

    -   Fixed an issue occurring on the first start while using a mod manager, there's now no need to restart/reload when installing a sound pack for the first time

-   **1.2.3**

    -   Minor edits to mod page

-   **1.2.2**

    -   Minor edits to mod page

-   **1.2.1**

    -   Modified how the script manages Sound Packs to improve fluidity when using a mod manager

-   **1.2.0**

    -   Added new terminal commands: "customsounds list" and "customsounds help"
    -   Sound Packs can now be created by adding custom sounds to named subfolders within the "CustomSounds" directory
    -   "CustomSounds" folder will be automatically created if it does not exist
    -   `[Chainloader] HideManagerGameObject` in BepInEx.cfg will automatically be set to "true" if it is still on defaut "false"

-   **1.1.1**

    -   Fixed some paths and updated the dependencies of LCSoundTool from version 1.2.0 to 1.2.2 to resolve additional issues with mod managers

-   **1.1.0**

	-   Added new terminal commands: "customsounds reload" and "customsounds revert"
	-   Fix path errors when installing with a mod manager

-   **1.0.0**

    -   Mod release