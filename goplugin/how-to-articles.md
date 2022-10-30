# How-to Articles

---

## How to.. Access GoPlugin community support

Simply join the official community [discord server](discord.gg/PtSFYtMkCu) where you can get access to the both community resources & the GoPlugin team.


## How to.. Become a GoPlugin Node Operator


The best resources to aid with setting up your node are as follows;

  1. Keep up to date with changes on the [official documentation](https://docs.goplugin.co/), paying special attention to the [system requirements](https://docs.goplugin.co/plugin-installations/how-to-install-plugin-node#system-requirements) as these can change & is something to consider when choosing the specs of your Virtual Private Server (VPS).

  2. The offical github [Plugin-deployment repository](https://github.com/GoPlugin/plugin-deployment) which has all the detailed guides on how to install and manage your node.

**NOTE:** _The recommended and most widely supported approach to installing your GoPlugin node is using what is called the 'Modular Script' method._

### How to.. Select a VPS to host your node

This is a commonly asked question on the official community [discord server](discord.gg/PtSFYtMkCu). The following are the current list of providers that node operators use. Be sure to factor in the above system requirements.

  - [Racknerd](https://tinyurl.com/BlackFridayPLI)
  - [Liteserver](https://liteserver.nl/nvme-ssd-vps/)
  - [Netcup](https://www.netcup.de/vserver/vps.php#v-server-details)
  - [Strato](https://www.strato.de/server/linux-vserver/)
  - [Hetzner](https://www.hetzner.com/cloud)
  - [Vultr](https://www.vultr.com/)
  - [Contabo](https://contabo.com/)
  - [Servarica](https://servarica.com/)


Do NOT use the following provider(s) as previous nodes have experienced issues simply due to being associated with crypto;
  - EthernetServers


**NOTE ::** _This is simply a list of current known providers and is not exhaustive. None of the providers listed here are in anyway officially endorsed by GoPlugin._

---


## How to.. Monitor your node

While there are many platforms available that will provide various levels of monitoring, we have made every effort to eliminate costs and so the following solutions are proposed;

  - [UptimeRobot](https://uptimerobot.com/)
     This is a free service and provides basic ping and port checking monitor with email & app push notifications

  - [Netdata](https://www.netdata.cloud/)
     This is a free service which provides detailed system & process monitoring with all historic data stored locally on the host system. So from a security perspective your node data stays on your node. Also includes Machine Learning (ML) for anomoly detection.

    You can install netdata with configuration for monitoring the plugin node processes using the following script should you wish;
    https://github.com/inv4fee2020/pli_netdata
    
