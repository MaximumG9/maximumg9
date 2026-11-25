# Shadow Info

## Videos of Shadow

### Wato Videos
- [The Greatest Social Deduction Game You've Never Heard Of...](https://youtu.be/c-4Grd-G5zI)
- [Can You Trust Your Closest Friends?](https://youtu.be/yC_rvmT6Ke8)
- [Can I Stop Everyone From Slaying The Dragon?](https://youtu.be/MRC23WJotFc)
- [Everyone Who Finds me Dies...](https://youtu.be/sw_yk9PPy44)
- [Hiding a Hitman in the End](https://youtu.be/W59pEy24lKk)

### Jammin Videos
- [Never invite a PvPer to your social deduction game](https://youtu.be/OlfdeLt9BT4)
- [Aura Farming in a Social deduction game (Shadow)](https://youtu.be/HlyR4SOvwCg)
- [Absolutely Ruining a Social deduction game (Shadow)](https://youtu.be/AIloCqRYVo4)

# Implementations of Shadow
## Old Shadow (Latest full implementation)
(Fabric Mod) \
[GitHub](https://github.com/MaximumG9/ShadowOld)
### Setup:
TODO

## Old Old Shadow (eclipsia)
(Paper Plugin) \
[GitHub](https://github.com/MaximumG9/eclipsia)

### Setup:
1. Set up a paper 1.20.4 server
2. Install [Simple Voice Chat](https://modrinth.com/plugin/simple-voice-chat/versions?l=paper), [World Edit](https://modrinth.com/plugin/worldedit), [ViaVersion](https://modrinth.com/plugin/viaversion), [ViaBackwards](https://modrinth.com/plugin/viabackwards), [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/), and the [Shadow Plugin](https://github.com/MaximumG9/eclipsia) (Requires compiling the Shadow Plugin from source)
3. Before starting the server, change these 2 settings in the voicemod config
   ![change port to -1 and max_voice_distance to 24.0](../voicechatconfig.png)
5. Start the server and have everyone join with the [simple voice chat mod](https://modrinth.com/plugin/simple-voice-chat/versions?l=fabric) as well as [fabric api](https://modrinth.com/mod/fabric-api). Make sure everyone is using [fabric loader](https://fabricmc.net/)
6. Do /seed and find a stronghold using [chunkbase](https://www.chunkbase.com/apps/seed-map)
7. Teleport to that location and use **/\$location** to set the spawn region for the game. If it fails, move around a bit until you get the portal room within the world border
8. Set up roles with **/\$roles** and make sure that the amount of roles is equal to the amount of players in the game. Also use this time to check that you have the modifiers you want with **/\$modifiers**, and also do **/\$config food RANDOM**
9. Have everyone verify that their voice chat is working, verify that the end is fully reset, and start the game by using **/\$start**

## Old Old Old Shadow (command block)
(Sponge Style Schematic) \
[Download](../Command_ShadowV6-1-1.schem)

### Setup:
TODO
