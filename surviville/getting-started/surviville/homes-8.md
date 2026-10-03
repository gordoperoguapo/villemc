---
description: Delivery info for VilleMC (Survival)
icon: envelope
---

# Delivery

## Delivery

Want to send items to another player without meeting up? Delivery lets you package up to 27 item slots and ship them directly to any player on the server, even if they are offline. A physical Allay courier spawns in the world to pick up and deliver your package, making the whole experience feel a lot more alive than a simple virtual mailbox.

***

### How It Works

1. Use `/delivery send <player>` to open the package creation GUI.
2. Place the items you want to send into the package slots.
3. Choose your delivery speed: Standard or Express.
4. Review the cost and confirm. The price is calculated automatically based on distance, item count, and speed.
5. An Allay courier spawns and picks up your package. Another Allay delivers it to the recipient in real time.

If the recipient is offline when you send, the package is held and their courier greets them the moment they log back in.

***

### Delivery Speeds

**Standard** - The affordable option. Delivery time is based on the distance between you and the recipient. Good for everyday sends when you are not in a rush.

**Express** - Twice as fast as standard and twice as expensive. Use this when you need items to arrive quickly.

***

### Pricing

Delivery is not free. The cost is calculated dynamically based on a few factors.

**Base cost** - Every delivery starts with a flat $25 base fee.\
**Distance** - A small additional charge is added per block of distance between you and the recipient.\
**Item weight** - The more items you pack in the box the higher the price.\
**Express multiplier** - Express deliveries cost 2.5x more than standard.\
**Tax** - A 5% tax is applied on top of the calculated total.

You can get a price estimate before committing by using `/delivery cost <player>`.

***

### Commands

✅ `/delivery send <player>` - Open the package creation GUI to send a delivery.\
✅ `/delivery cost <player>` - Get a price estimate for a delivery to that player before sending.\
✅ `/delivery track <id>` - Track the status of an active delivery using its ID.\
✅ `/delivery list` - View all of your current active deliveries.

***

### Tips and Good to Know

⭐ You can send up to 27 item slots per package so pack efficiently to keep costs down.\
⭐ Use `/delivery cost` before sending to check the price. Express to a player across the map can get expensive.\
⭐ Offline deliveries are fully supported. If your recipient is not online the Allay will wait and greet them on login.\
⭐ Both the sender and recipient receive notifications when a package is picked up and when it arrives.\
⭐ Standard delivery is the better choice for heavy or high-item-count packages since the express multiplier compounds with weight cost.
