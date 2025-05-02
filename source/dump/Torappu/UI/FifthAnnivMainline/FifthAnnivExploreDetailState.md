# FifthAnnivExploreDetailState

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExplorePlanView _planPrefab`

- `RectTransform _planContainer`

- `FifthAnnivExploreEventView _eventPrefab`

- `RectTransform _eventContainer`

- `FifthAnnivExploreLogView _logPrefab`

- `FifthAnnivExploreDetailBackButton _backBtn`

- `RectTransform _logContainer`

- `UIBlendRTImage _blurImage`

- `Boolean m_hasInited`

- `FifthAnnivExplorePlanView m_planView`

- `FifthAnnivExploreEventView m_eventView`

- `FifthAnnivExploreLogView m_logView`

- `UIPageFinder m_pageFinder`

- `FifthAnnivExploreDecisionProp m_decisionProp`

- `FifthAnnivExploreDetailStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _ConfirmOption(String)`

- `Void _ConfirmLogContinue()`

- `Void _ConfirmEventOptionClick(FifthAnnivExploreOptionModel)`

- `Void _NavToEvtResultView(ExploreSelectEventOptionResponse)`

- `Void _ConfirmTargetOptionClick(FifthAnnivExploreOptionModel)`

- `Void _NavToTargetResultState(ExploreSelectTargetOptionResponse)`

- `Void _JumpToPrevEvt()`

- `Void _JumpToNextEvt()`

- `Void _SelectOption(String)`

- `Void _NavToOptionView(String)`

- `Void _BackToPrevious()`

- `Void _CloseSelf()`

- `Boolean _IsStateStable()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreDetailState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 MSG_NAV_TO_OPTION; // 0x0
	public const Int32 MSG_SELECT_OPTION; // 0x0
	public const Int32 MSG_JUMP_TO_PREV_EVT; // 0x0
	public const Int32 MSG_JUMP_TO_NEXT_EVT; // 0x0
	public const Int32 MSG_OPTION_CONFIRM; // 0x0
	public const Int32 MSG_LOG_CONTINUE_CONFIRM; // 0x0
	public const Int32 MSG_BACK_TO_PREVIOUS; // 0x0
	private FifthAnnivExplorePlanView _planPrefab; // 0x70
	private RectTransform _planContainer; // 0x78
	private FifthAnnivExploreEventView _eventPrefab; // 0x80
	private RectTransform _eventContainer; // 0x88
	private FifthAnnivExploreLogView _logPrefab; // 0x90
	private FifthAnnivExploreDetailBackButton _backBtn; // 0x98
	private RectTransform _logContainer; // 0xa0
	private UIBlendRTImage _blurImage; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private FifthAnnivExplorePlanView m_planView; // 0xb8
	private FifthAnnivExploreEventView m_eventView; // 0xc0
	private FifthAnnivExploreLogView m_logView; // 0xc8
	private UIPageFinder m_pageFinder; // 0xd0
	private FifthAnnivExploreDecisionProp m_decisionProp; // 0xe0
	private FifthAnnivExploreDetailStateBean m_stateBean; // 0xe8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0__ConfirmOption; // 0x10
	private static DelegateBridge __Hotfix0__ConfirmLogContinue; // 0x18
	private static DelegateBridge __Hotfix0__ConfirmEventOptionClick; // 0x20
	private static DelegateBridge __Hotfix0__NavToEvtResultView; // 0x28
	private static DelegateBridge __Hotfix0__ConfirmTargetOptionClick; // 0x30
	private static DelegateBridge __Hotfix0__NavToTargetResultState; // 0x38
	private static DelegateBridge __Hotfix0__JumpToPrevEvt; // 0x40
	private static DelegateBridge __Hotfix0__JumpToNextEvt; // 0x48
	private static DelegateBridge __Hotfix0__SelectOption; // 0x50
	private static DelegateBridge __Hotfix0__NavToOptionView; // 0x58
	private static DelegateBridge __Hotfix0__BackToPrevious; // 0x60
	private static DelegateBridge __Hotfix0__CloseSelf; // 0x68
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x70
	private static DelegateBridge __Hotfix0_OnEnter; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x29106ec VA: 0x7594f286ec
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2910754 VA: 0x7594f28754
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2910d58 VA: 0x7594f28d58
	private Void _ConfirmOption(String optionId) { }
	// RVA: 0x2910efc VA: 0x7594f28efc
	private Void _ConfirmLogContinue() { }
	// RVA: 0x2911194 VA: 0x7594f29194
	private Void _ConfirmEventOptionClick(FifthAnnivExploreOptionModel currOptionModel) { }
	// RVA: 0x2911720 VA: 0x7594f29720
	private Void _NavToEvtResultView(ExploreSelectEventOptionResponse response) { }
	// RVA: 0x29113f4 VA: 0x7594f293f4
	private Void _ConfirmTargetOptionClick(FifthAnnivExploreOptionModel currOptionModel) { }
	// RVA: 0x2911834 VA: 0x7594f29834
	private Void _NavToTargetResultState(ExploreSelectTargetOptionResponse obj) { }
	// RVA: 0x2910b20 VA: 0x7594f28b20
	private Void _JumpToPrevEvt() { }
	// RVA: 0x2910c3c VA: 0x7594f28c3c
	private Void _JumpToNextEvt() { }
	// RVA: 0x29109e8 VA: 0x7594f289e8
	private Void _SelectOption(String optionId) { }
	// RVA: 0x29108b0 VA: 0x7594f288b0
	private Void _NavToOptionView(String choiceId) { }
	// RVA: 0x2910fa4 VA: 0x7594f28fa4
	private Void _BackToPrevious() { }
	// RVA: 0x2911654 VA: 0x7594f29654
	private Void _CloseSelf() { }
	// RVA: 0x2911094 VA: 0x7594f29094
	private Boolean _IsStateStable() { }
	// RVA: 0x29119a0 VA: 0x7594f299a0
	protected override Void OnEnter() { }
	// RVA: 0x2911b44 VA: 0x7594f29b44
	private Void _InitIfNot() { }
	// RVA: 0x2911cfc VA: 0x7594f29cfc
	public Void .ctor() { }
	// RVA: 0x2911da8 VA: 0x7594f29da8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```