This repo is a collection of scripts written in the Skript language that provide useful functions for a survival minecraft server.
The plugins included are required for many of the scripts to function.



Plugin functionality:
  Viaversion/ViaBackwards - gives crossversion compatability, allowing clients to connect to a modern server with a outdated client.
  Skript(and plugins) - provides a powerfull scripting language that is used to create most of the functions in this repo.



Scripts:

  Remote - allows remote updating of scripts from this repo, and moderator file manipulation when granted permissions.
  
  Survival_Utils - provides many features including:
    * Death Coords - sends death coords to a player that died.
    * AFK display - greys out a players name when motionless for a specified period of time.
    * Co-ordinate command - /coords sends the player their current coords.
    * Nether calculator - /nether <x> <y> <z> sends the player the equivelent coordinates in the nether. Good for easy portal calculation.
  
  Chatmanager - allows chat colors via /chatcolor and parses {xyz} as player coordinates. 
  
  Deathmessages - includes some custom death messages to spice things up.
  
  Single_sleep - a simple singleplayer sleep module.
  
  

* Using the command "/skload <script name>" in game or via console will update the specified script with the most recent one from this repo. may need to reload script manualy to take effect("/sk reload <script name>")

