# EnemyDuelEntryState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `RectTransform _backBtnRt`

- `EnemyDuelEntryView _enemyDuelEntryView`

- `Single _enterOpenMainDelay`

- `Single _enterShowGuideBookDelay`

- `UIAnimationLocation _enterAnim`

- `EnemyDuelEntryTimeLineView _timeLineView`

- `RectTransform _frontLoopAnimContainer`

- `RectTransform _backLoopAnimContainer`

- `RawImage _bgRtImage`

- `Boolean m_isInited`

- `String m_actId`

- `Tween m_animTween`

- `Int32 m_dailyDialog`

- `Int32 m_rewardDialog`

- `EnemyDuelEntryPage m_page`

- `EnemyDuelEntryStateBean m_stateBean`

- `EnemyDuelEntryAnimHolder m_backLoopHolder`

- `EnemyDuelEntryAnimHolder m_frontLoopHolder`

- `EnemyDuelEntryAnimHolder m_spineLoopHolder`


## Properties

- `String actId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `String get_actId()`

- `Void _InitIfNot()`

- `Void _BuildDynLoopAnimHolder()`

- `Void _BindBackRT(RenderTexture)`

- `Void _UnBindBackRT()`

- `Void OnDestroy()`

- `Void TriggerEntryAnim(Action)`

- `Void ResetEntryAnim(Boolean)`

- `Void _OnEnterAnimEndOpenWnd()`

- `Boolean _CheckIfAnimPlaying()`

- `Void _CancelTweenIfNeeded()`

- `Boolean _CheckNeedAutoShow()`

- `Void _TryConsumeGuideBookAutoShow()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _UpdateData()`

- `Void _OnDialogClick(String, TDialogParam, Int32, out)`

- `Void _OnBackClickImpl()`

- `Void _OnMainWindowClick()`

- `Void _OnOpenMainWindow()`

- `Void _OnMusicWindowClick()`

- `Void _OnMainWindowCloseClick()`

- `Void _OnMusicWindowCloseClick()`

- `Void _OnHomeClick()`

- `Void _OnMileStoneClick()`

- `Void _OnEnterRoomClick()`

- `Boolean _CheckPassPreposedMode()`

- `Void _ResetAllWnd(Boolean, Boolean)`

- `Void _OnMedalClick()`

- `Void _OnCreateRoomClick()`

- `Void _OnMatchClick()`

- `Void _PlayLoopAnims()`

- `Void _StopLoopAnimsIfNeeded()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryState : PopupFadeState, IValueMsgReceiver, ICompDialogCallBack, IHotfixable
{
	private const String GUIDE_SUB_SIGNAL; // 0x0
	private const Int32 INPUT_MAX_CNT; // 0x0
	private RectTransform _backBtnRt; // 0x70
	private EnemyDuelEntryView _enemyDuelEntryView; // 0x78
	private Single _enterOpenMainDelay; // 0x80
	private Single _enterShowGuideBookDelay; // 0x84
	private UIAnimationLocation _enterAnim; // 0x88
	private UIAnimationLocation[] _loopAnims; // 0x98
	private EnemyDuelEntryTimeLineView _timeLineView; // 0xa0
	private RectTransform _frontLoopAnimContainer; // 0xa8
	private RectTransform _backLoopAnimContainer; // 0xb0
	private RawImage _bgRtImage; // 0xb8
	private Boolean m_isInited; // 0xc0
	private String m_actId; // 0xc8
	private Tween m_animTween; // 0xd0
	private List`1 m_loopTweens; // 0xd8
	private Int32 m_dailyDialog; // 0xe0
	private Int32 m_rewardDialog; // 0xe4
	private EnemyDuelEntryPage m_page; // 0xe8
	private EnemyDuelEntryStateBean m_stateBean; // 0xf0
	private EnemyDuelEntryAnimHolder m_backLoopHolder; // 0xf8
	private EnemyDuelEntryAnimHolder m_frontLoopHolder; // 0x100
	private EnemyDuelEntryAnimHolder m_spineLoopHolder; // 0x108
	public const Int32 ON_BACK_CLICK; // 0x0
	public const Int32 ON_MAIN_WINDOW_CLICK; // 0x0
	public const Int32 ON_MUSIC_WINDOW_CLICK; // 0x0
	public const Int32 ON_MAIN_WINDOW_CLOSE_CLICK; // 0x0
	public const Int32 ON_MUSIC_WINDOW_CLOSE_CLICK; // 0x0
	public const Int32 ON_HOME_CLICK; // 0x0
	public const Int32 ON_MILESTONE_CLICK; // 0x0
	public const Int32 ON_DAILY_CLICK; // 0x0
	public const Int32 ON_ENTER_ROOM_CLICK; // 0x0
	public const Int32 ON_CREATE_ROOM_CLICK; // 0x0
	public const Int32 ON_MATCH_CLICK; // 0x0
	public const Int32 ON_REWARD_CLICK; // 0x0
	public const Int32 ON_MEDAL_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0_get_actId; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__BuildDynLoopAnimHolder; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0__BindBackRT; // 0x30
	private static DelegateBridge __Hotfix0__UnBindBackRT; // 0x38
	private static DelegateBridge __Hotfix0_OnResume; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0_TriggerEntryAnim; // 0x50
	private static DelegateBridge __Hotfix0_ResetEntryAnim; // 0x58
	private static DelegateBridge __Hotfix0__OnEnterAnimEndOpenWnd; // 0x60
	private static DelegateBridge __Hotfix0__CheckIfAnimPlaying; // 0x68
	private static DelegateBridge __Hotfix0__CancelTweenIfNeeded; // 0x70
	private static DelegateBridge __Hotfix0__CheckNeedAutoShow; // 0x78
	private static DelegateBridge __Hotfix0__TryConsumeGuideBookAutoShow; // 0x80
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x88
	private static DelegateBridge __Hotfix0__UpdateData; // 0x90
	private static DelegateBridge __Hotfix0__OnDialogClick; // 0x98
	private static DelegateBridge __Hotfix0__OnBackClickImpl; // 0xa0
	private static DelegateBridge __Hotfix0__OnMainWindowClick; // 0xa8
	private static DelegateBridge __Hotfix0__OnOpenMainWindow; // 0xb0
	private static DelegateBridge __Hotfix0__OnMusicWindowClick; // 0xb8
	private static DelegateBridge __Hotfix0__OnMainWindowCloseClick; // 0xc0
	private static DelegateBridge __Hotfix0__OnMusicWindowCloseClick; // 0xc8
	private static DelegateBridge __Hotfix0__OnHomeClick; // 0xd0
	private static DelegateBridge __Hotfix0__OnMileStoneClick; // 0xd8
	private static DelegateBridge __Hotfix0__OnEnterRoomClick; // 0xe0
	private static DelegateBridge __Hotfix0__CheckPassPreposedMode; // 0xe8
	private static DelegateBridge __Hotfix0__ResetAllWnd; // 0xf0
	private static DelegateBridge __Hotfix0__OnMedalClick; // 0xf8
	private static DelegateBridge __Hotfix0__OnCreateRoomClick; // 0x100
	private static DelegateBridge __Hotfix0__OnMatchClick; // 0x108
	private static DelegateBridge __Hotfix0__PlayLoopAnims; // 0x110
	private static DelegateBridge __Hotfix0__StopLoopAnimsIfNeeded; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	public String actId { get; }

	// RVA: 0x2947110 VA: 0x7594f5f110
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2947178 VA: 0x7594f5f178
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x29486f8 VA: 0x7594f606f8
	public String get_actId() { }
	// RVA: 0x29487e4 VA: 0x7594f607e4
	private Void _InitIfNot() { }
	// RVA: 0x2948958 VA: 0x7594f60958
	private Void _BuildDynLoopAnimHolder() { }
	// RVA: 0x2949078 VA: 0x7594f61078
	protected override Void OnEnter() { }
	// RVA: 0x29491e8 VA: 0x7594f611e8
	private Void _BindBackRT(RenderTexture texture) { }
	// RVA: 0x29493f4 VA: 0x7594f613f4
	private Void _UnBindBackRT() { }
	// RVA: 0x29494b4 VA: 0x7594f614b4
	protected override Void OnResume() { }
	// RVA: 0x29496f0 VA: 0x7594f616f0
	private Void OnDestroy() { }
	// RVA: 0x2946c60 VA: 0x7594f5ec60
	public Void TriggerEntryAnim(Action onAnimFinish) { }
	// RVA: 0x294701c VA: 0x7594f5f01c
	public Void ResetEntryAnim(Boolean isShow) { }
	// RVA: 0x2949aa0 VA: 0x7594f61aa0
	private Void _OnEnterAnimEndOpenWnd() { }
	// RVA: 0x2949c24 VA: 0x7594f61c24
	private Boolean _CheckIfAnimPlaying() { }
	// RVA: 0x29498c4 VA: 0x7594f618c4
	private Void _CancelTweenIfNeeded() { }
	// RVA: 0x2949964 VA: 0x7594f61964
	private Boolean _CheckNeedAutoShow() { }
	// RVA: 0x2949a18 VA: 0x7594f61a18
	private Void _TryConsumeGuideBookAutoShow() { }
	// RVA: 0x2949ca0 VA: 0x7594f61ca0
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2949528 VA: 0x7594f61528
	private Void _UpdateData() { }
	// RVA: 0x VA: 0x0
	private Void _OnDialogClick(String dialogPath, TDialogParam dialogParam, Int32 dialogInstIn, out Int32 dialogInstOut) { }
	// RVA: 0x2947424 VA: 0x7594f5f424
	private Void _OnBackClickImpl() { }
	// RVA: 0x294755c VA: 0x7594f5f55c
	private Void _OnMainWindowClick() { }
	// RVA: 0x2949b50 VA: 0x7594f61b50
	private Void _OnOpenMainWindow() { }
	// RVA: 0x2947650 VA: 0x7594f5f650
	private Void _OnMusicWindowClick() { }
	// RVA: 0x294773c VA: 0x7594f5f73c
	private Void _OnMainWindowCloseClick() { }
	// RVA: 0x2947818 VA: 0x7594f5f818
	private Void _OnMusicWindowCloseClick() { }
	// RVA: 0x29478f4 VA: 0x7594f5f8f4
	private Void _OnHomeClick() { }
	// RVA: 0x2947a64 VA: 0x7594f5fa64
	private Void _OnMileStoneClick() { }
	// RVA: 0x29481b0 VA: 0x7594f601b0
	private Void _OnEnterRoomClick() { }
	// RVA: 0x294a0d8 VA: 0x7594f620d8
	private Boolean _CheckPassPreposedMode() { }
	// RVA: 0x29492fc VA: 0x7594f612fc
	private Void _ResetAllWnd(Boolean isMainShow, Boolean isMusicShow) { }
	// RVA: 0x2948560 VA: 0x7594f60560
	private Void _OnMedalClick() { }
	// RVA: 0x2947c68 VA: 0x7594f5fc68
	private Void _OnCreateRoomClick() { }
	// RVA: 0x2947e44 VA: 0x7594f5fe44
	private Void _OnMatchClick() { }
	// RVA: 0x2948b28 VA: 0x7594f60b28
	private Void _PlayLoopAnims() { }
	// RVA: 0x2949760 VA: 0x7594f61760
	private Void _StopLoopAnimsIfNeeded() { }
	// RVA: 0x294a7d0 VA: 0x7594f627d0
	public Void .ctor() { }
	// RVA: 0x294a984 VA: 0x7594f62984
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x294a98c VA: 0x7594f6298c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```