# UnicastIPAddressInformationCollection

**Namespace:** `System.Net.NetworkInformation`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
public class UnicastIPAddressInformationCollection : ICollection`1, IEnumerable`1, IEnumerable
{
	private Collection`1 addresses; // 0x10

	public virtual Int32 Count { get; }
	public virtual Boolean IsReadOnly { get; }

	// RVA: 0x634723c VA: 0x759895f23c
	protected internal Void .ctor() { }
	// RVA: 0x63472c4 VA: 0x759895f2c4
	public virtual Void CopyTo(UnicastIPAddressInformation[] array, Int32 offset) { }
	// RVA: 0x634732c VA: 0x759895f32c
	public virtual Int32 get_Count() { }
	// RVA: 0x634737c VA: 0x759895f37c
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x6347384 VA: 0x759895f384
	public virtual Void Add(UnicastIPAddressInformation address) { }
	// RVA: 0x63473e4 VA: 0x759895f3e4
	internal Void InternalAdd(UnicastIPAddressInformation address) { }
	// RVA: 0x634743c VA: 0x759895f43c
	public virtual Boolean Contains(UnicastIPAddressInformation address) { }
	// RVA: 0x6347494 VA: 0x759895f494
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x63474a4 VA: 0x759895f4a4
	public virtual IEnumerator`1 GetEnumerator() { }
	// RVA: 0x63474f4 VA: 0x759895f4f4
	public virtual Boolean Remove(UnicastIPAddressInformation address) { }
	// RVA: 0x6347554 VA: 0x759895f554
	public virtual Void Clear() { }
}
```