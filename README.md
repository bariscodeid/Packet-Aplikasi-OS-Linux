# Paket Installasi Software for Linux Ubuntu 16.04.06 LTS
Packet Ubuntu 16.04 LTS Tools Packets

### Aplikasi Development:
Aplikasi terkait aplikasi untuk kebutuhan mendevelop seperti mobile apps, website dan lain sebagainya
- Android Studio IDE, Java, Paket Kebutuhan Tools Pelengkap Dev Mobile Apps https://developer.android.com/studio/
```bash
mcreator@indonesia:~$ sudo apt -y install default-jdk
mcreator@indonesia:~$ sudo apt -y install libc6:i386 libncurses5:i386 
mcreator@indonesia:~$ sudo apt -y install libstdc++6:i386 lib32z1 libbz2-1.0:i386
```
- http://guides.beanstalkapp.com/version-control/git-on-linux.html
- GitKraken IDE https://www.gitkraken.com/download
- VirtualBox https://www.virtualbox.org/wiki/Downloads
- Intellij IDEA for Java IDE https://www.jetbrains.com/idea/download/#section=linux
- Vysor https://chrome.google.com/webstore/detail/vysor/gidgenkbbabolejbgbpnhbimgjbffefm?utm_source=chrome-app-launcher-info-dialog
- VStudio https://www.valentina-db.com/en/get-free-valentina-studio
- Postman Desktop https://www.getpostman.com/apps
- Draw.io for Desktop https://chrome.google.com/webstore/detail/drawio-desktop/pebppomjfocnoigkeepgbmcifnnlndla?hl=en-GB
- PopSQL https://popsql.io/
- DB Browser for SQLite https://sqlitebrowser.org/
- LAMP Server https://github.com/septiyadii/Course-of-Website/wiki/Materi-K:-Membangun-Web-Server-di-VM-Ubuntu-Server-16.04.03-LTS

### Tools Desktop
- Unity Tweak Tools (Theme & Icon like Mac OS for Ubuntu 16.04.04 LTS)
```bash
# Theme Manger
mcreator@indonesia:~$ sudo apt -y install unity-tweak-tool
# Ubuntu Theme & Icon like Mac OS
mcreator@indonesia:~$ sudo add-apt-repository ppa:noobslab/macbuntu
mcreator@indonesia:~$ sudo apt -y update
mcreator@indonesia:~$ sudo apt -y install macbuntu-os-icons-lts-v7 macbuntu-os-ithemes-lts-v7
# Albert Launcher
mcreator@indonesia:~$ sudo apt -y install install albert
# Plank Docked
mcreator@indonesia:~$ sudo apt -y install plank
mcreator@indonesia:~$ sudo apt -y install macbuntu-os-plank-theme-lts-v7

```
- Web Browser Google Chrome https://www.google.com/intl/id_ALL/chrome/"
- WPS Office http://wps-community.org/downloads
- Peek (For convert to Gif) 
```bash
mcreator@indonesia:~$ sudo add-apt-repository ppa:peek-developers/stable
mcreator@indonesia:~$ sudo apt apt -y update && sudo apt -y install peek
```
- Audacious
```bash
mcreator@indonesia:~$ sudo apt -y install audacious
```
- MPV
```bash
mcreator@indonesia:~$ sudo apt -y install mpv
```
- Inkscape
```bash
mcreator@indonesia:~$ sudo apt -y install inkscape
```
- MarkDown Editor https://github.com/i38/justmd/releases
- Unrar & Unzip
```bash
mcreator@indonesia:~$ sudo apt -y install unrar unzip
```
- Git
```bash
mcreator@indonesia:~$ sudo apt -y install git
```
- Telegram Desktop
```bash
mcreator@indonesia:~$ sudo add-apt-repository ppa:atareao/telegram
mcreator@indonesia:~$ sudo apt -y update
mcreator@indonesia:~$ sudo apt -y install telegram
```
- Simplescreen Recorder
```bash
mcreator@indonesia:~$ sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder
mcreator@indonesia:~$ sudo apt-get update
mcreator@indonesia:~$ sudo apt-get install simplescreenrecorder
```
- Typing Test https://chrome.google.com/webstore/detail/typing-test/badmljhachfobngipeladdganhdgomhp
- Valentina Studio IDE https://www.valentina-db.com/en/studio/download/current <br><br>
<img src="https://github.com/koderspeach/Packet-OS-Linux/blob/a4714000f578f423489640b600b55f17209b31b1/1.png"/> <br><br>
```bash
# Serial Key
VS-L-DWF2NA2Q61TMWFK9-7EVLSA286MPYRPG8-V82EZKYTSD4FVPGQ-VNF2NA2Q61TMXW93
```
- Plugin Sourcecode Viewer for Posting in Wordpress https://wordpress.org/plugins/enlighter/

- Install Sublime Text
```bash
mcreator@indonesia:~$ wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
mcreator@indonesia:~$ echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
mcreator@indonesia:~$ sudo apt-get update
mcreator@indonesia:~$ sudo apt-get install sublime-text

This is the register key 
----- BEGIN LICENSE -----
sgbteam
Single User License
EA7E-1153259
8891CBB9 F1513E4F 1A3405C1 A865D53F
115F202E 7B91AB2D 0D2A40ED 352B269B
76E84F0B CD69BFC7 59F2DFEF E267328F
215652A3 E88F9D8F 4C38E3BA 5B2DAAE4
969624E7 DC9CD4D5 717FB40C 1B9738CF
20B3C4F1 E917B5B3 87C38D9C ACCE7DD8
5F7EF854 86B9743C FADC04AA FB0DA5C0
F913BE58 42FEA319 F954EFDD AE881E0B
------ END LICENSE ------
```
- Install Paket Insomnia for Linux Debian Base
```
# Add to sources
echo "deb https://dl.bintray.com/getinsomnia/Insomnia /" \
    | sudo tee -a /etc/apt/sources.list.d/insomnia.list

# Add public key used to verify code signature
wget --quiet -O - https://insomnia.rest/keys/debian-public.key.asc \
    | sudo apt-key add -

# Refresh repository sources and install Insomnia
sudo apt-get update
sudo apt-get install insomnia
```

- Gravit Designer

```
bariscode@indonesia:~/Downloads$ sudo snap install gravit-designer
```

- Zenkit Plan

```
bariscode@indonesia:~/Downloads$ sudo snap install zenkit
```

- Termius Apps

```
bariscode@indonesia:~/Downloads$ sudo snap install termius-app
```
