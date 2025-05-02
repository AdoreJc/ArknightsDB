# EnemyDuelPrepareWaitConnectState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelPreparePage m_page`

- `Bean m_statebean`

- `Boolean m_hasConnected`

- `Boolean m_registerdEvent`

- `Boolean m_hasAlertDisconnect`

- `Int32 m_entranceDialogInst`


## Methods

- `Void Update()`

- `Void OnDestroy()`

- `Void _RegisterEvent()`

- `Void _UnRegisterEvent()`

- `Void _HandleTeamChanged(Object)`

- `Void _OpenShowEntrance()`

- `Void <OnResume>b__9_0(Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareWaitConnectState : UIPopupState
{
	private EnemyDuelPreparePage m_page; // 0x60
	private Bean m_statebean; // 0x68
	private Boolean m_hasConnected; // 0x70
	private Boolean m_registerdEvent; // 0x71
	private Boolean m_hasAlertDisconnect; // 0x72
	private Int32 m_entranceDialogInst; // 0x74
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__RegisterEvent; // 0x30
	private static DelegateBridge __Hotfix0__UnRegisterEvent; // 0x38
	private static DelegateBridge __Hotfix0__HandleTeamChanged; // 0x40
	private static DelegateBridge __Hotfix0__OpenShowEntrance; // 0x48
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x60
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2993f78 VA: 0x7594fabf78
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2993fe0 VA: 0x7594fabfe0
	protected override Void OnEnter() { }
	// RVA: 0x29940ec VA: 0x7594fac0ec
	protected override Void OnResume() { }
	// RVA: 0x2994248 VA: 0x7594fac248
	private Void Update() { }
	// RVA: 0x29943f0 VA: 0x7594fac3f0
	protected override Void OnExit() { }
	// RVA: 0x2994538 VA: 0x7594fac538
	private Void OnDestroy() { }
	// RVA: 0x29945a0 VA: 0x7594fac5a0
	private Void _RegisterEvent() { }
	// RVA: 0x2994464 VA: 0x7594fac464
	private Void _UnRegisterEvent() { }
	// RVA: 0x2994678 VA: 0x7594fac678
	private Void _HandleTeamChanged(Object arg) { }
	// RVA: 0x2994738 VA: 0x7594fac738
	private Void _OpenShowEntrance() { }
	// RVA: 0x2994888 VA: 0x7594fac888
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2994a00 VA: 0x7594faca00
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2994b78 VA: 0x7594facb78
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2994c84 VA: 0x7594facc84
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2994d90 VA: 0x7594facd90
	public Void .ctor() { }
	// RVA: 0x2994eac VA: 0x7594faceac
	private Void <OnResume>b__9_0(Boolean succ) { }
	// RVA: 0x2994fe4 VA: 0x7594facfe4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2994fec VA: 0x7594facfec
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2994ff4 VA: 0x7594facff4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```