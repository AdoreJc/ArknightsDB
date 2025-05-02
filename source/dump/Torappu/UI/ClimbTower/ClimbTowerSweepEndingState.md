# ClimbTowerSweepEndingState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSweepEndingView _view`

- `UIAnimationLocation _entryAnimLocation`

- `ClimbTowerSweepEndingStateBean m_stateBean`

- `Boolean m_isInited`

- `Tween m_entryTween`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _RemoveStateToEntry()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSweepEndingState : PopupFadeState, IValueMsgReceiver
{
	private ClimbTowerSweepEndingView _view; // 0x70
	private UIAnimationLocation _entryAnimLocation; // 0x78
	private ClimbTowerSweepEndingStateBean m_stateBean; // 0x88
	private Boolean m_isInited; // 0x90
	private Tween m_entryTween; // 0x98
	public const Int32 CLOSE_SWEEP_ENDING_STATE; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__RemoveStateToEntry; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2cd30c4 VA: 0x75952eb0c4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2cd312c VA: 0x75952eb12c
	protected override Void OnEnter() { }
	// RVA: 0x2cd3388 VA: 0x75952eb388
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2cd31dc VA: 0x75952eb1dc
	private Void _InitIfNot() { }
	// RVA: 0x2cd351c VA: 0x75952eb51c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2cd35c0 VA: 0x75952eb5c0
	private Void _RemoveStateToEntry() { }
	// RVA: 0x2cd3748 VA: 0x75952eb748
	public Void .ctor() { }
	// RVA: 0x2cd38a0 VA: 0x75952eb8a0
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2cd38c8 VA: 0x75952eb8c8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2cd38d0 VA: 0x75952eb8d0
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```