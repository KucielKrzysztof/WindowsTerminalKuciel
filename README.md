# Windows Terminal Starship configuration
## Windows
### 1. Starship config path:
```cmd
C:\Users\<User_Name>\.config\starship.toml
```

### 2. Starship install:
```cmd
winget install --id Starship.Starship
```

### 3. Download and install clink:
https://github.com/chrisant996/clink/releases

### 4. Config clink:
4.1 Open cmd.

4.2 Create a new configuration file 'starship.lua' in the directory '%LocalAppData%\clink\':
```cmd
notepad %LocalAppData%\clink\starship.lua
```
4.3 Copy and paste this code into 'starship.lua':
```lua
load(io.popen('starship init cmd'):read("*a"))()
```
4.4 Save and quit 'starship.lua'.

### 5. docs:
https://starship.rs/installing/

### 6. how it looks:
![screen1](screen.png)

## Linux
# to do LINUX VERSION (i mean it's done but need to guide it for future self to restore quick)
