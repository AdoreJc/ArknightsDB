# CharacterSkinHooker

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _useFakeProjectile`


## Properties

- `Boolean useFakeProjectile`


## Methods

- `Boolean get_useFakeProjectile()`

- `Boolean TryHookEffect(String, out)`

- `Boolean TryHookProjectile(String, out, out, out)`

- `Void GatherEffects(List`1)`

- `Void GatherEffectsBlackList(List`1, List`1)`

- `Void GatherProjectiles(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CharacterSkinHooker : MonoBehaviour, IEffectSource, IProjectileSource, IHotfixable
{
	private EffectReplacePair[] _replaceEffectPairs; // 0x18
	private Boolean _useFakeProjectile; // 0x20
	private FakeProjectileConfig[] _fakeProjectileConfigs; // 0x28
	private static DelegateBridge __Hotfix0_get_useFakeProjectile; // 0x0
	private static DelegateBridge __Hotfix0_get_replaceEffectPairs; // 0x8
	private static DelegateBridge __Hotfix0_TryHookEffect; // 0x10
	private static DelegateBridge __Hotfix0_TryHookProjectile; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffectsBlackList; // 0x28
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean useFakeProjectile { get; }
	public EffectReplacePair[] replaceEffectPairs { get; }

	// RVA: 0x3fb9420 VA: 0x75965d1420
	public Boolean get_useFakeProjectile() { }
	// RVA: 0x3fb9488 VA: 0x75965d1488
	public EffectReplacePair[] get_replaceEffectPairs() { }
	// RVA: 0x3fb94f0 VA: 0x75965d14f0
	public Boolean TryHookEffect(String originEffectKey, out String newEffectKey) { }
	// RVA: 0x3fb9580 VA: 0x75965d1580
	public Boolean TryHookProjectile(String originProjectileKey, out String graphicProjectileKey, out String logicProjectileKey, out MountPointType muzzlePoint) { }
	// RVA: 0x3fb9740 VA: 0x75965d1740
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x3fb98b0 VA: 0x75965d18b0
	public Void GatherEffectsBlackList(List`1 blackList, List`1 blackListIncludeSkin) { }
	// RVA: 0x3fb9b28 VA: 0x75965d1b28
	public Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x3fb9d44 VA: 0x75965d1d44
	public Void .ctor() { }
}
```