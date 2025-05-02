# VortexMultiHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _pullDuration`

- `String _castEffect`

- `Int32 m_pullForceLevel`


## Methods

- `Int32 RegisterPullRemainingTime()`

- `IEnumerator _DoPull(Enemy)`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`

- `Boolean <>xLuaBaseProxy_DealHitTarget(Entity, Boolean)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class VortexMultiHitBehaviour : SelectorHitBehaviour, IEffectSource
{
	private Single _pullDuration; // 0x80
	private String _castEffect; // 0x88
	private Int32 m_pullForceLevel; // 0x90
	private List`1 m_pullRemainingTimeList; // 0x98
	private static DelegateBridge __Hotfix0_RegisterPullRemainingTime; // 0x0
	private static DelegateBridge __Hotfix0__DoPull; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x18
	private static DelegateBridge __Hotfix0_DealHitTarget; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1d968a4 VA: 0x75943ae8a4
	private Int32 RegisterPullRemainingTime() { }
	// RVA: 0x1d969dc VA: 0x75943ae9dc
	private IEnumerator _DoPull(Enemy target) { }
	// RVA: 0x1d96ad4 VA: 0x75943aead4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d96ca0 VA: 0x75943aeca0
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d96dc4 VA: 0x75943aedc4
	protected override Boolean DealHitTarget(Entity target, Boolean force) { }
	// RVA: 0x1d96ef4 VA: 0x75943aeef4
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d97014 VA: 0x75943af014
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d97128 VA: 0x75943af128
	public Void .ctor() { }
	// RVA: 0x1d971f4 VA: 0x75943af1f4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d971fc VA: 0x75943af1fc
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
	// RVA: 0x1d97204 VA: 0x75943af204
	private Boolean <>xLuaBaseProxy_DealHitTarget(Entity P0, Boolean P1) { }
	// RVA: 0x1d97210 VA: 0x75943af210
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
}
```