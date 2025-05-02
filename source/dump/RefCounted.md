# RefCounted

**Namespace:** ` `


## Fields

- `Int32 m_RefCount`

- `T value`


## Properties

- `Int32 refCount`


## Methods

- `Int32 get_refCount()`

- `Void Acquire()`

- `Void Release()`

- `RefCounted Copy()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class RefCounted
{
	private static UInt32 m_NextId; // 0x0
	private Int32 m_RefCount; // 0x0
	private readonly UInt32 m_Id; // 0x0
	public T value; // 0x0

	public Int32 refCount { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_refCount() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void Acquire() { }
	// RVA: 0x VA: 0x0
	public Void Release() { }
	// RVA: 0x VA: 0x0
	public RefCounted Copy() { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```