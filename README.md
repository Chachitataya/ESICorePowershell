# ESICorePowershell
Scripting for Eve Online's ESI API, core program for webrequests and parsing results with powershell

The intention is to prototype an application that runs in Powershell. There are two main projects, with several subprojects - Automation and Interface.

===>Automation:
-Automatically reads and writes to a directory filled with several text files (in .txt. or .csv format). Down the road, this will feed to a database rather than a disjointed series of files in a directory. 
-This will automatically download price information for review - the goal is to find buy/sell arbitrage opportunities between regions, to find process/reprocess arbitrage opportunities within regions, and to calculate cost and profit of production on industry (starting with tier 1 production).

Region Scope: Systems of Jita, Rens, Amarr, Dodixie (Regions: The Forge, Heimatar, Domain, and Sinq Laison, respectively)
Stretch Goals: Tier 2 production, Database functionality.

===>Interface: 
-Manually gets files, takes input for item IDs and query types (e.g. Character information, market information, region information)
