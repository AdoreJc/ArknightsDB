# Event

**Namespace:** `Spine`


## Properties

- `EventData Data`

- `Single Time`

- `Int32 Int`

- `Single Float`

- `String String`

- `Single Volume`

- `Single Balance`


## Methods

- `EventData get_Data()`

- `Single get_Time()`

- `Int32 get_Int()`

- `Void set_Int(Int32)`

- `Single get_Float()`

- `Void set_Float(Single)`

- `String get_String()`

- `Void set_String(String)`

- `Single get_Volume()`

- `Void set_Volume(Single)`

- `Single get_Balance()`

- `Void set_Balance(Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Event
{
	internal readonly EventData data; // 0x10
	internal readonly Single time; // 0x18
	internal Int32 intValue; // 0x1c
	internal Single floatValue; // 0x20
	internal String stringValue; // 0x28
	internal Single volume; // 0x30
	internal Single balance; // 0x34

	public EventData Data { get; }
	public Single Time { get; }
	public Int32 Int { get; set; }
	public Single Float { get; set; }
	public String String { get; set; }
	public Single Volume { get; set; }
	public Single Balance { get; set; }

	// RVA: 0x61d4a18 VA: 0x75987eca18
	public EventData get_Data() { }
	// RVA: 0x61d4a20 VA: 0x75987eca20
	public Single get_Time() { }
	// RVA: 0x61d4a28 VA: 0x75987eca28
	public Int32 get_Int() { }
	// RVA: 0x61d4a30 VA: 0x75987eca30
	public Void set_Int(Int32 value) { }
	// RVA: 0x61d4a38 VA: 0x75987eca38
	public Single get_Float() { }
	// RVA: 0x61d4a40 VA: 0x75987eca40
	public Void set_Float(Single value) { }
	// RVA: 0x61d4a48 VA: 0x75987eca48
	public String get_String() { }
	// RVA: 0x61d4a50 VA: 0x75987eca50
	public Void set_String(String value) { }
	// RVA: 0x61d4a58 VA: 0x75987eca58
	public Single get_Volume() { }
	// RVA: 0x61d4a60 VA: 0x75987eca60
	public Void set_Volume(Single value) { }
	// RVA: 0x61d4a68 VA: 0x75987eca68
	public Single get_Balance() { }
	// RVA: 0x61d4a70 VA: 0x75987eca70
	public Void set_Balance(Single value) { }
	// RVA: 0x61d4a78 VA: 0x75987eca78
	public Void .ctor(Single time, EventData data) { }
	// RVA: 0x61d4b1c VA: 0x75987ecb1c
	public override String ToString() { }
}
```