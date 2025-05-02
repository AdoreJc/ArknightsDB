# EnemyDuelBattleDefaultState

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
public class EnemyDuelBattleDefaultState : EnemyDuelBattleState
{
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_GetSupportedGameState; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x20
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2985e24 VA: 0x7594f9de24
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2985e88 VA: 0x7594f9de88
	protected override EnemyDuelServiceGameState GetSupportedGameState() { }
	// RVA: 0x2985eec VA: 0x7594f9deec
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2986054 VA: 0x7594f9e054
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x29861bc VA: 0x7594f9e1bc
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x29862a0 VA: 0x7594f9e2a0
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2986384 VA: 0x7594f9e384
	public Void .ctor() { }
	// RVA: 0x29863f0 VA: 0x7594f9e3f0
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2986418 VA: 0x7594f9e418
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2986440 VA: 0x7594f9e440
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x2986468 VA: 0x7594f9e468
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
}
```