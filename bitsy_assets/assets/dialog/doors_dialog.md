DOORS DIALOG
============
27/01/2023_17:47:06, UGLY ARTIST GAME STUDIO

DESCRIPTION
===========

A set of re-usable asstes for [Adam Le Doux](https://twitter.com/adamledoux)'s 
[Bitsy Game Maker](https://ledoux.itch.io/bitsy) from the UGLY ARTIST 
STUDIO [Bitsy demo YouTube series](https://www.youtube.com/@uglyartistgamestudio).

CODE
====

	DLG 6
	"""
	{
  	  - {item "stick"} * {item "stone"} * {item "grass"} >= 1 ?
      	{property locked false}"You found all crafting materials to craft a STONE AXE."
  	  - else ?
    	{property locked true}"You need the crafting materials: STICK, STONE and GRASS to craft a STONE AXE."
	}
	"""
	NAME crafting_table_exit_1

	DLG 0
	YOU: "X&%$! I forgot my keys!"
	NAME forgot_keys_dialog

	DLG d
	"""
	{
  	  - {item "pfandglas"} >= 3 ?
    	{property locked false}FRITZ: "Thx for the 
    	{rbw}Pfandflaschen(TM){/rbw} have fun on Bell Heach, harr, 
    	harr, harr!"
  	  - else ?
    	{property locked true}FRITZ: This is the way to Bell 
    	Heach, but I can't you let in. v.i.p., you know. But if 
    	you bring me 6 {rbw}Pfandflaschen(TM){/rbw} I make you a 
    	new deal.
	}
	"""
	NAME pfandflaschen_door_dialog

	DLG 8
	"""
	{
  	  - {item "old_short_sword"} * {item "rusted_piss_pott"} * {item "broken_toilet_door"} >= 1 ?
    	{property locked false}you found all items and get out the tutorial jail. now, start your adventure.
  	  - else ?
     	{property locked true}equip your shit and THEN get out the tutorial jail. 
	}
	"""
	NAME locked_exit_1

UGLY LICENSE 2023
================= 

Free version
------------

* You can only use these assets in non-commercial projects.
* You can only use the unmodified assets.
* You can not redistribute or resale the assets, even if modified.

Paid version
------------

* You can use these assets in commercial projects.
* You can modify the assets.
* You can not redistribute or resale  the assets, even if modified.

Credit is appreciated but not required.

CONTACT
=======

* UGLY ARTIST GAME STUDIO
* [itch.io](https://ugly-artist-studio.itch.io) 
* [youtube.com](https://www.youtube.com/@uglyartistgamestudio)
* [github.com](https://github.com/uglyartistgamestudio)
