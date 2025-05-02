# HashSet

**Namespace:** `Org.BouncyCastle.Utilities.Collections`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.Collections
public class HashSet : ISet, ICollection, IEnumerable
{
	private readonly IDictionary impl; // 0x10

	public virtual Int32 Count { get; }
	public virtual Boolean IsEmpty { get; }
	public virtual Boolean IsFixedSize { get; }
	public virtual Boolean IsReadOnly { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }

	// RVA: 0x66fbf58 VA: 0x7598d13f58
	public Void .ctor() { }
	// RVA: 0x66fbfc8 VA: 0x7598d13fc8
	public Void .ctor(IEnumerable s) { }
	// RVA: 0x66fc2f8 VA: 0x7598d142f8
	public virtual Void Add(Object o) { }
	// RVA: 0x66fc3a8 VA: 0x7598d143a8
	public virtual Void AddAll(IEnumerable e) { }
	// RVA: 0x66fc690 VA: 0x7598d14690
	public virtual Void Clear() { }
	// RVA: 0x66fc734 VA: 0x7598d14734
	public virtual Boolean Contains(Object o) { }
	// RVA: 0x66fc7e0 VA: 0x7598d147e0
	public virtual Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x66fc910 VA: 0x7598d14910
	public virtual Int32 get_Count() { }
	// RVA: 0x66fc9b4 VA: 0x7598d149b4
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x66fcacc VA: 0x7598d14acc
	public virtual Boolean get_IsEmpty() { }
	// RVA: 0x66fcb7c VA: 0x7598d14b7c
	public virtual Boolean get_IsFixedSize() { }
	// RVA: 0x66fcc20 VA: 0x7598d14c20
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x66fccc4 VA: 0x7598d14cc4
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x66fcd68 VA: 0x7598d14d68
	public virtual Void Remove(Object o) { }
	// RVA: 0x66fce14 VA: 0x7598d14e14
	public virtual Void RemoveAll(IEnumerable e) { }
	// RVA: 0x66fd0fc VA: 0x7598d150fc
	public virtual Object get_SyncRoot() { }
}
```