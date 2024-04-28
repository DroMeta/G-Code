# GitHub desktop. 

This script is meant for personal use but anyone is more then welcome to use it as you wish. The said script will download and install the most recent GitHub desktop version for your Linux OS. It is able to install, update and uninstall GitHub desktop. By default, the script will automatically check if an update is available.
The script works with deb and rpm packages, so it will fall back to the available AppImage If your system does not use deb or rpm.

## Execute
Executable bash scripts below. it will download then install GitHub Desktop
| Tool | Command                                                                                                                        |
|:-----|:-------------------------------------------------------------------------------------------------------------------------------|
| curl | `bash -c "$(curl -fsSL https://raw.githubusercontent.com/DroMeta/GHub-Code/main/installGitHubDesktop.sh)" `       |
| wget | `bash -c "$(wget -O- https://raw.githubusercontent.com/DroMeta/GHub-Code/main/installGitHubDesktop.sh)"`          |

### Manual execution
It is always a good idea to inspect the script you are getting off the webnets. 
Please go ahead and inspect the scripts first or we can execute the script manually with the methods below now.
```bash
# --------------------
# curl method
curl -fsSL https://raw.githubusercontent.com/DroMeta/GHub-Code/main/installGitHubDesktop.sh -o installGitHubDesktop.sh
# wget method
wget https://raw.githubusercontent.com/DroMeta/GHub-Code/main/installGitHubDesktop.sh
# --------------------
bash ./installGitHubDesktop.sh
```

## Optional flags
| Flag                      | Description                                 |
|:--------------------------|:--------------------------------------------|
| -m (install \| uninstall) | Install or uninstall GitHub desktop.        |
| -v                        | Enable verbose mode.                        |

Tested the script on:
- Ubuntu 22.04.2 LTS, Mint 21.1
- Fedora 37 Workstation

The project came to life as a result of [berkorbay](https://gist.github.com/berkorbay)'s presumably discontinued gist page, which can be viewed [here](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1).

Please feel free to contribute.
