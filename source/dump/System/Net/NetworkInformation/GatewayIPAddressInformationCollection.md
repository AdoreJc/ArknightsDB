# GatewayIPAddressInformationCollection

**Namespace:** `System.Net.NetworkInformation`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
public class GatewayIPAddressInformationCollection : ICollection`1, IEnumerable`1, IEnumerable
{
	private Collection`1 addresses; // 0x10

	public virtual Int32 Count { get; }
	public virtual Boolean IsReadOnly { get; }

	// RVA: 0x63464ec VA: 0x759895e4ec
	protected internal Void .ctor() { }
	// RVA: 0x6346574 VA: 0x759895e574
	public virtual Void CopyTo(GatewayIPAddressInformation[] array, Int32 offset) { }
	// RVA: 0x63465dc VA: 0x759895e5dc
	public virtual Int32 get_Count() { }
	// RVA: 0x634662c VA: 0x759895e62c
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x6346634 VA: 0x759895e634
	public virtual Void Add(GatewayIPAddressInformation address) { }
	// RVA: 0x6346694 VA: 0x759895e694
	internal Void InternalAdd(GatewayIPAddressInformation address) { }
	// RVA: 0x63466ec VA: 0x759895e6ec
	public virtual Boolean Contains(GatewayIPAddressInformation address) { }
	// RVA: 0x6346744 VA: 0x759895e744
	public virtual IEnumerator`1 GetEnumerator() { }
	// RVA: 0x6346794 VA: 0x759895e794
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x63467a4 VA: 0x759895e7a4
	public virtual Boolean Remove(GatewayIPAddressInformation address) { }
	// RVA: 0x6346804 VA: 0x759895e804
	public virtual Void Clear() { }
}
```