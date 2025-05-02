# RL04TempNodeUpgradeItemModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Int32 <sortId>k__BackingField`


## Properties

- `Int32 sortId`


## Methods

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Void LoadData(RoguelikeTempNodeUpgradeItemData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04TempNodeUpgradeItemModel : RL04NodeUpgradeItemModel
{
	private Int32 <sortId>k__BackingField; // 0x34
	private static DelegateBridge __Hotfix0_get_sortId; // 0x0
	private static DelegateBridge __Hotfix0_set_sortId; // 0x8
	private static DelegateBridge __Hotfix0_get_isTemp; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Int32 sortId { get; set; }
	public override Boolean isTemp { get; }

	// RVA: 0x2b33ed4 VA: 0x759514bed4
	public Int32 get_sortId() { }
	// RVA: 0x2b33f3c VA: 0x759514bf3c
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2b33fb8 VA: 0x759514bfb8
	public override Boolean get_isTemp() { }
	// RVA: 0x2b33194 VA: 0x759514b194
	public Void LoadData(RoguelikeTempNodeUpgradeItemData tempItemData) { }
	// RVA: 0x2b33128 VA: 0x759514b128
	public Void .ctor() { }
}
```