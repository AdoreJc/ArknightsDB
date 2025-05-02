# ActMultiV3PrepareMainStageChoosePanel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3PrepareMainStageChooseView _view`

- `ActMultiV3PrepareMainStageChooseProperty m_prop`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnCopyRoomId()`

- `Void EventOnClickGuestReadyBtn()`

- `Void EventOnClickGuestCancelReadyBtn()`

- `Void EventOnEnterGameBtnClick()`

- `Void EventOnFlipModeToggleClick()`

- `Void EventOnOpenStageDetailBtn()`

- `Void EventOnBtnChooseStageClicked()`

- `Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainStageChoosePanel : ActMultiV3PrepareMainStepPanelBase
{
	private ActMultiV3PrepareMainStageChooseView _view; // 0x38
	private ActMultiV3PrepareMainStageChooseProperty m_prop; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private UIStateFinder m_stateFinder; // 0x58
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0_get_step; // 0x0
	private static DelegateBridge __Hotfix0_GetMainViewConfig; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCopyRoomId; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClickGuestReadyBtn; // 0x28
	private static DelegateBridge __Hotfix0_EventOnClickGuestCancelReadyBtn; // 0x30
	private static DelegateBridge __Hotfix0_EventOnEnterGameBtnClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnFlipModeToggleClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnOpenStageDetailBtn; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBtnChooseStageClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override ActMultiV3PrepareStepType step { get; }

	// RVA: 0x3176ef0 VA: 0x759578eef0
	public override ActMultiV3PrepareStepType get_step() { }
	// RVA: 0x3176f58 VA: 0x759578ef58
	public override ActMultiV3PrepareMainViewConfig GetMainViewConfig() { }
	// RVA: 0x3176fc0 VA: 0x759578efc0
	private Void _InitIfNot() { }
	// RVA: 0x31773fc VA: 0x759578f3fc
	protected override Void OnUpdate(ActMultiV3StepUpdateCase updateCase) { }
	// RVA: 0x3177b68 VA: 0x759578fb68
	public Void EventOnCopyRoomId() { }
	// RVA: 0x3177d88 VA: 0x759578fd88
	public Void EventOnClickGuestReadyBtn() { }
	// RVA: 0x3177e44 VA: 0x759578fe44
	public Void EventOnClickGuestCancelReadyBtn() { }
	// RVA: 0x3177efc VA: 0x759578fefc
	public Void EventOnEnterGameBtnClick() { }
	// RVA: 0x3178178 VA: 0x7595790178
	public Void EventOnFlipModeToggleClick() { }
	// RVA: 0x31783ec VA: 0x75957903ec
	public Void EventOnOpenStageDetailBtn() { }
	// RVA: 0x3178518 VA: 0x7595790518
	public Void EventOnBtnChooseStageClicked() { }
	// RVA: 0x31785bc VA: 0x75957905bc
	public Void .ctor() { }
	// RVA: 0x317862c VA: 0x759579062c
	private Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase P0) { }
}
```