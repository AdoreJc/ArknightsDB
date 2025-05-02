# SandboxV2ItemTrapData

**Namespace:** `Torappu`


## Fields

- `String itemId`

- `String trapId`

- `Int32 trapPhase`

- `Int32 trapLevel`

- `Int32 skillIndex`

- `Int32 skillLevel`

- `Int32 buildingLevel`

- `String updatedItemId`

- `String minLevelItemId`

- `String baseItemName`

- `SandboxV2TrapItemType itemType`

- `SandboxV2ItemTrapTag itemTag`

- `String buffId`


## Methods

- `Boolean ShouldSerializebuffId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2ItemTrapData
{
	public String itemId; // 0x10
	public String trapId; // 0x18
	public Int32 trapPhase; // 0x20
	public Int32 trapLevel; // 0x24
	public Int32 skillIndex; // 0x28
	public Int32 skillLevel; // 0x2c
	public Int32 buildingLevel; // 0x30
	public String updatedItemId; // 0x38
	public String minLevelItemId; // 0x40
	public String baseItemName; // 0x48
	public SandboxV2TrapItemType itemType; // 0x50
	public SandboxV2ItemTrapTag itemTag; // 0x54
	public String buffId; // 0x58


	// RVA: 0x34b2630 VA: 0x7595aca630
	public Boolean ShouldSerializebuffId() { }
	// RVA: 0x34b2650 VA: 0x7595aca650
	public Void .ctor() { }
}
```