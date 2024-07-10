# TerrAltair
A virtual CPU made in [TerraTech](https://store.steampowered.com/app/285920/TerraTech)

##### Table of Contents:
- [Capabilities](#capabilities)
- [Snapshots](#snapshots)
- [Circuit](#circuit)
- [Documentation](#documentation)
- [Assembler](#assembler)
  - [How to run it](#how-to-run-it)
    - [Linux](#linux)
    - [Windows](#windows)
    - [MacOS](#macos)
- [Contact me](#contact-me)
## Capabilities
TODO
## Snapshots
I will distribute the snapshots using Steam Workshop for now:

* [TBA] The main CPU snapshot
- [TBA] My own CPU programs
- [TBA] My miscellaneous I/O modules
## Circuit
A circuit file for [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution) is available:
- [The cicruit](https://github.com/PinguThePenguin007/terraltair/blob/main/TerrAltair.circ)
## Documentation
The assembler documentation will be in GitHub wiki for now:
* [The GitHub wiki](https://github.com/PinguThePenguin007/terraltair/wiki)

* [The layout](https://github.com/PinguThePenguin007/terraltair/blob/main/TerrAltair%20instruction%20layout.txt)

## Assembler
[The script](https://github.com/PinguThePenguin007/terraltair/blob/main/terraltair_assembler.lua) can be found inside the repository alongside with example code snippets
### How to run it
#### Linux
Install Lua using your distribution's package manager:
##### Ubuntu/Debian
```
sudo apt install lua
```
##### Fedora
```
sudo dnf install lua
```
##### Arch (and its derivatives)
```
sudo pacman -S lua
```
---
Download [the script](https://github.com/PinguThePenguin007/terraltair/blob/main/terraltair_assembler.lua)

Or clone the whole repository (you'll need Git for this):
```
git clone https://github.com/PinguThePenguin007/terraltair.git
cd terraltair
```
You may need to give the script execution permissions, too:
```
chmod +111 terraltair_assembler.lua
```
Run the script:
```
./terraltair_assembler.lua --help
```

#### Windows
Exact instructions TODO

You can try downloading [the latest Lua binary](https://luabinaries.sourceforge.net/download.html) and running something like this:
```
Lua.exe terraltair_assembler.lua --help
```
#### MacOS
Dunno. Anyone up to be a tester for me? :P

## Contact me
Use Matrix or Discord to ask me any questions about the CPU:
- My matrix:  @pinguthecatgirl:catgirl.cloud
- My discord: TBA

For bugs, suggestions or other issues please use [GitHub Issues](https://github.com/PinguThePenguin007/terraltair/issues) :)
