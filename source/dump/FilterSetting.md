# FilterSetting

**Namespace:** ` `


## Fields

- `FilterButtonItem m_item`


## Properties

- `FilterType filterType`

- `Int32 param`


## Methods

- `FilterType get_filterType()`

- `Int32 get_param()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterSetting
{
	private FilterButtonItem m_item; // 0x10

	public FilterType filterType { get; }
	public Int32 param { get; }

	// RVA: 0x380d534 VA: 0x7595e25534
	public Void .ctor(FilterButtonItem item) { }
	// RVA: 0x380c5b8 VA: 0x7595e245b8
	public FilterType get_filterType() { }
	// RVA: 0x380c5d4 VA: 0x7595e245d4
	public Int32 get_param() { }
}
```