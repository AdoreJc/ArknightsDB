# FixupHolderList

**Namespace:** `System.Runtime.Serialization`


## Methods

- `Void EnlargeArray()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization
internal class FixupHolderList
{
	internal FixupHolder[] m_values; // 0x10
	internal Int32 m_count; // 0x18


	// RVA: 0x5fb6740 VA: 0x75985ce740
	internal Void .ctor() { }
	// RVA: 0x5fb684c VA: 0x75985ce84c
	internal Void .ctor(Int32 startingSize) { }
	// RVA: 0x5fb68c0 VA: 0x75985ce8c0
	internal virtual Void Add(FixupHolder fixup) { }
	// RVA: 0x5fb696c VA: 0x75985ce96c
	private Void EnlargeArray() { }
}
```