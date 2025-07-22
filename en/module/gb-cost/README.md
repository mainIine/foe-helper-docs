--- 
description: GB Cost Calculator 
---

# GB Cost Calculator

![Icon](https://github.com/user-attachments/assets/f914ee3f-69a7-4d8a-9e03-dad21405413a)

If you want to help others level their Great Buildings — whether voluntarily or by accident — this tool is essential.  
It calculates all relevant values for you and can be customized to your needs.

## Layout

![Layout](https://github.com/user-attachments/assets/0a3422b5-d5fb-427d-aba6-ae94b4ea84ee)


The Cost Calculator interface is structured from top to bottom as follows:

- **Building name**
- **Owner information**, including a link to the player’s [foe.scoredb.io](https://foe.scoredb.io/) profile
- **Owner's guild**
- **Current level** of the building and its maximum level
- **Arc Bonus** – your current Arc bonus (e.g., 100%)
- Buttons to switch between predefined investment percentages
- **Investing at:** – set a custom percentage manually
- **Table columns:**
  - Supporter place number (P1–P5)
  - Required FP investment per spot (based on the chosen percentage)
  - FP difference (how much is profit or overpaid based on your Arc bonus)
  - Blueprints earned (based on Arc bonus)
  - Medals earned (based on Arc bonus)

Additional info:
- **Remaining FPs to level:** FPs still needed to reach the next level
- **Active recurring quest:** shows if a recurring quest has been completed

## Configuration

Click the **gear icon** in the title bar to open the Configuration menu.

![Configuration](https://github.com/user-attachments/assets/2e068b61-d4d5-4278-b995-d3d6c0332e33)

The Configuration interface is structured top-to-bottom as follows:
- **Percentage Buttons** - A series of pre-set contribution percentages (e.g. 90%, 91%, 100%, etc.) used for GB reward calculations.

{% hint style="info" %}
Each button has an X to remove it, except your Arc bonus %. 
{% endhint %}

- **New Value** - Allows you to input a custom percentage manually. The green “+” button adds your custom percentage to the list above.
- **Save donation factor per Conversation** - When enabled, your default investment % factor is defined by % you used last time in that conversation (thread).
- **Save Button** - Applies and saves all the above settings.

## Usage

The FP values in the supporter table are color-coded to show whether a spot is safe to invest in:

### Green = Safe Contribution Spot

If the spot is secure and cannot be overtaken after your investment, the row is highlighted in green.

![Safe spot](https://github.com/user-attachments/assets/7a2e29a2-3b1c-4ee0-9bd5-958c083cdf93)

### Red = Not Secured Contribution Spot

If the spot is still vulnerable and can be overtaken, the row turns red and shows (in red text eg.+123) how many FPs are missing to secure it.

![Not secure spot](https://github.com/user-attachments/assets/81cc5723-5076-4600-8dbb-b7e125480bc2)


### Blue = Already Invested

If you’ve already contributed exactly the calculated amount, the row turns blue.  
It will remain blue the next time you open the building, provided your investment is recognized.

![Already Invested](https://github.com/user-attachments/assets/bb322f55-20a5-42c1-8244-7785f2d609d6)

If your contribution differs from the calculated value, the row is highlighted blue with numbers shown in red: [invested FP] / [expected FP].
(eg. chosen investment 100% which is 30 FPs, invested 29 FPs, showing 29/30)

![Partial investment](https://github.com/user-attachments/assets/e850950a-84ac-41b8-8750-cb7798ef64de)

### Gray = Unavailable Spots

If there are no donor spots available, all rows are displayed in gray.

![Unavailable Spots](https://github.com/user-attachments/assets/6b56f28d-bb1d-40b9-9ca1-b4e828e27560)

### Shaded = GB Level locked

If the building’s next level is locked, donor spots are unavailable.

![Locked Level](https://github.com/user-attachments/assets/9a7881b8-a27a-4766-8127-b2d22271bebe)

### Shaded = GB not connected to road

If the building is not connected to the road, donor spots are unavailable.

![Not connected to road](https://github.com/user-attachments/assets/67534165-b518-4bc2-ad0f-e293235303fb)
