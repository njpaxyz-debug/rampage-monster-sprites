# In-Game Economy System Documentation

## Currency Flows
- **Description:** This section outlines how currency is generated, distributed, and spent within the game.
- **Key Flows:**
  - **Earning Currency:** Players earn currency through various means such as completing quests, defeating monsters, and selling items.
  - **Spending Currency:** Currency can be spent on upgrading equipment, purchasing resources, or accessing premium features.

## Resource Scaling
- **Description:** Resource scaling refers to how the availability and cost of resources changes as players progress through the game.
- **Scaling Mechanics:**
  - **Initial Costs:** Costs for resources are lower at the beginning of the game.
  - **Incremental Increases:** Resource costs increase based on player level or game progression.

## Prestige Mechanics
- **Description:** Prestige mechanics allow players to reset their progress for greater rewards.
- **Prestige Levels:**
  - Players can reach prestige levels that unlock new abilities and bonuses.
  - Example Formula: `Prestige Bonus = Base Bonus * (1 + Prestige Level * Scaling Factor)`

## Season Pass Structure
- **Description:** The season pass provides players with additional rewards for completing challenges during the season.
- **Components:**
  - **Free Track:** Available to all players with basic rewards.
  - **Premium Track:** Requires purchase and offers exclusive rewards.

## Balance Targets
- **Description:** Balance targets ensure that the game remains fair and engaging for all players.
- **Metrics:**
  - **Player Engagement:** Measure time spent in-game vs. rewards earned.
  - **Economic Flow:** Analyze inflow and outflow of currency.

## Detailed Formulas
- **Currency Generation:** `Currency Generated = Base Rate + (Player Level * Level Multiplier)`
- **Resource Acquisition Rate:** `Acquisition Rate = Base Rate * (1 + (Resource Upgrade Level * Upgrade Multiplier))`
- **Cost Increase Formula:** `Next Cost = Current Cost * (1 + Growth Rate)`

---

This document serves as a comprehensive guide to understanding the economy system within the game.