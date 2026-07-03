# Spam Key Mod

A lightweight Quality of Life mod that automates repetitive actions in Valheim.

It **doesn't** modify skill gain, bypass game mechanics, or provide unfair advantages. Instead, it repeatedly performs selected inputs for you, making repetitive gameplay less tedious and allowing you to step away from your keyboard when appropriate.

Perfect for AFK-friendly skill training and servers with local character progression.

---

# Features

### Fully configurable hotkey

Configure a toggle key in the **F1 Configuration Manager**.

**Default:** `Mouse3 (Back)`

Switch automation on or off instantly, or change modes with **Shift + Mouse3** without opening the configuration menu.

---

### Adjustable repeat interval

Set the delay between repeated actions.

**Default:** `0.1 seconds`

---

### Supported automation modes

* Attack
* Block
* Interact
* Sprint
* Jump
* Sneak
* Fishing
* Swimming
* Cultivator / Hammer
* Bow
* Eitr Magic

---

### On-screen indicator

A small status indicator appears in the upper-left corner whenever automation is enabled.

---

# Automation Modes

## Attack

Continuously performs the primary attack.

Perfect for AFK skill training or repetitive combat actions.

---

## Block

Repeatedly taps the block button, making parries much easier.

Need to hold block continuously instead? Enable the dedicated option under **Special Mode Settings**.

---

## Interact

Rapidly presses the **Interact** key.

Greatly speeds up filling furnaces, smelters, spinning wheels, windmills, and other crafting stations.

Uses the global spam interval.

---

## Sprint

Automatically sprints forward while managing stamina.

* Stops when stamina is depleted.
* Resumes automatically after recovering to **50%** stamina.

The same stamina management logic is shared by several other automation modes.

---

## Jump

Continuously jumps while automatically managing stamina.

---

## Sneak

Continuously moves while sneaking using the same stamina management logic as Sprint.

---

## Fishing

Automatically casts and reels in the fishing rod.

You can configure:

* Cast duration
* Casting distance

The next cast begins automatically after stamina has fully recovered.

---

## Swimming

Automatically swims forward.

If stamina drops below the configured threshold (20% by default), the character turns around and swims back toward shore.

After fully recovering stamina, swimming resumes automatically.

---

## Cultivator / Hammer

Automatically cultivates terrain or places structures.

Features:

* Automatic stamina management
* Stops when tool durability reaches **1**

---

## Bow

Optimized for Bow skill training.

Uses an emote-based animation cancel to increase firing speed.

Safety features:

* Stops automatically when durability reaches **1**

Prefer vanilla behavior?

Simply use the regular **Attack** mode instead.

---

## Eitr Magic

Continuously holds the attack button.

Primarily intended for elemental magic, such as the **Staff of Frost**.

When Eitr falls below **5**, casting pauses automatically until Eitr has recovered to **50%**.

---

# Configuration

Open the **F1** menu (requires **Jotunn** or **BepInEx Configuration Manager**) and select **Spam Key Mod**.

### 1. Key

Configure:

* Toggle key
* Spam interval

### 2. Actions

Select which automation mode should be active.

### 3. Special Mode Settings

Additional options for specific automation modes.

---

# Requirements

* [BepInEx Pack for Valheim](https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim/)
* [Jotunn](https://thunderstore.io/c/valheim/p/ValheimModding/Jotunn/)

---

# FAQ

### Does this increase skill gain?

No.

The mod does not modify experience gain or skill progression.

---

### Does it bypass game mechanics?

No.

It simply automates repeated key presses while respecting the game's normal mechanics.

---

# About

This project was built almost entirely with the help of Claude Sonnet 5 and ChatGPT.

I'm not a programmer, so while I've tested every feature extensively, there may still be undiscovered bugs.

The mod originally started as a personal project for myself and a few friends. Since I couldn't find anything similar on Thunderstore, I decided to share it with the community.


