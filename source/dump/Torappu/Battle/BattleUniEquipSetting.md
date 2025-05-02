# BattleUniEquipSetting

**Namespace:** `Torappu.Battle`


## Methods

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleUniEquipSetting : MonoBehaviour, IHotfixable, IEffectSource
{
	private String[] _effects; // 0x18
	private static DelegateBridge __Hotfix0_get_effects; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public String[] effects { get; }

	// RVA: 0x3fd4854 VA: 0x75965ec854
	public String[] get_effects() { }
	// RVA: 0x3fd48bc VA: 0x75965ec8bc
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x3fd4990 VA: 0x75965ec990
	public Void .ctor() { }
}
```