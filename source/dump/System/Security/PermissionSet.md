# PermissionSet

**Namespace:** `System.Security`


## Fields

- `PermissionState state`

- `ArrayList list`

- `Boolean _declsec`


## Methods

- `Void Demand()`

- `IEnumerator GetEnumerator()`

- `Boolean IsEmpty()`

- `Boolean IsUnrestricted()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security
public class PermissionSet : ISecurityEncodable, ICollection, IEnumerable, IDeserializationCallback
{
	private static Object[] psUnrestricted; // 0x0
	private PermissionState state; // 0x10
	private ArrayList list; // 0x18
	private Boolean _declsec; // 0x20
	private Boolean[] _ignored; // 0x28
	private static Object[] action; // 0x8

	public virtual Int32 Count { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }

	// RVA: 0x5f40618 VA: 0x7598558618
	internal Void .ctor() { }
	// RVA: 0x5f4070c VA: 0x759855870c
	public Void .ctor(PermissionState state) { }
	// RVA: 0x5f400d4 VA: 0x75985580d4
	internal Void .ctor(IPermission perm) { }
	// RVA: 0x5f40fb0 VA: 0x7598558fb0
	public virtual Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x5f41128 VA: 0x7598559128
	public Void Demand() { }
	// RVA: 0x5f40120 VA: 0x7598558120
	internal Void CasOnlyDemand(Int32 skip) { }
	// RVA: 0x5f41710 VA: 0x7598559710
	public IEnumerator GetEnumerator() { }
	// RVA: 0x5f41360 VA: 0x7598559360
	public Boolean IsEmpty() { }
	// RVA: 0x5f41700 VA: 0x7598559700
	public Boolean IsUnrestricted() { }
	// RVA: 0x5f41734 VA: 0x7598559734
	public override String ToString() { }
	// RVA: 0x5f408ac VA: 0x75985588ac
	public virtual SecurityElement ToXml() { }
	// RVA: 0x5f41760 VA: 0x7598559760
	public virtual Int32 get_Count() { }
	// RVA: 0x5f41784 VA: 0x7598559784
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x5f417a8 VA: 0x75985597a8
	public virtual Object get_SyncRoot() { }
	// RVA: 0x5f417ac VA: 0x75985597ac
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
	// RVA: 0x5f40d98 VA: 0x7598558d98
	public override Boolean Equals(Object obj) { }
	// RVA: 0x5f40f6c VA: 0x7598558f6c
	public override Int32 GetHashCode() { }
	// RVA: 0x5f417b0 VA: 0x75985597b0
	private static Void .cctor() { }
}
```