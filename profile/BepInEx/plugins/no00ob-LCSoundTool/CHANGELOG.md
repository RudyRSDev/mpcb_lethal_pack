-   **1.3.2**

    -   Small bug fixes.
    -	Made networking optional. It was never meant to be forced on. It can now be toggled from the config file.

-   **1.3.1**

    -   Changed the random clip seperator from "_" to "-".


-   **1.3.0**

    -   Internal restructure of multiple parts of the mod. Shouldn't change previous behaviour.
    -	Added support for random replacement clips. One vanilla sound can now have new multiple random clips with set chances that play randomly when the vanilla sound would.
    -	Fixed multiple small bugs. AudioSources with playOnAwake set to true should now play more than once when the scene is not reloaded between playback.
    -	Experimental networking for Unity AudioClips. Send AudioClips over the network to all connected players, also optionally sync all of the networked clips of the host to all clients.
    -	Minor tweaks for game v45

-   **1.2.2**

    -   Added support for mod managers. This changes the folder structure and loading of custom sounds a bit and all mods will need to be updated to work with mod managers. Old mods will continue to work with the newest release when manually installed. Mods only need to update to support mod managers, otherwise no sounds will load when using a mod manager.

-   **1.2.1**

    -   Minor edits to mod page.

-   **1.2.0**

    -   Added ability to load sound files from plugins folder, more in depth logging option and support for most AudioSources with playOnAwake flag set to true.

-   **1.1.1**

    -   Minor edits to mod page.

-   **1.1.0**

    -   Added a way to replace any in game audio clip by a custom one. Mod released on thunderstore.

-   **1.0.0**

    -   Mod released on github.
