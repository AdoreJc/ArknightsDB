# ThemePreset

**Namespace:** ` `


## Fields

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
// Namespace : 
public class ThemePreset : IDIYPreset
{
	private String <roomType>k__BackingField; // 0x10
	private String <floorModifierId>k__BackingField; // 0x18
	private String <wallModifierId>k__BackingField; // 0x20
	public List`1 presetItems; // 0x28

	public String name { get; }
	public String roomType { get; set; }
	public String floorModifierId { get; set; }
	public String wallModifierId { get; set; }
	public String thumbnailUrl { get; }
	public IEnumerable`1 items { get; }

	// RVA: 0x3d2bb7c VA: 0x7596343b7c
	public String get_name() { }
	// RVA: 0x3d2bbc4 VA: 0x7596343bc4
	public String get_roomType() { }
	// RVA: 0x3d2bbcc VA: 0x7596343bcc
	public Void set_roomType(String value) { }
	// RVA: 0x3d2bbd4 VA: 0x7596343bd4
	public String get_floorModifierId() { }
	// RVA: 0x3d2bbdc VA: 0x7596343bdc
	public Void set_floorModifierId(String value) { }
	// RVA: 0x3d2bbe4 VA: 0x7596343be4
	public String get_wallModifierId() { }
	// RVA: 0x3d2bbec VA: 0x7596343bec
	public Void set_wallModifierId(String value) { }
	// RVA: 0x3d2bbf4 VA: 0x7596343bf4
	public String get_thumbnailUrl() { }
	// RVA: 0x3d2bc3c VA: 0x7596343c3c
	public IEnumerable`1 get_items() { }
	// RVA: 0x3d29784 VA: 0x7596341784
	public Void .ctor() { }
}
```