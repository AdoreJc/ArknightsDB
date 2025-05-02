# MaterialReplacements

**Namespace:** `SoftMasking`


## Methods

- `Material Get(Material)`

- `Void Release(Material)`

- `Void ApplyAll()`

- `Void DestroyAllAndClear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : SoftMasking
internal class MaterialReplacements
{
	private readonly IMaterialReplacer _replacer; // 0x10
	private readonly Action`1 _applyParameters; // 0x18
	private readonly List`1 _overrides; // 0x20


	// RVA: 0x2b4c744 VA: 0x7595164744
	public Void .ctor(IMaterialReplacer replacer, Action`1 applyParameters) { }
	// RVA: 0x2b4c7fc VA: 0x75951647fc
	public Material Get(Material original) { }
	// RVA: 0x2b4cb14 VA: 0x7595164b14
	public Void Release(Material replacement) { }
	// RVA: 0x2b4cc78 VA: 0x7595164c78
	public Void ApplyAll() { }
	// RVA: 0x2b4cd5c VA: 0x7595164d5c
	public Void DestroyAllAndClear() { }
}
```