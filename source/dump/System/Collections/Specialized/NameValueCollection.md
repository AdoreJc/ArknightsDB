# NameValueCollection

**Namespace:** `System.Collections.Specialized`


## Properties

- `String Item`

- `String Item`


## Methods

- `Void InvalidateCachedArrays()`

- `String get_Item(String)`

- `Void set_Item(String, String)`

- `String get_Item(Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Specialized
public class NameValueCollection : NameObjectCollectionBase
{
	private String[] _all; // 0x50
	private String[] _allKeys; // 0x58

	public String Item { get; set; }
	public String Item { get; }
	public virtual String[] AllKeys { get; }

	// RVA: 0x640a5e4 VA: 0x7598a225e4
	public Void .ctor() { }
	// RVA: 0x640a698 VA: 0x7598a22698
	public Void .ctor(Int32 capacity, IEqualityComparer equalityComparer) { }
	// RVA: 0x640a738 VA: 0x7598a22738
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x640a7dc VA: 0x7598a227dc
	protected Void InvalidateCachedArrays() { }
	// RVA: 0x640a804 VA: 0x7598a22804
	private static String GetAsOneString(ArrayList list) { }
	// RVA: 0x640a9a4 VA: 0x7598a229a4
	private static String[] GetAsStringArray(ArrayList list) { }
	// RVA: 0x640aa44 VA: 0x7598a22a44
	public virtual Void Add(String name, String value) { }
	// RVA: 0x640ad58 VA: 0x7598a22d58
	public virtual String Get(String name) { }
	// RVA: 0x640ade4 VA: 0x7598a22de4
	public virtual String[] GetValues(String name) { }
	// RVA: 0x640ae70 VA: 0x7598a22e70
	public virtual Void Set(String name, String value) { }
	// RVA: 0x640b030 VA: 0x7598a23030
	public virtual Void Remove(String name) { }
	// RVA: 0x640b28c VA: 0x7598a2328c
	public String get_Item(String name) { }
	// RVA: 0x640b29c VA: 0x7598a2329c
	public Void set_Item(String name, String value) { }
	// RVA: 0x640b2ac VA: 0x7598a232ac
	public virtual String Get(Int32 index) { }
	// RVA: 0x640b3cc VA: 0x7598a233cc
	public virtual String GetKey(Int32 index) { }
	// RVA: 0x640b46c VA: 0x7598a2346c
	public String get_Item(Int32 index) { }
	// RVA: 0x640b47c VA: 0x7598a2347c
	public virtual String[] get_AllKeys() { }
	// RVA: 0x640b5c4 VA: 0x7598a235c4
	internal Void .ctor(DBNull dummy) { }
}
```