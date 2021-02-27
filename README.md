# Peirdjescraft

PeirdjesCraft is a minecraft modpack that runs on 1.12.2 that I made to play with my friends. It contains lots of technical, magical and building mods for a full list open the folder **Mods** in the repo.

## Installation

Download the modpack from [Technicpack](https://www.technicpack.net/modpack/peirdjescraft.1775737) to start the modpack or install the Technic Launcher and search for **PeirdjesCraft**



## Server Creation


1. Download forge 1.12.2 from [Forge](https://files.minecraftforge.net/) to the folder where you want to create your modpack. 
2. Download minecraft server 1.12.2 from [MCVersions](https://mcversions.net/download/1.12.2) and place it in the same folder
3. Download the modpack from [Technicpack](https://www.technicpack.net/modpack/peirdjescraft.1775737)
4. Copy the folders **Mods** and **Config** into the folder
5. Create a file named run.bat and place the following code in it, where you replace the 6144M with the amount of MB of ram you want the server to use and replace forge-1.12.2.jar to whatever filename your forge file has.
```bash
java -Xmx6144M -Xms6144M -jar forge-1.12.2.jar -o true nogui
```
6. Run the **run.bat** file once
7. Open the newly created file named 'eula' and change False to True to agree with the eula
8. Run the **run.bat** file again and wait until it is fully loaded you will see a CMD screen with information.
9. Stop the server by typing **Stop** in the server window and wait until it closes
10. Edit the values in **server.properties** to match your IP, Port number and further settings 
11. Run server again and **Enjoy!**

## License
[MIT](https://choosealicense.com/licenses/mit/)
