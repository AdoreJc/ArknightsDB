# ActMultiV3PageRoutePolicy

**Namespace:** `Torappu.Activity.ActMultiV3`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PageRoutePolicy : ActivityPageRoutePolicy
{
	private static DelegateBridge __Hotfix0_GenerateEntryPageRoutePath; // 0x0
	private static DelegateBridge __Hotfix0_GenerateRoutePathsFromDataBundle; // 0x8
	private static DelegateBridge __Hotfix0_GenerateRoutePathsFromStage; // 0x10
	private static DelegateBridge __Hotfix0__RouteToEntryHome; // 0x18
	private static DelegateBridge __Hotfix0_GetActType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x30db65c VA: 0x75956f365c
	protected override ActivityPageRoutePath GenerateEntryPageRoutePath(CommonEntryRouteInput param) { }
	// RVA: 0x30db794 VA: 0x75956f3794
	protected override List`1 GenerateRoutePathsFromDataBundle(BattleOutRouteInput param) { }
	// RVA: 0x30db980 VA: 0x75956f3980
	protected override List`1 GenerateRoutePathsFromStage(CommonStageRouteInput param) { }
	// RVA: 0x30dba50 VA: 0x75956f3a50
	private List`1 _RouteToEntryHome(String actId) { }
	// RVA: 0x30dbc04 VA: 0x75956f3c04
	protected override ActivityType GetActType() { }
	// RVA: 0x30dbc6c VA: 0x75956f3c6c
	public Void .ctor() { }
}
```