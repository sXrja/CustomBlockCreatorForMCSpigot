# CustomBlockCreatorForMCSpigot
A Custom Block Creator for Minecraft Spigot (CBC) that is mainly used to build in creative mode.


## How does it work?
First! The Plugin needs a Resource Pack that you can download here on Github.
After that you need to go into the plugins folder and search the settings.json for CBC.
Here are some example settings that apply to the Template Pack:

```
{
  "customBlocks": [
    {
      "name": "Better Stone Bricks",
      "material": "STONE_BRICK_SLAB",
      "customModelData": 1001
    },
    {
      "name": "Better Mossy Stone Bricks",
      "material": "MOSSY_STONE_BRICK_SLAB",
      "customModelData": 1002
    }
  ],
  "menu": {
    "inventorySize": 9,
    "title": "Custom Blocks"
  }
}
```
In the Template Pack you can create your own Blocks and just add these in the settings.
The Plugin works with waterlogged double slaps cause its not possible to get them the normal way!
### ITS NOT REPLACING ANY OF THE VANILLA BLOCKS!!!

To get these Custom Block into your inventory use the command: /customblocks. There are all Blocks listed that you put into the settings File!
The Blocks are Displayed as bat_spawn_egg's. To see the Block just Place the Egg somewhere on the ground.

## Known Issues:
- when placing the bat_spawn_egg into water it will spawn an bat with current Block name

## Permissions:
```
Use the /customblocks command: bcb.usemenu
```

Updating it soon! 
Wanna learn more? check out my youtube: https://youtube.com/@sxrja
