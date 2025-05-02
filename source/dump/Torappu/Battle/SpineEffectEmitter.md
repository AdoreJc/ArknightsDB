# SpineEffectEmitter

**Namespace:** `Torappu.Battle`


## Fields

- `Unit m_owner`


## Methods

- `Void Init(Unit)`

- `Void PlayEffect(Int32)`

- `Void GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SpineEffectEmitter : MonoBehaviour, IEffectSource, IHotfixable
{
	private SpineEffectPreset[] _spineEffectPresets; // 0x18
	private Unit m_owner; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_PlayEffect; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3fb9db4 VA: 0x75965d1db4
	public Void Init(Unit owner) { }
	// RVA: 0x3fb9e38 VA: 0x75965d1e38
	public Void PlayEffect(Int32 index) { }
	// RVA: 0x3fba250 VA: 0x75965d2250
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x3fba4c8 VA: 0x75965d24c8
	public Void .ctor() { }
}
```