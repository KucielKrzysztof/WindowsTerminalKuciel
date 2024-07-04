# Windows Terminal

### Starship config directory:
C:\Users\XYZ\.config\starship.toml

### Starship install:

winget install --id Starship.Starship

clink:
https://github.com/chrisant996/clink/releases

Config clink:
1. Open cmd.
2. Create a new configuration file 'starship.lua' in the directory '%LocalAppData%\clink\':
```cmd
notepad %LocalAppData%\clink\starship.lua
```
3. Copy and paste this code into 'starship.lua':
```lua
load(io.popen('starship init cmd'):read("*a"))()
```
4. Save and quit 'starship.lua'.

### docs:
https://starship.rs/installing/

### how it looks:
![screen1](screen.png)
