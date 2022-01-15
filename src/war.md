# War

War works with nations sieging down towns. Only nations can go to war.

To declare war on someone first your nation must enemy them with `/n enemy add <NationName>`
Go to one of their towns you want to siege and place a non-white banner close to the wilderness in the town. This will start a siege. 
  - Dead players keep their level and inventory, but their weapon/armour/tool durability is degraded by 20%.
  - The defending town cannot recruit new residents, claim/unclaim land, or move it's homeblock.
  - Each nation can only have 3 sieges going on at once.

Only while a battle session is active can Battle Points be earned
  - Battle Sessions start on weekdays at 19:10 and 21:10 UTC.
  - Battle Sessions start on weekends at 12:10, 14:10, 16:10, 18:10, and 20:10 UTC.
  - Battle Sessions last 50 minutes.
  - Whenever a siege participant of military rank dies in the Siege-Zone (regardless of cause), 150 battle points are awarded to the opposing side.

Banner Control
  - The Timed-Point-Zone is a 16 block radius around the Siege-Banner.
  - As a siege participant of military rank, move into the Timed-Point-Zone. A Banner Control Session will start
  - If an enemy player enters the Timed-Point-Zone while you are in a Banner Control Session, you will glow.
  - If you remain alive and still within the Timed-Point-Zone, for 7 minutes, you will gain Banner Control for your side, or be added to the Banner Control List.
  - Your team will automatically gets 30 Battle Points every minute for each player on the Banner Control List.
  - If a team steals battle control from the opposing team, the stealing team get an instant Banner Control Reversal Bonus, equal to twice the number battle points the enemy earned from capping the banner
  - Allied nations can fully contribute to each other's banner control.

Anyone without a millitary rank from the warring nations will get poison effect if they enter the banner zone. Give millitary ranks to people with `/n rank add <name> <rank>`.
Millitary Ranks
- private
- sergeant
- lietenant
- captain
- major
- colonel
- general

Private rank gets $100 of plunder and for each rank it goes up by $50 except major->colonel->general it goes up by $100.

Win Battle
  - Be the team with the highest Battle Points when the current battle session ends.
  - The winner gets their Battle Points applied to the Siege Balance (added for attacker; subtracted for defender), the loser's Battle Points are lost.

Win Siege
  - Each siege lasts a maximum of 3 days, but this duration can be cut short if the attacker abandons, or the defender surrenders.
  - When the siege ends, if the Siege Balance is greater than zero, the attacker wins, if the Siege Balance is zero or less, the defender wins.
  - After the siege ends, the besieged town receives Siege Immunity, for x3 times the duration of the siege which protects the town from further attacks.
  - After the siege ends, the besieged town also receives Revolt Immunity for 75% the duration of the Siege Immunity which stops the town from revolting

Plunder Town
  - This option is available to victorious nations
  To execute this action, as king or general, place a chest in the wilderness close to the town.
    - This action will rob the town of $40/plot:
    - The plunder is divided between the bank of the victorious nation, and the soldiers who contributed to the victory, at a ratio of 3:1.
    - Soldiers contributions are measured by banner control: a soldier receives exactly one share if they gain banner control at least once during a battle.
  - A plundered town cannot fall due to the money loss (it can only go 'bankrupt', preserving the town completely but blocking building/claiming/recruitment).

Invade Town
  - This option is available to victorious attacking nations.
  - To execute this action, as a king/general, place a non-white banner in the wilderness close to the town:
    - This action will invade the town, setting the victorious nation to be its occupier.
  - The occupied town remains a full part of the home nation, with the exception of the following areas, where it is counted as part of the occupying nation:
    - 50% of Town Resources.
    - Bonus plots contributions.
    - Dynmap town colour.
    - Guardian town effects.
  -  Occupied towns can free themselves from occupation if they win a Revolt Siege. A Revolt Siege starts when the mayor places a non-white banner outside the town.
  - The occupying nation can attempt to stamp out rebellion via a Suppression siege. A Suppression SIege starts when the occupier places a non-white banner outside the town.

Abandon Attack
  - As a siege attacker (king/general/mayor, depending on siege type), place an all-white banner in the wilderness close to the town.

Surrender Town
  - As a siege defender (king/general/mayor, depending on siege type), place an all-white banner in the wilderness close the the town.

For more in depth documentation read the [Siege War Guide](https://github.com/TownyAdvanced/SiegeWar/wiki/Siege-War-User-Guide) or do `/sw guide` in game.