# NarantS2HitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String m_comebackAtkScaleKey`

- `Single m_comebackAtkScale`

- `Boolean m_active`


## Methods

- `Void SwitchToComebackState()`

- `Void OnTriggerStay2D(Collider2D)`

- `Void _DoTargetStay(IPtrObject)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DealHitTarget(Entity, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class NarantS2HitBehaviour : HitBehaviour
{
	private String m_comebackAtkScaleKey; // 0xa8
	private Single m_comebackAtkScale; // 0xb0
	private Boolean m_active; // 0xb4
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x8
	private static DelegateBridge __Hotfix0_SwitchToComebackState; // 0x10
	private static DelegateBridge __Hotfix0_OnTriggerStay2D; // 0x18
	private static DelegateBridge __Hotfix0__DoTargetStay; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1d6a350 VA: 0x7594382350
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6a42c VA: 0x759438242c
	protected override Void DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d6a4d0 VA: 0x75943824d0
	public Void SwitchToComebackState() { }
	// RVA: 0x1d6a5cc VA: 0x75943825cc
	private Void OnTriggerStay2D(Collider2D collision) { }
	// RVA: 0x1d6a7d4 VA: 0x75943827d4
	private Void _DoTargetStay(IPtrObject obj) { }
	// RVA: 0x1d6a968 VA: 0x7594382968
	public Void .ctor() { }
	// RVA: 0x1d6aa28 VA: 0x7594382a28
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d6aa2c VA: 0x7594382a2c
	private Void <>xLuaBaseProxy_DealHitTarget(Entity P0, Boolean P1) { }
}
```