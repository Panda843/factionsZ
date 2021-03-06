# factionsZ v1.0.0 - BETA

A plugin for managing factions in game.

Download the latest version here : (https://github.com/Panda843/factionsZ/releases/download/factionsZ_v1.0.0_BETA/factionsZ_v1.0.0.phar)
## Commands / Permissions

```
(All faction commands) => factionsZ.command - Permission to use all commands

/f create => factionsZ.command.create - Permission to create a faction (default)
/f disband => factionsZ.command.disband - Permission to disband a faction (default)
/f invite => factionsZ.command.invite - Permission to invite a player to the faction (default)
/f accept => factionsZ.command.accept - Permission to accept a faction invite (default)
/f deny => factionsZ.command.deny - Permission to deny a faction invite (default)
/f leave => factionsZ.command.leave - Permission to leave a faction (default)
/f kick => factionsZ.command.kick - Permission to kick a player from the faction (default)
/f promote => factionsZ.command.promote - Permission to kick a player from the faction (default)
/f demote => factionsZ.command.demote - Permission to kick a player from the faction (default)
/f desc => factionsZ.command.desc - Permission change a faction's description (default)
/f help => factionsZ.command.help - Permission to view all faction commands (default)
/f info => factionsZ.command.info - Permission to get info of a faction (default)
/f about => factionsZ.command.about - Permission to view details about the plugin (default)
/f sethome => factionsZ.command.sethome - Permission to set your faction's home (default)
/f home => factionsZ.command.home - Permission to go to your faction's home (default)
/f unsethome => factionsZ.command.unsethome - Permission to get info of a faction (default)
/f claim => factionsZ.command.claim - Permission to claim a land for your faction (default)
/f unclaim => factionsZ.command.unclaim - Permission to unclaim the land of your faction (default)
/f top => factionsZ.command.top - Permission to get a list of the top factions (default)
/f plead => factionsZ.command.plead - Permission to pass the leadership of a faction (default)
/f ally => factionsZ.command.ally - Permission to send an ally request to a faction (default)
/f aaccept => factionsZ.command.aaccept - Permission to accept an alliance request (default)
/f adeny => factionsZ.command.adeny - Permission to deny an alliance request (default)
/f unally => factionsZ.command.unally - Permission to break alliance with a faction (default)
/f c => factionsZ.command.chat - Permission to enable faction chat (default)
/f ac => factionsZ.command.achat - Permission to enable ally chat (default)

/f admin => factionsZ.command.admin - Permission to bypass claim protection (OP)
```
To edit some of the properties of this plugin, please edit the config.yml. If you want to disable claiming, faction chat, ally chat or something else instead, you can always use PurePerms to remove the permission from players. 

## PureChat compatiblity :
This plugin is currently "NOT" compatible with PureChat. Why? Because I can't add support for PureChat, the maker of PureChat himself should add support for factionsZ if you want this plugin to be compatible with PureChat. 

But do not worry! Until then, you can replace your existing PureChat phar with my modified PureChat phar which is at (https://github.com/Panda843/PureChat/releases/download/MODDED_v1.4.0/PureChat_v1.4.0.phar) This modified version will support factionsZ. If you already have factionsZ enabled and the new phar, go to the PureChat config and set "default-factions-plugin" to factionsZ. 

## TO-DO for next update :
```
Add /f overclaim, /f map and some more commands
Add JSONProvider (for now only sqlite is available)
Optimize some parts of the code and fix bugs (if there are any)
```
## Author

* **Panda843** - (https://github.com/Panda843)
