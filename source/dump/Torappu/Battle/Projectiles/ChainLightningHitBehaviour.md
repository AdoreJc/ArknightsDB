# ChainLightningHitBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _atkScale`

- `Boolean _useChainPrefix`

- `Boolean _playChainEffectAndAudioAfterSelectTarget`

- `CircleRange _rangeToLoad`

- `TargetValidator _freeJumpValidator`

- `ChainLightningEffectBehaviour m_effect`

- `Single m_atkScale`


## Properties

- `ChainLightningEffectBehaviour effect`


## Methods

- `ChainLightningEffectBehaviour get_effect()`

- `Void PlayChainAudio()`

- `Boolean _IsFreeJump(Entity)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2)`

- `Void <>xLuaBaseProxy_OnProjectileReached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ChainLightningHitBehaviour : SelectorHitBehaviour
{
	private Single _atkScale; // 0x80
	private Boolean _useChainPrefix; // 0x84
	private Boolean _playChainEffectAndAudioAfterSelectTarget; // 0x85
	private CircleRange _rangeToLoad; // 0x88
	public TargetValidator _freeJumpValidator; // 0x90
	private ChainLightningEffectBehaviour m_effect; // 0x98
	private List`1 m_targetsList; // 0xa0
	private Single m_atkScale; // 0xa8
	private static DelegateBridge __Hotfix0_get_effect; // 0x0
	private static DelegateBridge __Hotfix0_get_targetsList; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_DoSelectTargetToHit; // 0x18
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x20
	private static DelegateBridge __Hotfix0_PlayChainAudio; // 0x28
	private static DelegateBridge __Hotfix0__IsFreeJump; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	protected ChainLightningEffectBehaviour effect { get; }
	public IEnumerable`1 targetsList { get; }

	// RVA: 0x1d5f014 VA: 0x7594377014
	protected ChainLightningEffectBehaviour get_effect() { }
	// RVA: 0x1d5f0ec VA: 0x75943770ec
	public IEnumerable`1 get_targetsList() { }
	// RVA: 0x1d5f154 VA: 0x7594377154
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d5f5cc VA: 0x75943775cc
	protected override Void DoSelectTargetToHit(Vector2 inputPos) { }
	// RVA: 0x1d5fce0 VA: 0x7594377ce0
	public override Void OnProjectileReached() { }
	// RVA: 0x1d5fb34 VA: 0x7594377b34
	private Void PlayChainAudio() { }
	// RVA: 0x1d5fa54 VA: 0x7594377a54
	private Boolean _IsFreeJump(Entity target) { }
	// RVA: 0x1d5fd80 VA: 0x7594377d80
	public Void .ctor() { }
	// RVA: 0x1d5fe44 VA: 0x7594377e44
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d5fe4c VA: 0x7594377e4c
	private Void <>xLuaBaseProxy_DoSelectTargetToHit(Vector2 P0) { }
	// RVA: 0x1d5fe54 VA: 0x7594377e54
	private Void <>xLuaBaseProxy_OnProjectileReached() { }
}
```