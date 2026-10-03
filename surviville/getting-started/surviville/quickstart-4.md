---
description: How to claim land on VilleMC (survival)
icon: shovel
---

# Land Claiming

## Land Claiming

Your builds are your business. Surviville uses **GriefPrevention** along with a custom **GUI addon** to let you protect your land from griefers, thieves, and unwanted guests without needing to ask staff for help. Most of your claim management can be done through a clean, easy-to-use inventory menu. We use a custom built plugin to help you identify claims quickly via particles and blocks!\
<br>

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

***

### Getting Started

Every new player receives a starter pool of claim blocks just for joining, and you continue earning more simply by playing. Claim blocks are the currency of land protection. The more you have, the more land you can protect.

To **create a claim**, hold a **Golden Shovel** and right-click two opposite corners of the area you want to protect. The land between those corners, all the way up to the build height limit, becomes yours.

To **inspect a claim** (or check if a block is already claimed), hold a **Stick** and right-click any block.

***

### The Claim GUI

The easiest way to manage your claims is through the built-in GUI. Simply type `/claim` to open your main claim menu. From there you can navigate everything including your claim list, trust settings, flags, and more through inventory menus without needing to memorize commands.

#### Quick GUI Commands

✅ `/claim` - Open your main claim management menu.\
✅ `/claim list` - Browse all of your claims in a visual menu.\
✅ `/claim info` - View detailed info about the claim you're standing in.\
✅ `/claim warp <claimID>` - Warp directly to one of your claims.\
✅ `/claim fly` - Toggle flight inside your own claim (if enabled).\
✅ `/claim claimblocks` - Open the claim blocks menu to buy or sell blocks.\
✅ `/claim create [radius]` - Create a new claim centered on your position.

***

### Claim Commands

These commands still work alongside the GUI if you prefer typing them directly.

#### Core Commands

✅ `/abandonclaim` - Delete the claim you're standing in and recover those blocks.\
✅ `/abandonallclaims` - Delete all of your claims at once.\
✅ `/claimslist` - View a summary of all your claims and block usage.\
✅ `/trapped` - Escape a claim you've gotten stuck inside.\
✅ `/buyclaimblocks <amount>` - Purchase additional claim blocks with in-game currency.\
✅ `/sellclaimblocks <amount>` - Convert claim blocks back into in-game currency.

#### Trust Commands

You can invite other players into your claim with different levels of access, either through the GUI (`/claim trust <player>`) or with commands directly:

✅ `/trust <player>` - Full build and break access inside your claim.\
✅ `/containertrust <player>` - Access to chests, furnaces, crafting tables, and animals, but no building.\
✅ `/accesstrust <player>` - Access to buttons, levers, and beds only.\
✅ `/permissiontrust <player>` - Lets a player manage trust levels in your claim on your behalf.\
✅ `/untrust <player>` - Remove a specific player's permissions from your claim.\
✅ `/untrust all` - Remove all permissions for everyone in your claim at once.\
✅ `/trustlist` - See who has access to the claim you're standing in.

#### Extra Player Management

✅ `/claim ban <player>` - Prevent a specific player from ever entering your claim.\
✅ `/claim unban <player>` - Remove a claim ban.\
✅ `/claim kickout <player>` - Immediately remove a player who is currently inside your claim.\
✅ `/claim transferclaim <player>` - Transfer ownership of a claim to another player.

#### Subdivision Commands

You can divide your claim into sub-sections with their own independent permissions, which is useful for shared bases, shops, or town districts.

✅ `/subdivideclaims` (or `/sc`) - Switch your Golden Shovel to subdivision mode.\
✅ `/basicclaims` (or `/bc`) - Switch back to normal claiming mode.\
✅ `/restrictsubclaim` (or `/rsc`) - Make a subclaim fully independent so it does not inherit permissions from the parent claim.

***

### Claim Flags

Claim flags let you customize how your claim behaves beyond the standard protections. The easiest way to manage them is through the GUI. Just open `/claim` and navigate to your claim settings. You can also use `/setclaimflag <flag>` and `/unsetclaimflag <flag>` while standing in your claim, or `/listclaimflags` to see what is currently active.

#### Useful Flags for Players

🚩 `NoMonsterSpawns` - Prevents hostile mobs from spawning inside your claim.\
🚩 `EnterMessage <text>` - Display a custom message to anyone who walks into your claim.\
🚩 `ExitMessage <text>` - Display a message when someone leaves your claim.\
🚩 `NoEnter` - Prevent other players from entering your claim entirely.\
🚩 `NoFlight` - Disable flight inside your claim.\
🚩 `NoHunger` - Prevents hunger from depleting inside your claim.\
🚩 `AllowPvP` - Enable PvP inside your claim. _(Eternal rank exclusive, see Ranks for details.)_

> 💡 Not all flags are available to all players. Some flags require specific rank permissions to use. Check the flag settings inside your `/claim` GUI for a full list of what is available to you.

***

### Tips and Good to Know

⭐ Your claim blocks accumulate automatically the longer you play.\
⭐ Unclaimed land is **not protected**. Always claim your builds before logging off.\
⭐ Claims extend all the way to the sky limit so no one can build over you.\
⭐ Explosions from TNT and creepers cannot damage blocks inside a claim by default.\
⭐ Animals and crops inside your claim cannot be harmed or trampled by other players.\
⭐ You can check how many claim blocks you have with `/claim claimblocks` or `/claimslist`.
