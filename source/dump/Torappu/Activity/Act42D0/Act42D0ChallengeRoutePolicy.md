# Act42D0ChallengeRoutePolicy

**Namespace:** `Torappu.Activity.Act42D0`


## Methods

- `Boolean <>xLuaBaseProxy_UseActPolicy(Condition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeRoutePolicy : CustomActivityStageRoutePolicy`1
{
	private static DelegateBridge __Hotfix0_UseActPolicy; // 0x0
	private static DelegateBridge __Hotfix0_GetOverrideActivityIdFromDataBundle; // 0x8
	private static DelegateBridge __Hotfix0_get_pageName; // 0x10
	private static DelegateBridge __Hotfix0_CreateParamFromDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_CreateParamFromStage; // 0x20
	private static DelegateBridge __Hotfix0_GetActType; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String pageName { get; }

	// RVA: 0x31fe55c VA: 0x759581655c
	protected override Boolean UseActPolicy(Condition condition) { }
	// RVA: 0x31fe6a4 VA: 0x75958166a4
	protected override Void GetOverrideActivityIdFromDataBundle(BattleOutRouteInput input, out String actId) { }
	// RVA: 0x31fe750 VA: 0x7595816750
	protected override String get_pageName() { }
	// RVA: 0x31fe7cc VA: 0x75958167cc
	protected override Param CreateParamFromDataBundle(BattleOutRouteInput input) { }
	// RVA: 0x31fe890 VA: 0x7595816890
	protected override Param CreateParamFromStage(ActRouteTarget input) { }
	// RVA: 0x31fe9a4 VA: 0x75958169a4
	protected override ActivityType GetActType() { }
	// RVA: 0x31fea0c VA: 0x7595816a0c
	public Void .ctor() { }
	// RVA: 0x31fea9c VA: 0x7595816a9c
	private Boolean <>xLuaBaseProxy_UseActPolicy(Condition P0) { }
}
```