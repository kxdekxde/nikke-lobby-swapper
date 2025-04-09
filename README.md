# NIKKE Lobby Wallpaper Swapper
A simple tool useful to mod [NIKKE](https://nikke-en.com/) bundles. Thanks to Bingle and Danieru for the help.


## Source code:

The .exe file is a SFX file created with WinRAR that contains all of the Python scripts and JSON files needed, it can be extracted with WinRAR/7Zip.


## Before to use this tool:

  - Download and install [.NET SDK 8](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-8.0.404-windows-x64-installer).
  - Download and install [Python](https://www.python.org/downloads/), along with all of the addons included (pip, etc).
  - Download and install [Microsoft C++ Build Tools](https://aka.ms/vs/17/release/vs_BuildTools.exe), and after that install the necessary libraries following [this video](https://files.catbox.moe/vqsuix.mp4).

  - Open a Windows PowerShell window as Admin, type:
    ```
    pip install UnityPy
    ```
    And hit enter to install UnityPy for Python.
  - On the same PowerShell window type:
    ```
    pip install requests
    ``` 
    Hit enter to install.



## Usage:

1. Double-click the exe file "DOROLobbySwapper.exe". If the tool asks you to Run as Admin you must to allow it.
2. You will see the message "=== Character that will be used for the lobby swap ===", write the character that will be used for the swap. For my example I write Cinderella. Hit Enter.
3. You will see another message "Write the lobby skin number for {character_name}:", if you want to swap a default lobby wallpaper you must to write 00, if it's a skin you must to write the corresponding number 01/02/03/04 etc. For my example I write 00 since it's Cinderella default lobby wallpaper. Hit Enter.
4. You will see another message "=== Character that will have their lobby swapped ===", write the other character name. For my example I write Maxwell since I'm swapping Cinderella default lobby over Maxwell default lobby. Hit Enter.
5. You will see the message "Write the lobby skin number for {character_name}:" again, write the corresponding skin number. For my example I write 00 again since I'm swapping Cinderella default lobby (00) over Maxwell default lobby (00). Hit Enter.
6. The tool will start to process the files and to make the swap automatically so just wait until the process finishes, the Terminal window will close automatically.
7. If everything worked you will see the changes when you launch your game and set your lobby wallpaper on your home screen.




Happy modding! ^‿^
