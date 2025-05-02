# ScalableAuraHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _scalePerSecond`

- `String _effectKey`

- `Boolean m_isStoped`

- `FP m_scalePerSecond`

- `FP m_curScale`

- `FP m_startRadius`

- `FP m_moveEndTime`

- `CircleRange m_circleRange`

- `PeriodicTimer m_moveTimer`


## Methods

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileBorn()`

- `Void <>xLuaBaseProxy_OnProjectileReached()`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ScalableAuraHitBehaviour : AuraHitBehaviour, IEffectSource
{
	private Single _scalePerSecond; // 0xb8
	private String _effectKey; // 0xc0
	private Boolean m_isStoped; // 0xc8
	private FP m_scalePerSecond; // 0xd0
	private FP m_curScale; // 0xd8
	private FP m_startRadius; // 0xe0
	private FP m_moveEndTime; // 0xe8
	private CircleRange m_circleRange; // 0xf0
	private ObjectPtr`1 m_effect; // 0xf8
	private PeriodicTimer m_moveTimer; // 0x108
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileBorn; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x10
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1d6fa68 VA: 0x7594387a68
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d6fd90 VA: 0x7594387d90
	public override Void OnProjectileBorn() { }
	// RVA: 0x1d6ffd0 VA: 0x7594387fd0
	public override Void OnProjectileReached() { }
	// RVA: 0x1d70224 VA: 0x7594388224
	public override Void OnProjectileStop() { }
	// RVA: 0x1d70418 VA: 0x7594388418
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d706bc VA: 0x75943886bc
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d707d0 VA: 0x75943887d0
	public Void .ctor() { }
	// RVA: 0x1d708e4 VA: 0x75943888e4
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d708ec VA: 0x75943888ec
	private Void <>xLuaBaseProxy_OnProjectileBorn() { }
	// RVA: 0x1d708f4 VA: 0x75943888f4
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
	// RVA: 0x1d708fc VA: 0x75943888fc
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x1d70904 VA: 0x7594388904
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```