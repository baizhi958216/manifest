
# FiimeOS

开始编译
---------------
开始通过下方git获取FiimeROM的源代码  
To get started with the FiimeOS sources, you'll need to get familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

要初始化本地存储库，请使用命令：  
To initialize your local repository, use command:

```bash
repo init -u https://github.com/FiimeROM/manifest.git -b fiimeos-12.0-v1
```

同步命令：  
Then sync up:

```bash
repo sync
```

编译步骤
-------------------
使用 envsetup.sh 脚本初始化 ROM 环境。  
Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

克隆相关设备dt等  
Lunch your device after cloning all device sources if needed.

```bash
lunch arrow_devicecodename-buildtype
```

开始编译  
Start compilation

```bash
m otapackage
```

或者使用下面的命令  
OR

```bash
m bacon
```	 

官方QQ群：833588972  
好运！
