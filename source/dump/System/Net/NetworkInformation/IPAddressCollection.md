# IPAddressCollection

**Namespace:** `System.Net.NetworkInformation`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
public class IPAddressCollection : ICollection`1, IEnumerable`1, IEnumerable
{
	private Collection`1 addresses; // 0x10

	public virtual Int32 Count { get; }
	public virtual Boolean IsReadOnly { get; }

	// RVA: 0x6346864 VA: 0x759895e864
	protected internal Void .ctor() { }
	// RVA: 0x63468ec VA: 0x759895e8ec
	public virtual Void CopyTo(IPAddress[] array, Int32 offset) { }
	// RVA: 0x6346954 VA: 0x759895e954
	public virtual Int32 get_Count() { }
	// RVA: 0x63469a4 VA: 0x759895e9a4
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x63469ac VA: 0x759895e9ac
	public virtual Void Add(IPAddress address) { }
	// RVA: 0x6346a0c VA: 0x759895ea0c
	internal Void InternalAdd(IPAddress address) { }
	// RVA: 0x6346a64 VA: 0x759895ea64
	public virtual Boolean Contains(IPAddress address) { }
	// RVA: 0x6346abc VA: 0x759895eabc
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x6346acc VA: 0x759895eacc
	public virtual IEnumerator`1 GetEnumerator() { }
	// RVA: 0x6346b1c VA: 0x759895eb1c
	public virtual Boolean Remove(IPAddress address) { }
	// RVA: 0x6346b7c VA: 0x759895eb7c
	public virtual Void Clear() { }
}
```