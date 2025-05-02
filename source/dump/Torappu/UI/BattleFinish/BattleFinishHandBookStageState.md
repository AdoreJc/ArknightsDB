# BattleFinishHandBookStageState

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `RectTransform _container`

- `BattleFinishHandBookStageStateBean m_stateBean`

- `BattleFinishHandBookStageView m_battleFinishView`


## Methods

- `Boolean _InitActivityBattleFinish()`

- `Void _DoSceneJump()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishHandBookStageState : UIPopupState
{
	private RectTransform _container; // 0x60
	private BattleFinishHandBookStageStateBean m_stateBean; // 0x68
	private BattleFinishHandBookStageView m_battleFinishView; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitActivityBattleFinish; // 0x10
	private static DelegateBridge __Hotfix0__DoSceneJump; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x30
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2e86f44 VA: 0x759549ef44
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e86fac VA: 0x759549efac
	protected override Void OnEnter() { }
	// RVA: 0x2e87054 VA: 0x759549f054
	private Boolean _InitActivityBattleFinish() { }
	// RVA: 0x2e87254 VA: 0x759549f254
	private Void _DoSceneJump() { }
	// RVA: 0x2e872b8 VA: 0x759549f2b8
	protected override Void OnResume() { }
	// RVA: 0x2e8739c VA: 0x759549f39c
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2e87514 VA: 0x759549f514
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2e87620 VA: 0x759549f620
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2e87798 VA: 0x759549f798
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2e878a4 VA: 0x759549f8a4
	public Void .ctor() { }
	// RVA: 0x2e87950 VA: 0x759549f950
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e87958 VA: 0x759549f958
	private Void <>xLuaBaseProxy_OnResume() { }
}
```