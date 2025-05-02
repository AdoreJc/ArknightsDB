# ObjectHolderList

**Namespace:** `System.Runtime.Serialization`


## Methods

- `Void EnlargeArray()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization
internal class ObjectHolderList
{
	internal ObjectHolder[] m_values; // 0x10
	internal Int32 m_count; // 0x18

	internal Int32 Version { get; }
	internal Int32 Count { get; }

	// RVA: 0x5fb29f0 VA: 0x75985ca9f0
	internal Void .ctor() { }
	// RVA: 0x5fb6b10 VA: 0x75985ceb10
	internal Void .ctor(Int32 startingSize) { }
	// RVA: 0x5fb6b84 VA: 0x75985ceb84
	internal virtual Void Add(ObjectHolder value) { }
	// RVA: 0x5fb5a10 VA: 0x75985cda10
	internal ObjectHolderListEnumerator GetFixupEnumerator() { }
	// RVA: 0x5fb6c30 VA: 0x75985cec30
	private Void EnlargeArray() { }
	// RVA: 0x5fb6d28 VA: 0x75985ced28
	internal Int32 get_Version() { }
	// RVA: 0x5fb6d30 VA: 0x75985ced30
	internal Int32 get_Count() { }
}
```