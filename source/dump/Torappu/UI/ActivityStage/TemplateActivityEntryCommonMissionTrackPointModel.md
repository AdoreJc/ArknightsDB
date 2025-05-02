# TemplateActivityEntryCommonMissionTrackPointModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `Boolean m_hasCanGetRewardMission`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityEntryCommonMissionTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_hasCanGetRewardMission; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x30951d0 VA: 0x75956ad1d0
	public Boolean get_isShow() { }
	// RVA: 0x3095238 VA: 0x75956ad238
	public Void UpdateState(Object param) { }
	// RVA: 0x3095308 VA: 0x75956ad308
	public Void .ctor() { }
}
```