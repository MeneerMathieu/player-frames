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
 1. WinnieTheDampoeh
 2. BombLW
 3. Squibs__
 4. TheAI
 5. Fury_101
 6. Malino05
 7. TALLPUP
 8. Nettakrim
 9. Grimmauld
 10. SplashBrotherBE
 11. UnWin
 12. Eragaurd
 13. TheMysticalMarv
 14. Xyoto_prime
 15. TitanicFog
 16. xorizontal
 17. Craft49er
 18. _Pusher
 19. Flamium
 20. Hraponssi

Done!
