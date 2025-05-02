# ObjectPool

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 m_MaxSize`


## Properties

- `Int32 maxSize`


## Methods

- `Int32 get_maxSize()`

- `Void set_maxSize(Int32)`

- `Int32 Size()`

- `T Get()`

- `Void Release(T)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ObjectPool`1
{
	private readonly Stack`1 m_Stack; // 0x0
	private Int32 m_MaxSize; // 0x0

	public Int32 maxSize { get; set; }

	// RVA: 0x VA: 0x0
	public Int32 get_maxSize() { }
	// RVA: 0x VA: 0x0
	public Void set_maxSize(Int32 value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 maxSize) { }
	// RVA: 0x VA: 0x0
	public Int32 Size() { }
	// RVA: 0x VA: 0x0
	public T Get() { }
	// RVA: 0x VA: 0x0
	public Void Release(T element) { }
}
```