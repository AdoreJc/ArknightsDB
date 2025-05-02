# FurnitureAcquireCondTriggerHolder

**Namespace:** `Torappu.LocalTrack`


## Methods

- `Int32 _GetFurnitureCount(String, PlayerDataModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class FurnitureAcquireCondTriggerHolder : PlayerTrackTriggerHolder`1
{
	private static DelegateBridge __Hotfix0_CreatePlayerDataPathList; // 0x0
	private static DelegateBridge __Hotfix0__GetFurnitureCount; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfToTrigger; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f18ccc VA: 0x7596530ccc
	protected override IList`1 CreatePlayerDataPathList() { }
	// RVA: 0x3f18e6c VA: 0x7596530e6c
	private Int32 _GetFurnitureCount(String furnitureId, PlayerDataModel data) { }
	// RVA: 0x3f18f44 VA: 0x7596530f44
	protected override Boolean CheckIfToTrigger(FurnitureAcquireCondTrigger trigger, PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x3f19010 VA: 0x7596531010
	public Void .ctor() { }
}
```