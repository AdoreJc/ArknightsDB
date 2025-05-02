# ObjectIDGenerator

**Namespace:** `System.Runtime.Serialization`


## Methods

- `Int32 FindElement(Object, out)`

- `Void Rehash()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization
public class ObjectIDGenerator
{
	internal Int32 m_currentCount; // 0x10
	internal Int32 m_currentSize; // 0x14
	internal Int64[] m_ids; // 0x18
	internal Object[] m_objs; // 0x20
	private static readonly Int32[] sizes; // 0x0


	// RVA: 0x5fb2110 VA: 0x75985ca110
	public Void .ctor() { }
	// RVA: 0x5fb21fc VA: 0x75985ca1fc
	private Int32 FindElement(Object obj, out Boolean found) { }
	// RVA: 0x5fb22c0 VA: 0x75985ca2c0
	public virtual Int64 GetId(Object obj, out Boolean firstTime) { }
	// RVA: 0x5fb2748 VA: 0x75985ca748
	public virtual Int64 HasId(Object obj, out Boolean firstTime) { }
	// RVA: 0x5fb2454 VA: 0x75985ca454
	private Void Rehash() { }
	// RVA: 0x5fb281c VA: 0x75985ca81c
	private static Void .cctor() { }
}
```