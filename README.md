# mc-lan-proxy.sprx
Lan/online MC PS4/PS5 jailbreak
📌 Complete Tutorial: Installing and Configuring mc_lan_proxy on PS4
Download and Registration
Download the required PKG: IV0000-CYPS00001_00-CYPRUSSERVICES00.pkg from the official registry at cyprusservices.uk. Install it on your PS4.

Create an account directly on the website cyprusservices.uk

Installing Files and Plugins
Place the mc_lan_proxy.sprx file into the /data/GoldHEN/plugins/ folder on your PS4.

Open your plugin.ini file (or create it) and add the following lines under your game ID ([CUSA00265]):

[CUSA00265]
/data/GoldHEN/plugins/CyprusNetwork.prx
/data/GoldHEN/plugins/mc_lan_proxy.sprx

Server Configuration (servers.ini)
Create a file named servers.ini inside the /data/GoldHEN/mc_lan_proxy/ directory.

This is also where you can configure and add your own custom servers. Add this content to get started:

[settings]
protocol=589
version=1.20.10
relay_base_port=19140

[serveur]
name=Mon Serveur
ip=109.248.4.148
port=19132

[serveur 2]
name=Craft PE
ip=109.248.4.148
port=19132

Launching the Game
Start your game on the PS4 and enjoy your servers! 

Minecraft Java Spigot-26.1 plugin that allows users to connect using mc-lan-proxy.sprx, and Geyser Standalone PS4, a server that bridges existing Java servers.

https://www.mediafire.com/file/aoaw6wla3aa5706/geyser_standalone_ps4.jar/file
https://www.mediafire.com/file/79c3xc8u1f62e34/geyser-ps4.jar/file
