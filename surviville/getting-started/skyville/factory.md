---
description: How to use island teams.
icon: conveyor-belt
---

# Factory

## Factory

Skyville's factory system lets you build automated production lines on your island — automatically harvesting crops, smelting ores, crafting items, and sorting chests without lifting a finger. The deeper you go, the more powerful your island becomes.

***

### Getting Started

Everything in the factory system is accessed through one command:

✅ `/factory` - Opens the factory menu where you can browse and obtain all factory devices.

To start building, you need two things: **devices** and **power**. Devices are the machines that do the work. Power is what makes them run.

***

### Power

Every device on your island requires power to function. Power does not come from a single source — you build a **power grid** by connecting generators and devices together using the **Wire Tool**.

**To build a power grid:**

1. Place a generator (start with a Combustion Generator or Solar Panel)
2. Grab the **Wire Tool** from `/factory`
3. Left-click the generator, then left-click the next device or pylon in the chain
4. Keep connecting until all devices are on the grid

Power lines are visible between connected blocks. If a device has a power icon above it, it is on the grid. A red or missing icon means the connection chain is broken somewhere.

**For larger factories**, use **Power Pylons** as relay points to extend your grid across your island without needing every device adjacent to a generator.

#### Power Sources

| Generator            | How It Works                                                             |
| -------------------- | ------------------------------------------------------------------------ |
| Combustion Generator | Burns fuel (coal, charcoal, wood)                                        |
| Solar Panel          | Generates power from sunlight — output drops with dust buildup over time |
| Moonlight Panel      | Generates power at night                                                 |
| Wind Turbine         | Generates power passively from wind                                      |
| Geothermal Generator | Generates power from heat deep underground                               |
| Tidal Generator      | Generates power from running water                                       |
| Crank Generator      | Manually powered — very early game                                       |
| Steam Engine         | Requires a Boiler and water to produce steam power                       |

> 💡 Solar Panels degrade over time as dust builds up on them. Right-click a panel to clean it and restore full output. For reliable early power, a Combustion Generator burning charcoal is more consistent.

***

### Devices

Devices are the machines that automate tasks on your island. Place them, connect them to power, and they get to work.

#### Item Movement

| Device               | What It Does                                                                                       |
| -------------------- | -------------------------------------------------------------------------------------------------- |
| Mover                | Moves items between chests, furnaces, crafters, and other containers — the backbone of any factory |
| Transport Belt       | Carries items along a path on the ground                                                           |
| Fast Transport Belt  | A faster version of the Transport Belt                                                             |
| Turbo Transport Belt | The fastest belt tier                                                                              |
| Splitter             | Splits items from one belt onto two paths                                                          |
| Item Teleporter      | Teleports items between two points instantly                                                       |

> 💡 Movers are directional. Right-click a Mover to set which side pulls items in and which side pushes them out. If a Mover is not moving anything, check that its input and output faces are pointed at the right containers.

#### Farming & Gathering

| Device         | What It Does                                                                     |
| -------------- | -------------------------------------------------------------------------------- |
| Auto Harvester | Harvests crops automatically — requires a hoe                                    |
| Auto Planter   | Plants crops automatically — requires seeds                                      |
| Auto Logger    | Chops trees automatically — requires an axe                                      |
| Auto Shearer   | Shears nearby sheep automatically — requires shears                              |
| Auto Milker    | Milks nearby cows automatically — requires buckets                               |
| Auto Collector | Picks up item drops off the ground                                               |
| Auto Breeder   | Breeds nearby animals automatically                                              |
| Auto Butcher   | Kills animals once the herd reaches a set size                                   |
| Auto Plucker   | Collects feathers from chickens                                                  |
| Auto Cauldron  | Empties cauldrons filled by dripstones using buckets — great for automating lava |
| Auto Miner     | Generates ores over time — does not break blocks on your island                  |
| Auto Logger    | Chops trees using axes                                                           |

#### Crafting & Processing

| Device             | What It Does                                                                  |
| ------------------ | ----------------------------------------------------------------------------- |
| Crafter            | Automatically crafts any vanilla recipe using items fed into it               |
| Crude Assembler    | Crafts basic factory components                                               |
| Basic Assembler    | Crafts a wider range of factory items                                         |
| Advanced Assembler | Crafts the most complex factory components                                    |
| Crusher            | Processes raw materials into new forms                                        |
| Sifter             | Sifts materials to extract resources                                          |
| Recycler           | Breaks factory items back into their base components                          |
| Infuser            | Combines items using special processes                                        |
| Electric Furnace   | Smelts items using grid power instead of fuel — faster than a vanilla furnace |
| Incinerator        | Destroys unwanted items                                                       |

