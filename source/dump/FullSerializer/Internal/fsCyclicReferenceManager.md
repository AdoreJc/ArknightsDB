# fsCyclicReferenceManager

**Namespace:** `FullSerializer.Internal`


## Fields

- `Int32 _nextId`

- `Int32 _depth`


## Methods

- `Void Enter()`

- `Boolean Exit()`

- `Object GetReferenceObject(Int32)`

- `Void AddReferenceWithId(Int32, Object)`

- `Int32 GetReferenceId(Object)`

- `Boolean IsReference(Object)`

- `Void MarkSerialized(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsCyclicReferenceManager
{
	private Dictionary`2 _objectIds; // 0x10
	private Int32 _nextId; // 0x18
	private Dictionary`2 _marked; // 0x20
	private Int32 _depth; // 0x28


	// RVA: 0x34b73a4 VA: 0x7595acf3a4
	public Void Enter() { }
	// RVA: 0x34c413c VA: 0x7595adc13c
	public Boolean Exit() { }
	// RVA: 0x34b864c VA: 0x7595ad064c
	public Object GetReferenceObject(Int32 id) { }
	// RVA: 0x34b9430 VA: 0x7595ad1430
	public Void AddReferenceWithId(Int32 id, Object reference) { }
	// RVA: 0x34b7618 VA: 0x7595acf618
	public Int32 GetReferenceId(Object item) { }
	// RVA: 0x34b75b0 VA: 0x7595acf5b0
	public Boolean IsReference(Object item) { }
	// RVA: 0x34b78e8 VA: 0x7595acf8e8
	public Void MarkSerialized(Object item) { }
	// RVA: 0x34b6138 VA: 0x7595ace138
	public Void .ctor() { }
}
```