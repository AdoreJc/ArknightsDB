# MaterialReplacerImpl

**Namespace:** ` `


## Properties

- `Int32 order`


## Methods

- `Int32 get_order()`

- `Material Replace(Material)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MaterialReplacerImpl : IMaterialReplacer
{
	private readonly SoftMask _owner; // 0x10

	public Int32 order { get; }

	// RVA: 0x2b4e094 VA: 0x7595166094
	public Void .ctor(SoftMask owner) { }
	// RVA: 0x2b50ae8 VA: 0x7595168ae8
	public Int32 get_order() { }
	// RVA: 0x2b50af0 VA: 0x7595168af0
	public Material Replace(Material original) { }
	// RVA: 0x2b50bfc VA: 0x7595168bfc
	private static Material Replace(Material original, Shader defaultReplacementShader) { }
}
```