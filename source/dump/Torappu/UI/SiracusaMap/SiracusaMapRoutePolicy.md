# SiracusaMapRoutePolicy

**Namespace:** `Torappu.UI.SiracusaMap`


## Methods

- `String _TryGetNormalStageId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapRoutePolicy : CustomActivityStageRoutePolicy`1
{
	private static DelegateBridge __Hotfix0_GetActType; // 0x0
	private static DelegateBridge __Hotfix0_get_pageName; // 0x8
	private static DelegateBridge __Hotfix0_CreateParamFromStage; // 0x10
	private static DelegateBridge __Hotfix0_CreateParamFromDataBundle; // 0x18
	private static DelegateBridge __Hotfix0__TryGetNormalStageId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override String pageName { get; }

	// RVA: 0x24054ac VA: 0x7594a1d4ac
	protected override ActivityType GetActType() { }
	// RVA: 0x2405514 VA: 0x7594a1d514
	protected override String get_pageName() { }
	// RVA: 0x2405590 VA: 0x7594a1d590
	protected override Param CreateParamFromStage(ActRouteTarget input) { }
	// RVA: 0x24057f4 VA: 0x7594a1d7f4
	protected override Param CreateParamFromDataBundle(BattleOutRouteInput input) { }
	// RVA: 0x2405734 VA: 0x7594a1d734
	private String _TryGetNormalStageId(String stageId) { }
	// RVA: 0x24058f0 VA: 0x7594a1d8f0
	public Void .ctor() { }
}
```