# Act24SideRoutePolicy

**Namespace:** `Torappu.Activity.Act24side`


## Methods

- `Boolean _CheckIfAct24sideQuestStage(String, String)`

- `Boolean <>xLuaBaseProxy_UseActPolicy(Condition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24SideRoutePolicy : CustomActivityStageRoutePolicy`1
{
	private static DelegateBridge __Hotfix0_GetActType; // 0x0
	private static DelegateBridge __Hotfix0_get_pageName; // 0x8
	private static DelegateBridge __Hotfix0_CreateParamFromStage; // 0x10
	private static DelegateBridge __Hotfix0_CreateParamFromDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_UseActPolicy; // 0x20
	private static DelegateBridge __Hotfix0__CheckIfAct24sideQuestStage; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String pageName { get; }

	// RVA: 0x32c133c VA: 0x75958d933c
	protected override ActivityType GetActType() { }
	// RVA: 0x32c13a4 VA: 0x75958d93a4
	protected override String get_pageName() { }
	// RVA: 0x32c1420 VA: 0x75958d9420
	protected override Param CreateParamFromStage(ActRouteTarget input) { }
	// RVA: 0x32c15d4 VA: 0x75958d95d4
	protected override Param CreateParamFromDataBundle(BattleOutRouteInput input) { }
	// RVA: 0x32c1698 VA: 0x75958d9698
	protected override Boolean UseActPolicy(Condition condition) { }
	// RVA: 0x32c17b8 VA: 0x75958d97b8
	private Boolean _CheckIfAct24sideQuestStage(String zoneId, String stageId) { }
	// RVA: 0x32c19d0 VA: 0x75958d99d0
	public Void .ctor() { }
	// RVA: 0x32c1a60 VA: 0x75958d9a60
	private Boolean <>xLuaBaseProxy_UseActPolicy(Condition P0) { }
}
```