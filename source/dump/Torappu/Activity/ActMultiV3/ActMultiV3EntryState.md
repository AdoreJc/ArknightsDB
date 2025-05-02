# ActMultiV3EntryState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _topMenuContainer`

- `ActMultiV3EntryView _view`

- `UIAnimationLocation _animEntry`

- `UIAnimationLocation _animExit`

- `UIAnimationLocation _animMainToRoom`

- `UIAnimationLocation _animRoomToMain`

- `UIAnimationLocation _animMainToMatch`

- `ActMultiV3EntryJoinRoomMask _joinRoomMask`

- `ActMultiV3EntryProperty m_property`

- `Boolean m_inited`

- `String m_actId`

- `UIPageFinder m_pageFinder`

- `Coroutine m_entryHomeRoutedCoroutine`

- `Coroutine m_teamViewRoutedCoroutine`

- `ActMultiV3EntryPage m_page`

- `UICompDialogMgr m_dlgMgr`

- `Int32 m_squadNotEnoughConfirmDialog`


## Methods

- `Void _InitIfNot()`

- `Tween _GetAnimationTween(UIAnimationLocation, Boolean)`

- `Tween _GetEntryAnimTween()`

- `Boolean _IsUIStable()`

- `Void _StopCoroutineIfNeed()`

- `Void _RaiseAVGSignalIfNeed()`

- `IEnumerator _WaitForTransFinishCoroutine()`

- `Void UpdateDataOnGetInfo()`

- `Void EffectOnPage(ShowStatus, Boolean)`

- `Void _OnJumpToMedalGroupDisplayState(IStateBean)`

- `Void _OnJumpToRewardDetailState(IStateBean)`

- `Void _OnJumpToStageListState(IStateBean)`

- `Void _OnJumpToMatchState(IStateBean)`

- `Boolean CustomSetActive(Boolean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnBtnBack()`

- `Void _EventOnBtnManualClicked()`

- `Void _EventOnBtnRewardClicked()`

- `Void _EventOnBtnMilestoneClicked()`

- `Void _EventOnBtnMedalClicked()`

- `Void _EventOnBtnSquadClicked()`

- `Void _EventOnBtnStageClicked()`

- `Void _EventOnBtnTeamMatchClicked()`

- `Void _TryTriggerTeamTutorial()`

- `IEnumerator _WaitForFinishEnterRoom()`

- `Void _EventOnBtnQuickMatchClicked()`

- `Void _ClearQuickMatchTrackpoint()`

- `Void _ShowSquadCountNotEnoughDialog()`

- `Void _EventOnInputTeamIdChanged(String)`

- `Void _EventOnBtnCreateTeamClicked()`

- `Void _EventOnBtnJoinTeamClicked()`

- `Void _EventOnBtnTrainingRoomClicked()`

- `Void _OnCreateTeamRespHandle(ActMultiV3CreateTeamResponse)`

- `Void _OnSendJoinTeamRequest(String)`

- `Void _OnJoinTeamRespHandle(ActMultiV3JoinTeamResponse)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Tween <_InitIfNot>b__31_0()`

- `Tween <_InitIfNot>b__31_1()`

- `Tween <_InitIfNot>b__31_2()`

- `Tween <_InitIfNot>b__31_3()`

- `Tween <_InitIfNot>b__31_4()`

- `Tween <_InitIfNot>b__31_5()`

