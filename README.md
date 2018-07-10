# esx_jailer
Let cops jail people! Custom built by the SCRP team and Modified by timnboys to rework the chat commands to only work if your job is `police` which works alongside esx_policejob. Doesn't matter anymore if you are an admin or not.

# Installation
1. Clone the project and add it to your resorces directory
2. Add the project to your `server.cfg`
3. Import `esx_jailer.sql` in your database
4. Select language in `config.lua`

# How to jail
- Use the `esx_jailer:sendToJail(source, jailTime)` server side trigger
- Use the `/jail playerID jailTime` command (only cops)
- Use the `/unjail playerID` to unjail a player (only cops)

# Features
- Jail people!
- Saves jail info to database, aka anti-combat
- Keeps jail time updated

# Requirements
- ES
- ESX
- esx_policejob
- skinchanger
- MySQL Async

# Based off
- [Original script by Albo](https://forum.fivem.net/t/release-fx-jailer-1-1-0-0/41963)
- [dbjailer](https://github.com/SSPU1W/dbjailer)
- [esx_jailer by ESX-Public](https://github.com/ESX-PUBLIC/esx_jailer)
