Fortnite Lobby Bot Made By TakashiBTW
# fortnitepy-bot
A fortnite XMPP bot coded in Python with party capabilites.

## How do I get started?

* Install [Python 3.6](https://www.python.org/downloads/release/python-360/ "Python 3.6 Download") (suggested, any 3.x version *should* work, **APART FROM 3.8 DO NOT USE 3.8 OR ELSE YOU'LL GET A LOT OF ERRORS**.)


* Then run ``INSTALL PACKAGES.bat`` if you're on Windows or type these commands into console if you're on macOS / linux:
```
python3 -m pip install -U fortnitepy
python3 -m pip install -U aiohttp
python3 -m pip install -U colorama
python3 -m pip install -U BenBotAsync==1.0.1
```

Then fill out ``config.json`` with your configuration & run Start Bot.bat


## Config Documentation
```
"email": "",                                                - The bot accounts email.
"password": "",                                             - The bot accounts password.
"cid": "CID_028_Athena_Commando_F",                         - The skin that the bot wears when it joins.
"bid": "BID_004_BlackKnight",                               - The backpack that the bot wears when it joins.
"eid": "EID_Clapperboard",                                  - The emote that the bot does when it joins.
"pid": "Pickaxe_Lockjaw",                                   - The pickaxe that the bot has equiped.
"banner": "otherbanner28",                                  - The banner icon the bot uses.
"banner_colour": "defaultcolor15",                          - The colour of the banner icon.
"level": "100",                                             - Sets the clients level.
"bp_tier": 999999999,                                       - Sets the clients battle pass tier.
"status": "Created by xMistt, enjoy! <3",                   - Sets the clients presence.
"platform": "AND",                                          - Sets the clients platform seen in the lobby.
 ** ALL Platforms: **
 * XBL
 * NTS
 * PSN
 * WIN
 * IOS
 * AND
"friendaccept": "True",                                     - If the bot will accept every friend request.
"joinoninvite": "True",                                     - If the bot will join every party they are invited to.
"AdminPassword": "0001",                                    - The password to use to add themselves the the admin list.
"FullAccess": [                                             \
    "(Your Epic Name)"                                       - Decides who has access to EVERY command.
],                                                          /
"BlockList": [                                              \
    "(User's Epic Name)"                                     - Decides who doesn't have access to ANY command.
]                                                           /
```   

##Commands

!skin - Sets the outfit of the client using the outfits name.
Usage: !skin <skin name>

!backpack - Sets the backpack of the client using the backpacks name.
Usage: !backpack <backpack name> Or just '!backpack' to set to none.

!emote - Sets the emote of the client using the emotes
Usage: !emote <emote name>

!pickaxe - Sets the pickaxe of the client using the pickaxe name.
Usage: !pickaxe <pickaxe name>

!point - Points out a specified pickaxe.
Usage: !point <pickaxe name>

!pet - Sets the pet (backpack) of the client using the pets name.
Usage: !pet <pet name>

!emoji - Sets the emoji of the client using the emojis name.
Usage: !emoji <emoji name>

!reset - Resets the bot to it's default cosmetic loadout.
Usage: !reset

!variants - Changes the skin's variants to what you set. For a more detailed variants commands page, click here.
Usage: !variants <CID> <style type> <integer>

!purpleskull - Sets the outfit of the client to Purple Skull Trooper.
Usage: !purpleskull

!pinkghoul - Sets the outfit of the client to Pink Ghoul Trooper.
Usage: !pinkghoul

!normalghoul - Sets the outfit of the client to Normal Ghoul Trooper.
Usage: !normalghoul

!brainiacghoul - Sets the outfit of the client to Brainiac Ghoul Trooper.
Usage: !brainiacghoul

!purpleportal - Sets the backpack of the client to Purple Ghost Portal.
Usage: !purpleportal

!checkeredrenegade - Sets the outfit of the client to Checkered Renegade.
Usage: !checkeredrenegade

!banner - Sets the banner of the client.
Usage: !banner <icon> <colour> <level>

CID_ - Sets the outfit of the client using CID.
Usage: <CID>

BID_ Sets the backpack of the client using BID.
Usage: <BID>

PICKAXE_ID_ - Sets the pickaxe of the client using PICKAXE_ID.
Usage: <PICKAXE_ID>

EID_ - Sets the emote of the client using EID.
Usage: <EID>

PetCarrier_ - Sets the pet of the client using PetCarrier_.
Usage: <PetCarrier_>

Emoji_ - Sets the emoji of the client using Emoji_.
Usage: <Emoji_>

!stop - Clears/stops the emote currently playing.
Usage: !stop

!help - Displays a link to this webpage.
Usage: !help

Party Commands
!ready - Sets the readiness of the client to ready.
Usage: !ready

!unready/!sitin - Sets the readiness of the client to unready.
Usage: !unready

!sitout - Sets the readiness of the client to SittingOut.
Usage: !unready

!bp - Sets the battlepass info of the client.
Usage: !bp <tier>

!level - Sets the level of the client.
Usage: !level <level>

!invite - Invites the person who sent the message unless name is inputted. (User must be on friends list)
Usage: '!invite' OR '!invite <user>'

Playlist_ - Sets the lobbies selected playlist.
Usage: <Playlist ID>

!echo - Sends message to party chat with the given content. [Needs 'FullAccess']
Usage: !echo <message>

!status - Sends and sets the status of the client. [Needs 'FullAccess']
Usage: !status <text>

!leave - Leaves the current party. [Needs 'FullAccess']
Usage: !leave

!join - Joins the person's lobby unless a name is inputted. [Needs 'FullAccess']
Usage: !join OR !join <username>

!kick - Kicks the inputted user. [Needs 'FullAccess']
Usage: !kick <username>

!promote - Promotes the inputted user. [Needs 'FullAccess']
Usage: !promote <username>

!showfriends - Inputs a list of friends that the bot has added to the command prompt. [Needs 'FullAccess']
Usage: !showfriends

!add - Sends a friend request the inputted user. [Needs 'FullAccess']
Usage: !add <username>

!remove - Removes the inputted user as a friend. [Needs 'FullAccess']
Usage: !remove <username>

!admin add - Adds a player to the 'FullAccess' list. [Needs 'FullAccess']
Usage: !admin add <EPIC GAMES name>

!admin remove - Removes a player from the 'FullAccess' list. [Needs 'FullAccess']
Usage: !admin remove <EPIC GAMES name>

## MY Social Media

YouTube: https://www.youtube.com/TakashiBTW

Twitch: https://Twitch.tv/TakashiBTW
