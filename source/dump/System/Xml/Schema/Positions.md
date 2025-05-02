# Positions

**Namespace:** `System.Xml.Schema`


## Fields

- `ArrayList positions`


## Properties

- `Position Item`

- `Int32 Count`


## Methods

- `Int32 Add(Int32, Object)`

- `Position get_Item(Int32)`

- `Int32 get_Count()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Positions
{
	private ArrayList positions; // 0x10

	public Position Item { get; }
	public Int32 Count { get; }

	// RVA: 0x62d43b8 VA: 0x75988ec3b8
	public Int32 Add(Int32 symbol, Object particle) { }
	// RVA: 0x62d4460 VA: 0x75988ec460
	public Position get_Item(Int32 pos) { }
	// RVA: 0x62d44f0 VA: 0x75988ec4f0
	public Int32 get_Count() { }
	// RVA: 0x62d4514 VA: 0x75988ec514
	public Void .ctor() { }
}
```