# Yato2S2Behaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `FP _minDistance`

- `FP _maxDistance`

- `FP _intervalDistance`

- `FP _extandUnit`

- `FP m_distance`

- `Int32 m_intervalIndex`

- `FP m_distanceTolerance`


## Methods

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class Yato2S2Behaviour : SelectorHitBehaviour
{
	private FP _minDistance; // 0x80
	private FP _maxDistance; // 0x88
	private FP _intervalDistance; // 0x90
	private FP _extandUnit; // 0x98
	private FP m_distance; // 0xa0
	private Int32 m_intervalIndex; // 0xa8
	private FP m_distanceTolerance; // 0xb0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d97a7c VA: 0x75943afa7c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d97cd4 VA: 0x75943afcd4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d97fb0 VA: 0x75943affb0
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d98370 VA: 0x75943b0370
	public Void .ctor() { }
	// RVA: 0x1d98434 VA: 0x75943b0434
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d9843c VA: 0x75943b043c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d98444 VA: 0x75943b0444
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
}
```