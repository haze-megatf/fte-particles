# fte-particles
Personal repo to hold all of my FTE particles apart from any ongoing integration projects.  
FTE is an actively developed Quake 1 game engine that exposes its particle system to users via configuration files. This repo contains various configuration files and textures for different particle effects in Quake and Quake mods such as Team Fortress. These are my original works based off examples from Spike & FTE developers, Jedillama, Molgrum. The effects rely on textures from various Quake projects and open sources. Feel free to use and build upon.  

## How to:
* Top level CFGs mainly serve as a container to execute each of the individual effects, so adjust your paths accordingly in the main config.  
* Textures must be in \<quake folder\>/\<mod\>/textures/particles  
* Top level CFGs should go in \<quake folder\>/\<mod\>/  
* Suggest to put particle configs in \<quake folder\>/\<mod\>/particles/  
* Execute a top level CFG (such as hazed-particles.cfg) to use in game, or add "exec \<config name\>" to any game config that you use.  

## My To Do List:
  * Use new gas effect as a base for updating other effects (explosion, trails)  
  * Learn & implement shaders  
  * Use models as particles  
  * Use sound effects  

## Full
This is the main set of effects aka hazed-particles.cfg  

## Xmas [WIP]  
Some random Xmas themed effects, not a full set  

## Project-Q [WIP]   
An incomplete set of effects using only the Quake logo as a base texture  
[![Project Q](https://i9.ytimg.com/vi/0UW2TC452qE/mq1.jpg?sqp=CISv_oUG&rs=AOn4CLBMmzwSDCpgK61LfvRtgiuaipA3XQ)](https://youtu.be/0UW2TC452qE)
