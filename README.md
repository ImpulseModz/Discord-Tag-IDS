# DiscordTagIDs

### Version 1.0

This is a script that added prefixes to ID tags above players :) by using fully discord roles

#### Commands:
/tag-toggle - Turns off the prefix from being shown for the player (if they have a prefix in their tag)

/tags-toggle - Turns off all tags from being shown above other players for ONLY yourself (good for streamers and/or pictures)

On /tag-toggle not being active:

On /tag-toggle being active:

On /tags-toggle for tags not being active:

On /tags-toggle for tags being active: 

How does the tags look on players? Let's have a look :)

#### Installation
1. Download DiscordTagIDs 
2. Extract the .zip and place the folder in your /resources/ of your Fivem server
3. Start the resource in your server.cfg file
4. Enjoy :)

#### How to set up it up
The 1s in this part of the server.lua file must be replaced with the IDs of your discord roles that are equal to the prefix you have associated with it:
```lua
roleList = {
{0, "~w~"}, -- Regular Civilian / Non-Staff
{1, "~r~STAFF ~w~"}, --[[ T-Mod ]]-- 
{1, "~r~STAFF ~w~"}, --[[ Moderator ]]--
{1, "~r~STAFF ~w~"}, --[[ Admin ]]--
{1, "~p~MANAGEMENT ~w~"}, --[[ Management ]]--
{1, "~o~OWNER ~w~"}, --[[ Owner ]]--
}
