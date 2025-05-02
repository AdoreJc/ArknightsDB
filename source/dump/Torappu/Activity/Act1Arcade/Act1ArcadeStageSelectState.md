# Act1ArcadeStageSelectState

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeStageDetailView _stageDetailView`

- `Act1ArcadeStageSelectBottomInfoView _bottomInfoView`

- `UIAnimationLocation _entryAnim`

- `UIAnimationLocation _leaveAnim`

- `CanvasGroup _rootGroup`

- `Act1ArcadeToast _notifyToastPrefab`

- `Boolean m_isInited`

- `Int32 m_dialogInst`

- `Boolean m_blockClick`

- `Tween m_animTween`

- `Act1ArcadeStageSelectStateBean m_stateBean`

- `Boolean m_isFromBattle`

- `Int32 m_scoreInfoInstId`


## Methods

- `Void _OnClickBack()`

- `Void _InitIfNot()`

- `Void _InitStageItems(Act1ArcadeStageSelectViewModel)`

- `Boolean _IsUIStable()`

- `Void _JumpToBadgeState(IStateBean)`

- `Void _NotifyToast(String)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnZoneTagClicked(String)`

- `Void _EventOnStageTagClicked(String)`

- `Void _EventOnEnterStageClicked()`

- `Void _EventOnEnemyHandBookClicked()`

- `Void _EventOnMapClicked()`

- `Void _EventOnBadgeClicked()`

- `Void _EventOnScoreInfoClicked()`

- `Boolean <ShowCoroutine>b__40_0()`

- `Boolean <HideCoroutine>b__41_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageSelectState : UIPopupState, IValueMsgReceiver
{
	private List`1 _zoneEntryItemViews; // 0x60
	private List`1 _stageTagItemViews; // 0x68
	private Act1ArcadeStageDetailView _stageDetailView; // 0x70
	private Act1ArcadeStageSelectBottomInfoView _bottomInfoView; // 0x78
	private UIAnimationLocation _entryAnim; // 0x80
	private UIAnimationLocation _leaveAnim; // 0x90
	private CanvasGroup _rootGroup; // 0xa0
	private Act1ArcadeToast _notifyToastPrefab; // 0xa8
	private Boolean m_isInited; // 0xb0
	private Int32 m_dialogInst; // 0xb4
	private Boolean m_blockClick; // 0xb8
	private Tween m_animTween; // 0xc0
	private Act1ArcadeStageSelectStateBean m_stateBean; // 0xc8
	private Boolean m_isFromBattle; // 0xd0
	private Int32 m_scoreInfoInstId; // 0xd4
	public const Int32 MSG_ZONE_TAG_CLICK; // 0x0
	public const Int32 MSG_STAGE_TAG_CLICK; // 0x0
	public const Int32 MSG_ENTER_STAGE_CLICK; // 0x0
	public const Int32 MSG_ENEMY_HANDBOOK_CLICK; // 0x0
	public const Int32 MSG_MAP_CLICK; // 0x0
	public const Int32 MSG_BADGE_CLICK; // 0x0
	public const Int32 MSG_SCORE_INFO_CLICK; // 0x0
	private static DelegateBridge __Hotfix0__OnClickBack; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__InitStageItems; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x30
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x38
	private static DelegateBridge __Hotfix0__JumpToBadgeState; // 0x40
	private static DelegateBridge __Hotfix0__NotifyToast; // 0x48
	private static DelegateBridge __Hotfix0_OnMessage; // 0x50
	private static DelegateBridge __Hotfix0__EventOnZoneTagClicked; // 0x58
	private static DelegateBridge __Hotfix0__EventOnStageTagClicked; // 0x60
	private static DelegateBridge __Hotfix0__EventOnEnterStageClicked; // 0x68
	private static DelegateBridge __Hotfix0__EventOnEnemyHandBookClicked; // 0x70
	private static DelegateBridge __Hotfix0__EventOnMapClicked; // 0x78
	private static DelegateBridge __Hotfix0__EventOnBadgeClicked; // 0x80
	private static DelegateBridge __Hotfix0__EventOnScoreInfoClicked; // 0x88
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x90
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x98
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0xa0
	private static DelegateBridge __Hotfix0_HideImmediately; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0


	// RVA: 0x3410124 VA: 0x7595a28124
	private Void _OnClickBack() { }
	// RVA: 0x3410240 VA: 0x7595a28240
	private Void _InitIfNot() { }
	// RVA: 0x341049c VA: 0x7595a2849c
	private Void _InitStageItems(Act1ArcadeStageSelectViewModel stageSelectModel) { }
	// RVA: 0x3410880 VA: 0x7595a28880
	public override IStateBean GetCacheBean() { }
	// RVA: 0x34108e8 VA: 0x7595a288e8
	protected override Void OnEnter() { }
	// RVA: 0x3410eb0 VA: 0x7595a28eb0
	protected override Void OnResume() { }
	// RVA: 0x3410f78 VA: 0x7595a28f78
	private Boolean _IsUIStable() { }
	// RVA: 0x34110c8 VA: 0x7595a290c8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3411240 VA: 0x7595a29240
	private Void _JumpToBadgeState(IStateBean stateBean) { }
	// RVA: 0x3411368 VA: 0x7595a29368
	private Void _NotifyToast(String toastStr) { }
	// RVA: 0x3411448 VA: 0x7595a29448
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x34115e8 VA: 0x7595a295e8
	private Void _EventOnZoneTagClicked(String selectZoneId) { }
	// RVA: 0x341176c VA: 0x7595a2976c
	private Void _EventOnStageTagClicked(String selectStageId) { }
	// RVA: 0x34118cc VA: 0x7595a298cc
	private Void _EventOnEnterStageClicked() { }
	// RVA: 0x3411d34 VA: 0x7595a29d34
	private Void _EventOnEnemyHandBookClicked() { }
	// RVA: 0x3411e64 VA: 0x7595a29e64
	private Void _EventOnMapClicked() { }
	// RVA: 0x3412090 VA: 0x7595a2a090
	private Void _EventOnBadgeClicked() { }
	// RVA: 0x3412260 VA: 0x7595a2a260
	private Void _EventOnScoreInfoClicked() { }
	// RVA: 0x3412488 VA: 0x7595a2a488
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x3412600 VA: 0x7595a2a600
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x3412778 VA: 0x7595a2a778
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x34128c8 VA: 0x7595a2a8c8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x34129f0 VA: 0x7595a2a9f0
	public Void .ctor() { }
	// RVA: 0x3412a9c VA: 0x7595a2aa9c
	private Boolean <ShowCoroutine>b__40_0() { }
	// RVA: 0x3412ab0 VA: 0x7595a2aab0
	private Boolean <HideCoroutine>b__41_0() { }
	// RVA: 0x3412ac4 VA: 0x7595a2aac4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3412acc VA: 0x7595a2aacc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3412ad4 VA: 0x7595a2aad4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```