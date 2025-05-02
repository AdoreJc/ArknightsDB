# LongList

**Namespace:** `System.Runtime.Serialization`


## Fields

- `Int32 m_count`

- `Int32 m_totalItems`

- `Int32 m_currentItem`


## Methods

- `Void EnlargeArray()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization
internal class LongList
{
	private Int64[] m_values; // 0x10
	private Int32 m_count; // 0x18
	private Int32 m_totalItems; // 0x1c
	private Int32 m_currentItem; // 0x20

	internal Int32 Count { get; }
	internal Int64 Current { get; }

	// RVA: 0x5fb6760 VA: 0x75985ce760
	internal Void .ctor() { }
	// RVA: 0x5fb6a00 VA: 0x75985cea00
	internal Void .ctor(Int32 startingSize) { }
	// RVA: 0x5fb6768 VA: 0x75985ce768
	internal Void Add(Int64 value) { }
	// RVA: 0x5fb6b08 VA: 0x75985ceb08
	internal Int32 get_Count() { }
	// RVA: 0x5fb4844 VA: 0x75985cc844
	internal Void StartEnumeration() { }
	// RVA: 0x5fb4890 VA: 0x75985cc890
	internal Boolean MoveNext() { }
	// RVA: 0x5fb4850 VA: 0x75985cc850
	internal Int64 get_Current() { }
	// RVA: 0x5fb66b0 VA: 0x75985ce6b0
	internal Boolean RemoveElement(Int64 value) { }
	// RVA: 0x5fb6a74 VA: 0x75985cea74
	private Void EnlargeArray() { }
}
```