# StageBattleDiffGroupInfo

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Int32 diffGroupMaskInfo`

- `Int32 count`


## Properties

- `Int32 apCost`


## Methods

- `Int32 get_apCost()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageBattleDiffGroupInfo : IHotfixable
{
	public Int32 diffGroupMaskInfo; // 0x10
	public Int32 count; // 0x14
	public Dictionary`2 diffGroupStageModel; // 0x18
	private static DelegateBridge __Hotfix0_get_apCost; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Int32 apCost { get; }

	// RVA: 0x2f7e434 VA: 0x7595596434
	public Int32 get_apCost() { }
	// RVA: 0x2f7fef0 VA: 0x7595597ef0
	public Void .ctor() { }
}
```