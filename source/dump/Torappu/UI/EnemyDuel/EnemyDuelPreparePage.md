# EnemyDuelPreparePage

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `RectTransform _dialogContainer`

- `DataBundle m_savedInst`

- `UICompDialogMgr m_diaglogMgr`

- `Boolean m_isListeningTeamServer`

- `Boolean m_hasAlertedTeamDIsconnect`


## Properties

- `String actId`

- `Boolean isRoom`

- `Boolean hadJoinRoom`

- `String initModeId`

- `UICompDialogMgr dialogMgr`


## Methods

- `String get_actId()`

- `Boolean get_isRoom()`

- `Boolean get_hadJoinRoom()`

- `String get_initModeId()`

- `UICompDialogMgr get_dialogMgr()`

- `IEnumerator _RouteToRoomState()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnPageRouted()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPreparePage : StateEnginePage
{
	private RectTransform _dialogContainer; // 0xe8
	private DataBundle m_savedInst; // 0xf0
	private UICompDialogMgr m_diaglogMgr; // 0xf8
	private Boolean m_isListeningTeamServer; // 0x100
	private Boolean m_hasAlertedTeamDIsconnect; // 0x101
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_isRoom; // 0x8
	private static DelegateBridge __Hotfix0_get_hadJoinRoom; // 0x10
	private static DelegateBridge __Hotfix0_get_initModeId; // 0x18
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x20
	private static DelegateBridge __Hotfix0_OnCreate; // 0x28
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x30
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x38
	private static DelegateBridge __Hotfix0__RouteToRoomState; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String actId { get; }
	public Boolean isRoom { get; }
	public Boolean hadJoinRoom { get; }
	public String initModeId { get; }
	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x2993330 VA: 0x7594fab330
	public String get_actId() { }
	// RVA: 0x2993430 VA: 0x7594fab430
	public Boolean get_isRoom() { }
	// RVA: 0x2993508 VA: 0x7594fab508
	public Boolean get_hadJoinRoom() { }
	// RVA: 0x29935e0 VA: 0x7594fab5e0
	public String get_initModeId() { }
	// RVA: 0x2993678 VA: 0x7594fab678
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x29936e0 VA: 0x7594fab6e0
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x29937ac VA: 0x7594fab7ac
	protected override Void OnPageRouted() { }
	// RVA: 0x29938a0 VA: 0x7594fab8a0
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2993974 VA: 0x7594fab974
	private IEnumerator _RouteToRoomState() { }
	// RVA: 0x2993a48 VA: 0x7594faba48
	public Void .ctor() { }
	// RVA: 0x2993ab8 VA: 0x7594fabab8
	private IEnumerator <>n__0() { }
	// RVA: 0x2993ac0 VA: 0x7594fabac0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2993ac8 VA: 0x7594fabac8
	private Void <>xLuaBaseProxy_OnPageRouted() { }
	// RVA: 0x2993ad0 VA: 0x7594fabad0
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```