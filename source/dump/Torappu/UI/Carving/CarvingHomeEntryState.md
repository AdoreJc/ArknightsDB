# CarvingHomeEntryState

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingHomeEntryChallengeInfoView _infoView`

- `CarvingHomeEntryChallengeGroupView _groupView`

- `CarvingHomeEntryPageGroupView _pageGroupView`

- `UIAnimationLocation _entryAnim`

- `RectTransform _backRect`

- `CarvingHomeEntryStateBean m_stateBean`

- `Boolean m_hasInited`

- `Int32 m_introDialogInstId`

- `Int32 m_confirmDialogInstId`

- `Int32 m_settleDialogInstId`

- `Int32 m_handbookDialogInstId`

- `Tween m_entryAnim`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `String _GetActivityId()`

- `Void _GenerateEntryAnim()`

- `Void _EventOnBackBtnClicked()`

- `Void _EventOnOpenIntroDialog()`

- `Void _EventOnNextBtnClicked()`

- `Void _EventOnPrevBtnClicked()`

- `Void _EventOnStartChallengeBtnClicked()`

- `Void _OpenCarvingMainPage(CarvingCreateGameResponse)`

- `Void _EventOnSettleChallengeBtnClicked()`

- `Void _EventOnHandbookBtnClicked()`

- `Void _OnSettleChallengeConfirm()`

- `Void _OnSettleProceed(CarvingSettleResponse)`

- `Void _TryConsumeGuidebook()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomeEntryState : State, IValueMsgReceiver, ICompDialogCallBack, IHotfixable
{
	public const Int32 ON_NEXT_BTN_CLICKED; // 0x0
	public const Int32 ON_PREV_BTN_CLICKED; // 0x0
	public const Int32 ON_START_CHALLENGE_BTN_CLICKED; // 0x0
	public const Int32 ON_SETTLE_CHALLENGE_BTN_CLICKED; // 0x0
	public const Int32 ON_HANDBOOK_BTN_CLICKED; // 0x0
	private CarvingHomeEntryChallengeInfoView _infoView; // 0x50
	private CarvingHomeEntryChallengeGroupView _groupView; // 0x58
	private CarvingHomeEntryPageGroupView _pageGroupView; // 0x60
	private UIAnimationLocation _entryAnim; // 0x68
	private RectTransform _backRect; // 0x78
	private CarvingHomeEntryStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private Int32 m_introDialogInstId; // 0x8c
	private Int32 m_confirmDialogInstId; // 0x90
	private Int32 m_settleDialogInstId; // 0x94
	private Int32 m_handbookDialogInstId; // 0x98
	private Tween m_entryAnim; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__GetActivityId; // 0x38
	private static DelegateBridge __Hotfix0__GenerateEntryAnim; // 0x40
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__EventOnOpenIntroDialog; // 0x50
	private static DelegateBridge __Hotfix0__EventOnNextBtnClicked; // 0x58
	private static DelegateBridge __Hotfix0__EventOnPrevBtnClicked; // 0x60
	private static DelegateBridge __Hotfix0__EventOnStartChallengeBtnClicked; // 0x68
	private static DelegateBridge __Hotfix0__OpenCarvingMainPage; // 0x70
	private static DelegateBridge __Hotfix0__EventOnSettleChallengeBtnClicked; // 0x78
	private static DelegateBridge __Hotfix0__EventOnHandbookBtnClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnSettleChallengeConfirm; // 0x88
	private static DelegateBridge __Hotfix0__OnSettleProceed; // 0x90
	private static DelegateBridge __Hotfix0__TryConsumeGuidebook; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x2d93b58 VA: 0x75953abb58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d93bc0 VA: 0x75953abbc0
	protected override Void OnEnter() { }
	// RVA: 0x2d94444 VA: 0x75953ac444
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2d94bec VA: 0x75953acbec
	protected override Void OnExit() { }
	// RVA: 0x2d94c78 VA: 0x75953acc78
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2d95760 VA: 0x75953ad760
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2d93d6c VA: 0x75953abd6c
	private Void _InitIfNot() { }
	// RVA: 0x2d93ed4 VA: 0x75953abed4
	private String _GetActivityId() { }
	// RVA: 0x2d9454c VA: 0x75953ac54c
	private Void _GenerateEntryAnim() { }
	// RVA: 0x2d95cc0 VA: 0x75953adcc0
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x2d94198 VA: 0x75953ac198
	private Void _EventOnOpenIntroDialog() { }
	// RVA: 0x2d94d98 VA: 0x75953acd98
	private Void _EventOnNextBtnClicked() { }
	// RVA: 0x2d94ee4 VA: 0x75953acee4
	private Void _EventOnPrevBtnClicked() { }
	// RVA: 0x2d9501c VA: 0x75953ad01c
	private Void _EventOnStartChallengeBtnClicked() { }
	// RVA: 0x2d95e84 VA: 0x75953ade84
	private Void _OpenCarvingMainPage(CarvingCreateGameResponse response) { }
	// RVA: 0x2d952d0 VA: 0x75953ad2d0
	private Void _EventOnSettleChallengeBtnClicked() { }
	// RVA: 0x2d95558 VA: 0x75953ad558
	private Void _EventOnHandbookBtnClicked() { }
	// RVA: 0x2d958c0 VA: 0x75953ad8c0
	private Void _OnSettleChallengeConfirm() { }
	// RVA: 0x2d96084 VA: 0x75953ae084
	private Void _OnSettleProceed(CarvingSettleResponse response) { }
	// RVA: 0x2d943d4 VA: 0x75953ac3d4
	private Void _TryConsumeGuidebook() { }
	// RVA: 0x2d962bc VA: 0x75953ae2bc
	public Void .ctor() { }
	// RVA: 0x2d96420 VA: 0x75953ae420
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d96428 VA: 0x75953ae428
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x2d96434 VA: 0x75953ae434
	private Void <>xLuaBaseProxy_OnExit() { }
}
```