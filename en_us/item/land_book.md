[← Return to main page](../)
# Land Claim Groups
Protect your belongings and prevent theft. Plus, creepers can't blow it up~ it's amazing~
Can bind an infinite number of [Land Claim Generators](land_block.md)!
Monsters are not protected, only animals born within the land claim are.

## Data
<table>
    <tr>
        <td align="center">Disabled</td>
        <td align="center">Enabled</td>
    </tr>
    <tr>
        <td>
            <table>
                <tr><td align="end">Image</td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="128"/></td></tr>
                <tr><td align="end">Stack</td><td>64</td></tr>
                <tr><td align="end">Enchantment</td><td>None</td></tr>
            </table>
        </td>
        <td>
            <table>
                <tr><td align="end">Image</td><td><img src="https://i.imgur.com/duGvD3y.png" width="128"/></td></tr>
                <tr><td align="end">Stack</td><td>1</td></tr>
                <tr><td align="end">Enchantment</td><td>None</td></tr>
            </table>
        </td>
    </tr>
</table>

---
  
## Crafting
<table>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/Oqe8FMm.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/Vj4LxUG.png" width="48"/></td><td width="70"></td></tr>
    <tr><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td><img src="https://i.imgur.com/hK44ttL.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## Use
### Create New
Hold an inactive land claim book in your dominant hand and right-click to activate it.

### Generate Land Claim
Hold an active land claim book in your dominant hand and right-click on a [Land Claim Generator](land_block.md) to write to it.

<table>
    <tr><td align="center">Not Written</td><td align="center">Written</td></tr>
    <tr><td><img src="https://i.imgur.com/x9meQTF.png" width="400"/></td><td><img src="https://i.imgur.com/h2Kovir.png" width="400"/></td></tr>
</table>

