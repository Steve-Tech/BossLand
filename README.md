# Steve's BossLand Fork
[![Java CI with Maven](https://github.com/Steve-Tech/BossLand/actions/workflows/maven.yml/badge.svg)](https://github.com/Steve-Tech/BossLand/actions/workflows/maven.yml)

Steve's Improved BossLand fork.

Original Code: https://bitbucket.org/Eliminator/bossland/
## Commands
- /bossland:
    - Alias: /bl
    - Description: Base Boss Land command.
    - Permission: bl.cmds
    - Usages:
      - /bl spawn \<boss\> \[x y z\] \[world\] 
          - Spawns a Boss
      - /bl loot \<boss\>
          - Drops a Bosses' death loot
      - /bl setLoot \<boss\> \<id\>
          - Set loot for boss
      - /bl addLoot \<boss\>
          - Add loot for boss
      - /bl killBosses \<world\>
          - Remove bosses
      - /bl reload
          - Re-loads the config