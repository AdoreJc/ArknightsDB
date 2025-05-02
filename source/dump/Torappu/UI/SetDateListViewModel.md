# SetDateListViewModel

**Namespace:** `Torappu.UI`


## Fields

- `Int32 selectedDateIdx`

- `Int64 <dragContextID>k__BackingField`


## Properties

- `Int64 dragContextID`

- `Int32 pagerSelectedPage`

- `Int32 currentDate`


## Methods

- `Int64 get_dragContextID()`

- `Void set_dragContextID(Int64)`

- `Int32 get_pagerSelectedPage()`

- `Int32 get_currentDate()`

- `Int32 SwitchPagerIndex(Int32)`

- `Void UpdateSelection(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SetDateListViewModel
{
	public List`1 dates; // 0x10
	public Int32 selectedDateIdx; // 0x18
	private Int64 <dragContextID>k__BackingField; // 0x20

	public Int64 dragContextID { get; set; }
	public Int32 pagerSelectedPage { get; }
	public Int32 currentDate { get; }

	// RVA: 0x223e684 VA: 0x7594856684
	public Int64 get_dragContextID() { }
	// RVA: 0x223e68c VA: 0x759485668c
	private Void set_dragContextID(Int64 value) { }
	// RVA: 0x223d6ec VA: 0x75948556ec
	public Int32 get_pagerSelectedPage() { }
	// RVA: 0x223c3b8 VA: 0x75948543b8
	public Int32 get_currentDate() { }
	// RVA: 0x223ca28 VA: 0x7594854a28
	public Int32 SwitchPagerIndex(Int32 idx) { }
	// RVA: 0x223ca88 VA: 0x7594854a88
	public Void UpdateSelection(Int32 idx) { }
	// RVA: 0x223e5fc VA: 0x75948565fc
	public Void .ctor() { }
}
```