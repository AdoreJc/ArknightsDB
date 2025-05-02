# BattleFinishHomeState

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `BattleFinishHomeStateBean _stateBean`

- `UIFullScreenImage _blurBackground`

- `BattleFinishHomeView m_view`

- `Single m_animEndTime`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishHomeState : UIPopupState
{
	private BattleFinishHomeStateBean _stateBean; // 0x60
	private UIFullScreenImage _blurBackground; // 0x68
	private BattleFinishHomeView m_view; // 0x70
	private Single m_animEndTime; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x28
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2e87a90 VA: 0x759549fa90
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e87af8 VA: 0x759549faf8
	protected override Void OnEnter() { }
	// RVA: 0x2e87d94 VA: 0x759549fd94
	protected override Void OnResume() { }
	// RVA: 0x2e87e50 VA: 0x759549fe50
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2e87fa0 VA: 0x759549ffa0
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2e880f0 VA: 0x75954a00f0
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2e881fc VA: 0x75954a01fc
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2e88308 VA: 0x75954a0308
	public Void .ctor() { }
	// RVA: 0x2e88378 VA: 0x75954a0378
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e88380 VA: 0x75954a0380
	private Void <>xLuaBaseProxy_OnResume() { }
}
```