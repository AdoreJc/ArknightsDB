# KeyCollection

**Namespace:** ` `


## Fields

- `Hashtable _hashtable`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class KeyCollection : ICollection, IEnumerable
{
	private Hashtable _hashtable; // 0x10

	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }
	public virtual Int32 Count { get; }

	// RVA: 0x6089690 VA: 0x75986a1690
	internal Void .ctor(Hashtable hashtable) { }
	// RVA: 0x608a95c VA: 0x75986a295c
	public virtual Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x608aae8 VA: 0x75986a2ae8
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x608ab50 VA: 0x75986a2b50
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x608ab74 VA: 0x75986a2b74
	public virtual Object get_SyncRoot() { }
	// RVA: 0x608ab98 VA: 0x75986a2b98
	public virtual Int32 get_Count() { }
}
```