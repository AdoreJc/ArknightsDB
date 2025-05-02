# VecBreakOffenseStageGroupView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `RectTransform _stageViewContainer`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `VecBreakOffenseModel m_offenseModel`

- `String m_cacheFocusStageId`

- `Tween m_focusTween`


## Methods

- `Void _InitIfNot()`

- `Void _FocusWithAnim()`

- `VecBreakOffenseTweenType _GetFadeInTween(VecBreakOffenseStageModel, VecBreakOffenseStageModel)`

- `VecBreakOffenseTweenType _GetFadeOutTween(VecBreakOffenseStageModel, VecBreakOffenseStageModel)`

- `Void _CancleFocusTweenIfNeed(String, String)`

- `VecBreakOffenseStageView _GetViewInst(VecBreakOffenseStageModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffenseStageGroupView : DataBinder`1
{
	private RectTransform _stageViewContainer; // 0x20
	private Boolean m_hasInited; // 0x28
	private UIPageFinder m_pageFinder; // 0x30
	private Dictionary`2 m_stageViewDict; // 0x40
	private VecBreakOffenseModel m_offenseModel; // 0x48
	private String m_cacheFocusStageId; // 0x50
	private Tween m_focusTween; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__FocusWithAnim; // 0x10
	private static DelegateBridge __Hotfix0__GetFadeInTween; // 0x18
	private static DelegateBridge __Hotfix0__GetFadeOutTween; // 0x20
	private static DelegateBridge __Hotfix0__CancleFocusTweenIfNeed; // 0x28
	private static DelegateBridge __Hotfix0__GetViewInst; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x22d2d88 VA: 0x75948ead88
	public override Void OnValueChanged(VecBreakOffenseProp property) { }
	// RVA: 0x22d2e44 VA: 0x75948eae44
	private Void _InitIfNot() { }
	// RVA: 0x22d2efc VA: 0x75948eaefc
	private Void _FocusWithAnim() { }
	// RVA: 0x22d3714 VA: 0x75948eb714
	private VecBreakOffenseTweenType _GetFadeInTween(VecBreakOffenseStageModel prevStageModel, VecBreakOffenseStageModel currStageModel) { }
	// RVA: 0x22d3640 VA: 0x75948eb640
	private VecBreakOffenseTweenType _GetFadeOutTween(VecBreakOffenseStageModel prevStageModel, VecBreakOffenseStageModel currStageModel) { }
	// RVA: 0x22d34d8 VA: 0x75948eb4d8
	private Void _CancleFocusTweenIfNeed(String prevStageId, String currStageId) { }
	// RVA: 0x22d3280 VA: 0x75948eb280
	private VecBreakOffenseStageView _GetViewInst(VecBreakOffenseStageModel stageModel) { }
	// RVA: 0x22d3b28 VA: 0x75948ebb28
	public Void .ctor() { }
}
```