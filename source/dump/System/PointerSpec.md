# PointerSpec

**Namespace:** `System`


## Fields

- `Int32 pointer_level`


## Methods

- `Type Resolve(Type)`

- `StringBuilder Append(StringBuilder)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class PointerSpec : ModifierSpec
{
	private Int32 pointer_level; // 0x10


	// RVA: 0x610d788 VA: 0x7598725788
	internal Void .ctor(Int32 pointer_level) { }
	// RVA: 0x610d7b0 VA: 0x75987257b0
	public Type Resolve(Type type) { }
	// RVA: 0x610d804 VA: 0x7598725804
	public StringBuilder Append(StringBuilder sb) { }
	// RVA: 0x610d82c VA: 0x759872582c
	public override String ToString() { }
}
```