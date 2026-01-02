![htfmffmf](https://github.com/user-attachments/assets/6b58fee8-1d93-4eab-8ae5-a8bf93f86edd)


# Overview

***This is a collection of my custom themed fastfetch configs, feel free to use.***


## Table of Contents

1. [Preview](#preview)
2. [Installation](#installation)


## Preview
**Termux**

<img width="500" height="500" alt="Screenshot_20251210-215858_Termux (1)" src="https://github.com/user-attachments/assets/198ff0b7-4a20-44f7-9d49-db9394a80710" />



## Installation

**Install fastfetch, if not already:**

Debian
```ba
sudo apt install fastfetch -y
```

Arch
```ba
sudo pacman -Sy fastfetch -y
```

Termux
```ba
pkg install fastfetch -y
```

<br><br>

**Generating a config file**
```ba
fastfetch --gen-config
```


**Backing up old fastfetch config:**
```ba
cd ~/.config/fastfetch/
cp config.jsonc config.jsonc.bk
```


**Clone the repo:**
```ba
git clone https://github.com/kraken-503/fastfetch-configs.git
cd fastfetch-configs/
cp -r * ~/.config/fastfetch/
```

<p align="center">
  <em>Made with ❤️ by kraken-503</em>
</p>
