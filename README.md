# Win10 Program backup

### Win10 install [Chocolatey](https://chocolatey.org/install)
```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### Chocolatey
```bash
choco install notepadplusplus.install
choco install 7zip.install
choco install git.install
choco install nodejs.install
choco install jdk8
choco install vscode
choco install sumatrapdf.install
choco install curl
choco install thunderbird
choco install winscp.install
choco install firefoxesr
choco install yarn
choco install golang
choco install cmake
choco install youtube-dl
choco install maven
choco install ffmpeg
choco install postman
choco install everything
choco install msys2
choco install cmder
choco install winmerge
choco install git-lfs
choco install tor-browser

choco install intellijidea-community
choco install gradle
choco install tortoisesvn
choco install dbeaver
choco install sqlite
choco install android-sdk
choco install ghc
choco install telegram.install
choco install cabal
choco install jdk11
choco install eclipse
choco install google-chrome-x64
choco install gpg4win-vanilla

choco install windows-sdk-10.1
choco install anaconda3
choco install redis-64
choco install erlang
choco install mysql
choco install androidstudio
choco install nmap
choco install visualstudio2019community
choco install mobaxterm
choco install beyondcompare
choco install mongodb
choco install postgresql

choco install utorrent
choco install plantuml

choco install adb
choco install screentogif
choco install burp-suite-free-edition
choco install arduino
choco install soapui
choco install sbt
choco install haskell-stack
choco install haskell-dev

choco install nginx
choco install zerotier-one

choco install elixir

choco install rdmfree

choco install sudo
choco install rust
choco install cmdermini
choco install qdir
choco install opencv

choco install flutter
choco install xmind
choco install goodsync
choco install vmware-workstation-player
choco install jmeter
choco install syncthing
choco install steam-client
choco install elasticsearch
choco install oracle-sql-develop
choco install clover
choco install studio3ter

refreshenv
```

### Win10 Dir backup
```bash
mkdir -p 1_Program/0_usual/0_install
mkdir -p 1_Program/0_usual/1_not_install

mkdir -p 1_Program/1_dev/0_usual
mkdir -p 1_Program/0_usual/1_Java
mkdir -p 1_Program/0_usual/2_Db
mkdir -p 1_Program/0_usual/3_Python

mkdir -p 0_Data/0_usual/0_choco
mkdir -p 0_Data/1_dev/0_Java
```
