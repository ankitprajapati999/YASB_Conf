# ⚡ YASB Configuration by Lightning Ankit

This repository contains my **custom configuration setup for YASB (Yet Another Status Bar)** — a modern, minimal, and super clean status bar for Windows.  
You can use this config to instantly get the same layout, modules, and styling I use.

---

## 🧠 What’s YASB?

**YASB (Yet Another Status Bar)** is a lightweight and customizable status bar for Windows.  
It’s like a taskbar replacement that shows widgets, weather, battery, time, and more — all styled and modular.

You can get it directly from **Chocolatey** or **Winget**
---

## ⚙️ How to Set Up My Configuration

Follow these simple steps to get this setup working on your system 👇

### 1️⃣ Install YASB
If you don’t already have YASB installed, run this in PowerShell (as Administrator):

```
# Make a config folder first by executing 
mkdir .config

# Chocolatey : 

choco install yasb
^-This installs the latest version of YASB on your system with chocolatey.

    --- OR ---

# Winget :

winget install --id AmN.yasb 
^-This installs the latest version of YASB on your system with chocolatey.

```

### 2️⃣ Clone This Repo
Clone my configuration folder to your local machine:

```

git clone https://github.com/ankitprajapati999/YASB_Conf.git

# Then go inside the folder:
cd yasb

```

### 3️⃣ Locate the YASB Config Folder
After installing YASB from chocolatey or winget, it creates a configuration folder at:

C:\Users\<YourUserName>\.config\yasb
That’s the folder where YASB reads its setup.

### 4️⃣ Replace the Config Folder

Replace the files in your local YASB config folder with the ones from this repo:
Backup your existing yasb folder if you already have one.


Copy all files from this repo's yasb folder into:

C:\Users\<YourUserName>\.config\yasb

open the config.yaml file and find wheather widget in the api section place your weather api  // Get free wheather api from "https://www.weatherapi.com/"
Restart YASB (or log out and back in).

### 5️⃣ Done 🎉
You should now see my custom YASB layout running on your system.
Tweak it, remix it, or flex it your own way.

### 📦 Folder Structure
```
─ YASBconf
  ├── config.yaml
  ├── style.css
─ README.md       # This documentation
```

### 🧩 Notes
Don’t redistribute the YASB .exe — it’s owned by the original developer.

You can install it using Chocolatey or from the official repo.

You’re free to modify my configs as you like — just credit if you publish your version publicly.

## 👨‍💻 Author
Lightning Ankit (a.k.a. Light)
Python Developer

### 🫶 Credits
Huge respect to the original YASB developer and modifier: @da-rth, @amnweb
This repo only contains my custom configuration files, not the original YASB code.
