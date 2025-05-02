# EnemyDuelPrepareSelectModeState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelPrepareSelectModeView _view`

- `RectTransform _backBtnRect`

- `GameObject _backBtnObj`

- `UIAnimationLocation _enterAnim`

- `Boolean m_isInited`

- `AnimationSwitchTween m_enterAnimSwitchTween`

- `EnemyDuelPrepareSelectModeStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Boolean CustomSetActive(Boolean)`

- `Void _PassDataToRoomState(IStateBean)`

- `Void _PassDataToMatchState(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnSelectMode(ValueBundle)`

- `Void _EventOnCreateRoom()`

- `Void _StartSingleGame(String, ActivityEnemyDuelModeData)`

- `Void EventOnExitClick()`

- `Void EventOnMatchClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareSelectModeState : UIPopupState, IValueMsgReceiver, IPopupCustomActive
{
	private EnemyDuelPrepareSelectModeView _view; // 0x60
	private RectTransform _backBtnRect; // 0x68
	private GameObject _backBtnObj; // 0x70
	private UIAnimationLocation _enterAnim; // 0x78
	private Boolean m_isInited; // 0x88
	private AnimationSwitchTween m_enterAnimSwitchTween; // 0x90
	private EnemyDuelPrepareSelectModeStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0__PassDataToRoomState; // 0x30
	private static DelegateBridge __Hotfix0__PassDataToMatchState; // 0x38
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x48
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x50
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x58
	private static DelegateBridge __Hotfix0_OnMessage; // 0x60
	private static DelegateBridge __Hotfix0__EventOnSelectMode; // 0x68
	private static DelegateBridge __Hotfix0__EventOnCreateRoom; // 0x70
	private static DelegateBridge __Hotfix0__StartSingleGame; // 0x78
	private static DelegateBridge __Hotfix0_EventOnExitClick; // 0x80
	private static DelegateBridge __Hotfix0_EventOnMatchClick; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x299c050 VA: 0x7594fb4050
	private Void _InitIfNot() { }
	// RVA: 0x299c154 VA: 0x7594fb4154
	protected override Void OnEnter() { }
	// RVA: 0x299c3b8 VA: 0x7594fb43b8
	protected override Void OnPause() { }
	// RVA: 0x299c434 VA: 0x7594fb4434
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x299c4c4 VA: 0x7594fb44c4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x299c52c VA: 0x7594fb452c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x299c720 VA: 0x7594fb4720
	private Void _PassDataToRoomState(IStateBean iStatebean) { }
	// RVA: 0x299c8cc VA: 0x7594fb48cc
	private Void _PassDataToMatchState(IStateBean iStatebean) { }
	// RVA: 0x299ca10 VA: 0x7594fb4a10
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x299cb60 VA: 0x7594fb4b60
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x299ccb0 VA: 0x7594fb4cb0
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x299cdbc VA: 0x7594fb4dbc
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x299cec8 VA: 0x7594fb4ec8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x299cf8c VA: 0x7594fb4f8c
	private Void _EventOnSelectMode(ValueBundle msg) { }
	// RVA: 0x299d148 VA: 0x7594fb5148
	private Void _EventOnCreateRoom() { }
	// RVA: 0x299d4d4 VA: 0x7594fb54d4
	private Void _StartSingleGame(String actId, ActivityEnemyDuelModeData modeData) { }
	// RVA: 0x299d790 VA: 0x7594fb5790
	public Void EventOnExitClick() { }
	// RVA: 0x299d920 VA: 0x7594fb5920
	public Void EventOnMatchClick() { }
	// RVA: 0x299dbc8 VA: 0x7594fb5bc8
	public Void .ctor() { }
	// RVA: 0x299dc78 VA: 0x7594fb5c78
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x299dc80 VA: 0x7594fb5c80
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x299dc88 VA: 0x7594fb5c88
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```