# RuneInfo

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `String runeId`

- `String stageId`

- `Boolean isAvailable`

- `Boolean isSelected`

- `Boolean isUnlock`

- `Boolean isBanned`

- `String conflictKey`

- `Int32 point`

- `Int32 sortId`

- `String iconId`

- `String description`


## Properties

- `Boolean isNewHand`


## Methods

- `Boolean get_isNewHand()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class RuneInfo
{
	public String runeId; // 0x10
	public String stageId; // 0x18
	public Boolean isAvailable; // 0x20
	public Boolean isSelected; // 0x21
	public Boolean isUnlock; // 0x22
	public Boolean isBanned; // 0x23
	public String conflictKey; // 0x28
	public Int32 point; // 0x30
	public Int32 sortId; // 0x34
	public String iconId; // 0x38
	public String description; // 0x40

	public Boolean isNewHand { get; }

	// RVA: 0x31d90c0 VA: 0x75957f10c0
	public Boolean get_isNewHand() { }
	// RVA: 0x31d90d0 VA: 0x75957f10d0
	public Void .ctor() { }
}
```