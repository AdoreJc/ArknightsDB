# RoutePolicy

**Namespace:** ` `


## Methods

- `Boolean <>xLuaBaseProxy_UseActPolicy(Condition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoutePolicy : CustomActivityStageRoutePolicy`1
{
	private static DelegateBridge __Hotfix0_get_pageName; // 0x0
	private static DelegateBridge __Hotfix0_CreateParamFromDataBundle; // 0x8
	private static DelegateBridge __Hotfix0_CreateParamFromStage; // 0x10
	private static DelegateBridge __Hotfix0_GetOverrideZoneIdAndStageIdFromDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_GetActType; // 0x20
	private static DelegateBridge __Hotfix0_UseActPolicy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String pageName { get; }

	// RVA: 0x32eb158 VA: 0x7595903158
	protected override String get_pageName() { }
	// RVA: 0x32eb1d4 VA: 0x75959031d4
	protected override Param CreateParamFromDataBundle(BattleOutRouteInput input) { }
	// RVA: 0x32eb348 VA: 0x7595903348
	protected override Param CreateParamFromStage(ActRouteTarget input) { }
	// RVA: 0x32eb4d8 VA: 0x75959034d8
	protected override Void GetOverrideZoneIdAndStageIdFromDataBundle(BattleOutRouteInput input, out String zoneId, out String stageId) { }
	// RVA: 0x32eb5d8 VA: 0x75959035d8
	protected override ActivityType GetActType() { }
	// RVA: 0x32eb640 VA: 0x7595903640
	protected override Boolean UseActPolicy(Condition condition) { }
	// RVA: 0x32eb734 VA: 0x7595903734
	public Void .ctor() { }
	// RVA: 0x32eb7c4 VA: 0x75959037c4
	private Boolean <>xLuaBaseProxy_UseActPolicy(Condition P0) { }
}
```