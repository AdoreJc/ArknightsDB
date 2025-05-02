# BasicActivityItemViewModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `ItemBundle commonItemBundle`

- `ItemBundle replicateItemBundle`


## Properties

- `Boolean isReplicate`


## Methods

- `Boolean get_isReplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class BasicActivityItemViewModel
{
	public ItemBundle commonItemBundle; // 0x10
	public ItemBundle replicateItemBundle; // 0x18

	public Boolean isReplicate { get; }

	// RVA: 0x30a6d5c VA: 0x75956bed5c
	public Boolean get_isReplicate() { }
	// RVA: 0x30aafc4 VA: 0x75956c2fc4
	public Void .ctor(String actId, ItemBundle normalItem) { }
	// RVA: 0x30ab0b4 VA: 0x75956c30b4
	public Void .ctor(String actId, String itemId, Int32 count, ItemType itemType) { }
}
```