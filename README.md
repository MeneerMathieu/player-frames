# player-frames
Get Minecraft players with invisible item frames


![2022-02-05_14 47 32](https://user-images.githubusercontent.com/61655741/152644687-03a477af-3267-477c-b851-e417db2ab501.png)

How to download:
 1. Click on the green "Code" button.
 2. Pick "Download ZIP"
 3. Unzip the file so when you open the folder the first thing you see is the pack.mcmeta file. Place the folder into your recourses folder.
 4. Done!



How to get the items:
 - On CK (two options):
  1. Go to /p v WinnieTheDampoeh 2, you will see a whole row of item frames with the statues on them. Just middle click to grab one.
  2. Import one from singleplayer using saved toolbars.
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
 33. Fri3dNstuff
 34. janskalvik
 35. CAG2
 36. MrCreepie101c
 37. VAJvagyok
 38. Cistic
 39. eoneon
 40. Kuriku
 41. Eeveepro_
 42. SoloSwain
 43. TraksAG
 44. pv_pro
 45. JudyMarie258
 46. Lekro
 47. USNAYR
 48. LP0320
 49. zorua162
 50. Tiger63
 51. Godric213
 52. Crypzto
 53. BaconBurrito

And more, check this out:

{
  "players": [
    "WinnieTheDampoeh",
    "BombLW",
    "Squibs__",
    "TheAI",
    "Fury_101",
    "Malino05",
    "TALLPUP",
    "Nettakrim",
    "Grimmauld",
    "SplashBrotherBE",
    "UnWin",
    "Eragaurd",
    "TheMysticalMarv",
    "Xyoto_prime",
    "TitanicFog",
    "xorizontal",
    "Craft49er",
    "Wilh3lmMusic",
    "Flamium",
    "hraponssi",
    "Creepanator77",
    "_Nikku",
    "Hanafield",
    "_Tr3v0r_",
    "Jelly_exe",
    "Xeoran",
    "TheBreadFish",
    "RubenNL2",
    "Leiti",
    "JaneGleed",
    "Creasu",
    "Fri3dNstuff",
    "janskalvik",
    "CAG2",
    "MrCreepie101c",
    "VAJvagyok",
    "Cistic",
    "eoneon",
    "Kuriku",
    "Eeveepro_",
    "SoloSwain",
    "TraksAG",
    "pv_pro",
    "JudyMarie258",
    "Lekro",
    "USNAYR",
    "LP0320",
    "zorua162",
    "Tiger63",
    "Godric213",
    "Crypzto",
    "BaconBurrito",
    "TacoSquad",
    "NotMitchu",
    "BlamePrody",
    "YZEROgame",
    "Mylimo",
    "mexiscool",
    "Uncle_Seamus",
    "Kitirto",
    "Brownie1111",
    "melody479",
    "LogicBugs",
    "ArvidTT",
    "Lekro",
    "skoolh8er",
    "CosmoDaFox",
    "Daluuu",
    "Rohirrimjaw991",
    "WAFFLE_PENGUIN",
    "Deviss",
    "xX_Alberto_Xx",
    "oggabob",
    "CRAFTER_ROBO2002",
    "CRAFTER_ROBO2000",
    "qLudd",
    "wayne_64",
    "DSK1273",
    "Knifehand87",
    "EpicPix",
    "YaBoiRanger",
    "Canonic",
    "_smurfii_",
    "Legit030",
    "iRobo",
    "KalDraven",
    "SaintKlaus"
  ]
}

Done!
