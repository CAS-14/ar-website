[home](/) / permissions

## Permissions System

On the server exist several plugins that manage permissions. Hopefully this page is explanatory and easy to understand.

### OP Levels

No one on the server actually has vanilla permissions. Instead, there are several "groups" which provide levels of permissions.

- **Default:** The default group provides some basic teleport permissions (explained below), and a few performance check commands such as `/tps`
- **Creative:** This group gives you permissions for many commands in the creative world, such as `/gamemode` and `/give`. This is given to most trusted players.
- **Owner:** I (dynamite14) am the only one in this group; it gives all permissions including server and world management.

Due to a few issues, no one has command block access. I am working on finding a workaround so that players in group **Creative** can get some limited access for creations. Also, permissions are limited in the Nether and the End, and I still need to fix this.

### Multi Worlds

There are multiple worlds on the server, including Creative, Survival, and some WIP minigames. Anyone is able to teleport between main worlds by using `/tpp creative` or `/tpp survival`. Please note that you cannot teleport between worlds if you are in the Nether or the End of any world; enter the Overworld first. Your location and inventory will be remembered separately in worlds, so `/tpp` will always teleport you back to where you were, as if you are joining a different server. If there is a bug with the multiple worlds system, please report it to dynamite14 (my Discord is on the homepage).

### Teleportation Perms (Creative world only)

- **Default Players**: You are able to use `/tpa <player>` to request to teleport to a player, and `/tpahere <player>` to request to teleport a player to you. You also have access to the warps system by using `/warp <warp>` and `/warps`. You can use `/back` to undo a teleport.
- **Creative Perms**: Players with higher perms can use `/sethome`, `/home <home name>`, `/delhome`, and `/movehome` to save and teleport between locations. You also have the ability to teleport to a random place with `/rtp`.