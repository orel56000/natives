---
ns: WEAPON
aliases: ["0x4757F00BC6323CFE","_SET_WEAPON_DAMAGE_MODIFIER"]
---
## _SET_WEAPON_DAMAGE_MODIFIER

```c
// 0x4757F00BC6323CFE
void _SET_WEAPON_DAMAGE_MODIFIER_THIS_FRAME(Hash weaponHash, float damageMultiplier);
```

Changes the weapon damage output by the given multiplier value.

## Parameters
* **weaponHash**: Hash of the weapon
* **damageMultiplier**: Damage Multiplier

Does NOT need to be called every frame.

## Example

```lua
Citizen.CreateThread(function()
    SetWeaponDamageModifier(`WEAPON_CARBINERIFLE`, 0.8) 
end)
```
