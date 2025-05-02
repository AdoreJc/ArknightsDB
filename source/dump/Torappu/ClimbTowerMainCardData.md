# ClimbTowerMainCardData

**Namespace:** `Torappu`


## Fields

- `String id`

- `ClimbTowerCardType type`

- `String linkedTowerId`

- `Int32 sortId`

- `String name`

- `String desc`

- `PackedRuneData runeData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ClimbTowerMainCardData
{
	public String id; // 0x10
	public ClimbTowerCardType type; // 0x18
	public String linkedTowerId; // 0x20
	public Int32 sortId; // 0x28
	public String name; // 0x30
	public String desc; // 0x38
	public List`1 subCardIds; // 0x40
	public PackedRuneData runeData; // 0x48
	public List`1 trapIds; // 0x50


	// RVA: 0x349bf1c VA: 0x7595ab3f1c
	public Void .ctor() { }
}
```