# ProjectileProbElimateBehaviour

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _eliminateOnEnter`

- `String _effectOnEliminatePos`

- `String _audioSignalWhenEliminate`

- `FP m_prob`


## Methods

- `Void _DoElimateProjectile(Projectile)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnProjectileEnter(Projectile)`

- `Void <>xLuaBaseProxy_OnProjectileExit(Projectile)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ProjectileProbElimateBehaviour : ProjectileAuraBehaviour
{
	private Boolean _eliminateOnEnter; // 0x20
	private String _effectOnEliminatePos; // 0x28
	private String _audioSignalWhenEliminate; // 0x30
	private FP m_prob; // 0x38
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnProjectileEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnProjectileExit; // 0x10
	private static DelegateBridge __Hotfix0__DoElimateProjectile; // 0x18
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ed1438 VA: 0x75944e9438
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed1538 VA: 0x75944e9538
	public override Void OnProjectileEnter(Projectile projectile) { }
	// RVA: 0x1ed183c VA: 0x75944e983c
	public override Void OnProjectileExit(Projectile projectile) { }
	// RVA: 0x1ed1670 VA: 0x75944e9670
	private Void _DoElimateProjectile(Projectile projectile) { }
	// RVA: 0x1ed1974 VA: 0x75944e9974
	public override Void PreloadSpecialAudioSignals(String abilityId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1ed1a5c VA: 0x75944e9a5c
	public Void .ctor() { }
	// RVA: 0x1ed1acc VA: 0x75944e9acc
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed1ad4 VA: 0x75944e9ad4
	private Void <>xLuaBaseProxy_OnProjectileEnter(Projectile P0) { }
	// RVA: 0x1ed1adc VA: 0x75944e9adc
	private Void <>xLuaBaseProxy_OnProjectileExit(Projectile P0) { }
	// RVA: 0x1ed1ae4 VA: 0x75944e9ae4
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
}
```