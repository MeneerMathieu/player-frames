# player-frames
Get Minecraft players with invisible item frames

How to add a player:
  1. Go to assets/minecraft/models/item/flint.json
  2. Add this line: { "predicate": {"custom_model_data": NUMBER}, "model": "customplayer/PLAYERNAME"}, where PLAYERNAME is your playername in lowercase, number is the CustomModelData ID you want to give the statue.
  3. Go to assets/minecraft/models/customplayer/ and copy #template.json
  4. Rename your copy to your playername in lowercase
  5. Open the file and change "players/steve" in line 5 to "players/PLAYERNAME"
  6. Drop your skin, named PLAYERNAME.png in assets/minecraft/textures/players/

Done!
