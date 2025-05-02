# FxLODSetting

**Namespace:** `Torappu.Fx`


## Methods

- `Void ReplayEffect()`

- `Void ApplyLowDetail()`

- `Void ApplyLowDetail(Boolean)`

- `Void RevertToHighDetail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxLODSetting : MonoBehaviour, IHotfixable
{
	private List`1 _disableObjects; // 0x18
	private List`1 _particleDetailsHookers; // 0x20
	private static DelegateBridge __Hotfix0_get_disableObjects; // 0x0
	private static DelegateBridge __Hotfix0_get_particleDetailsHookers; // 0x8
	private static DelegateBridge __Hotfix0_ReplayEffect; // 0x10
	private static DelegateBridge __Hotfix0_ApplyLowDetail; // 0x18
	private static DelegateBridge __Hotfix1_ApplyLowDetail; // 0x20
	private static DelegateBridge __Hotfix0_RevertToHighDetail; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 disableObjects { get; }
	public List`1 particleDetailsHookers { get; }

	// RVA: 0x3efd14c VA: 0x759651514c
	public List`1 get_disableObjects() { }
	// RVA: 0x3efd1b4 VA: 0x75965151b4
	public List`1 get_particleDetailsHookers() { }
	// RVA: 0x3efd21c VA: 0x759651521c
	public Void ReplayEffect() { }
	// RVA: 0x3efd2cc VA: 0x75965152cc
	public Void ApplyLowDetail() { }
	// RVA: 0x3efd338 VA: 0x7596515338
	public Void ApplyLowDetail(Boolean force) { }
	// RVA: 0x3efda04 VA: 0x7596515a04
	public Void RevertToHighDetail() { }
	// RVA: 0x3efdf34 VA: 0x7596515f34
	public Void .ctor() { }
}
```