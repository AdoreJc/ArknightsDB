# Act1ArcadePageRoutePolicy

**Namespace:** `Torappu.Activity.Act1Arcade`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadePageRoutePolicy : ActivityPageRoutePolicy
{
	private static DelegateBridge __Hotfix0_GenerateRoutePathsFromStage; // 0x0
	private static DelegateBridge __Hotfix0_GenerateRoutePathsFromDataBundle; // 0x8
	private static DelegateBridge __Hotfix0_GenerateEntryPageRoutePath; // 0x10
	private static DelegateBridge __Hotfix0__RouteToEntryHome; // 0x18
	private static DelegateBridge __Hotfix0__RouteToEntryHomeBattleOut; // 0x20
	private static DelegateBridge __Hotfix0_GetActType; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x33ed858 VA: 0x7595a05858
	protected override List`1 GenerateRoutePathsFromStage(CommonStageRouteInput param) { }
	// RVA: 0x33edaec VA: 0x7595a05aec
	protected override List`1 GenerateRoutePathsFromDataBundle(BattleOutRouteInput param) { }
	// RVA: 0x33eddec VA: 0x7595a05dec
	protected override ActivityPageRoutePath GenerateEntryPageRoutePath(CommonEntryRouteInput param) { }
	// RVA: 0x33ed938 VA: 0x7595a05938
	private List`1 _RouteToEntryHome(String actId) { }
	// RVA: 0x33edbf4 VA: 0x7595a05bf4
	private List`1 _RouteToEntryHomeBattleOut(String actId, String prefStageId) { }
	// RVA: 0x33edf30 VA: 0x7595a05f30
	protected override ActivityType GetActType() { }
	// RVA: 0x33edf98 VA: 0x7595a05f98
	public Void .ctor() { }
}
```