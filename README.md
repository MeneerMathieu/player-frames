# player-frames
Get Minecraft players with invisible item frames

How to download:
 1. Click on the green "Code" button.
 2. Pick "Download ZIP"
 3. Unzip the file so when you open the folder the first thing you see is the pack.mcmeta file. Place the folder into your recourses folder.
 4. Done!



How to get the items:
 - On CK (two options):
  1. Go to /p v WinnieTheDampoeh 2, you will see a whole row of item frames with the statues on them. Just middle click to grab one.
  2. Import one from singleplayer
 - On singleplayer:
  1. use "/give @s flint{CustomModelData:YOUR ID}" to get the item. 



How to add a player:
  1. Go to assets/minecraft/models/item/flint.json
  2. Add this line: { "predicate": {"custom_model_data": NUMBER}, "model": "customplayer/PLAYERNAME"}, where PLAYERNAME is your playername in lowercase, number is the CustomModelData ID you want to give the statue.
  3. Go to assets/minecraft/models/customplayer/ and copy #template.json
  4. Rename your copy to your playername in lowercase
  5. Open the file and change "players/steve" in line 5 to "players/PLAYERNAME"
  6. Drop your skin, named PLAYERNAME.png in assets/minecraft/textures/players/



List of ID's:

 0. Steve
 1. Alex
 2. WinnieTheDampoeh
 3. BombLW
 4. Squibs_
 5. TheAI
 6. Fury_101
 7. Malino05
 8. TALLPUP
 9. Nettakrim
 10. Grimmauld
 11. SplashBrotherBE
 12. UnWin
 13. Eragaurd
 14. TheMysticalMarv
 15. Xyoto_prime
 16. TitanicFog
 17. xorizontal
 18. Craft49er
 19. _Pusher
 20. Flamium
 21. Hraponssi
 22. Creepanator77
 23. _Nikku
 24. Hanafield
 25. _tr33v0r_
 26. Jelly_exe
 27. Xeoran
 28. TheBreadFish
 29. RubenNL2
 30. Leiti
 31. JaneGleed
 32. Creasu

Done!
