# StagePreviewState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageStateBean _stateBean`

- `StagePreviewReplayView _replayView`

- `StagePreviewInfoNormalPanelHolder _dynNormalHolder`

- `StagePreviewInfoHardPanelHolder _dynHardHolder`

- `StagePreviewInfoSixStarPanelHolder _dynSixStarHolder`

- `Boolean m_isInited`

- `Int32 m_continusDialogInstId`

- `Int32 m_sixStarRuneSelectDialogInstId`

- `UIPageFinder m_uiPageFinder`


## Methods

- `Void _InitIfNot()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `StateRuntime _SaveToRuntime()`

- `Void _LoadFromRuntime(StateRuntime)`

- `Void OnStartBattleClick()`

- `Void OnOpenEnemyClick()`

- `Void OnOpenCampaginRules()`

- `Void OnOpenRewardClick()`

- `Void OnBeSpecial()`

- `Void OnBeNormal()`

- `Void OnOpenRewardHolder()`

- `Void OnContinuousBattleClick()`

- `Void _OnSelectedContinuousBattleTimes(Int32)`

- `Void OnStartPractiseClick()`

- `Void OnZoneMapEmptyAreaClicked()`

- `Void OnAutoBattleSwitchClick()`

- `Void OnReplayStoryOpenClick()`

- `Void OnReplayStoryTrigClick(Int32)`

- `Void OnAddedRecieveReward()`

- `Void OnLockedHardBattleClick()`

- `Void OnClosePreview()`

- `Void _OnGoToSquad(Boolean)`

- `StageViewModel _GetCurrentSelectedStageViewModel()`

- `Boolean _CheckCostBeforeStartBattle()`

- `Boolean _CheckIsGroupBattle()`

- `Boolean _CheckApBeforeStartBattle(Int32)`

- `Boolean _CheckEtBeforeStartBattle(String, Int32)`

- `Void _GoToSquad(Boolean)`

- `Boolean _CheckNeedToLoadBattleLog(out)`

- `Void _OnSixStarRuneSelectUpdate()`

- `Void _CheckAndTryTriggerSixStarAvg(String)`

- `Boolean _TryToTriggerSixStarAvg(String)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSwitchSixStarTagClick(StageSixStarRuneStatus)`

- `Void _OnSixStarRuneSelectBtnClick()`

- `Void _OnSixStarRewardGroupInfoBtnClick()`

- `Void <RegisterToDataListener>b__23_0(IStateBean)`

- `Void <OnAddedRecieveReward>b__41_0(GetMainlineCacheResponse)`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewState : StageBaseState, ICompDialogCallBack, IValueMsgReceiver
{
	public const Int32 MSG_SWITCH_SIX_STAR_RUNE_TAG; // 0x0
	public const Int32 MSG_SIX_STAR_RUNE_SELECT_BTN_CLICK; // 0x0
	public const Int32 MSG_SIX_STAR_REWARD_GROUP_BTN_CLICK; // 0x0
	private StageStateBean _stateBean; // 0x58
	private StagePreviewReplayView _replayView; // 0x60
	private StagePreviewInfoNormalPanelHolder _dynNormalHolder; // 0x68
	private StagePreviewInfoHardPanelHolder _dynHardHolder; // 0x70
	private StagePreviewInfoSixStarPanelHolder _dynSixStarHolder; // 0x78
	private StateCacheHandler`1 m_runtimeHandler; // 0x80
	private Boolean m_isInited; // 0x88
	private Int32 m_continusDialogInstId; // 0x8c
	private Int32 m_sixStarRuneSelectDialogInstId; // 0x90
	private UIPageFinder m_uiPageFinder; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x30
	private static DelegateBridge __Hotfix0_OnResume; // 0x38
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x40
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x48
	private static DelegateBridge __Hotfix0__SaveToRuntime; // 0x50
	private static DelegateBridge __Hotfix0__LoadFromRuntime; // 0x58
	private static DelegateBridge __Hotfix0_OnStartBattleClick; // 0x60
	private static DelegateBridge __Hotfix0_OnOpenEnemyClick; // 0x68
	private static DelegateBridge __Hotfix0_OnOpenCampaginRules; // 0x70
	private static DelegateBridge __Hotfix0_OnOpenRewardClick; // 0x78
	private static DelegateBridge __Hotfix0_OnBeSpecial; // 0x80
	private static DelegateBridge __Hotfix0_OnBeNormal; // 0x88
	private static DelegateBridge __Hotfix0_OnOpenRewardHolder; // 0x90
	private static DelegateBridge __Hotfix0_OnContinuousBattleClick; // 0x98
	private static DelegateBridge __Hotfix0__OnSelectedContinuousBattleTimes; // 0xa0
	private static DelegateBridge __Hotfix0_OnStartPractiseClick; // 0xa8
	private static DelegateBridge __Hotfix0_OnZoneMapEmptyAreaClicked; // 0xb0
	private static DelegateBridge __Hotfix0_OnAutoBattleSwitchClick; // 0xb8
	private static DelegateBridge __Hotfix0_OnReplayStoryOpenClick; // 0xc0
	private static DelegateBridge __Hotfix0_OnReplayStoryTrigClick; // 0xc8
	private static DelegateBridge __Hotfix0_OnAddedRecieveReward; // 0xd0
	private static DelegateBridge __Hotfix0_OnLockedHardBattleClick; // 0xd8
	private static DelegateBridge __Hotfix0_OnClosePreview; // 0xe0
	private static DelegateBridge __Hotfix0__OnGoToSquad; // 0xe8
	private static DelegateBridge __Hotfix0__GetCurrentSelectedStageViewModel; // 0xf0
	private static DelegateBridge __Hotfix0__CheckCostBeforeStartBattle; // 0xf8
	private static DelegateBridge __Hotfix0__CheckIsGroupBattle; // 0x100
	private static DelegateBridge __Hotfix0__CheckApBeforeStartBattle; // 0x108
	private static DelegateBridge __Hotfix0__CheckEtBeforeStartBattle; // 0x110
	private static DelegateBridge __Hotfix0__GoToSquad; // 0x118
	private static DelegateBridge __Hotfix0__CheckNeedToLoadBattleLog; // 0x120
	private static DelegateBridge __Hotfix0__OnSixStarRuneSelectUpdate; // 0x128
	private static DelegateBridge __Hotfix0__CheckAndTryTriggerSixStarAvg; // 0x130
	private static DelegateBridge __Hotfix0__TryToTriggerSixStarAvg; // 0x138
	private static DelegateBridge __Hotfix0_OnMessage; // 0x140
	private static DelegateBridge __Hotfix0__OnSwitchSixStarTagClick; // 0x148
	private static DelegateBridge __Hotfix0__OnSixStarRuneSelectBtnClick; // 0x150
	private static DelegateBridge __Hotfix0__OnSixStarRewardGroupInfoBtnClick; // 0x158
	private static DelegateBridge _c__Hotfix0_ctor; // 0x160

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2f6ae88 VA: 0x7595582e88
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f6aef0 VA: 0x7595582ef0
	private Void _InitIfNot() { }
	// RVA: 0x2f6b4fc VA: 0x75955834fc
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x2f6b690 VA: 0x7595583690
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x2f6b820 VA: 0x7595583820
	protected override Void OnExit() { }
	// RVA: 0x2f6b8ec VA: 0x75955838ec
	protected override Void OnEnter() { }
	// RVA: 0x2f6bb0c VA: 0x7595583b0c
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2f6bc90 VA: 0x7595583c90
	protected override Void OnResume() { }
	// RVA: 0x2f6bd00 VA: 0x7595583d00
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2f6bf64 VA: 0x7595583f64
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2f6c290 VA: 0x7595584290
	private StateRuntime _SaveToRuntime() { }
	// RVA: 0x2f6c3a4 VA: 0x75955843a4
	private Void _LoadFromRuntime(StateRuntime runtime) { }
	// RVA: 0x2f6c50c VA: 0x759558450c
	public Void OnStartBattleClick() { }
	// RVA: 0x2f6cbcc VA: 0x7595584bcc
	public Void OnOpenEnemyClick() { }
	// RVA: 0x2f6cd84 VA: 0x7595584d84
	public Void OnOpenCampaginRules() { }
	// RVA: 0x2f6ce9c VA: 0x7595584e9c
	public Void OnOpenRewardClick() { }
	// RVA: 0x2f6cfb4 VA: 0x7595584fb4
	public Void OnBeSpecial() { }
	// RVA: 0x2f6d0e8 VA: 0x75955850e8
	public Void OnBeNormal() { }
	// RVA: 0x2f6d1a4 VA: 0x75955851a4
	public Void OnOpenRewardHolder() { }
	// RVA: 0x2f6d2cc VA: 0x75955852cc
	public Void OnContinuousBattleClick() { }
	// RVA: 0x2f6c034 VA: 0x7595584034
	private Void _OnSelectedContinuousBattleTimes(Int32 times) { }
	// RVA: 0x2f6d66c VA: 0x759558566c
	public Void OnStartPractiseClick() { }
	// RVA: 0x2f6d9c8 VA: 0x75955859c8
	public Void OnZoneMapEmptyAreaClicked() { }
	// RVA: 0x2f6db0c VA: 0x7595585b0c
	public Void OnAutoBattleSwitchClick() { }
	// RVA: 0x2f6db80 VA: 0x7595585b80
	public Void OnReplayStoryOpenClick() { }
	// RVA: 0x2f6dc58 VA: 0x7595585c58
	public Void OnReplayStoryTrigClick(Int32 index) { }
	// RVA: 0x2f6ded4 VA: 0x7595585ed4
	public Void OnAddedRecieveReward() { }
	// RVA: 0x2f6e0fc VA: 0x75955860fc
	public Void OnLockedHardBattleClick() { }
	// RVA: 0x2f6e1dc VA: 0x75955861dc
	public Void OnClosePreview() { }
	// RVA: 0x2f6e320 VA: 0x7595586320
	private Void _OnGoToSquad(Boolean isPractice) { }
	// RVA: 0x2f6d84c VA: 0x759558584c
	private StageViewModel _GetCurrentSelectedStageViewModel() { }
	// RVA: 0x2f6c59c VA: 0x759558459c
	private Boolean _CheckCostBeforeStartBattle() { }
	// RVA: 0x2f6eca0 VA: 0x7595586ca0
	private Boolean _CheckIsGroupBattle() { }
	// RVA: 0x2f6eb24 VA: 0x7595586b24
	private Boolean _CheckApBeforeStartBattle(Int32 apCost) { }
	// RVA: 0x2f6e9ec VA: 0x75955869ec
	private Boolean _CheckEtBeforeStartBattle(String etItemId, Int32 etCost) { }
	// RVA: 0x2f6c6a4 VA: 0x75955846a4
	private Void _GoToSquad(Boolean isPractice) { }
	// RVA: 0x2f6ed24 VA: 0x7595586d24
	private Boolean _CheckNeedToLoadBattleLog(out Boolean allowNoBattleLog) { }
	// RVA: 0x2f6c14c VA: 0x759558414c
	private Void _OnSixStarRuneSelectUpdate() { }
	// RVA: 0x2f6ba30 VA: 0x7595583a30
	private Void _CheckAndTryTriggerSixStarAvg(String normalStageId) { }
	// RVA: 0x2f6ee64 VA: 0x7595586e64
	private Boolean _TryToTriggerSixStarAvg(String operationKey) { }
	// RVA: 0x2f6ef3c VA: 0x7595586f3c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f6f020 VA: 0x7595587020
	private Void _OnSwitchSixStarTagClick(StageSixStarRuneStatus newStatus) { }
	// RVA: 0x2f6f13c VA: 0x759558713c
	private Void _OnSixStarRuneSelectBtnClick() { }
	// RVA: 0x2f6f3d4 VA: 0x75955873d4
	private Void _OnSixStarRewardGroupInfoBtnClick() { }
	// RVA: 0x2f6f58c VA: 0x759558758c
	public Void .ctor() { }
	// RVA: 0x2f6f600 VA: 0x7595587600
	private Void <RegisterToDataListener>b__23_0(IStateBean _) { }
	// RVA: 0x2f6f624 VA: 0x7595587624
	private Void <OnAddedRecieveReward>b__41_0(GetMainlineCacheResponse response) { }
	// RVA: 0x2f6f6d4 VA: 0x75955876d4
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2f6f6dc VA: 0x75955876dc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f6f6e4 VA: 0x75955876e4
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x2f6f6ec VA: 0x75955876ec
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2f6f6f0 VA: 0x75955876f0
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```