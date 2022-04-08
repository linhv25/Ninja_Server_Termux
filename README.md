# Ninja_Server_Termux
Ninja School Server on Termux Android
# Version: 4.8 [Official]
# Update: 01/04/2022

[![Github All Releases](https://img.shields.io/github/downloads/KhanhNguyen9872/Ninja_Server_Termux/total.svg?style=for-the-badge)](https://github.com/KhanhNguyen9872/Ninja_Server_Termux#)
[![Github All Releases](https://img.shields.io/github/release/KhanhNguyen9872/Ninja_Server_Termux.svg?style=for-the-badge)](https://github.com/KhanhNguyen9872/Ninja_Server_Termux#)

# System Requirements
CPU: Quad-core with 1.30GHz or up <br />

Architecture: ARM 32-64bit <br />

Android 7.0 Nougat or up <br />

RAM: 2GB [Online Mode: 3GB or up] <br />

Internal storage: [2.5GB Offline only] - [2.8GB Offline + Online] - [3.3GB Full Package] <br />

Termux: Latest version! <br />

# Note

Server cannot be start if port 3306, 8080 is in used! <br />

Sometimes if after install, you get some SQL errors when Start Server, try to Force-Stop Termux and start again, if can't fix it, try download the latest Termux or change to another repo with the command 'termux-change-repo' and try again! <br />


# How to install?
 - Tutorial: https://youtu.be/puTeSrOrfL4
1. Download Termux APK (click on Picture): 
[![](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/raw/main/image/termux.png)](https://f-droid.org/repo/com.termux_118.apk)
 or 
[![](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/raw/main/image/termux.png)](https://github.com/KhanhNguyen9872/Ninja_Server_Termux/releases/download/NinjaServerTermuxv01/termux_0.118.apk)

2. Install Termux APK

3. Open Termux, copy this line and paste it on Termux

```bash
pkg upgrade -y && pkg install wget -y && wget -O install.sh https://raw.githubusercontent.com/KhanhNguyen9872/Ninja_Server_Termux/main/install.sh && bash install.sh https://fb.me/khanh10a1
```

4. Wait for a long time!
 
5. After Download 735MB and Install, Termux will ask you something, do it!

6. Choose Source you want to use! 
 
7. Enjoy!
# HOW TO CHANGE SOURCE?
1. Open Termux and run this command
```bash
tamp -start
```
2. Open New Session and run this command
```bash
menu
```
3. Choose Settings, and Choose 'Change Server'

4. Restart Termux!

# How to start?
1. Open Termux and run this command
```bash
tamp -start
```
2. Next, open New Session Termux and run this command
```bash
ninja
```
3. Open J2ME-Loader and Enjoy it!

# Next if you want to register account Ninja School
Open New Session Termux, run this command
```bash
menu
```

# How to start Online mode?
1. Open Termux, run tamp -start and menu
2. On menu, choose 7, and choose 7 again, choose Install Online Mode and wait for install
3. After install, Insert your authtoken ngrok
4. Open New Session, start ninja server normal
```bash
ninja
```
5. Open New Session, type
```bash
online
```
6. Choose your Server and you will have IP Online
7. Mod your file game with this IP Online, Enjoy!

# IF You don't see Ninja School in J2ME-Loader
 - Install ninja.jar file [using J2ME-Loader] and Enjoy!
```
ninja-Khanh.jar in /sdcard [Internal Storage]
```
