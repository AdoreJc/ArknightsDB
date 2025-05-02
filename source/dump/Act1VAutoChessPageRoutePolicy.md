# Act1VAutoChessPageRoutePolicy

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act1VAutoChessPageRoutePolicy : ActivityPageRoutePolicy
{
	private static DelegateBridge __Hotfix0_GetActType; // 0x0
	private static DelegateBridge __Hotfix0_GenerateRoutePathsFromStage; // 0x8
	private static DelegateBridge __Hotfix0_GenerateRoutePathsFromDataBundle; // 0x10
	private static DelegateBridge __Hotfix0_GenerateEntryPageRoutePath; // 0x18
	private static DelegateBridge __Hotfix0__RouteToEntryHome; // 0x20
	private static DelegateBridge __Hotfix0__RouteToEntryHomeBattleOut; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3363ab0 VA: 0x759597bab0
	protected override ActivityType GetActType() { }
	// RVA: 0x3363b18 VA: 0x759597bb18
	protected override List`1 GenerateRoutePathsFromStage(CommonStageRouteInput param) { }
	// RVA: 0x3363dac VA: 0x759597bdac
	protected override List`1 GenerateRoutePathsFromDataBundle(BattleOutRouteInput param) { }
	// RVA: 0x33640d8 VA: 0x759597c0d8
	protected override ActivityPageRoutePath GenerateEntryPageRoutePath(CommonEntryRouteInput param) { }
	// RVA: 0x3363bf8 VA: 0x759597bbf8
	private List`1 _RouteToEntryHome(String actId) { }
	// RVA: 0x3363e7c VA: 0x759597be7c
	private List`1 _RouteToEntryHomeBattleOut(String actId) { }
	// RVA: 0x3364204 VA: 0x759597c204
	public Void .ctor() { }
}
```