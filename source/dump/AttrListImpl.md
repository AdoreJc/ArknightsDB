# AttrListImpl

**Namespace:** ` `


## Properties

- `Int32 Length`


## Methods

- `Int32 get_Length()`

- `String GetName(Int32)`

- `String GetValue(Int32)`

- `String GetValue(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class AttrListImpl : IAttrList
{
	private List`1 attrNames; // 0x10
	private List`1 attrValues; // 0x18

	public Int32 Length { get; }
	public String[] Names { get; }
	public String[] Values { get; }

	// RVA: 0x5efafd8 VA: 0x7598512fd8
	public Int32 get_Length() { }
	// RVA: 0x5efb020 VA: 0x7598513020
	public String GetName(Int32 i) { }
	// RVA: 0x5efb078 VA: 0x7598513078
	public String GetValue(Int32 i) { }
	// RVA: 0x5efb0d0 VA: 0x75985130d0
	public String GetValue(String name) { }
	// RVA: 0x5efb190 VA: 0x7598513190
	public String[] get_Names() { }
	// RVA: 0x5efb1e0 VA: 0x75985131e0
	public String[] get_Values() { }
	// RVA: 0x5efa95c VA: 0x759851295c
	internal Void Clear() { }
	// RVA: 0x5efaeb0 VA: 0x7598512eb0
	internal Void Add(String name, String value) { }
	// RVA: 0x5ef9560 VA: 0x7598511560
	public Void .ctor() { }
}
```