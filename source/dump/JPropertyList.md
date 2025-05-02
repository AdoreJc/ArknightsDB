# JPropertyList

**Namespace:** ` `


## Properties

- `Int32 Count`

- `Boolean IsReadOnly`

- `JToken Item`


## Methods

- `Void Add(JToken)`

- `Void Clear()`

- `Boolean Contains(JToken)`

- `Void CopyTo(JToken[], Int32)`

- `Boolean Remove(JToken)`

- `Int32 get_Count()`

- `Boolean get_IsReadOnly()`

- `Int32 IndexOf(JToken)`

- `Void Insert(Int32, JToken)`

- `Void RemoveAt(Int32)`

- `JToken get_Item(Int32)`

- `Void set_Item(Int32, JToken)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : 
private class JPropertyList : IList`1, ICollection`1, IEnumerable`1, IEnumerable
{
	internal JToken _token; // 0x10

	public Int32 Count { get; }
	public Boolean IsReadOnly { get; }
	public JToken Item { get; set; }

	// RVA: 0x619b5b4 VA: 0x75987b35b4
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x619b650 VA: 0x75987b3650
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x619b654 VA: 0x75987b3654
	public Void Add(JToken item) { }
	// RVA: 0x619b65c VA: 0x75987b365c
	public Void Clear() { }
	// RVA: 0x619b668 VA: 0x75987b3668
	public Boolean Contains(JToken item) { }
	// RVA: 0x619b678 VA: 0x75987b3678
	public Void CopyTo(JToken[] array, Int32 arrayIndex) { }
	// RVA: 0x619b6ec VA: 0x75987b36ec
	public Boolean Remove(JToken item) { }
	// RVA: 0x619b71c VA: 0x75987b371c
	public Int32 get_Count() { }
	// RVA: 0x619b72c VA: 0x75987b372c
	public Boolean get_IsReadOnly() { }
	// RVA: 0x619b1d4 VA: 0x75987b31d4
	public Int32 IndexOf(JToken item) { }
	// RVA: 0x619b734 VA: 0x75987b3734
	public Void Insert(Int32 index, JToken item) { }
	// RVA: 0x619b748 VA: 0x75987b3748
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x619b75c VA: 0x75987b375c
	public JToken get_Item(Int32 index) { }
	// RVA: 0x619b770 VA: 0x75987b3770
	public Void set_Item(Int32 index, JToken value) { }
	// RVA: 0x619ae98 VA: 0x75987b2e98
	public Void .ctor() { }
}
```