- `Void <_OnSendJoinTeamRequest>b__70_0(ActMultiV3JoinTeamResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryState : PopupFadeState, IValueMsgReceiver, IPopupCustomActive, ICompDialogCallBack
{
	public const Int32 ON_BTN_MANUAL_CLICKED; // 0x0
	public const Int32 ON_BTN_MILESTONE_CLICKED; // 0x0
	public const Int32 ON_BTN_REWARD_CLICKED; // 0x0
	public const Int32 ON_BTN_SQUAD_CLICKED; // 0x0
	public const Int32 ON_BTN_STAGE_CLICKED; // 0x0
	public const Int32 ON_BTN_TEAM_MATCH_CLICKED; // 0x0
	public const Int32 ON_BTN_QUICK_MATCH_CLICKED; // 0x0
	public const Int32 ON_BTN_MEDAL_CLICKED; // 0x0
	public const Int32 ON_INPUT_TEAM_ID_CHANGED; // 0x0
	public const Int32 ON_BTN_CREATE_TEAM_CLICKED; // 0x0
	public const Int32 ON_BTN_JOIN_TEAM_CLICKED; // 0x0
	public const Int32 ON_BTN_TRAINING_ROOM_CLICKED; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private ActMultiV3EntryView _view; // 0x78
	private UIAnimationLocation _animEntry; // 0x80
	private UIAnimationLocation _animExit; // 0x90
	private UIAnimationLocation _animMainToRoom; // 0xa0
	private UIAnimationLocation _animRoomToMain; // 0xb0
	private UIAnimationLocation _animMainToMatch; // 0xc0
	private ActMultiV3EntryJoinRoomMask _joinRoomMask; // 0xd0
	private ActMultiV3EntryProperty m_property; // 0xd8
	private Boolean m_inited; // 0xe0
	private String m_actId; // 0xe8
	private UIStateTransitionTween`1 m_transitionTween; // 0xf0
	private UIPageFinder m_pageFinder; // 0xf8
	private Coroutine m_entryHomeRoutedCoroutine; // 0x108
	private Coroutine m_teamViewRoutedCoroutine; // 0x110
	private ActMultiV3EntryPage m_page; // 0x118
	private UICompDialogMgr m_dlgMgr; // 0x120
	private Int32 m_squadNotEnoughConfirmDialog; // 0x128
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__GetAnimationTween; // 0x8
	private static DelegateBridge __Hotfix0__GetEntryAnimTween; // 0x10
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0_OnPause; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0__StopCoroutineIfNeed; // 0x48
	private static DelegateBridge __Hotfix0__RaiseAVGSignalIfNeed; // 0x50
	private static DelegateBridge __Hotfix0__WaitForTransFinishCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_UpdateDataOnGetInfo; // 0x60
	private static DelegateBridge __Hotfix0_EffectOnPage; // 0x68
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x70
	private static DelegateBridge __Hotfix0__OnJumpToMedalGroupDisplayState; // 0x78
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailState; // 0x80
	private static DelegateBridge __Hotfix0__OnJumpToStageListState; // 0x88
	private static DelegateBridge __Hotfix0__OnJumpToMatchState; // 0x90
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x98
	private static DelegateBridge __Hotfix0_OnMessage; // 0xa0
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0xa8
	private static DelegateBridge __Hotfix0__EventOnBtnManualClicked; // 0xb0
	private static DelegateBridge __Hotfix0__EventOnBtnRewardClicked; // 0xb8
	private static DelegateBridge __Hotfix0__EventOnBtnMilestoneClicked; // 0xc0
	private static DelegateBridge __Hotfix0__EventOnBtnMedalClicked; // 0xc8
	private static DelegateBridge __Hotfix0__EventOnBtnSquadClicked; // 0xd0
	private static DelegateBridge __Hotfix0__EventOnBtnStageClicked; // 0xd8
	private static DelegateBridge __Hotfix0__EventOnBtnTeamMatchClicked; // 0xe0
	private static DelegateBridge __Hotfix0__TryTriggerTeamTutorial; // 0xe8
	private static DelegateBridge __Hotfix0__WaitForFinishEnterRoom; // 0xf0
	private static DelegateBridge __Hotfix0__EventOnBtnQuickMatchClicked; // 0xf8
	private static DelegateBridge __Hotfix0__ClearQuickMatchTrackpoint; // 0x100
	private static DelegateBridge __Hotfix0__ShowSquadCountNotEnoughDialog; // 0x108
	private static DelegateBridge __Hotfix0__EventOnInputTeamIdChanged; // 0x110
	private static DelegateBridge __Hotfix0__EventOnBtnCreateTeamClicked; // 0x118
	private static DelegateBridge __Hotfix0__EventOnBtnJoinTeamClicked; // 0x120
	private static DelegateBridge __Hotfix0__EventOnBtnTrainingRoomClicked; // 0x128
	private static DelegateBridge __Hotfix0__OnCreateTeamRespHandle; // 0x130
	private static DelegateBridge __Hotfix0__OnSendJoinTeamRequest; // 0x138
	private static DelegateBridge __Hotfix0__OnJoinTeamRespHandle; // 0x140
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150


	// RVA: 0x30ea060 VA: 0x7595702060
	private Void _InitIfNot() { }
	// RVA: 0x30ea4d0 VA: 0x75957024d0
	private Tween _GetAnimationTween(UIAnimationLocation animationLocation, Boolean isInverse) { }
	// RVA: 0x30ea5bc VA: 0x75957025bc
	private Tween _GetEntryAnimTween() { }
	// RVA: 0x30ea740 VA: 0x7595702740
	private Boolean _IsUIStable() { }
	// RVA: 0x30ea884 VA: 0x7595702884
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30ea8e8 VA: 0x75957028e8
	protected override Void OnEnter() { }
	// RVA: 0x30eaf58 VA: 0x7595702f58
	protected override Void OnResume() { }
	// RVA: 0x30eb134 VA: 0x7595703134
	protected override Void OnPause() { }
	// RVA: 0x30eb294 VA: 0x7595703294
	protected override Void OnExit() { }
	// RVA: 0x30eb1a8 VA: 0x75957031a8
	private Void _StopCoroutineIfNeed() { }
	// RVA: 0x30eb034 VA: 0x7595703034
	private Void _RaiseAVGSignalIfNeed() { }
	// RVA: 0x30eb308 VA: 0x7595703308
	private IEnumerator _WaitForTransFinishCoroutine() { }
	// RVA: 0x30eb3dc VA: 0x75957033dc
	public Void UpdateDataOnGetInfo() { }
	// RVA: 0x30eb494 VA: 0x7595703494
	public Void EffectOnPage(ShowStatus showStatus, Boolean fastMode) { }
	// RVA: 0x30eb568 VA: 0x7595703568
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x30eb83c VA: 0x759570383c
	private Void _OnJumpToMedalGroupDisplayState(IStateBean stateBean) { }
	// RVA: 0x30eb978 VA: 0x7595703978
	private Void _OnJumpToRewardDetailState(IStateBean stateBean) { }
	// RVA: 0x30ebbf4 VA: 0x7595703bf4
	private Void _OnJumpToStageListState(IStateBean stateBean) { }
	// RVA: 0x30ebd44 VA: 0x7595703d44
	private Void _OnJumpToMatchState(IStateBean stateBean) { }
	// RVA: 0x30ebdc8 VA: 0x7595703dc8
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x30ebebc VA: 0x7595703ebc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x30ed300 VA: 0x7595705300
	private Void _EventOnBtnBack() { }
	// RVA: 0x30ec0b0 VA: 0x75957040b0
	private Void _EventOnBtnManualClicked() { }
	// RVA: 0x30ec300 VA: 0x7595704300
	private Void _EventOnBtnRewardClicked() { }
	// RVA: 0x30ec1c8 VA: 0x75957041c8
	private Void _EventOnBtnMilestoneClicked() { }
	// RVA: 0x30eca98 VA: 0x7595704a98
	private Void _EventOnBtnMedalClicked() { }
	// RVA: 0x30ec474 VA: 0x7595704474
	private Void _EventOnBtnSquadClicked() { }
	// RVA: 0x30ec5c4 VA: 0x75957045c4
	private Void _EventOnBtnStageClicked() { }
	// RVA: 0x30ec730 VA: 0x7595704730
	private Void _EventOnBtnTeamMatchClicked() { }
	// RVA: 0x30ed614 VA: 0x7595705614
	private Void _TryTriggerTeamTutorial() { }
	// RVA: 0x30ed864 VA: 0x7595705864
	private IEnumerator _WaitForFinishEnterRoom() { }
	// RVA: 0x30ec8c8 VA: 0x75957048c8
	private Void _EventOnBtnQuickMatchClicked() { }
	// RVA: 0x30ed938 VA: 0x7595705938
	private Void _ClearQuickMatchTrackpoint() { }
	// RVA: 0x30ed4d0 VA: 0x75957054d0
	private Void _ShowSquadCountNotEnoughDialog() { }
	// RVA: 0x30ecbd0 VA: 0x7595704bd0
	private Void _EventOnInputTeamIdChanged(String inputVal) { }
	// RVA: 0x30eccd8 VA: 0x7595704cd8
	private Void _EventOnBtnCreateTeamClicked() { }
	// RVA: 0x30ecf54 VA: 0x7595704f54
	private Void _EventOnBtnJoinTeamClicked() { }
	// RVA: 0x30ed174 VA: 0x7595705174
	private Void _EventOnBtnTrainingRoomClicked() { }
	// RVA: 0x30edbb4 VA: 0x7595705bb4
	private Void _OnCreateTeamRespHandle(ActMultiV3CreateTeamResponse resp) { }
	// RVA: 0x30ede5c VA: 0x7595705e5c
	private Void _OnSendJoinTeamRequest(String teamId) { }
	// RVA: 0x30ee058 VA: 0x7595706058
	private Void _OnJoinTeamRespHandle(ActMultiV3JoinTeamResponse resp) { }
	// RVA: 0x30ee314 VA: 0x7595706314
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x30ee444 VA: 0x7595706444
	public Void .ctor() { }
	// RVA: 0x30ee55c VA: 0x759570655c
	private Tween <_InitIfNot>b__31_0() { }
	// RVA: 0x30ee560 VA: 0x7595706560
	private Tween <_InitIfNot>b__31_1() { }
	// RVA: 0x30ee56c VA: 0x759570656c
	private Tween <_InitIfNot>b__31_2() { }
	// RVA: 0x30ee578 VA: 0x7595706578
	private Tween <_InitIfNot>b__31_3() { }
	// RVA: 0x30ee584 VA: 0x7595706584
	private Tween <_InitIfNot>b__31_4() { }
	// RVA: 0x30ee590 VA: 0x7595706590
	private Tween <_InitIfNot>b__31_5() { }
	// RVA: 0x30ee59c VA: 0x759570659c
	private Void <_OnSendJoinTeamRequest>b__70_0(ActMultiV3JoinTeamResponse response) { }
	// RVA: 0x30ee688 VA: 0x7595706688
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x30ee690 VA: 0x7595706690
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x30ee698 VA: 0x7595706698
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x30ee6a0 VA: 0x75957066a0
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x30ee6a8 VA: 0x75957066a8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```