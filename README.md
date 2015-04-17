# morgenster-player
No-install single file streaming audio player for the Morgenster church

The Morgenster church streams their services through www.kerkdienstgemist.nl. Several members of the church had trouble accessing the streaming url due to browser issues. So a simple solution that was not dependent on the browser configuration of the user was needed.

Using VLC-lite and 7z self extracting archives the following solution was created:

The entire player is contained in a single executable self extracting archive (7z).
When the user double clicks the .exe file, VLC-lite is extracted from the archive into the system TEMP folder, from where it is automatically launched with the correct streaming URL.

When the user exits the player, the extracted files are removed from the TEMP directory again.

By using this solution the user does not have to go through the process of installing an application and configuring the settings. They just need to download an .exe file and execute it.
