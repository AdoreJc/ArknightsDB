# ComponentResourceManager

**Namespace:** `System.ComponentModel`


## Fields

- `Hashtable _resourceSets`

- `CultureInfo _neutralResourcesCulture`


## Properties

- `CultureInfo NeutralResourcesCulture`


## Methods

- `CultureInfo get_NeutralResourcesCulture()`

- `Void ApplyResources(Object, String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class ComponentResourceManager : ResourceManager
{
	private Hashtable _resourceSets; // 0x88
	private CultureInfo _neutralResourcesCulture; // 0x90

	private CultureInfo NeutralResourcesCulture { get; }

	// RVA: 0x63b7470 VA: 0x75989cf470
	public Void .ctor() { }
	// RVA: 0x63b74c8 VA: 0x75989cf4c8
	public Void .ctor(Type t) { }
	// RVA: 0x63b7530 VA: 0x75989cf530
	private CultureInfo get_NeutralResourcesCulture() { }
	// RVA: 0x63b75c4 VA: 0x75989cf5c4
	public Void ApplyResources(Object value, String objectName) { }
	// RVA: 0x63b75d4 VA: 0x75989cf5d4
	public virtual Void ApplyResources(Object value, String objectName, CultureInfo culture) { }
	// RVA: 0x63b8074 VA: 0x75989d0074
	private SortedList`2 FillResources(CultureInfo culture, out ResourceSet resourceSet) { }
}
```