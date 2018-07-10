# esx_jailer
Let cops jail people! Custom built by the SCRP team
- [FiveM Forum thread](https://forum.fivem.net/t/release-esx-jailer/82896)

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
- [Original script](https://forum.fivem.net/t/release-fx-jailer-1-1-0-0/41963)
- [dbjailer](https://github.com/SSPU1W/dbjailer)
