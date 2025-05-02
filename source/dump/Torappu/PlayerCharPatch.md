# PlayerCharPatch

**Namespace:** `Torappu`


## Fields

- `String skinId`

- `Int32 defaultSkillIndex`

- `String currentEquip`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerCharPatch
{
	public String skinId; // 0x10
	public Int32 defaultSkillIndex; // 0x18
	public PlayerCharSkill[] skills; // 0x20
	public String currentEquip; // 0x28
	public ListDict`2 equip; // 0x30


	// RVA: 0x32cfae4 VA: 0x75958e7ae4
	public Void .ctor() { }
}
```