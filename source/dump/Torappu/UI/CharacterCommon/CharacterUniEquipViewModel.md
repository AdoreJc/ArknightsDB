# CharacterUniEquipViewModel

**Namespace:** `Torappu.UI.CharacterCommon`


## Fields

- `UniEquipData data`

- `Int32 level`

- `Boolean isShow`

- `Boolean isUnlock`

- `Boolean isEquip`

- `Int32 sortOrder`


## Methods

- `Int32 CompareTo(CharacterUniEquipViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterCommon
public class CharacterUniEquipViewModel : IComparable`1
{
	public UniEquipData data; // 0x10
	public Int32 level; // 0x18
	public Boolean isShow; // 0x1c
	public Boolean isUnlock; // 0x1d
	public Boolean isEquip; // 0x1e
	public Int32 sortOrder; // 0x20


	// RVA: 0x2d8e8f4 VA: 0x75953a68f4
	public Int32 CompareTo(CharacterUniEquipViewModel other) { }
	// RVA: 0x2d8e914 VA: 0x75953a6914
	public Void .ctor() { }
}
```