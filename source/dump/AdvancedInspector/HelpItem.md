# HelpItem

**Namespace:** `AdvancedInspector`


## Fields

- `HelpType type`

- `String message`

- `HelpPosition position`


## Properties

- `HelpType Type`

- `String Message`

- `HelpPosition Position`


## Methods

- `HelpType get_Type()`

- `Void set_Type(HelpType)`

- `String get_Message()`

- `Void set_Message(String)`

- `HelpPosition get_Position()`

- `Void set_Position(HelpPosition)`

- `Boolean Equals(HelpItem)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class HelpItem : IEquatable`1
{
	private HelpType type; // 0x10
	private String message; // 0x18
	private HelpPosition position; // 0x20

	public HelpType Type { get; set; }
	public String Message { get; set; }
	public HelpPosition Position { get; set; }

	// RVA: 0x1b220b0 VA: 0x759413a0b0
	public HelpType get_Type() { }
	// RVA: 0x1b220b8 VA: 0x759413a0b8
	public Void set_Type(HelpType value) { }
	// RVA: 0x1b220c0 VA: 0x759413a0c0
	public String get_Message() { }
	// RVA: 0x1b220c8 VA: 0x759413a0c8
	public Void set_Message(String value) { }
	// RVA: 0x1b220d0 VA: 0x759413a0d0
	public HelpPosition get_Position() { }
	// RVA: 0x1b220d8 VA: 0x759413a0d8
	public Void set_Position(HelpPosition value) { }
	// RVA: 0x1b16584 VA: 0x759412e584
	public Void .ctor(HelpType type, String message) { }
	// RVA: 0x1b15f98 VA: 0x759412df98
	public Void .ctor(HelpType type, String message, HelpPosition position) { }
	// RVA: 0x1b220e0 VA: 0x759413a0e0
	public Boolean Equals(HelpItem help) { }
	// RVA: 0x1b22130 VA: 0x759413a130
	public override Boolean Equals(Object obj) { }
	// RVA: 0x1b221ec VA: 0x759413a1ec
	public override Int32 GetHashCode() { }
}
```