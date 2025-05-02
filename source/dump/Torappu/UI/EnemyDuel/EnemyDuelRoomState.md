# EnemyDuelRoomState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelPrepareRoomView _view`

- `Text _ping`

- `RectTransform _backBtnRect`

- `CanvasGroup _lostConnectionPanel`

- `Boolean m_isInited`

- `Boolean m_eventRegistered`

- `Boolean m_hasAlertDisconnect`

- `Int32 m_entranceDialogInst`

- `FadeSwitchTween m_lostConnectionFade`

- `EnemyDuelTeamDisconnectReason m_cachedReason`

- `EnemyDuelPrepareRoomStateBean m_stateBean`


## Methods

- `Boolean CustomSetActive(Boolean)`

- `Void Update()`

- `Void OnDestroy()`

- `Void _InitIfNot()`

- `Void _UpdatePingStr(Int32, List`1)`

- `Void _RegisterEventIfNeed()`

- `Void _ReleaseEventIfNeed()`

- `Void _HandleTeamChanged(Object)`

- `Void _HandleGetNameCard(Object)`

- `Void _HandleTeamLeave(Object)`

- `Void _HandleTeamDisconnectException(Object)`

- `IEnumerator _EnsureBackToRoomCoroutine(Boolean)`

- `Void EventOnStartBattle()`

- `Void EventOnLeave()`

- `Void EventOnCopyTeamID()`

- `Void EventOnClickBlank()`

- `Void EventOnClickNpcToggle()`

- `Void OnMessage(Int32, ValueBundle)`

- `Boolean _ValidatePlayerCardOption(Int32, out)`

- `Void _EventOnCheckAvatar(Int32)`

- `Void _EventOnCheckNameCard(Int32)`

- `Void _EventOnAddFriend(Int32)`

- `Void _EventOnKick(Int32)`

- `Void <OnEnter>b__13_0(GetFriendAndRequestSendListResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoomState : UIPopupState, IValueMsgReceiver, IPopupCustomActive
{
	private EnemyDuelPrepareRoomView _view; // 0x60
	private Text _ping; // 0x68
	private RectTransform _backBtnRect; // 0x70
	private CanvasGroup _lostConnectionPanel; // 0x78
	private Boolean m_isInited; // 0x80
	private Boolean m_eventRegistered; // 0x81
	private Boolean m_hasAlertDisconnect; // 0x82
	private Int32 m_entranceDialogInst; // 0x84
	private FadeSwitchTween m_lostConnectionFade; // 0x88
	private EnemyDuelTeamDisconnectReason m_cachedReason; // 0x90
	private EnemyDuelPrepareRoomStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x20
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__UpdatePingStr; // 0x58
	private static DelegateBridge __Hotfix0__RegisterEventIfNeed; // 0x60
	private static DelegateBridge __Hotfix0__ReleaseEventIfNeed; // 0x68
	private static DelegateBridge __Hotfix0__HandleTeamChanged; // 0x70
	private static DelegateBridge __Hotfix0__HandleGetNameCard; // 0x78
	private static DelegateBridge __Hotfix0__HandleTeamLeave; // 0x80
	private static DelegateBridge __Hotfix0__HandleTeamDisconnectException; // 0x88
	private static DelegateBridge __Hotfix0__EnsureBackToRoomCoroutine; // 0x90
	private static DelegateBridge __Hotfix0_EventOnStartBattle; // 0x98
	private static DelegateBridge __Hotfix0_EventOnLeave; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnCopyTeamID; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnClickBlank; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnClickNpcToggle; // 0xb8
	private static DelegateBridge __Hotfix0_OnMessage; // 0xc0
	private static DelegateBridge __Hotfix0__ValidatePlayerCardOption; // 0xc8
	private static DelegateBridge __Hotfix0__EventOnCheckAvatar; // 0xd0
	private static DelegateBridge __Hotfix0__EventOnCheckNameCard; // 0xd8
	private static DelegateBridge __Hotfix0__EventOnAddFriend; // 0xe0
	private static DelegateBridge __Hotfix0__EventOnKick; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0


	// RVA: 0x29a0d2c VA: 0x7594fb8d2c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29a0d94 VA: 0x7594fb8d94
	protected override Void OnEnter() { }
	// RVA: 0x29a1474 VA: 0x7594fb9474
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x29a15ec VA: 0x7594fb95ec
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x29a1764 VA: 0x7594fb9764
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x29a1870 VA: 0x7594fb9870
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x29a197c VA: 0x7594fb997c
	protected override Void OnExit() { }
	// RVA: 0x29a1b74 VA: 0x7594fb9b74
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x29a1bf0 VA: 0x7594fb9bf0
	private Void Update() { }
	// RVA: 0x29a203c VA: 0x7594fba03c
	private Void OnDestroy() { }
	// RVA: 0x29a1164 VA: 0x7594fb9164
	private Void _InitIfNot() { }
	// RVA: 0x29a1f30 VA: 0x7594fb9f30
	private Void _UpdatePingStr(Int32 ping, List`1 pingConds) { }
	// RVA: 0x29a12e0 VA: 0x7594fb92e0
	private Void _RegisterEventIfNeed() { }
	// RVA: 0x29a19e4 VA: 0x7594fb99e4
	private Void _ReleaseEventIfNeed() { }
	// RVA: 0x29a223c VA: 0x7594fba23c
	private Void _HandleTeamChanged(Object arg) { }
	// RVA: 0x29a2560 VA: 0x7594fba560
	private Void _HandleGetNameCard(Object arg) { }
	// RVA: 0x29a2994 VA: 0x7594fba994
	private Void _HandleTeamLeave(Object arg) { }
	// RVA: 0x29a2a2c VA: 0x7594fbaa2c
	private Void _HandleTeamDisconnectException(Object arg) { }
	// RVA: 0x29a2498 VA: 0x7594fba498
	private IEnumerator _EnsureBackToRoomCoroutine(Boolean thenGotoBattleCd) { }
	// RVA: 0x29a2b1c VA: 0x7594fbab1c
	public Void EventOnStartBattle() { }
	// RVA: 0x29a2dec VA: 0x7594fbadec
	public Void EventOnLeave() { }
	// RVA: 0x29a30b4 VA: 0x7594fbb0b4
	public Void EventOnCopyTeamID() { }
	// RVA: 0x29a3260 VA: 0x7594fbb260
	public Void EventOnClickBlank() { }
	// RVA: 0x29a3328 VA: 0x7594fbb328
	public Void EventOnClickNpcToggle() { }
	// RVA: 0x29a3544 VA: 0x7594fbb544
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x29a3d84 VA: 0x7594fbbd84
	private Boolean _ValidatePlayerCardOption(Int32 idx, out EnemyDuelPrepareRoomPlayerCardViewModel playerCardViewModel) { }
	// RVA: 0x29a365c VA: 0x7594fbb65c
	private Void _EventOnCheckAvatar(Int32 idx) { }
	// RVA: 0x29a3758 VA: 0x7594fbb758
	private Void _EventOnCheckNameCard(Int32 idx) { }
	// RVA: 0x29a390c VA: 0x7594fbb90c
	private Void _EventOnAddFriend(Int32 idx) { }
	// RVA: 0x29a3bac VA: 0x7594fbbbac
	private Void _EventOnKick(Int32 idx) { }
	// RVA: 0x29a3f20 VA: 0x7594fbbf20
	public Void .ctor() { }
	// RVA: 0x29a3fd0 VA: 0x7594fbbfd0
	private Void <OnEnter>b__13_0(GetFriendAndRequestSendListResponse resp) { }
	// RVA: 0x29a4070 VA: 0x7594fbc070
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x29a4078 VA: 0x7594fbc078
	private Void <>xLuaBaseProxy_OnExit() { }
}
```