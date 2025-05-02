# VecBreakOffenseRoutePolicy

**Namespace:** `Torappu.UI.VecBreak`


## Methods

- `Boolean <>xLuaBaseProxy_UseActPolicy(Condition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseRoutePolicy : CustomActivityStageRoutePolicy`1
{
	private static DelegateBridge __Hotfix0_get_pageName; // 0x0
	private static DelegateBridge __Hotfix0_CreateParamFromDataBundle; // 0x8
	private static DelegateBridge __Hotfix0_CreateParamFromStage; // 0x10
	private static DelegateBridge __Hotfix0_GetOverrideActivityIdFromDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_GetActType; // 0x20
	private static DelegateBridge __Hotfix0_UseActPolicy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String pageName { get; }

	// RVA: 0x22e14bc VA: 0x75948f94bc
	protected override String get_pageName() { }
	// RVA: 0x22e1538 VA: 0x75948f9538
	protected override Params CreateParamFromDataBundle(BattleOutRouteInput input) { }
	// RVA: 0x22e1600 VA: 0x75948f9600
	protected override Params CreateParamFromStage(ActRouteTarget input) { }
	// RVA: 0x22e17a8 VA: 0x75948f97a8
	protected override Void GetOverrideActivityIdFromDataBundle(BattleOutRouteInput input, out String actId) { }
	// RVA: 0x22e1854 VA: 0x75948f9854
	protected override ActivityType GetActType() { }
	// RVA: 0x22e18bc VA: 0x75948f98bc
	protected override Boolean UseActPolicy(Condition condition) { }
	// RVA: 0x22e1ad8 VA: 0x75948f9ad8
	public Void .ctor() { }
	// RVA: 0x22e1b68 VA: 0x75948f9b68
	private Boolean <>xLuaBaseProxy_UseActPolicy(Condition P0) { }
}
```