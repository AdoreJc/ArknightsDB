# DIYPreset

**Namespace:** `Torappu.Building.DIY`


## Fields

- `String <name>k__BackingField`

- `String <roomType>k__BackingField`

- `String <floorModifierId>k__BackingField`

- `String <wallModifierId>k__BackingField`


## Properties

- `String name`

- `String roomType`

- `String floorModifierId`

- `String wallModifierId`

- `String thumbnailUrl`


## Methods

- `String get_name()`

- `Void set_name(String)`

- `String get_roomType()`

- `Void set_roomType(String)`

- `String get_floorModifierId()`

- `Void set_floorModifierId(String)`

- `String get_wallModifierId()`

- `Void set_wallModifierId(String)`

- `String get_thumbnailUrl()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYPreset : IDIYPreset
{
	public List`1 itemList; // 0x10
	private String <name>k__BackingField; // 0x18
	private String <roomType>k__BackingField; // 0x20
	private String <floorModifierId>k__BackingField; // 0x28
	private String <wallModifierId>k__BackingField; // 0x30

	public String name { get; set; }
	public String roomType { get; set; }
	public String floorModifierId { get; set; }
	public String wallModifierId { get; set; }
	public String thumbnailUrl { get; }
	public IEnumerable`1 items { get; }

	// RVA: 0x37b35ac VA: 0x7595dcb5ac
	public String get_name() { }
	// RVA: 0x37b35b4 VA: 0x7595dcb5b4
	public Void set_name(String value) { }
	// RVA: 0x37b35bc VA: 0x7595dcb5bc
	public String get_roomType() { }
	// RVA: 0x37b35c4 VA: 0x7595dcb5c4
	public Void set_roomType(String value) { }
	// RVA: 0x37b35cc VA: 0x7595dcb5cc
	public String get_floorModifierId() { }
	// RVA: 0x37b35d4 VA: 0x7595dcb5d4
	public Void set_floorModifierId(String value) { }
	// RVA: 0x37b35dc VA: 0x7595dcb5dc
	public String get_wallModifierId() { }
	// RVA: 0x37b35e4 VA: 0x7595dcb5e4
	public Void set_wallModifierId(String value) { }
	// RVA: 0x37b35ec VA: 0x7595dcb5ec
	public String get_thumbnailUrl() { }
	// RVA: 0x37b3634 VA: 0x7595dcb634
	public IEnumerable`1 get_items() { }
	// RVA: 0x37b363c VA: 0x7595dcb63c
	public Void .ctor() { }
}
```