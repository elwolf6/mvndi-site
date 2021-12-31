# Towny Resources

Town production information is shown on the town screen `/t`.

Surveys
  - Before resources can be be produced by a town, they must first be discovered.
  - Resources can only be discovered by doing Surveys.
  - Each Survey discovers a resource of a new level and type
    - Survey 1: Reveals Level 1 Resource. Cost 250. Minimum num townblocks 10.
    - Survey 2: Reveals Level 2 Resource. Cost 1000. Minimum num townblocks 50.
    - Survey 3: Reveals Level 3 Resource. Cost 5000. Minumum num townblocks 100.
    - Survey 4: Reveals Level 4 Resource. Cost 20000. Minimum num townblocks 200.
  - To do a Survey, enter the target town and run `/tr survey`.
  - If the Survey succeeds, a global success message will be generated.

Daily Production
  - On each new Towny New Day, towns automatically produce resources.
  - Production is modified by the resource level
    - Resource Level 1: Production bonus N/A. Minimum town level 2.
    - Resource Level 2: Production bonus +100%. Minimum town level 4
    - Resource Level 3: Production bonus +200%. Minimum town level 6
    - Resource Level 4: Production bonus +300%. Minimum town level 8
  - After resources are produced, they are shown as available for collection on the town screen `/t`.
  - If a town is not high enough level to produce a resource, the amount shows as zero.
  - For each resource, a town can store a maximum of 5x the production amount. When stores are full, subsequent production is lost.
  - Collecting Town Resources
    - To collect town resources, as a mayor/assistant/treasurer, enter your town and run `/tr towncollect`.
    - The available resources will then be dropped at your position.

Nation Production
  - Nation production & collection information is shown on the nation screen `/n`.
  - If a town belongs to, or is occupied by, a nation, then 50% of the town production is diverted to the nation.
  - To collect nation resources, as a king/assistant/treasurer, enter your capital and run /tr nationcollect
  - The available resources will then be dropped at your position.

Daily Extraction Limits
  - Extraction is limited per resource category.
  - Example: The resource category of "Common Rocks" contains both STONE and COBBLESTONE. Extracting either of those items counts towards the daily limit.
  - Extraction is limited per Towny day.
  - The daily extraction limits of all players are reset at Towny New Day.
  - When a player hits their daily extraction limit for a particular category of material, they will see an information bar message.

You can send a message only to players in your lands using /tc.
Switch back to global chat with /g.
For more in depth documentation read the [Towny Guide](https://github.com/TownyAdvanced/Towny/wiki/How-Towny-Works) or watch these [Tutorials](https://www.youtube.com/playlist?list=PLvzvmyk0uI0WsLf4iyJZRhD_T2e-ANCmE).