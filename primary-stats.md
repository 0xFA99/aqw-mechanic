
# Primary Stats
**Primary Stats** are the fundamental attributes that define a character's abilities and effectiveness in various aspects of AQW gameplay. There stats, such as Strength, Intelligence, Endurance, Dexterity, Wisdom and Luck are crucial for determining a character's performance in combat, defence and other key areas.
- **Strength**: Grants Attack Power to all classes, and additionally extra Critical Chance to melee classes.
- **Intellect**: Provides Spell Power and Magical Resistance to all classes, and additionally extra Damage and Cooldown Reduction for caster classes.
- **Endurance**: Increases the Max Health of all classes.
- **Dexterity**: Grants extra Hit Chance and Dodge Chance to melee classes.
- **Wisdom**: Provides Dodge Chance to all classes, and additionally extra Hit Chance and Critical Chance to caster classes.
- **Luck**: Increases Critical Chance and Critical Damage, and additionally provides small improvements to all classes’ favored stats.

Each class in the game has a specific distribution of these primary stats based on their role and playstyle. Understanding how these stats are allocated and how they interact can help players optimize their characters for the best performance in their chosen roles.

## Base Class
Each class comes with a unique set of base stats that define its core strengths and how those stats convert into combat effectiveness. These **Base Class Stats** are designed with specific roles in mind, so while all classes follow a similar structure, they are not created equal.

## Formula for Total Class Base

The **Total Class Base** is calculated using the following formula:
```
15 + ((current level - 1) / (max level - 1)) x 747
```
Once the **Total Class Base** is determined, it is distributed across the character's Primary Stats based on the class type.

## Percentage of Class Models
Each class has its own unique distribution of stats such as Strength (STR), Intelligence (INT), Endurance (END), Dexterity (DEX), Wisdom (WIS) and Luck (LUK). There distributions are expressed as percentages of the total base, as shown in the table below:

| Category | STR | INT | END | DEX | WIS | LUK |
|----------|-----|-----|-----|-----|-----|-----|
| Tank Melee | 0.27 | 0.05 | 0.30 | 0.22 | 0.10 | 0.06 |
| Dodge Melee | 0.20 | 0.05 | 0.22 | 0.33 | 0.10 | 0.10 |
| Hybrid Melee | 0.24 | 0.24 | 0.20 | 0.20 | 0.07 | 0.05 |
| Power Melee | 0.30 | 0.02 | 0.18 | 0.30 | 0.06 | 0.14 |
| Offensive Caster | 0.06 | 0.33 | 0.20 | 0.11 | 0.15 | 0.15 |
| Defensive Caster | 0.08 | 0.30 | 0.27 | 0.10 | 0.10 | 0.15 |
| Power Caster | 0.06 | 0.28 | 0.23 | 0.05 | 0.28 | 0.10 |
| Luck Hybrid | 0.22 | 0.08 | 0.18 | 0.21 | 0.08 | 0.23 |

## Example
We'll calculate the total class base for a **Level 50** with **Warrior Class (Tank Melee)** and demonstrate how the base stats are allocated to the Primary Stat.

**Step 1: Calculate the Total Class Base**

We use the following formula to calculate the total class base.
```
15 = ((50 - 1) / (100 - 1)) x 747 = 384.727 = 385
```
**Step 2: Allocate to Primary Stats Attributes**

To calculate each stat's allocation, multiply the total base value (385) by the percentage assigned to each stat. Then round the nearest whole number. 
```
STR: 385 x 0.27 = 103.95 = 104
INT: 385 x 0.05 = 19.250 = 19
END: 385 x 0.30 = 115.50 = 116
DEX: 385 x 0.22 = 84.700 = 85
WIS: 385 x 0.10 = 38.500 = 39
LUK: 385 x 0.06 = 23.100 = 23
```

**Final Primary Stats for a Level 50 with Warrior Class**:
- Strength: 104
- Intellect: 19
- Endurance: 116
- Dexterity: 85
- Wisdom: 39
- Luck: 23

This method ensures that the stats are scaled proportionally to the warrior's level and the role of each primary stat.
