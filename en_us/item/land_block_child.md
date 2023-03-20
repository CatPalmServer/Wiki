[← Return to main page](../)
# Subclaim Allocator
I have leased the blocks to you, please make good use of them!  

## Data
<table>
    <tr><td align="end">Image</td><td><img src="https://i.imgur.com/iQ3sZVq.png" width="128"/></td></tr>
    <tr><td align="end">Stack</td><td>64</td></tr>
    <tr><td align="end">Enchantment</td><td>None</td></tr>
</table>

---

## Crafting
<table>
    <tr><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td colspan="3"></td></tr>
    <tr><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td><img src="https://i.imgur.com/hhnlgTn.png" width="48"/></td><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td width="70" align="center"><img src="https://i.imgur.com/VE0KqIE.png" width="40"/></td><td><img src="https://i.imgur.com/iQ3sZVq.png" width="48"/></td><td width="70">x 4</td></tr>
    <tr><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td><img src="https://i.imgur.com/GkMJMSS.png" width="48"/></td><td colspan="3"></td></tr>
</table>

---

## Use
Rename an [anvil](https://minecraft.fandom.com/wiki/Anvil) to the ID of the [land group](land_book.md) you want to assign and place it down:
- The unit of assignment by chunk.
- Each chunk can have at most one sub-territory allocator.
- An anvil can only be placed in a block that belongs to a **main territory**.
- A **sub-territory** inherits all permissions from the **main territory**.
- Configuring a **sub-territory** requires the [R owner](land_book.md#R-owner) permission of the **main territory**.
- Changing the **main territory** will render the **sub-territory** invalid.
- The **main territory** can assign the **sub-territory** without requiring the [R owner](land_book.md#R-owner) permission of the **sub-territory**.
- The activity of a **sub-territory** belongs to the **main territory**.