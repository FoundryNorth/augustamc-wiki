# Towny & Nations

## Towns

1. Find a good location to start your town using **`/map`** in-game. You can also view these links [here](../../#links).&#x20;
2. Towns must be created using our custom command (HERE)



## Town Creation Requirements.

> Players must have their minecraft account linked to their discord.&#x20;
>
> Players now must be rank 5 to submit a town creation requests&#x20;
>
> Players must have +3 members (4 total including owner) that have agreed to join their town within 24 hrs of being created.&#x20;
>
> Players must submit a town creation application with the requirements requested fulfilled.

* Towns can claim **8 plots per resident** free of any initial charge.&#x20;
* Bonus plots can be purchased for in-game money using **`/t buy bonus`**. Bonus plots can also be obtained by joining a [nation](./#nations) as well as through in-game rewards
* Extra bonus plots can be earned through in-game ranks and the Quest Crate
* If a town fails to pay upkeep, it will go bankrupt. If the town hits its debt cap, it will fall. The debt cap is **$10,000 per resident** in the town.
  * <mark style="color:red;">**!IMPORTANT!**</mark> If your town hits its debt cap - it will be deleted and slowly return to natural world generation.
* There is a **$50 daily upkeep** fee on each claimed plot every real-life day. This money is taken from the town bank.&#x20;
* To calculate how much you owe each day - you can either look at your /t info or calculate $50 \* town claim size.

## Outposts

* Your towns level (amount of members) now influences the amount of outposts your town may have. This change is to encourage meaningful use of outposts and their story to your town.
* Outposts are land claims that are not connected to your original town area.&#x20;
* This is useful to claim things like spawners that you find out in the wild or in other worlds.&#x20;
* Every town can claim up to **1 outpost upon creation.**&#x20;
* Members -> # Of Outposts&#x20;
  * 0 = 0&#x20;
  * 1 = 0&#x20;
  * 2 = 1&#x20;
  * 6 = 1&#x20;
  * 10 = 2&#x20;
  * 14 = 2&#x20;
  * 20 = 3&#x20;
  * 24 = 3&#x20;
  * 28 = 4

**1.** Stand where you want to create a new outpost. Use **`/plotborder`** or press **F3+g** to see the plot borders. \
\
**2.** Use **`/t claim outpost`**\
\
**3.** Use **`/t claim`** while standing in bordering plots to expand the outpost claim like you would for your regular town.\
\
**4.** Use **`/t outpost [number]`** to teleport to your new outpost.

## Nations

* Nations are teams of up to **20 allied towns** with up to **100 residents**.&#x20;
* They offer various benefits/features such as up to **144 bonus plot claims** and up to **4 extra outposts**.&#x20;
* The larger the nation, the bigger its plot/outpost limit per town.
  *

      ```
      0 = 0

      10 = 1

      20 = 2

      30 = 3

      40 = 4

      60 = 5
      ```

1. To create a nation, a player must be **Master** [rank](broken-reference) or above. They must also be the **mayor** of their town. It is free to create a nation once a player has met these requirements.
2. Use **`/n new [Nation_Name]`** to create a nation.
3. Nations pay a daily upkeep fee of **$2500** per town. This money is automatically withdrawn from the nation bank each day. Deposit money using **`/n deposit [amount]`.**
4.

## Create A Campsite

* Campsites allow players to temporarily claim and protect 1 plot(chunk) of land for **48 hours** before needing to relight the campfire or create/join their own town.
* Whenever you're ready, [create your own town](./#towns) or join one to permanently protect your things and gain access to surveying for resources and many other useful features.

1. Find a location for your temporary campsite. Use **`/map`** in-game or explore on your own until you find a good location.
2. Craft and **place a campfire** on the ground within the plot you want to claim. A message will pop up asking you if you want to make a camp there. Click on or type **`/confirm`** in chat.
3. Done! Your camp is created. You and your things will be protected for up to **48 hours** as you get started. If you want to extend this time, simply relight the campfire after the 48 hours have expired.&#x20;

## Official Video Guides:

[https://www.youtube.com/watch?v=A8DD8050SUI\&list=PLvzvmyk0uI0WsLf4iyJZRhD\_T2e-ANCmE](https://www.youtube.com/watch?v=A8DD8050SUI\&list=PLvzvmyk0uI0WsLf4iyJZRhD_T2e-ANCmE)

{% embed url="https://www.youtube.com/watch?v=A8DD8050SUI&list=PLvzvmyk0uI0WsLf4iyJZRhD_T2e-ANCmE" %}

## All Towny Commands:

* This information has been copied from Llama (owner/main dev of Towny) with his permission. You can view the originally posted information here: <[https://github.com/TownyAdvanced/Towny/wiki/Towny-Commands](https://github.com/TownyAdvanced/Towny/wiki/Towny-Commands)>

### Introduction To Towny Commands

* This list breaks each command down by word. Eg: /resident set perm {on/off}.
* For resident commands, the add command would auto-match online players, while add+ requires exact spelling to choose offline players.
* Just about every subcommand has it's own help menu. Use /resident set, or a similar cutoff, to show all the options for that command ingame. You can also use /resident set ?, you will probably need to use that in the case where a subcommand actually has a function by itself. Example: /town claim, and /town claim ? would show all it's subcommands.
* The { } brackets are used to show variables, or what you need to fill in. The elipse ".." (or shortened elipse) is used to show that you can specify multiple things at once (like inviting 10 residents at once).
* The {bleh/blah/bluh} is used to show that the input can be multiple words.
* An empty bullet represents that the subcommand itself does something and will not show a help menu.

### /towny

* Shows basic towny commands.
* ? - Shows more towny commands.
* map - Shows the towny map.
* prices - Shows taxes/costs associated with running a town.
* time - Shows time until next new-day (tax/upkeep collection.)
* top
  * residents {all/town/nation} - Shows top residents.
  * land {all/resident/town} - Shows top land owners.
* tree - Shows lots of stuff.
* universe - Shows full towny stats, resident/town/nation/world counts as well as townblocks claimed.
* v - Shows towny version.
* war
  * stats
  * scores

### /plot

* Shows the /plot commands.
* claim - Resident command to personally claims a plot that are for sale.
  * auto - Resident command to personally claim an area of plots that are for sale, around the player typing the command.
* unclaim - Resident command to unclaim personally owned plots.
  * circle/rect - Resident command to unclaim personally owned plots in a circle or rectangle shape.
  * {# (radius around current position)} - Radius of the area to unclaim.
* {forsale/fs} - Set a plot for sale.
  * circle/rect - Set a shape.
  * {# (radius around current position)} - Radius of the area to set forsale.
  * \$$ - Cost of plot.
  * circle/rect - Set a shape.
    * {# (radius around current position)} - Radius of the area to set forsale.
* {notforsale/nfs} - Set a plot to not be for sale.
  * circle/rect - Set a shape.
  * {# (radius around current position)} - Radius of the area to set notforsale.
* perm - Shows the perm line of the plot in which the player stands.
* set
  * reset - Sets a shop/embassy/arena/wilds plot back to a normal plot.
  * shop - Sets a plot to a shop plot.
  * embassy - Sets a plot to an embassy plot.
  * arena - Sets a plot to an arena plot.
  * wilds - Sets a plot to a wilds plot.
  * name - allows a mayor or plot-owner to rename plots they own, overwriting the \~Unowned message. Personal-plots display both the plot's given name and the name of the plot-owner.
  * perm&#x20;
  * {on/off} - Edits the perm line of the single plot in which the player is standing. [See here for details.](http://code.google.com/a/eclipselabs.org/p/towny/wiki/HowTownyWorks#Towny_Perms)
  * {resident/ally/outsider} {on/off}
  * {build/destroy/switch/itemuse} {on/off}
  * {resident/ally/outsider} {build/destroy/switch/itemuse} {on/off}
  * reset - Resets the plot in which you stand to the default perm line of the /town or /resident screen (depending on if the plot is owned personally or by the town.)
* toggle
  * fire - Turn on/off firespread in the plot in which you stand.
  * pvp - Turn on/off pvp in the plot in which you stand.
  * explosion - Turn on/off explosions in the plot in which you stand.
  * mob - Turn on/off hostile mobspawning in the plot in which you stand.
* clear - Command to remove list of block id's from a plot, used by a mayor on town-owned land, or by a plot-owner on their personal plots.

### /resident

* Shows a player their resident screen.
* ? - Shows /res commands available.
* {resident} - Shows a player another player's resident screen.
* friend
  * add {resident} .. {resident} - Resident adds online player to their friends list.
  * add+ {resident} .. {resident} - Resident adds offline player to their friends list.
  * remove {resident} .. {resident} - Resident removes online player from their friends list.
  * remove+ {resident} .. {resident} - Resident removes offline player from their friends list.
  * clearlist - Removes all friends from a resident's friend list.
* list - Lists residents in towny's data folder.
* spawn - If deny\_bed\_use: true in the config.yml and player has a current bed spawn, command will teleport player to their bed.
* toggle
  * map - Turns on map which refreshes when moving across plot borders.
  * townclaim - Turns on mode where /town claim is automatically used when moving across plot borders.
  * plotborder - Turns on smokey plot-border view. Border shows when players cross to different townblocks.
  * reset - This turns off all modes that are active.
* set
  * perm
  * {on/off} - Edits the perm line on the resident screen. [See here for details.](http://code.google.com/a/eclipselabs.org/p/towny/wiki/HowTownyWorks#Towny_Perms)
  * {friend/ally/outsider} {on/off}
  * {build/destroy/switch/itemuse} {on/off}
  * {friend/ally/outsider} {build/destroy/switch/itemuse} {on/off}
  * reset - This takes the perm line seen in the /resident screen and applies it to all plots personally owned by the player typing it.
* tax - Shows taxes a player pays.

### /town

* Shows a player their town's town screen.
* ? - Shows /town commands available.
* {town} - Shows a player another town's town screen.
* here - Shows you the town screen of the town in which you stand.
* leave - Leaves a town.
* list - Lists towns.
* online - Shows players in your town which are online.
* new
  * {townname} - Creates new town.
  * {townname} {mayor} - Admin command to create town.
* add {resident} .. {resident} - Mayor command to add residents to your town.
* kick {resident} .. {resident} - Mayor command to remove residents from your town.
* spawn - Teleports you to your town's spawn.
* spawn {town} - Teleports you to another town's spawn.
* claim - Mayor command to claim the townblock in which you stand for your town.
  * outpost - Claims an outpost for your town.
  * {# (radius around current position)} - Claims an area of townblocks around you for your town.
  * auto - Claims as many townblocks around you as is possible given money in townbank and available townblocks.
* unclaim - Mayor command to unclaim the townblock in which you stand.
  * all - Mayor command to unclaim all townblocks.
  * {# (radius around current position)} - Command to unclaim an area of townblocks around you.
* withdraw {$} - Removes money from town bank.
* deposit {$} - Adds money from player to the town bank.
* buy
  * bonus {amount} - Buys available bonus townblocks.
* delete {town name} - Admin/Mayor command to delete a town from towny's data folder's files.
* outpost
  * {# (where # equals the corresponding outpost's number)} - Teleports to an outpost.
* ranklist - Displays residents and their ranks.
* rank {add|remove} {playername} {rankname} - Grants or removes a rank to a resident of the town.
* reslist - Displays a full list of residents in the town.
* set
  * board {message} - Sets message seen by residents upon logging in.
  * mayor {resident} - Mayor command to give mayor status to another resident.
  * homeblock - Sets the homeblock and spawn of your town.
  * spawn - Sets the town spawn, must be done inside the homeblock.
  * name {name} - Change your town's name.
  * outpost - Sets a townblock as an outpost.
  * perm
  * {on/off} - Edits the perm line on the town screen. [See here for details.](http://code.google.com/a/eclipselabs.org/p/towny/wiki/HowTownyWorks#Towny_Perms)
  * {resident/ally/outsider} {on/off}
  * {build/destroy/switch/itemuse} {on/off}
  * {resident/ally/outsider} {build/destroy/switch/itemuse} {on/off}
  * reset - This takes the perm line seen in the /town screen and applies it to all plots owned by the town.
  * tag {upto4character} - Sets the town's tag, which is sometimes used on that chat line.
  * clear - Clears the tag set for the town.
  * taxes {$} - Sets taxes collected from each resident daily. Also sets percentage if taxpercent is toggled on.
  * plottax {$} - Set taxes collected from each resident daily, per plot that they own.
  * plotprice {$} - Sets default cost of plot for the town.
  * shopprice {$} - Sets default cost of a shopplot for the town.
  * shoptax {$} - Set taxes collected from each resident daily, per shopplot that they own.
  * embassyprice {$} - Sets default cost of a embassy plot for the town.
  * embassytax {$} - Set taxes collected from each resident daily, per embassy plot that they own.
* toggle
  * explosion - Turn on/off explosions in town.
  * fire - Turn on/off firespread in town.
  * mobs - Turn on/off hostile mobspawning in town.
  * public - Turn on/off public /town spawning and the co-ordinates of the town's homeblock in the /town screen.
  * pvp - Turn on/off pvp in town.
  * taxpercent - Turn on/off taxing by percent/flatrate.
  * open - Turn on/off public joining to your town.
* join {townname} - Command to join a town that doesn't require invites.

### /nation

* Shows a player their nation's nation screen.
* ? - Shows /nation commands.
* list - Lists nations.
* online - Shows players in your nation which are online.
* {nation} - Shows a player the /nation screen of another nation.
* leave - Mayor command to leave the nation they are a part of.
* withdraw {$} - King command to remove money from the nation bank.
* deposit {$} - King command to add money to the nation bank.
* new
  * {nationname} - Mayor command to create a nation.
  * {nationname} {capitaltown} - Admin command to create a new nation, set capitol.
* rank - Command to set assistant/custom ranks in the nation.
* add {town} .. {town} - Invites/Adds a town to your nation.
* kick {town} .. {town} - Removes a town from your nation.
* delete {nation} - Deletes your nation.
* ally
  * add {nation} .. {nation} - Add a nation to your nation's ally list.
  * remove {nation} .. {nation} - Removes a nation from your nation's ally list.
* enemy
  * add {nation} .. {nation} - Add a nation to your nation's enemy list.
  * remove {nation} .. {nation} - Removes a nation from your nation's enemy list.
* rank {add|remove} {playername} {rankname} - Grants or removes a rank to a resident of the nation.
* set
  * king {resident} - King command to change the king of the nation.
  * captial {town} - Sets the capitol and king of the nation.
  * taxes {$} - Sets nationtax applied to the towns within the nation.
  * name {name} - Sets the nation's name.
  * title {name} {titlegoeshere} - King command to add a Title to a member of the nation.
  * surname {name} {surnamegoeshere} - King command to add a Suffix to a member of the nation.
  * tag {upto4character} - Sets the nation's tag, which is sometimes used on that chat line.
  * clear - Clears the tag set for the nation.
* toggle
  * neutral - Sets whether your nation will pay daily to be neutral during towny war.

### Chat Commands

* /townchat, /tc
  * Put in from of text to speak with members of your town only, or without text afterwards to enter the channel.
* /nationchat, /nc
  * Put in from of text to speak with members of your nation only, or without text afterwards to enter the channel.
* /global, /g
  * Put in from of text to speak in globalchat, or without text afterwards to enter the channel.
* /res set mode reset
  * Reset chat mode to default chat.
* /a - admin chat.
* /m - moderator chat.
* /vip - VIP chat.
* /channel leave|join {channel} - Channel leaving and joining.
* /leave {channel} - Leaves a channel.
* /join {channel} - Joins a channel.
* /chmute {channel} {player} - Mutes a player in a channel.
* /mutelist {channel} - Displays mute list for a channel.
* /chunmute {channel} {player} - Unmutes a player in a channel.
