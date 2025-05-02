# TemplateActivityEntryMissionTrackPointModel

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
public class TemplateActivityEntryMissionTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_hasCanGetRewardMission; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean isShow { get; }

	// RVA: 0x30ab1d8 VA: 0x75956c31d8
	public Boolean get_isShow() { }
	// RVA: 0x30ab240 VA: 0x75956c3240
	public Void UpdateState(Object param) { }
	// RVA: 0x30ab3a4 VA: 0x75956c33a4
	public Void .ctor() { }
}
```