# Stack

**Namespace:** `System.Collections`


## Fields

- `Int32 _size`

- `Int32 _version`

- `Object _syncRoot`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections
public class Stack : ICollection, IEnumerable, ICloneable
{
	private Object[] _array; // 0x10
	private Int32 _size; // 0x18
	private Int32 _version; // 0x1c
	private Object _syncRoot; // 0x20
	private const Int32 _defaultCapacity; // 0x0

	public virtual Int32 Count { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }

	// RVA: 0x6082ce8 VA: 0x759869ace8
	public Void .ctor() { }
	// RVA: 0x6082d54 VA: 0x759869ad54
	public Void .ctor(Int32 initialCapacity) { }
	// RVA: 0x6082e30 VA: 0x759869ae30
	public virtual Int32 get_Count() { }
	// RVA: 0x6082e38 VA: 0x759869ae38
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x6082e40 VA: 0x759869ae40
	public virtual Object get_SyncRoot() { }
	// RVA: 0x6082eb8 VA: 0x759869aeb8
	public virtual Void Clear() { }
	// RVA: 0x6082ee8 VA: 0x759869aee8
	public virtual Object Clone() { }
	// RVA: 0x6082f78 VA: 0x759869af78
	public virtual Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x6083238 VA: 0x759869b238
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x60832f4 VA: 0x759869b2f4
	public virtual Object Peek() { }
	// RVA: 0x608337c VA: 0x759869b37c
	public virtual Object Pop() { }
	// RVA: 0x6083420 VA: 0x759869b420
	public virtual Void Push(Object obj) { }
}
```