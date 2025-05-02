# ItemCondTriggerHolder

**Namespace:** `Torappu.LocalTrack`


## Methods

- `Boolean _CheckIfItemCountSatisfied(String, Int32, PlayerDataModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class ItemCondTriggerHolder : PlayerTrackTriggerHolder`1
{
	private static DelegateBridge __Hotfix0_CheckIfToTrigger; // 0x0
	private static DelegateBridge __Hotfix0_CreatePlayerDataPathList; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfItemCountSatisfied; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f19108 VA: 0x7596531108
	protected override Boolean CheckIfToTrigger(ItemCondTrigger trigger, PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x3f192c4 VA: 0x75965312c4
	protected override IList`1 CreatePlayerDataPathList() { }
	// RVA: 0x3f191e4 VA: 0x75965311e4
	private Boolean _CheckIfItemCountSatisfied(String itemId, Int32 targetCount, PlayerDataModel data) { }
	// RVA: 0x3f193f4 VA: 0x75965313f4
	public Void .ctor() { }
}
```