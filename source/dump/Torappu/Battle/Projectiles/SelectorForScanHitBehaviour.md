# SelectorForScanHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetSelector _scanSelector`

- `Single _interval`

- `Int32 m_maxHitNum`

- `PeriodicTimer m_periodicTimer`


## Properties

- `TargetSelector selector`


## Methods

- `TargetSelector get_selector()`

- `Boolean _DealHitTarget(Entity, Boolean)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class SelectorForScanHitBehaviour : Behaviour
{
	private TargetSelector _scanSelector; // 0x28
	private Single _interval; // 0x30
	private Int32 m_maxHitNum; // 0x34
	private PeriodicTimer m_periodicTimer; // 0x38
	private List`1 m_targetsList; // 0x40
	private static DelegateBridge __Hotfix0_get_selector; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__DealHitTarget; // 0x18
	private static DelegateBridge __Hotfix0_DoSelectTarget; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected TargetSelector selector { get; }

	// RVA: 0x1d72568 VA: 0x759438a568
	protected TargetSelector get_selector() { }
	// RVA: 0x1d725d0 VA: 0x759438a5d0
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d72844 VA: 0x759438a844
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d72998 VA: 0x759438a998
	private Boolean _DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d72a38 VA: 0x759438aa38
	protected virtual Void DoSelectTarget(Vector2 inputPos) { }
	// RVA: 0x1d72de8 VA: 0x759438ade8
	public Void .ctor() { }
	// RVA: 0x1d72ee8 VA: 0x759438aee8
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d72ef0 VA: 0x759438aef0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```