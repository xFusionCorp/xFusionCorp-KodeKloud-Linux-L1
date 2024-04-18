---
title: "KodeKloud Engineer task: Create a user in Linux"
datePublished: Thu Apr 18 2024 03:52:23 GMT+0000 (Coordinated Universal Time)
cuid: clv4pgxvf000e08lfgwqn993v
slug: kodekloud-engineer-task-create-a-user-in-linux
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1713412210354/6d17d6da-aa8a-49e3-bbed-74a837c0d3f9.png
tags: linux, task, system-admin, kodekloud, linuxsystemadministration, systemadministration, kodekloudengineer, kodekloudtasks, linuxnetworking-networkconfiguration-networkdiagnostics-sysadmintips-linuxcommands, linux-unix-processes-systemadministration-processmanagement-foregroundprocesses-backgroundprocesses-processtypes-daemonprocesses-terminalcommands-systemresources-operatingsystems

---

# ***Step 1: Connect to the App Server***

```powershell
ssh app_server_username@server_name

# example
ssh tony@stapp01
```

# *Step 2: Switch to root User*

```powershell
sudo su
```

# *Step 3: Add the asked user, set the user UID as asked, and set the directory where the user will be created*

```powershell
useradd -m user_name -u UID -d directory_path

# example
useradd -m anita -u 1026 -d /var/www/anita
```

# *Step 4: Verify the User*

```powershell
cat /etc/passwd | grep -i user_name

# example
cat /etc/passwd | grep -i anita
```

<mark>Congratulation! you've successfully completed the very first Task!!! 🎉</mark>