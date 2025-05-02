# Act42D0NormalRoutePolicy

**Namespace:** `Torappu.Activity.Act42D0`


## Methods

- `Boolean <>xLuaBaseProxy_UseActPolicy(Condition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0NormalRoutePolicy : CustomActivityStageRoutePolicy`1
{
	private static DelegateBridge __Hotfix0_get_pageName; // 0x0
	private static DelegateBridge __Hotfix0_CreateParamFromDataBundle; // 0x8
	private static DelegateBridge __Hotfix0_GetOverrideActivityIdFromDataBundle; // 0x10
	private static DelegateBridge __Hotfix0_CreateParamFromStage; // 0x18
	private static DelegateBridge __Hotfix0_GetActType; // 0x20
	private static DelegateBridge __Hotfix0_UseActPolicy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String pageName { get; }

	// RVA: 0x3202d98 VA: 0x759581ad98
	protected override String get_pageName() { }
	// RVA: 0x3202e14 VA: 0x759581ae14
	protected override Param CreateParamFromDataBundle(BattleOutRouteInput input) { }
	// RVA: 0x3202ed8 VA: 0x759581aed8
	protected override Void GetOverrideActivityIdFromDataBundle(BattleOutRouteInput input, out String actId) { }
	// RVA: 0x3202f84 VA: 0x759581af84
	protected override Param CreateParamFromStage(ActRouteTarget input) { }
	// RVA: 0x3203098 VA: 0x759581b098
	protected override ActivityType GetActType() { }
	// RVA: 0x3203100 VA: 0x759581b100
	protected override Boolean UseActPolicy(Condition condition) { }
	// RVA: 0x3203248 VA: 0x759581b248
	public Void .ctor() { }
	// RVA: 0x32032d8 VA: 0x759581b2d8
	private Boolean <>xLuaBaseProxy_UseActPolicy(Condition P0) { }
}
```