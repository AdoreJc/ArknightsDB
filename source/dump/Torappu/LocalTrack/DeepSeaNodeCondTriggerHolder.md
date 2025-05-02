# DeepSeaNodeCondTriggerHolder

**Namespace:** `Torappu.LocalTrack`


## Methods

- `Boolean _CheckIfLogStatusSatisfied(String, PlayerDataModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class DeepSeaNodeCondTriggerHolder : PlayerTrackTriggerHolder`1
{
	private static DelegateBridge __Hotfix0_CheckIfToTrigger; // 0x0
	private static DelegateBridge __Hotfix0_CreatePlayerDataPathList; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfLogStatusSatisfied; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f17ad8 VA: 0x759652fad8
	protected override Boolean CheckIfToTrigger(DeepSeaNodeCondTrigger trigger, PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x3f17c8c VA: 0x759652fc8c
	protected override IList`1 CreatePlayerDataPathList() { }
	// RVA: 0x3f17bac VA: 0x759652fbac
	private Boolean _CheckIfLogStatusSatisfied(String nodeId, PlayerDataModel data) { }
	// RVA: 0x3f17e2c VA: 0x759652fe2c
	public Void .ctor() { }
}
```