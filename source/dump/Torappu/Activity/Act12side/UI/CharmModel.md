# CharmModel

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `CharmItemData <data>k__BackingField`

- `Int32 <count>k__BackingField`

- `Boolean newUnlock`

- `Boolean selected`

- `Int32 typeSelIdx`


## Properties

- `CharmItemData data`

- `Int32 count`


## Methods

- `CharmItemData get_data()`

- `Void set_data(CharmItemData)`

- `Int32 get_count()`

- `Void set_count(Int32)`

- `Void RefreshStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmModel
{
	private CharmItemData <data>k__BackingField; // 0x10
	private Int32 <count>k__BackingField; // 0x18
	public Boolean newUnlock; // 0x1c
	public Boolean selected; // 0x1d
	public Int32 typeSelIdx; // 0x20

	public CharmItemData data { get; set; }
	public Int32 count { get; set; }

	// RVA: 0x34508c8 VA: 0x7595a688c8
	public Void .ctor(CharmItemData charmData, Int32 cnt) { }
	// RVA: 0x3450904 VA: 0x7595a68904
	public CharmItemData get_data() { }
	// RVA: 0x345090c VA: 0x7595a6890c
	private Void set_data(CharmItemData value) { }
	// RVA: 0x3450914 VA: 0x7595a68914
	public Int32 get_count() { }
	// RVA: 0x345091c VA: 0x7595a6891c
	private Void set_count(Int32 value) { }
	// RVA: 0x3450924 VA: 0x7595a68924
	public Void RefreshStatus() { }
}
```