#### Power & Storage

| Device                    | What It Does                                               |
| ------------------------- | ---------------------------------------------------------- |
| Battery                   | Stores power on the grid                                   |
| Power Pylon               | Relays power across longer distances                       |
| Power Pylon Mk2           | Extended range pylon                                       |
| Power Substation          | Bridges separate power grids together                      |
| Power Provider / Receiver | Shares surplus power between grids                         |
| Power Meter               | Displays current power production and consumption          |
| Battery Monitor           | Shows current battery charge level                         |
| Power Breaker             | Acts as a switch to cut power to part of a grid            |
| Crate Manager             | Compresses stacks of items into crates for compact storage |

#### Defense

| Device              | What It Does                                           |
| ------------------- | ------------------------------------------------------ |
| Bow Turret          | Fires arrows at nearby hostile mobs                    |
| Advanced Bow Turret | An upgraded bow turret with better range and fire rate |
| Laser Turret        | Fires a laser at nearby enemies                        |
| SAM Site            | Anti-air missile defense                               |
| Turret Controller   | Coordinates groups of turrets                          |

#### Utility

| Device             | What It Does                                                                      |
| ------------------ | --------------------------------------------------------------------------------- |
| Research Lab       | Used to research technologies in the tech tree                                    |
| Production Monitor | Tracks how much a device has produced over time                                   |
| Redstone Emitter   | Emits a redstone signal based on conditions                                       |
| Auto Timer         | Triggers events on a timed interval                                               |
| Overdriver         | Speeds up adjacent devices at the cost of extra power                             |
| Flood Light        | Lights up a large area                                                            |
| Billboard          | Displays custom text above it                                                     |
| Trade Beacon       | A trading post that accepts specific items in exchange for others                 |
| Chunk Loader       | Keeps a chunk loaded so your factory runs while you are away                      |
| Elevator           | Lets you move between floors instantly by looking up or down while standing on it |
| Blueprinter        | Copies and pastes device layouts                                                  |

***

### Building an Auto Smelter

A simple auto smelter moves raw ore in, smelts it, and moves ingots out — all automatically.

**What you need:**

* 2x Mover
* 1x Vanilla Furnace
* 2x Chest (input and output)
* Fuel in the furnace (or a third Mover + fuel chest)
* Wire Tool + a generator

**Setup:**

1. Place your input chest, furnace, and output chest
2. Place **Mover #1** between the input chest and the furnace — set its input to face the chest and output to face the top of the furnace (ingredient slot)
3. Place **Mover #2** between the furnace and the output chest — set its input to face the side of the furnace (output slot) and output to face the chest
4. Connect both Movers to your power grid
5. Add fuel to the furnace's bottom slot manually, or add a third Mover pulling from a fuel chest into the furnace's fuel slot for a fully hands-free setup

***

### Technology Tree

The factory system has a technology tree that gates access to more advanced devices. Research is done at a **Research Lab** and requires Science Packs — factory items you craft and feed into the lab.

As you unlock more tech, new devices and crafting options become available. Progress your way up the tree to unlock the full factory experience.

Science Packs unlock in roughly this order:

* Automation Science Pack - Basic tech
* Logistic Science Pack - Logistics and transport
* Military Science Pack - Defense devices
* Chemical Science Pack - Advanced processing
* Production Science Pack - High-end factory components
* Utility Science Pack - End-game utility devices

***

### Commands

✅ `/factory` - Opens the factory menu to browse and obtain devices

> 💡 Most factory interaction happens by right-clicking devices in the world, not through commands. The `/factory` menu is mainly for getting devices and managing settings.

***

### Tips and Good to Know

⭐ Movers are the most versatile device in the system — almost every automated production line is built around them. Get comfortable with how they work early.\
⭐ Right-clicking any device opens its settings. Most devices have filters, speed options, and other configurable settings in their GUI.\
⭐ Devices only run when powered. If something stops working, check the power grid first — a missing wire connection is usually the cause.\
⭐ Solar Panels are easy early power but need regular cleaning as dust builds up and reduces output. Keep a combustion generator as a backup.\
⭐ Use **Overdrivers** next to devices you want running faster — they consume more power but significantly speed up output.\
⭐ The **Production Monitor** is great for tracking which parts of your factory are bottlenecking. Place one on your key machines to see throughput in real time.\
⭐ **Chunk Loaders** keep your island's factory running even when you are offline — place one near your main production area so your machines do not pause the moment you log off.
