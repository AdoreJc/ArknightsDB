# TemplateMissionViewModelBasePlugin

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `TemplateMissionViewModel m_context`


## Methods

- `Void SetContext(TemplateMissionViewModel)`

- `Int32 GetShowClaimAllBtnNeedCount()`

- `Boolean CheckMissionShowAbleFlag(ITemplateMissionListItemViewModel)`

- `Boolean Compare(ITemplateMissionListItemViewModel, ITemplateMissionListItemViewModel, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionViewModelBasePlugin : ITemplateMissionViewModelPlugin, IHotfixable
{
	private const Int32 SHOW_CLAIM_ALL_BTN_MISSION_ITEM_NEED_COUNT; // 0x0
	protected TemplateMissionViewModel m_context; // 0x10
	private static DelegateBridge __Hotfix0_SetContext; // 0x0
	private static DelegateBridge __Hotfix0_GetShowClaimAllBtnNeedCount; // 0x8
	private static DelegateBridge __Hotfix0_CheckMissionShowAbleFlag; // 0x10
	private static DelegateBridge __Hotfix0_Compare; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x236f050 VA: 0x7594987050
	public Void SetContext(TemplateMissionViewModel viewModel) { }
	// RVA: 0x236f0d4 VA: 0x75949870d4
	public Int32 GetShowClaimAllBtnNeedCount() { }
	// RVA: 0x236f13c VA: 0x759498713c
	public Boolean CheckMissionShowAbleFlag(ITemplateMissionListItemViewModel item) { }
	// RVA: 0x236f1b8 VA: 0x75949871b8
	public Boolean Compare(ITemplateMissionListItemViewModel a, ITemplateMissionListItemViewModel b, out Int32 result) { }
	// RVA: 0x236f55c VA: 0x759498755c
	public Void .ctor() { }
}
```