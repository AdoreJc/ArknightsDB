# SymbolsDictionary

**Namespace:** `System.Xml.Schema`


## Fields

- `Int32 last`

- `Hashtable names`

- `Hashtable wildcards`

- `ArrayList particles`

- `Object particleLast`

- `Boolean isUpaEnforced`


## Properties

- `Int32 Count`

- `Boolean IsUpaEnforced`


## Methods

- `Int32 get_Count()`

- `Boolean get_IsUpaEnforced()`

- `Void set_IsUpaEnforced(Boolean)`

- `Int32 AddName(XmlQualifiedName, Object)`

- `Void AddNamespaceList(NamespaceList, Object, Boolean)`

- `Void AddWildcard(String, Object)`

- `ICollection GetNamespaceListSymbols(NamespaceList)`

- `Boolean Exists(XmlQualifiedName)`

- `Object GetParticle(Int32)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class SymbolsDictionary
{
	private Int32 last; // 0x10
	private Hashtable names; // 0x18
	private Hashtable wildcards; // 0x20
	private ArrayList particles; // 0x28
	private Object particleLast; // 0x30
	private Boolean isUpaEnforced; // 0x38

	public Int32 Count { get; }
	public Boolean IsUpaEnforced { get; set; }

	// RVA: 0x62d3474 VA: 0x75988eb474
	public Void .ctor() { }
	// RVA: 0x62d352c VA: 0x75988eb52c
	public Int32 get_Count() { }
	// RVA: 0x62d3538 VA: 0x75988eb538
	public Boolean get_IsUpaEnforced() { }
	// RVA: 0x62d3540 VA: 0x75988eb540
	public Void set_IsUpaEnforced(Boolean value) { }
	// RVA: 0x62d354c VA: 0x75988eb54c
	public Int32 AddName(XmlQualifiedName name, Object particle) { }
	// RVA: 0x62d3680 VA: 0x75988eb680
	public Void AddNamespaceList(NamespaceList list, Object particle, Boolean allowLocal) { }
	// RVA: 0x62d3a34 VA: 0x75988eba34
	private Void AddWildcard(String wildcard, Object particle) { }
	// RVA: 0x62d3bb0 VA: 0x75988ebbb0
	public ICollection GetNamespaceListSymbols(NamespaceList list) { }
	// RVA: 0x62d433c VA: 0x75988ec33c
	public Boolean Exists(XmlQualifiedName name) { }
	// RVA: 0x62d436c VA: 0x75988ec36c
	public Object GetParticle(Int32 symbol) { }
}
```