# War

**For reference on how the wars operate, please look at this link below.**

[Towny Event War](https://townyadvanced.github.io/eventwar.html)

This page assumes you have read and understand the contents of link above.


Mvndicraft currently only has 4 of the 5 wartypes in Event War as currently the "World War" type is under development.

## Obtaining Tokens
One token is added to each town and nation, once every Towny Day. (24 hours)

## Declaring War
In order to declare war you must redeem a War Declaration using your war tokens.

Using these commands you can redeem tokens for your town/nation.

> /t redeem token <war_type></br>
> /n redeem token <war_type>

### Valid War Types
- riot
- townwar
- civilwar
- nationwar

### Declaration Permissions
- Residents are allowed to declare riots.
- Mayors are allowed to declare town and civil wars.
- Kings are allowed to declare nation wars.

## General Settings
- Block HP: ON
	- TownBlock HP: 18
	- HomeBlock HP: 36
		- Block HP will tick once every 5 seconds when considered active.
- Mayor/King Death: OFF
- Startup Delay: 0
- Points Per Kill: 5
- Fire Spread: ON
- Explosions: ON
- Economy: ON
	- Death Cost: $50
	- TownBlock Loss Cost: $100
	- If a town runs out of money during a war, they are removed from the war.
- Points
	- TownBlock: 10 (Awarded when a townblock is won)
	- Town: 20 (Awarded when a town is knocked out of a war)
	- Nation 100 (Awarded when a nation is knocked out of a war)

## War Type Specific Settings
### Riot
- Token cost: 3
- Minimum Required Players: 3
- Base Spoils: $10
- Cooldown Time: 5 days 
- Resident Lives: 3
- Mayor Lives: 2
- Switch Use: NO
- Item Use: NO
- Winner Takes Over Town: YES
### Town 
- Token Cost: 1
- Minimum Required Players: 3
- Base Spoils: $100
- Cooldown Time: 1 day
- Resident Lives: 3
- Mayor Lives: 2
- Switch Use: YES
- Item Use: NO
- Winner Takes Over Town: NO
### Civil 
- Token Cost: 4
- Minimum Required Players: 4
- Base Spoils: $500
- Cooldown Time: 4 days
- Resident Lives: 6
- Mayor Lives: 4
- Switch Use: NO
- Item Use: NO
- Winner Takes Over Nation: YES
### Nation
- Token Cost: 2
- Minimum Required Players: 6
- Base Spoils: $1000
- Cooldown Time: 2 days
- Resident Lives: 9
- Mayor Lives: 6
- Switch Use: NO
- Item Use: NO
- Winner Conquers Towns: YES

