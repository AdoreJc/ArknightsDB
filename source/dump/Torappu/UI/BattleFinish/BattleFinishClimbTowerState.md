# BattleFinishClimbTowerState

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `RectTransform _viewContainer`

- `BattleFinishClimbTowerStateBean m_stateBean`


## Methods

- `Boolean _InitClimbTowerBattleFinish()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishClimbTowerState : UIPopupState
{
	private RectTransform _viewContainer; // 0x60
	private BattleFinishClimbTowerStateBean m_stateBean; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitClimbTowerBattleFinish; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x28
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2e84d58 VA: 0x759549cd58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e84dc0 VA: 0x759549cdc0
	protected override Void OnEnter() { }
	// RVA: 0x2e84e48 VA: 0x759549ce48
	private Boolean _InitClimbTowerBattleFinish() { }
	// RVA: 0x2e852ac VA: 0x759549d2ac
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2e85424 VA: 0x759549d424
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2e8559c VA: 0x759549d59c
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2e856a8 VA: 0x759549d6a8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2e857b4 VA: 0x759549d7b4
	public Void .ctor() { }
	// RVA: 0x2e85860 VA: 0x759549d860
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```