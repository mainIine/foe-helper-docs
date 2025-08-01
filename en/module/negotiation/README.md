--- 
description: This module is designed to help you with negotiations.
---

# Negotiations Helper

![Icon](./.images/icon.png)

In many parts of the game, negotiations must be carried out — sometimes simple, sometimes complex. This module is designed to help you with them.

## Menu Overview

![Negotiation table](./.images/menu-layout.png)

The dialog provides the following information and options:

- **Save current goods?** – If enabled, the current-age goods will be prioritized for suggestions. If disabled, goods from the previous age will be tested first.
- **Save medals?** – When enabled, medals are preserved until all other goods have been tested. This is especially useful in earlier ages.
- **Chance** – Indicates the probability of completing the current round.
- **Round** – Shows how many negotiation rounds remain. If a Tavern boost is active, the assistant will recognize this and display `1/4` accordingly.
- **Preferred order** – Lists the resources available for the negotiation. You can change their order before the first round via drag & drop.

## Configuration

![Settings menu](./.images/settings-menu.png)

In the settings, you can choose whether the Negotiation Assistant should launch automatically when a negotiation starts.

## Usage

The bottom half of the dialog displays the resources the tool suggests for negotiation.  
Once you’ve selected your resource and clicked **Pay & Negotiate**, suggestions for the next round will appear:

![Negotiation table Round 2](./.images/negotiation-round-two.png)

The small circles below the suggestions show the **shortcut keys** you can use.  
For example, in the third column in the image above, it shows `3-1`:
- Press **3** to select the third negotiator.
- Press **1** to assign the sixth resource (e.g., Supplies).
- Once all offers are selected, press **Spacebar** to confirm payment.

{% hint style="warning" %}
If you manually select and pay with a resource that wasn’t suggested, you’ll get a warning. From that point, support will be disabled for the current negotiation:
{% endhint %}
![Wrong good selected](./.images/manual-negotiation.png)

## FAQ

**Q: Why doesn’t the Negotiation Assistant appear during Guild Battleground negotiations?**  
A: The assistant not only helps negotiate better, but also faster. This affects the balance of Guild Battlegrounds, so the feature was disabled there.  
It remains active in other areas like Expeditions, Quests, and Feudal Japan.
