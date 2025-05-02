# ValueCollection

**Namespace:** ` `


## Fields

- `Hashtable _hashtable`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class ValueCollection : ICollection, IEnumerable
{
	private Hashtable _hashtable; // 0x10

	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }
	public virtual Int32 Count { get; }

	// RVA: 0x608974c VA: 0x75986a174c
	internal Void .ctor(Hashtable hashtable) { }
	// RVA: 0x608abb4 VA: 0x75986a2bb4
	public virtual Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x608ad40 VA: 0x75986a2d40
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x608ada8 VA: 0x75986a2da8
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x608adcc VA: 0x75986a2dcc
	public virtual Object get_SyncRoot() { }
	// RVA: 0x608adf0 VA: 0x75986a2df0
	public virtual Int32 get_Count() { }
}
```