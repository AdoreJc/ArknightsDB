# EventData

**Namespace:** `Spine`


## Fields

- `Int32 <Int>k__BackingField`

- `Single <Float>k__BackingField`

- `String <String>k__BackingField`

- `String <AudioPath>k__BackingField`

- `Single <Volume>k__BackingField`

- `Single <Balance>k__BackingField`


## Properties

- `String Name`

- `Int32 Int`

- `Single Float`

- `String String`

- `String AudioPath`

- `Single Volume`

- `Single Balance`


## Methods

- `String get_Name()`

- `Int32 get_Int()`

- `Void set_Int(Int32)`

- `Single get_Float()`

- `Void set_Float(Single)`

- `String get_String()`

- `Void set_String(String)`

- `String get_AudioPath()`

- `Void set_AudioPath(String)`

- `Single get_Volume()`

- `Void set_Volume(Single)`

- `Single get_Balance()`

- `Void set_Balance(Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class EventData
{
	internal String name; // 0x10
	private Int32 <Int>k__BackingField; // 0x18
	private Single <Float>k__BackingField; // 0x1c
	private String <String>k__BackingField; // 0x20
	private String <AudioPath>k__BackingField; // 0x28
	private Single <Volume>k__BackingField; // 0x30
	private Single <Balance>k__BackingField; // 0x34

	public String Name { get; }
	public Int32 Int { get; set; }
	public Single Float { get; set; }
	public String String { get; set; }
	public String AudioPath { get; set; }
	public Single Volume { get; set; }
	public Single Balance { get; set; }

	// RVA: 0x61d4b38 VA: 0x75987ecb38
	public String get_Name() { }
	// RVA: 0x61d4b40 VA: 0x75987ecb40
	public Int32 get_Int() { }
	// RVA: 0x61d4b48 VA: 0x75987ecb48
	public Void set_Int(Int32 value) { }
	// RVA: 0x61d4b50 VA: 0x75987ecb50
	public Single get_Float() { }
	// RVA: 0x61d4b58 VA: 0x75987ecb58
	public Void set_Float(Single value) { }
	// RVA: 0x61d4b60 VA: 0x75987ecb60
	public String get_String() { }
	// RVA: 0x61d4b68 VA: 0x75987ecb68
	public Void set_String(String value) { }
	// RVA: 0x61d4b70 VA: 0x75987ecb70
	public String get_AudioPath() { }
	// RVA: 0x61d4b78 VA: 0x75987ecb78
	public Void set_AudioPath(String value) { }
	// RVA: 0x61d4b80 VA: 0x75987ecb80
	public Single get_Volume() { }
	// RVA: 0x61d4b88 VA: 0x75987ecb88
	public Void set_Volume(Single value) { }
	// RVA: 0x61d4b90 VA: 0x75987ecb90
	public Single get_Balance() { }
	// RVA: 0x61d4b98 VA: 0x75987ecb98
	public Void set_Balance(Single value) { }
	// RVA: 0x61d4ba0 VA: 0x75987ecba0
	public Void .ctor(String name) { }
	// RVA: 0x61d4c34 VA: 0x75987ecc34
	public override String ToString() { }
}
```