# Pool

**Namespace:** `Spine`


## Fields

- `Int32 <Peak>k__BackingField`


## Properties

- `Int32 Count`

- `Int32 Peak`


## Methods

- `Int32 get_Count()`

- `Int32 get_Peak()`

- `Void set_Peak(Int32)`

- `T Obtain()`

- `Void Free(T)`

- `Void Clear()`

- `Void Reset(T)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Pool`1
{
	public readonly Int32 max; // 0x0
	private readonly Stack`1 freeObjects; // 0x0
	private Int32 <Peak>k__BackingField; // 0x0

	public Int32 Count { get; }
	public Int32 Peak { get; set; }

	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public Int32 get_Peak() { }
	// RVA: 0x VA: 0x0
	private Void set_Peak(Int32 value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 initialCapacity, Int32 max) { }
	// RVA: 0x VA: 0x0
	public T Obtain() { }
	// RVA: 0x VA: 0x0
	public Void Free(T obj) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	protected Void Reset(T obj) { }
}
```