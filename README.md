# Shadow-Man-Remastered-Console-Commands

stat
<ul>
	<li>stat shadowman.player - list player info</li>
	<li>stat shadowman.ai - list AI information</li>
</ul>

freecam - allows you to fly around with a free camera that isn't attached to the player

god - makes the player invincible so their health cannot go down

demigod - makes the player invincible so their health can go down but cannot reach 0

infiniteammo - toggles infinite ammo on or off

givehealth - fully heals the player

givedarksoul <soul level between 0 and 10> - sets your dark soul level to the amount specified

freezegamelogic - freezes the game's logic

givetedpoints - unlocks all teddy warps

giveinv - gives the player the specified item
<ul>
	<li>giveinv -1 - gives the player all items</li>
	<li>giveinv 1 - gives the player an Accumulator</li>
	<li>giveinv 2 - gives the player the Asson</li>
	<li>giveinv 3 - gives the player the Baton</li>
	<li>giveinv 4 - gives the player the Book of Shadows</li>
	<li>giveinv 5 - gives the player a Cadeaux</li>
	<li>giveinv 6 - gives the player the Calabash</li>
	<li>giveinv 7 - gives the player the Handgun</li>
	<li>giveinv 8 - ???</li>
	<li>giveinv 9 - gives the player the Engineer's Key</li>
	<li>giveinv 10 - gives the player the Enseigne</li>
	<li>giveinv 11 - gives the player the Flambeau</li>
	<li>giveinv 12 - gives the player the 0.9-SMG</li>
	<li>giveinv 13 - gives the player the MP909</li>
	<li>giveinv 14 - gives the player the Flashlight</li>
	<li>giveinv 15 - ???</li>
	<li>giveinv 16 - gives the player the L'Eclipser: La Lune</li>
	<li>giveinv 17 - gives the player the L'Eclipser: La Lame</li>
	<li>giveinv 18 - gives the player the Marteau</li>
	<li>giveinv 19 - ???</li>
	<li>giveinv 20 - gives the player a Prism</li>
	<li>giveinv 21 - gives the player the Key Card</li>
	<li>giveinv 22 - gives the player The Prophecy</li>
	<li>giveinv 23 - gives the player a Retractor</li>
	<li>giveinv 24 - gives the player Jack's Journal</li>
	<li>giveinv 25 - gives the player the Handgun</li>
	<li>giveinv 26 - gives the player the Shotgun</li>
	<li>giveinv 27 - ???</li>
	<li>giveinv 28 - gives the player the L'Eclipser: Le Soleil</li>
	<li>giveinv 29 - gives the player the Teddy Bear</li>
	<li>giveinv 30 - gives the player the Violator (and the second violator if you type it again)</li>
</ul>
	

inventory

givevoodoo <amount between 0 and 100> - sets the player's voodoo power (orange bar) to the specified amount

givecadeaux <amount between -666 and 666> - gives the player the specified amount of cadeaux

giveammo9mm <amount between -100 and 100> - gives the player the specified amount of 9mm ammo

giveammoshotgun <amount between -12 and 12> - gives the player the specified amount of shotgun ammo

giveammoviolator <amount between -250 and 250> - gives the player the specified amount of violator ammo

spawnobj

playspeech

testcutscene

givegad
<ul>
	<li>givegad 0 - removes all gads</li>
	<li>givegad 1 - </li>
	<li>givegad 2 - </li>
	<li>givegad 3 - </li>
	<li>givegad 4 - gives the player poigne and gad 1</li>
	<li>givegad 5 - gives the player poigne and gad 2</li>
	<li>givegad 6 - gives the player poigne and gad 3</li>
	<li>givegad 7 - gives the player poigne and gad 4</li>
</ul>

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