If the territory generator (land_block.md) has already been written, it must be dismantled before it can be reused. The placement of the territory is the same as that of the beacon (https://minecraft.fandom.com/wiki/Campfire):

<img src="https://i.imgur.com/nW7GC4b.png" width="720"/>  

The top block is the territory generator (land_block.md).
The bottom four layers can be mixed with small, medium, and large energy territories (land_energy.md).
When all four layers are filled, you get an additional 20% energy points. The formula for converting energy points is:

<table>
    <tr><td align="center">Energy</td><td align="center">Points</td></tr>
    <tr><td align="center">Small</td><td align="center">1</td></tr>
    <tr><td align="center">Medium</td><td align="center">9</td></tr>
    <tr><td align="center">Large</td><td align="center">81</td></tr>
</table>

<table>
    <tr><td align="center">Without all four layers</td><td><code>Block radius</code>=ceiling(sqrt(<code>Total points</code>)/<code>2</code>)-<code>1</code></td></tr>
    <tr><td align="center">With all four layers</td><td><code>Block radius</code>=ceiling(sqrt(<code>Total points</code>x<code>1.2</code>)/<code>2</code>)-<code>1</code></td></tr>
</table>

The actual area is the total block area = square (block radius + 1 + block radius).
It will not overwrite territories that were occupied earlier than itself:  

<table>
    <tr><td><img src="https://i.imgur.com/THNRtuf.png" width="400"/></td><td><img src="https://i.imgur.com/C4waK6f.png" width="400"/></td></tr>
</table>


### Get territory.
If you accidentally lose the activated territory group book, there is still a way to retrieve it.
Hold the unused territory group book in your dominant hand and right-click on the territory generator (land_block.md) to restore the written territory group to the book.

### Rename.
Change the name of the activated territory group book on the anvil (https://minecraft.fandom.com/wiki/Anvil) to the desired name, and the name of the territory group will change accordingly.
Up to 36 arbitrary characters can be entered.
Due to the caching mechanism, some redirects may take up to 30 seconds for the new name to take effect.

### Group book.
The first and second pages are explanations, and the third page begins with (ALL) = and all #permissions, in the format of player = permission list.
Players can be nicknames or names, but after editing, they are automatically converted to nicknames (rename_milk.md).
```yaml
# Maximum limit of 200 players.
#Format:
# Player name = permission list.
#Permissions:
#  A Armor Stand
#  B Boat
#  D Break block
#  E Entity interaction
#  F Item Frame
#  G Painting
#  H Hurt entity
#  I Block interaction
#  L Read Lectern
#  M Minecart
```
```yaml
#  P Place block
#  R Owner
#  S Spawn entity
#  T Trigger mechanism
#  U Bucket
#  V PVP
#  Y Fly
```
```yaml
(ALL)=
Your player name=ABDEFGHILMPRSTUVY
```

Allow all players to fly:  
```yaml
(ALL)=Y
Your player name=ABDEFGHILMPRSTUVY
```
Grant all permissions to I_PLAYER player:
```yaml
(ALL)=
Your player name=ABDEFGHILMPRSTUVY
I_PLAYER=ABDEFGHILMPRSTUVY
```

Lines starting with `#` are comments and are not included in the content
For example, the following line
```yaml
(ALL)=A
```
is commented out
```yaml
#(ALL)=A
```
and will disappear after the update.

---

## Permissions:
- ### A Armor Stand
  [Armor Stand](https://minecraft.fandom.com/wiki/Armor_Stand): placing, damaging, and dressing up
- ### B Boat
  [Boat](https://minecraft.fandom.com/wiki/Boat): placing, damaging, and riding
- ### D Break block
  [Block](https://minecraft.fandom.com/wiki/Block) destruction
- ### E Entity interaction
  [Entity](https://minecraft.fandom.com/wiki/Animal) feeding
- ### F Item Frame
  [Item Frame](https://minecraft.fandom.com/wiki/Item_Frame): placing, damaging, changing items, and rotating
- ### G Painting
  [Painting](https://minecraft.fandom.com/wiki/Painting): placing and damaging
- ### H Hurt entity
  [Entity](https://minecraft.fandom.com/wiki/Entity) damage
  ※ Only protect animals born within the territory
- ### I Block interaction
  [Chest](https://minecraft.fandom.com/wiki/Chest) usage
  [Campfire](https://minecraft.fandom.com/wiki/Campfire) usage
  [Sign](https://minecraft.fandom.com/wiki/Sign) changing
  [Jukebox](https://minecraft.fandom.com/wiki/Jukebox) adjustment
- ### L Read Lectern
  [Lectern](https://minecraft.fandom.com/wiki/Lectern) reading
- ### M Minecart
  [Minecart](https://minecraft.fandom.com/wiki/Minecart): placing, damaging, and riding
- ### P Place block
  [Block](https://minecraft.fandom.com/wiki/Block) placement
- ### R Owner
  [Territory Generator](land_block.md): writing and demolishing
  Change territory permissions
  Territory energy placement and demolition
- ### S Spawn entity
  [Spawn Egg](https://minecraft.fandom.com/wiki/Spawn_Egg) usage
  [Friendly Mob Leash](rope.md) usage
  [Hostile Mob Leash](rope.md) usage
- ### T Trigger mechanism
  [Tripwire Hook] (https://minecraft.fandom.com/wiki/Fishing_Rod) triggered
  [Trapped Chest] (https://minecraft.fandom.com/wiki/Trapped_Chest) used
  [Pressure Plate] (https://minecraft.fandom.com/wiki/Pressure_Plate) triggered
- ### U Bucket
  [Bucket] (https://minecraft.fandom.com/wiki/Water_Bucket) used
  [Lava Bucket] (https://minecraft.fandom.com/wiki/Lava_Bucket) used
- ### V PVP
  [Player] (https://minecraft.fandom.com/wiki/Player) damaged
- ### Y Fly
  [Land Flying Device] (land_flying_device.md) flying
  [Cat Bowl] (../feature/cat_bowl.md) observer switch
  [Cat Bowl] (../feature/cat_bowl.md) magnetically attracted dropped items
  

---

## Active
The following actions will increase activity:
- Entity trading, +`100` per transaction
- Block breaking, placing, and updating, +`40` per action
- Item picking up, dropping, container taking, and container putting, +`20` per action
- Entity damage, +`10` per damage
- [Cat Bowl] (../feature/cat_bowl.md) player presence, +`4` per second
- Player presence, +`1` per second

The maximum activity limit for each chunk is `200,000`. Every `5,000` activity in the territory can keep `1` point of [Land Energy] (land_energy.md).
Every 12 months, the remaining [Land Energy] (land_energy.md) points will be checked. If the total is less than `20`%, everything will be destroyed; otherwise:
- Unpreserved [Land Energy] (land_energy.md) will be destroyed
- No preservable [Land Energy] (land_energy.md) will be destroyed along with the [Land Generator] (land_block.md)

The pointer points to the activated [Land Generator] (land_block.md), showing a reference to the activity from `0`% to `999`%.
Formula = minimum(`999`, round_down(`total activity`/((`current time`-`time of last check or creation`)/`6 months`)/`5000.0`/`current total energy points`x`100.0`))
Generally speaking, anything over 100% is safe and undamaged.
