# ActMultiV3QuickMatchState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3QuickMatchView _view`

- `ActMultiV3MatchingView _matchingPrefab`

- `RectTransform _matchingContainer`

- `RectTransform _topMenuContainer`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `ActMultiV3QuickMatchStateBean m_stateBean`

- `ActMultiV3MatchingView m_matchingView`

- `Int32 m_trainingStageConfirmDlgInstId`

- `String m_cacheStageId`

- `ActMultiV3MapModeType m_cacheModeType`

- `LoopRequestSender m_loopSender`


## Methods

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Boolean _OnInitMatchResponse(ActMultiV3StartMatchResponse)`

- `Boolean _CreateInitRequest(out, out)`

- `Void _OnLoopSenderTick(Single)`

- `Boolean _CreateCancelRequest(out, out)`

- `Boolean _CreateQueryRequest(out, out)`

- `Boolean _CreateMatchQueryRequest(Boolean, out, out)`

- `Boolean _OnQueryMatchResponse(ActMultiV3QueryMatchResponse)`

- `Void _EventOnBtnBack()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnNavToRoom()`

- `Void _EventOnCancelMatchClick()`

- `Void _EventOnPosItemClick(String)`

- `Void _EventOnDiffItemClick(String)`

- `Void _StartGuideBattle(ActMultiV3MapModeType)`

- `ILoadAsset _GetAsssetLoader()`

- `Void _EventOnTrainingClick(String)`

- `Void _EventOnInverseToggle()`

- `Boolean _CheckIfSuccess(ActMultiV3StartMatchResponse, ActMultiV3QuickMatchModel, out)`

- `Void EventOnPosPanelRaycastClick()`

- `Void EventOnBtnPosClick()`

- `Void EventOnBtnStartMatch()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3QuickMatchState : State, IValueMsgReceiver, ICompDialogCallBack
{
	private const Int32 QUERY_REQUEST_INTERVAL; // 0x0
	public const Int32 MSG_DIFF_ITEM_CLICK; // 0x0
	public const Int32 MSG_POS_ITEM_CLICK; // 0x0
	public const Int32 MSG_INVERSE_TOGGLE_CLICK; // 0x0
	public const Int32 MSG_CANCEL_MATCH_CLICK; // 0x0
	public const Int32 MSG_NAV_TO_MATCH_ROOM; // 0x0
	public const Int32 MSG_TRAINING_ITEM_CLICK; // 0x0
	private ActMultiV3QuickMatchView _view; // 0x50
	private ActMultiV3MatchingView _matchingPrefab; // 0x58
	private RectTransform _matchingContainer; // 0x60
	private RectTransform _topMenuContainer; // 0x68
	private Boolean m_hasInited; // 0x70
	private UIPageFinder m_pageFinder; // 0x78
	private ActMultiV3QuickMatchStateBean m_stateBean; // 0x88
	private ActMultiV3MatchingView m_matchingView; // 0x90
	private Int32 m_trainingStageConfirmDlgInstId; // 0x98
	private String m_cacheStageId; // 0xa0
	private ActMultiV3MapModeType m_cacheModeType; // 0xa8
	private LoopRequestSender m_loopSender; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__OnInitMatchResponse; // 0x30
	private static DelegateBridge __Hotfix0__CreateInitRequest; // 0x38
	private static DelegateBridge __Hotfix0__OnLoopSenderTick; // 0x40
	private static DelegateBridge __Hotfix0__CreateCancelRequest; // 0x48
	private static DelegateBridge __Hotfix0__CreateQueryRequest; // 0x50
	private static DelegateBridge __Hotfix0__CreateMatchQueryRequest; // 0x58
	private static DelegateBridge __Hotfix0__OnQueryMatchResponse; // 0x60
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x68
	private static DelegateBridge __Hotfix0_OnMessage; // 0x70
	private static DelegateBridge __Hotfix0__EventOnNavToRoom; // 0x78
	private static DelegateBridge __Hotfix0__EventOnCancelMatchClick; // 0x80
	private static DelegateBridge __Hotfix0__EventOnPosItemClick; // 0x88
	private static DelegateBridge __Hotfix0__EventOnDiffItemClick; // 0x90
	private static DelegateBridge __Hotfix0__StartGuideBattle; // 0x98
	private static DelegateBridge __Hotfix0__GetAsssetLoader; // 0xa0
	private static DelegateBridge __Hotfix0__EventOnTrainingClick; // 0xa8
	private static DelegateBridge __Hotfix0__EventOnInverseToggle; // 0xb0
	private static DelegateBridge __Hotfix0__CheckIfSuccess; // 0xb8
	private static DelegateBridge __Hotfix0_EventOnPosPanelRaycastClick; // 0xc0
	private static DelegateBridge __Hotfix0_EventOnBtnPosClick; // 0xc8
	private static DelegateBridge __Hotfix0_EventOnBtnStartMatch; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8


	// RVA: 0x3129db0 VA: 0x7595741db0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3129e18 VA: 0x7595741e18
	protected override Void OnEnter() { }
	// RVA: 0x312a5d8 VA: 0x75957425d8
	protected override Void OnResume() { }
	// RVA: 0x312a6d4 VA: 0x75957426d4
	protected override Void OnExit() { }
	// RVA: 0x312a75c VA: 0x759574275c
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x3129f9c VA: 0x7595741f9c
	private Void _InitIfNot() { }
	// RVA: 0x312a864 VA: 0x7595742864
	private Boolean _OnInitMatchResponse(ActMultiV3StartMatchResponse response) { }
	// RVA: 0x312ab68 VA: 0x7595742b68
	private Boolean _CreateInitRequest(out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x312ae40 VA: 0x7595742e40
	private Void _OnLoopSenderTick(Single waitSec) { }
	// RVA: 0x312af2c VA: 0x7595742f2c
	private Boolean _CreateCancelRequest(out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x312b1f8 VA: 0x75957431f8
	private Boolean _CreateQueryRequest(out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x312afbc VA: 0x7595742fbc
	private Boolean _CreateMatchQueryRequest(Boolean isCancel, out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x312b288 VA: 0x7595743288
	private Boolean _OnQueryMatchResponse(ActMultiV3QueryMatchResponse response) { }
	// RVA: 0x312b428 VA: 0x7595743428
	private Void _EventOnBtnBack() { }
	// RVA: 0x312b4f4 VA: 0x75957434f4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x312bb6c VA: 0x7595743b6c
	private Void _EventOnNavToRoom() { }
	// RVA: 0x312baf0 VA: 0x7595743af0
	private Void _EventOnCancelMatchClick() { }
	// RVA: 0x312b7b0 VA: 0x75957437b0
	private Void _EventOnPosItemClick(String posTypeStr) { }
	// RVA: 0x312b638 VA: 0x7595743638
	private Void _EventOnDiffItemClick(String modeId) { }
	// RVA: 0x312be50 VA: 0x7595743e50
	private Void _StartGuideBattle(ActMultiV3MapModeType modeType) { }
	// RVA: 0x312aaf8 VA: 0x7595742af8
	private ILoadAsset _GetAsssetLoader() { }
	// RVA: 0x312bdb0 VA: 0x7595743db0
	private Void _EventOnTrainingClick(String modeTypeStr) { }
	// RVA: 0x312b9b8 VA: 0x75957439b8
	private Void _EventOnInverseToggle() { }
	// RVA: 0x312a9bc VA: 0x75957429bc
	private Boolean _CheckIfSuccess(ActMultiV3StartMatchResponse response, ActMultiV3QuickMatchModel viewModel, out String toastStr) { }
	// RVA: 0x312c0e4 VA: 0x75957440e4
	public Void EventOnPosPanelRaycastClick() { }
	// RVA: 0x312c1cc VA: 0x75957441cc
	public Void EventOnBtnPosClick() { }
	// RVA: 0x312c2b4 VA: 0x75957442b4
	public Void EventOnBtnStartMatch() { }
	// RVA: 0x312c400 VA: 0x7595744400
	public Void .ctor() { }
	// RVA: 0x312c4b0 VA: 0x75957444b0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x312c4b8 VA: 0x75957444b8
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x312c4c0 VA: 0x75957444c0
	private Void <>xLuaBaseProxy_OnExit() { }
}
```