# Shadow-Man-Remastered-Console-Commands

stat
	stat shadowman.player - list player info
	stat shadowman.ai - list AI information

freecam - allows you to fly around with a free camera that isn't attached to the player

god - makes the player invincible so their health cannot go down

demigod - makes the player invincible so their health can go down but cannot reach 0

infiniteammo - toggles infinite ammo on or off

givehealth - fully heals the player

givedarksoul <soul level between 0 and 10> - sets your dark soul level to the amount specified

freezegamelogic - freezes the game's logic

givetedpoints - unlocks all teddy warps

giveinv - gives the player the specified item
	giveinv -1 - gives the player all items
	giveinv 1 - gives the player an Accumulator
	giveinv 2 - gives the player the Asson
	giveinv 3 - gives the player the Baton
	giveinv 4 - gives the player the Book of Shadows
	giveinv 5 - gives the player a Cadeaux
	giveinv 6 - gives the player the Calabash
	giveinv 7 - gives the player the Handgun
	giveinv 8 - ???
	giveinv 9 - gives the player the Engineer's Key
	giveinv 10 - gives the player the Enseigne
	giveinv 11 - gives the player the Flambeau
	giveinv 12 - gives the player the 0.9-SMG
	giveinv 13 - gives the player the MP909
	giveinv 14 - gives the player the Flashlight
	giveinv 15 - ???
	giveinv 16 - gives the player the L'Eclipser: La Lune
	giveinv 17 - gives the player the L'Eclipser: La Lame
	giveinv 18 - gives the player the Marteau
	giveinv 19 - ???
	giveinv 20 - gives the player a Prism
	giveinv 21 - gives the player the Key Card
	giveinv 22 - gives the player The Prophecy
	giveinv 23 - gives the player a Retractor
	giveinv 24 - gives the player Jack's Journal
	giveinv 25 - gives the player the Handgun
	giveinv 26 - gives the player the Shotgun
	giveinv 27 - ???
	giveinv 28 - gives the player the L'Eclipser: Le Soleil
	giveinv 29 - gives the player the Teddy Bear
	giveinv 30 - gives the player the Violator (and the second violator if you type it again)
	

inventory

givevoodoo <amount between 0 and 100> - sets the player's voodoo power (orange bar) to the specified amount

givecadeaux <amount between -666 and 666> - gives the player the specified amount of cadeaux

giveammo9mm <amount between -100 and 100> - guves the player the specified amount of 9mm ammo

giveammoshotgun <amount between -12 and 12> - guves the player the specified amount of shotgun ammo

giveammoviolator <amount between -250 and 250> - guves the player the specified amount of violator ammo

spawnobj

playspeech

testcutscene

givegad
	givegad 0 - removes all gads
	givegad 1 - 
	givegad 2 - 
	givegad 3 - 
	givegad 4 - gives the player poigne and gad 1
	givegad 5 - gives the player poigne and gad 2
	givegad 6 - gives the player poigne and gad 3
	givegad 7 - gives the player poigne and gad 4

setpos <sector> <x> <y> <z> - sets the players position

jumpsector <increment number, either -1 or 1> - teleports the player to another sector

# CVARS

con_showfps <0 or 1> - shows your FPS in the top right

g_freezeai <0 or 1> - freezes AI in place

r_hideaimeshes <0 or 1> - makes AI meshes invisible (doesn't affect projectiles)

r_showaievents <0 or 1> - display AI events

r_showAIPath <0 or 1> - display AI path network

r_hidetransparentsurfaces <0 or 1> - hide translucent surfaces

r_showobjectbounds <0 or 1> - display object bounding boxes

r_showobjectorigins <0 or 1> - display object origins

r_showdetectboxes <0 or 1> - display detect boxes

r_showspecialtriggers <0 or 1> - display special trigger boxes

r_showleafs <0 or 1> - display leafs (not sure what these are but it appears to be some kind of level geometry)

r_showcollisionballs <0 or 1> - display object collision balls

g_wireframemode <0 or 1> - shows the world as a wireframe which allows you to see through walls and see what areas and enemies are currently loaded