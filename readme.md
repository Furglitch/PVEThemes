Original idea and SASS files from https://github.com/Weilbyte/PVEDiscordDark

# Supported Proxmox Versions
- 7.4
- 8.0

## UI Tweaks
there is a few additional tweaks that can be enabled using the script. These are:
- Hide the "no valid subscription" warning
- Add update buttons to the theme selector panel itself
- Add a progress bar to show how much ram ZFS Cache is using

## Installation
Run the following commands in your PVE instance:
```bash
git clone https://github.com/Happyrobot33/PVEThemes
cd PVEThemes
chmod +x install.sh
./install.sh
```

Or this one-liner:
```bash
git clone https://github.com/Happyrobot33/PVEThemes && cd PVEThemes && chmod +x install.sh && ./install.sh
```

if you have ran the install.sh script before, you can instead just run the run.sh script
```bash
chmod +x run.sh
./run.sh
```

if you are running into issues updating the script, run the following commands:
```bash
git pull
chmod +x install.sh
./install.sh
```
This should hopefully fix any issues.

![avali](./themes/previews/theme-avali.png)
![discord dark](./themes/previews/theme-discord-dark.png)
![discord light](./themes/previews/theme-discord-light.png)
![nordigr](./themes/previews/theme-nordigr.png)
![catppuccin latte](./themes/previews/theme-catppuccin-latte.png)
![catppuccin frappe](./themes/previews/theme-catppuccin-frappe.png)
![catppuccin macchiato](./themes/previews/theme-catppuccin-macchiato.png)
![catppuccin mocha](./themes/previews/theme-catppuccin-mocha.png)