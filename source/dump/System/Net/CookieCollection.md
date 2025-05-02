# CookieCollection

**Namespace:** `System.Net`


## Fields

- `ArrayList m_list`

- `DateTime m_TimeStamp`

- `Boolean m_has_other_versions`

- `Boolean m_IsReadOnly`


## Properties

- `Cookie Item`

- `Int32 Count`

- `Boolean IsSynchronized`

- `Object SyncRoot`


## Methods

- `Cookie get_Item(Int32)`

- `Void Add(Cookie)`

- `Void Add(CookieCollection)`

- `Int32 get_Count()`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `Void CopyTo(Array, Int32)`

- `IEnumerator GetEnumerator()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class CookieCollection : ICollection, IEnumerable
{
	internal Int32 m_version; // 0x10
	private ArrayList m_list; // 0x18
	private DateTime m_TimeStamp; // 0x20
	private Boolean m_has_other_versions; // 0x28
	private Boolean m_IsReadOnly; // 0x29

	public Cookie Item { get; }
	public Int32 Count { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }
	internal Boolean IsOtherVersionSeen { get; }

	// RVA: 0x6439268 VA: 0x7598a51268
	public Void .ctor() { }
	// RVA: 0x643931c VA: 0x7598a5131c
	public Cookie get_Item(Int32 index) { }
	// RVA: 0x6439408 VA: 0x7598a51408
	public Void Add(Cookie cookie) { }
	// RVA: 0x6439890 VA: 0x7598a51890
	public Void Add(CookieCollection cookies) { }
	// RVA: 0x6439bf0 VA: 0x7598a51bf0
	public Int32 get_Count() { }
	// RVA: 0x6439c14 VA: 0x7598a51c14
	public Boolean get_IsSynchronized() { }
	// RVA: 0x6439c1c VA: 0x7598a51c1c
	public Object get_SyncRoot() { }
	// RVA: 0x6439c20 VA: 0x7598a51c20
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x6439c44 VA: 0x7598a51c44
	internal DateTime TimeStamp(Stamp how) { }
	// RVA: 0x6439d04 VA: 0x7598a51d04
	internal Boolean get_IsOtherVersionSeen() { }
	// RVA: 0x6439d0c VA: 0x7598a51d0c
	internal Int32 InternalAdd(Cookie cookie, Boolean isStrict) { }
	// RVA: 0x64394cc VA: 0x7598a514cc
	internal Int32 IndexOf(Cookie cookie) { }
	// RVA: 0x643a1c4 VA: 0x7598a521c4
	internal Void RemoveAt(Int32 idx) { }
	// RVA: 0x6439b90 VA: 0x7598a51b90
	public IEnumerator GetEnumerator() { }
}
```