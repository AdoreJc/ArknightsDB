# MaterialReplacerChain

**Namespace:** `SoftMasking`


## Fields

- `Int32 <order>k__BackingField`


## Properties

- `Int32 order`


## Methods

- `Int32 get_order()`

- `Void set_order(Int32)`

- `Material Replace(Material)`

- `Void Initialize()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : SoftMasking
public class MaterialReplacerChain : IMaterialReplacer
{
	private readonly List`1 _replacers; // 0x10
	private Int32 <order>k__BackingField; // 0x18

	public Int32 order { get; set; }

	// RVA: 0x2b4d7f4 VA: 0x75951657f4
	public Void .ctor(IEnumerable`1 replacers, IMaterialReplacer yetAnother) { }
	// RVA: 0x2b4dabc VA: 0x7595165abc
	public Int32 get_order() { }
	// RVA: 0x2b4dac4 VA: 0x7595165ac4
	private Void set_order(Int32 value) { }
	// RVA: 0x2b4dacc VA: 0x7595165acc
	public Material Replace(Material material) { }
	// RVA: 0x2b4d8f4 VA: 0x75951658f4
	private Void Initialize() { }
}
```