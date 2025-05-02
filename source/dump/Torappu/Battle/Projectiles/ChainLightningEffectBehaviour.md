# ChainLightningEffectBehaviour

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `String _mainEffect`

- `Boolean _playSpecialEffectOnFirstOne`

- `String _specialHitEffect`

- `Boolean _finishMainEffectsBeforePlay`

- `Boolean _playEffectOnHitPoint`


## Properties

- `Boolean playSpecialEffectOnFirstOne`


## Methods

- `Boolean get_playSpecialEffectOnFirstOne()`

- `Void _ResetLineRenders()`

- `Void PlayLineEffect(List`1)`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_Init(ILocatable, ILocatable, Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class ChainLightningEffectBehaviour : Behaviour, IEffectSource
{
	private String _mainEffect; // 0x28
	private Boolean _playSpecialEffectOnFirstOne; // 0x30
	private String _specialHitEffect; // 0x38
	private Boolean _finishMainEffectsBeforePlay; // 0x40
	private Boolean _playEffectOnHitPoint; // 0x41
	private ObjectPtr`1 m_mainEffect; // 0x48
	private ObjectPtr`1 m_hitEffect; // 0x58
	private LineRenderer[] m_lineRenderers; // 0x68
	private List`1 m_positions; // 0x70
	private static DelegateBridge __Hotfix0_get_playSpecialEffectOnFirstOne; // 0x0
	private static DelegateBridge __Hotfix0_get_lineRenderers; // 0x8
	private static DelegateBridge __Hotfix0__ResetLineRenders; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x20
	private static DelegateBridge __Hotfix0_PlayLineEffect; // 0x28
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	protected Boolean playSpecialEffectOnFirstOne { get; }
	protected LineRenderer[] lineRenderers { get; }

	// RVA: 0x1d5e2f0 VA: 0x75943762f0
	protected Boolean get_playSpecialEffectOnFirstOne() { }
	// RVA: 0x1d5e358 VA: 0x7594376358
	protected LineRenderer[] get_lineRenderers() { }
	// RVA: 0x1d5e3fc VA: 0x75943763fc
	private Void _ResetLineRenders() { }
	// RVA: 0x1d5e46c VA: 0x759437646c
	public override Void Init(ILocatable start, ILocatable target, Projectile projectile) { }
	// RVA: 0x1d5e514 VA: 0x7594376514
	public override Void OnProjectileStop() { }
	// RVA: 0x1d5e6e0 VA: 0x75943766e0
	public Void PlayLineEffect(List`1 targets) { }
	// RVA: 0x1d5ee2c VA: 0x7594376e2c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d5ef40 VA: 0x7594376f40
	public Void .ctor() { }
	// RVA: 0x1d5f004 VA: 0x7594377004
	private Void <>xLuaBaseProxy_Init(ILocatable P0, ILocatable P1, Projectile P2) { }
	// RVA: 0x1d5f00c VA: 0x759437700c
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```