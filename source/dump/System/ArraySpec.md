# ArraySpec

**Namespace:** `System`


## Fields

- `Int32 dimensions`

- `Boolean bound`


## Methods

- `Type Resolve(Type)`

- `StringBuilder Append(StringBuilder)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class ArraySpec : ModifierSpec
{
	private Int32 dimensions; // 0x10
	private Boolean bound; // 0x14


	// RVA: 0x610d5e0 VA: 0x75987255e0
	internal Void .ctor(Int32 dimensions, Boolean bound) { }
	// RVA: 0x610d610 VA: 0x7598725610
	public Type Resolve(Type type) { }
	// RVA: 0x610d674 VA: 0x7598725674
	public StringBuilder Append(StringBuilder sb) { }
	// RVA: 0x610d714 VA: 0x7598725714
	public override String ToString() { }
}
```