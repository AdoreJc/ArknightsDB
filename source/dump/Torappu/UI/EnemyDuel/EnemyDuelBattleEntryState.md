# EnemyDuelBattleEntryState

**Namespace:** `Torappu.UI.EnemyDuel`


## Methods

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleEntryState : EnemyDuelBattleState
{
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_GetSupportedGameState; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x20
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2986568 VA: 0x7594f9e568
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29865cc VA: 0x7594f9e5cc
	protected override EnemyDuelServiceGameState GetSupportedGameState() { }
	// RVA: 0x2986634 VA: 0x7594f9e634
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x298679c VA: 0x7594f9e79c
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2986904 VA: 0x7594f9e904
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x29869e8 VA: 0x7594f9e9e8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2986acc VA: 0x7594f9eacc
	public Void .ctor() { }
	// RVA: 0x2986b38 VA: 0x7594f9eb38
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2986b60 VA: 0x7594f9eb60
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2986b88 VA: 0x7594f9eb88
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x2986bb0 VA: 0x7594f9ebb0
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
}
```