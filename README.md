# Luna Multiplayer - Linux Server Management Scripts
The **Linux Server Management scripts** aim to provide a full management tool set for a **Luna Multiplayer server**. They allow to manage most aspects of the server

  * Installing and updating mod
  * Creating/editing/deleting server instances (including editing the serverconfig through a commandline interface)
  * List all instances with basic information or show detailed information on a single instance
  * Starting/stopping instances including graceful shutdown if the server has not hung up
  * Backup of game data files (instance configurations, logs, saves)

This wiki will guide you through the setup and usage of the tool set.  
[wiki](https://github.com/artnod78/KSP-DMP-Manager/wiki)

More information for **Luna Multiplayer** [here](http://lunamultiplayer.com/)

-------------

### TODO List
* Upgrade instances with ``lmm.sh updateengine`` command
* More settings group
* Add instances version in ``lmm.sh instances list`` output

-------------

### PATCH Note
#### 2018/03/14 v0.0.2
* Fix ``checkGamePortUsed`` in ``lmm.sh instances edit <InstanceName>``
* Edit Wiki
#### 2018/02/25 v0.0.1
* Start project
