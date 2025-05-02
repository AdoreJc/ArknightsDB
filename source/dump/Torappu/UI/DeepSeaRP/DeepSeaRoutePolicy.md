# DeepSeaRoutePolicy

**Namespace:** `Torappu.UI.DeepSeaRP`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRoutePolicy : CustomActivityStageRoutePolicy`1
{
	private static DelegateBridge __Hotfix0_GetActType; // 0x0
	private static DelegateBridge __Hotfix0_get_pageName; // 0x8
	private static DelegateBridge __Hotfix0_CreateParamFromStage; // 0x10
	private static DelegateBridge __Hotfix0_CreateParamFromDataBundle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String pageName { get; }

	// RVA: 0x29c6db0 VA: 0x7594fdedb0
	protected override ActivityType GetActType() { }
	// RVA: 0x29c6e18 VA: 0x7594fdee18
	protected override String get_pageName() { }
	// RVA: 0x29c6e94 VA: 0x7594fdee94
	protected override Params CreateParamFromStage(ActRouteTarget input) { }
	// RVA: 0x29c7034 VA: 0x7594fdf034
	protected override Params CreateParamFromDataBundle(BattleOutRouteInput param) { }
	// RVA: 0x29c70f8 VA: 0x7594fdf0f8
	public Void .ctor() { }
}
```